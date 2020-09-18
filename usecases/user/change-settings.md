<table>
    <tr>
        <td>
            <strong>Name</strong>
        </td>
        <td>
            Change Settings
        </td>
    </tr>
    <tr>
        <td>
            <strong>Actor</strong>
        </td>
        <td>
            User
        </td>
    </tr>
    <tr>
        <td>
            <strong>Description</strong>            
        </td>
        <td>
            Actor changes settings
        </td>
    </tr>
    <tr>
        <td>
            <strong>Pre-condition</strong>
        </td>
        <td>
            Actor is 
            <a href="login.md">
            logged in
            </a> 
        </td>
    </tr>
    <tr>
        <td>
            <strong>Scenario</strong>
        </td>
        <td>
            <ul>
                <li>1|
                    Actor selects the hamburg menu button
                </li>
                <li>
                    2| System displays options to interact with 
                </li>
                <li>
                    3| Actor selects settings
                </li>
                <li>
                    4| System displays settings
                </li>
                <li>
                    5| Actor selects setting to change
                </li>
                <li>
                    6| System displays a confirmation message
                </li>
                <li>
                    7| Actor selects confirm changes
                </li>
                <li>
                    8| System changed settings
                </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            <strong>Result</strong>
        </td>
        <td>
            Actor has changed the settings
        </td>
    </tr>
    <tr>
        <td>
            <strong>Exceptions</strong>
        </td>
        <td>
            <ul>
                <li>
                    5| Actor is authorized to changes this setting
                </li>
            </ul>
        </td>
    </tr>
    <td>
                <strong>Alternate Flow</strong>
            </td>
            <td>
            <li>
                                7a| Actor selects cancel changes
                            </li>
            </td>      
</table>

