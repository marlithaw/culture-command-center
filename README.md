# Matchbook Culture Command Center

One workbook. Three boards. One design system. Open **index.html** to start.

## The three views
| File | View | Use it for |
|---|---|---|
| `launch_kit_dashboard.html` | Launch Kit Completion Dashboard | Executive readout: module readiness, KPIs, punch list, wins |
| `live_tracker.html` | Live Culture Tracker | Folder audit board: ten chains per folder (MET / PARTIAL / GAP / CLOSED) with evidence |
| `culture_dashboard.html` | Culture Macro Board | 182 session cards (Student Culture Camp + BOY Adult Calibration) with the full detail side panel |

## The single source of truth: Matchbook_Culture_Data.xlsx
- **Folders tab** → drives the Launch Kit Dashboard, Live Tracker, and Command Center stats
  (completion_pct, completion_status, punch_item as `HIGH | Title | Detail`, the ten chain columns, main_gap — prefix `CLOSED yyyy-mm-dd:` to land it on the Wins board)
- **Board_Cards tab** → drives the Macro Board
  (status: Built / Partial / Needs build · res_* columns: Built / Partial / Need / Yes · all detail text feeds the side panel)

Edit the workbook, save it beside the HTML files, refresh — every view updates together.
On the live site, re-upload only the workbook to update everything.

If a browser blocks local auto-loading, click **Load Data** in the nav of any page and pick
the workbook once — it is saved in the browser and shared by all views.

## Deploying
Upload index.html, the three board pages, and Matchbook_Culture_Data.xlsx to the same web root.

## Legacy files
`matchbook_tracker_data.csv`, `matchbook-system.css`, `culture-dashboard-enhancements.js`,
and `design-qa.md` are superseded by this bundle and safe to delete.
