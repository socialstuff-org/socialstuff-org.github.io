<table>
    <tr>
        <td>
            <strong>Name</strong>
        </td>
        <td>
            Update report reason
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
                <a href="../../services/backend/reporting.md">Settings Service</a>
            </td>
        </tr>
    <tr>
        <td>
            <strong>Description</strong>
        </td>
        <td>
            This use case describes the procedure of updating a report reason
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
                   The system receives the task to update a report reason
                </li>
                <li>
                    The system validates the new attributes of the report reason
                </li>
                <li>
                    The system updates the report reason.
                </li>
                <li>
                    The system notifies the client that the reason has been edited successfully.
                </li>
            </ol>
        </td>
    </tr>
    <tr>
        <td>
            <strong>Result</strong>
        </td>
        <td>
            A report reason has been updated
        </td>
    </tr>
    <tr>
        <td>
            <strong>Exceptions</strong>
        </td>
        <td>
            <li>
                The new attributes are invalid
            </li> 
            <li>
                The system notifies the user that the attributes are invalid
            </li>          
        </td>
    </tr>
</table>
