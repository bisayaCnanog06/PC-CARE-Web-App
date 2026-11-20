# PC CARE — Style Guide

## Visual direction

Use a quiet, practical school IT dashboard style: dark navy for navigation and
headings, teal for primary actions and selected states, white surfaces, and a
soft gray page background. Keep visual emphasis on ticket status and the
primary form action.

## Tokens

The shared tokens are defined at the top of `../prototype/css/style.css`.

| Token | Use |
|---|---|
| `--navy-950`, `--navy-800` | Sidebar and primary text |
| `--teal-700`, `--teal-600` | Primary actions and active navigation |
| `--gray-50` through `--gray-700` | Page background, borders, secondary text |
| `--white` | Cards and form surfaces |
| `--font-sans` | System sans-serif stack for readable, familiar typography |

## Components

- Sidebar navigation with simple inline line icons.
- Compact statistic cards and toolbar controls.
- Status and priority badges with text labels (not color alone).
- Bordered table with clear row actions; mobile rows become labeled cards.
- Form fields with visible labels, required indicators, and a validation example.

## Responsive behavior

At narrow widths, the sidebar becomes a compact top navigation and the ticket
table reflows into cards. The design is intended to fit a 390px viewport without
horizontal page scrolling.
