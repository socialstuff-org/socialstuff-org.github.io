<style>
ol {
  counter-reset: section;
  list-style-type: none;
}

li::before {
  counter-increment: section;
  content: counters(section, ".") " ";
}
</style>

<table>
    <tr>
        <td>
            <strong>Name</strong>
        </td>
        <td>
            Require invite
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
            In this use case, the actor changes the server settings, so invitation codes are required for user registrations or not.
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
                    Actor changes the setting "Registration invitations"
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
            If "Registration invitations" is set to "required", the system now requires invitation codes to be present on user registration.
            On the value "off", the system will not require invitation codes.
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
