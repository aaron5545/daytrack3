# Daytrack 3

Day tracker with tasks, hours worked and a goal countdown in one view.

Live: https://aaron5545.github.io/daytrack3/

- Single self-contained `index.html`, no backend. Data stays in your browser (storage key `daytrack3.v1`).
- First launch copies data once from Daytrack 2 (`daytrack2.v1`), or Daytrack 1 (`daytrack.v1`) if there is no v2 data.
- Log hours at the bottom of each day column (1-hour steps).
- Goal panel: days left, average and total hours, and aligned task-success and hours bars per day. Click a day to open it.
- To update: replace `index.html` and commit to `main`; Pages redeploys in about a minute.
