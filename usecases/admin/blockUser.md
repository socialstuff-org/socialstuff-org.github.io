<table>
    <tr>
        <td>
            <strong>Name</strong>
        </td>
        <td>
            Block user
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
                <a href="../../services/backend/reporting.md">Reporting Service</a>
            </td>
        </tr>
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
            Actor is an admin
        </td>
    </tr>
    <tr>
        <td>
            <strong>Scenario</strong>
        </td>
        <td>
            <ol>
                <li>
                   The system receives the task to block a user
                </li>
                <li>
                    The system marks a user as marked.
                </li>
                <li>
                    The system notifies the client that the block has been executed.
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
