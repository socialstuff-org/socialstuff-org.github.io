<table>
    <tr>
        <td>
            <strong>Name</strong>
        </td>
        <td>
            Ban user
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
                <strong>Service</strong>
            </td>
            <td>
                <a href="../../services/backend/settings.md">Settings Service</a>
            </td>
        </tr>
    <tr>
    <tr>
        <td>
            <strong>Description</strong>
        </td>
        <td>
            This use case describes the procedure of banning a user/removing their access to the system.
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
        <td>
            <strong>Scenario</strong>
        </td>
        <td>
            <ol>
                <li>
                    Actor views user and decides to block a user.
                </li>
                <li>
                    System <a href="./blockUser.md">blocks the user</a>.
                </li>
                <li>
                    System applies the login ban and informs the actor about the result.
                </li>
            </ol>
        </td>
    </tr>
    <tr>
        <td>
            <strong>Result</strong>
        </td>
        <td>
            The user to ban can not login into the system anymore and all current logins will be terminated.
        </td>
    </tr>
    <tr>
        <td>
            <strong>Exceptions</strong>
        </td>
        <td>
            <ul>
                <li>
                    1. System message: "unknown user"
                </li>
                <li>
                    1.1 Use case ends here
                </li>
            </ul>
        </td>
    </tr>
</table>
