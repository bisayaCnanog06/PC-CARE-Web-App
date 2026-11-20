# PC CARE — CRUD Map

The map below describes the wider intended product. Only the repair-ticket
list and add-form screens are represented in this static assignment.

| Area | Administrator | Technician | WS1 interface |
|---|---|---|---|
| Laboratories | Create, view, update, delete | View | Not implemented |
| Computers | Create, view, update, delete | View | Computer labels appear in ticket examples |
| Repair tickets | Create, view, update, delete | View assigned tickets; update progress | List and add-form mockups |
| Staff | Create, view, update, delete | View | Staff names appear in dropdown examples |
| Repair assignments | Manage assignments | View own assignments | Not implemented |
| Maintenance schedules | Manage schedules | View schedules | Not implemented |
| Status history | View ticket history | Record progress changes | Not implemented |
| Repair activities | View and manage activities | Record repair actions | Not implemented |
| Parts | Manage parts and stock | Check availability | Not implemented |
| Ticket parts | Manage parts used per ticket | Record parts used | Not implemented |

No destructive or persistent action is implemented. Ticket deletion should
preserve related repair history according to the final database policy.
