<table>
    <tr>
        <td>
            <strong>Name</strong>
        </td>
        <td>
            Require E-Mail confirmation
        </td>
    </tr>
    <tr>
        <td>
            <strong>Actor</strong>
        </td>
        <td>
            Admin
        </td>
    </tr>
    <tr>
        <td>
            <strong>Description</strong>
        </td>
        <td>
            In this use case, the actor changes the server settings, so E-Mail confirmation for user registration is required, or not.
        </td>
    </tr>
    <tr>
        <td>
            <strong>Pre-condition</strong>
        </td>
        <td>
            Actor is logged in: <a href="./login.md">login</a>
        </td>
    </tr>
    <tr>
        <td>
            <strong>Scenario</strong>
        </td>
        <td>
            <ol>
                <li>
                    Actor opens an overview of system settings.
                </li>
                <li>
                    System shows the available settings of the system.
                </li>
                <li>
                    Actor changes the setting "E-Mail Confirmation"
                    <ol>
                        <li> to "required".</li>
                        <li> to "off".</li>
                    </ol>
                </li>
                <li>
                    System applies the requested settings change.
                </li>
            </ol>
        </td>
    </tr>
    <tr>
        <td>
            <strong>Result</strong>
        </td>
        <td>
            If "E-Mail Confirmation" is set to "required", the system now requires a valid E-Mail address to be present on user registration, as well as confirming the validity of said E-Mail address..
            On the value "off", the system will not require E-Mail confirmation.
        </td>
    </tr>
    <tr>
        <td>
            <strong>Exceptions</strong>
        </td>
        <td>
            N/A
        </td>
    </tr>
</table>
