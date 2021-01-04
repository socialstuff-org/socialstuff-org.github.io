#Reporting Service
- [Description](#description)
- [Rest interfaces](#Rest interfaces)  
    - [Reporting settings](#Reporting settings)  
    - [Security settings](#Security settings)
- [Example use case execution](#Example Add Report reason)

##Description
The reporting service handles the reporting system. This includes administrative tasks like managing for which reasons 
users can be reported, as well as the reporting system itself (reporting users and banning them). 
The administrative tasks, like adding new report reasons, manually blocking and unblocking users, can be done via the 
[settings service](settings.md).  

##Rest interfaces

```
GET: /report-reason/report-reason
```
Returns all report reasons as a JSON array.  

```
POST: /report-reason/report-reason
body:
{
    "reason": "some reason",
    "max_report_violations": 5
}
```
adds a new report reason.

```
PUT: /report-reason/report-reason
body:
{
    "id": 123,
    "reason": "some reason",
    "max_report_violations": 5
}
```
Edits an existing report reason.


```
DELETE: /report-reason/report-reason
headers:
    - "id": 123
```
Deletes a report reason
```
POST: /report
@param req request from the client. Follow this layout:
  Headers:
   - user_token 
Body:
    {
        "username": "userHashOfUserBeingReported",
        "reason_id": 123
    }
```
used for reporting a user. Verifies if the user sending out the report has already reported the user for the same reason in the past 15 minutes.
In that case the report will not pass. Otherwise the report will be registered in the database