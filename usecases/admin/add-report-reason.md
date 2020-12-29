<table>
    <tr>
        <td>
            <strong>Name</strong>
        </td>
        <td>
            Create report reason
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
            This use case describes the procedure of creating a report reason
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
                   The system receives a report reason
                </li>
                <li>
                    The system validates the report reason.
                </li>
                <li>
                    The system adds the report reason.
                </li>
                <li>
                    The system notifies the client that the reason has been added.
                </li>
            </ol>
        </td>
    </tr>
    <tr>
        <td>
            <strong>Result</strong>
        </td>
        <td>
            A report reason has been added
        </td>
    </tr>
    <tr>
        <td>
            <strong>Exceptions</strong>
        </td>
        <td>
            <li>
                The reason contains invalid attributes
            </li>   
            <li>
                The system notifies the client about the invalid attributes
            </li>             
        </td>
    </tr>
</table>
