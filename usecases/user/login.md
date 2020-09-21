<table>
    <tr>
        <td>
            <strong>Name</strong>
        </td>
        <td>
            Login
        </td>
    </tr>
    <tr>
        <td>
            <strong>Actor</strong>
        </td>
        <td>
             <a href="../user.md"> User </a>
        </td>
    </tr>
    <tr>
        <td>
            <strong>Description</strong>            
        </td>
        <td>
            The user logs in to the system
        </td>
    </tr>
    <tr>
        <td>
            <strong>Pre-condition</strong>
        </td>
        <td>
             The <a href="../user.md"> User </a> has to be <a href="register.md"> registered </a>
        </td>
    </tr>
    <tr>
        <td>
            <strong>Scenario</strong>
        </td>
        <td>
            <ul>
                <li>
                    The actor navigates to login
                </li>
                <li>
                    The actor provides their login credentials and the server details
                </li>
                <li>
                    The system verifies the login credentials
                </li>
                <li>
                    The system logs in the actor
                </li>
               </ul>
                    </ul>
                </li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            <strong>Result</strong>
        </td>
        <td>
            The actor is logged in
        </td>
    </tr>
    <tr>
        <td>
            <strong>Exceptions</strong>
        </td>
        <td>
             <li>
                if the everything goes right:
                <ul>
                    <li>
                        if credentials are valid
                        <ul>
                            the system logs in the user
                        </ul>
                    </li>
                    <li>
                        else
                        <ul>
                            The user notifies that the credentials were invalid
                        </ul>
                    </li>
                </li>
            </li>
            </ul>
        </td>
    </tr>      
</table>
