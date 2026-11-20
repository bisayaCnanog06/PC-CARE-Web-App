# PC CARE — Project Brief

## Purpose

PC CARE is intended to help school computer laboratories organize computer
repair and maintenance records, assignments, activities, status changes, and
spare-parts use.

## Current assignment scope

This WS1 deliverable is a static HTML/CSS interface with two pages:

- A repair-ticket list with search and filter controls, five sample records,
  View/Edit/Delete controls, and an empty-state example.
- An Add Repair Ticket form with required indicators, foreign-key dropdowns
  showing readable names, and a visible example validation message.

No page connects to a database. Controls are visual examples; JavaScript,
PHP, and MySQL are intentionally out of scope.

## Data assumptions

The original SQL file was not supplied. The chosen proposal deck describes
`REPAIR_TICKET` fields as `Ticket_ID`, `Computer_ID`, `Reported_By`,
`Date_Reported`, `Problem`, `Priority`, and `Current_Status`. This list is
provisional. Computer and ticket samples are fictional. Staff display names
were supplied for this interface and have not been verified against the
database.

The required ten table names are documented in `../database/schema.sql`, but
their actual columns, key definitions, and constraints must be verified against
the authoritative SQL before implementation.
