# Capacity-Planner

**VMware vSphere capacity planning** in the browser — a purpose-built planner that mirrors the logic in **`Capacity Planning worksheet.xlsx`**, without turning the spreadsheet into a giant HTML grid.

## Use it

1. Open **`index.html`** in your browser (double-click in File Explorer, or drag the file into Edge/Chrome).

   No install, no server, no npm, no Python.

2. Use the three tabs (**Capacity Provider**, **Capacity Consumer**, **Cost Comparison** — same names as the workbook; **Read Me** is not duplicated).

   The page content follows the workbook (section order and labels). Inputs use a light green field style; everything else updates as you type.

Figures update as you type. Nothing is saved or uploaded (all client-side).

## Workbook

Keep the **`.xlsx`** for full notes, the reservation model, and Excel-only details. The web app focuses on the main allocation story and indicative cost blocks.

## Repository layout

- **`index.html`** — the whole app (HTML + CSS + JS).
- **`Capacity Planning worksheet.xlsx`** — source workbook (optional local file; not loaded by the page).

There is no backend in this repo anymore.
