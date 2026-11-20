# PC CARE — WS1 Static Interface

A beginner-friendly static HTML and CSS interface for the PC CARE repair-ticket workflow.
Open `prototype/list.html` or `prototype/form.html` directly in a browser; no
server, JavaScript, PHP, or database connection is required.

## Project structure

- `prototype/list.html` — responsive repair-ticket list with search/filter controls,
  sample records, row actions, and an empty-state example.
- `prototype/form.html` — Add Repair Ticket form.
- `prototype/css/style.css` — shared styles and design tokens.
- `database/schema.sql` and `database/seed.sql` — source-status notes; they are
  intentionally not executable schema or seed scripts.
- `docs/` — brief, CRUD map, design guide, and wireframe notes.
- `docs/03-sitemap.png` and `docs/03-user-flow.png` — project diagrams.

## Schema and sample-data note

The original SQL database was not present in the project folder. The selected
proposal deck documents these `REPAIR_TICKET` fields:
`Ticket_ID`, `Computer_ID`, `Reported_By`, `Date_Reported`, `Problem`,
`Priority`, and `Current_Status`. These are treated as **provisional** until
checked against the authoritative database. The separate 10-table proposal
found nearby uses different ticket columns, so it was not silently merged into
this interface.

Ticket IDs, computer labels, dates, and descriptions displayed in the HTML are
fictional presentation examples, not records copied from the database. Staff
display names were supplied for this interface and are not verified employee
records. The form’s dropdowns use readable computer and staff names while their
option values illustrate the corresponding foreign-key IDs.

Before creating or connecting a database, replace the notes in `database/` with
the actual DDL and approved seed data. No database columns, keys, or
relationships are asserted by this static assignment.

## Scope

This deliverable implements only the two static pages for the current WS1
assignment. Search, filters, row actions, and saving are visual-only and do not
perform operations.
