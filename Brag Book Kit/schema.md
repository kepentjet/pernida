# Brag Book Schema

One row per contribution. Columns in this order:

| Column | Format | Notes |
|---|---|---|
| Date | YYYY/MM/DD | Date the work was done or delivered |
| Project/Area | Text | Project, team, or area of work |
| Task | Text | Short name of the task |
| Contribution | Text | What Michael did, in his own role |
| Stakeholders | Text | People involved or who benefited. Use names in the work copy and roles in the personal copy |
| Impact Categories | Revenue, Cost, Time, Automation | Pick one or more. Separate with ", " |
| Business Impact | Bullets | One bullet per line, each starting with "- " |
| Praises | Text | Written praise, quoted exactly, with who said it |
| Skills | Text | Tools used or learned. Separate with ", " |
| Visibility | Team, Cross-team, Leadership, External | Most senior level that saw the work |

## CSV rules

- UTF-8, comma-separated, header row first.
- Wrap any value that has a comma or a line break in double quotes.
- Business Impact keeps its bullets on separate lines inside one quoted cell.

## Impact Categories

- Revenue: brought in, grew, or protected income
- Cost: cut or avoided spending
- Time: saved hours for Michael or others
- Automation: replaced a manual step with a system

Adjust this list to match each company's performance review criteria. See `setup-checklist.md`.

## Example row

| Column | Value |
|---|---|
| Date | 2026/09/18 |
| Project/Area | Sales Operations |
| Task | Weekly pipeline report |
| Contribution | Built a script that pulls CRM data and generates the weekly pipeline report |
| Stakeholders | Head of Sales, 4-person sales ops team |
| Impact Categories | Time, Automation |
| Business Impact | - Cut weekly report prep from 6h to 1h<br>- Removed copy-paste errors from the Monday leadership deck |
| Praises | "This saves my Monday morning." Head of Sales, Slack |
| Skills | Python, CRM API, Google Sheets |
| Visibility | Leadership |

This row is an example. It is not a real entry.
