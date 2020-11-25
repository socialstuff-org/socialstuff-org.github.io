# Identity service

## Default Requirements
<table>
    <tr>
        <th>Affected object</th>
        <th>Requirement</th>
        <th>Value</th>
    </tr>
    <tr>
        <td>Username</td>
        <td>minimum length</td>
        <td>3</td>
    </tr>
   <tr>
       <td>Username</td>
       <td>maximum length</td>
       <td>20</td>
   </tr>
   <tr>
       <td>Password</td>
       <td>minimum length</td>
       <td>10</td>
   </tr>
  <tr>
      <td>Password</td>
      <td>maximum length</td>
      <td>50</td>
  </tr>
    <tr>
        <td>Password</td>
        <td>min. 1 LOWER_WORD_CHARS</td>
        <td>abcdefghijklmnopqrstuvwxyz</td>
    </tr>
    <tr>
        <td>Password</td>
        <td>min. 1 UPPER_WORD_CHARS</td>
        <td>ABCDEFGHIJKLMNOPQRSTUVWXYZ</td>
    </tr>
    <tr>
        <td>Password</td>
        <td>min. 1 NUMBER_CHARS</td>
        <td>1234567890</td>
    </tr>
    <tr>
        <td>Password</td>
        <td>min. 1 SPECIAL_CHARS</td>
        <td>!@#$%^&*()-_=+[]{};\'":,.<>/?`~€</td>
    </tr>
</table>

## Sample data for registration / login

<table>
    <tr>
        <th>Username</th>
        <th>Password</th>
    </tr>
    <tr>
        <td>alice</td>
        <td>SomePassword1!</td>
    </tr>
    <tr>
        <td>bob</td>
        <td>SomePassword1!</td>
    </tr>
    <tr>
        <td>charlie</td>
        <td>SomePassword1!</td>
    </tr>
</table>

## Setup instructions

- Download sample application data [here](../../downloads/trale-user-bootstrap.zip).
- Extract ".trale" directory to your home directory so that the folder structure looks like this:

##### On Linux:
```
~/home/.trale
```
##### On MacOS:
```
~/Users/{username}/.trale
```

##### On Windows:
```
C:\Users\{username}\.trale
```
