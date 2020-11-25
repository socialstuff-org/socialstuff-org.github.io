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
        <td>LOWER_WORD_CHARS</td>
        <td>available chars</td>
        <td>abcdefghijklmnopqrstuvwxyz</td>
    </tr>
    <tr>
        <td>UPPER_WORD_CHARS</td>
        <td>available chars</td>
        <td>ABCDEFGHIJKLMNOPQRSTUVWXYZ</td>
    </tr>
    <tr>
        <td>NUMBER_CHARS</td>
        <td>available chars</td>
        <td>1234567890</td>
    </tr>
    <tr>
        <td>SPECIAL_CHARS</td>
        <td>available chars</td>
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

- Download sample application data [here](../../downloads/identity-sample.zip).
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
