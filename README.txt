Budget Tracker v7 - Backup & Restore

New features:
- Export Data: saves monthly budget, budget history, carryover start month, carryover history calculations, and all transactions to a JSON backup file.
- Import Data: restores that backup into another copy of the app.
- Pay From: Monthly Budget or Carryover Balance.
- Editable transactions and editable monthly budget remain included.

IMPORTANT FOR EXISTING PHONE DATA:
1. Update the Home Screen app/site to this version without deleting the existing app or clearing Safari website data.
2. Open the copy that still shows your transactions.
3. Tap Export Data and save the JSON file to Files/iCloud Drive.
4. Open the fresh GitHub/Safari copy, tap Import Data, and select that backup file.

Updating files at the same GitHub Pages URL should not intentionally erase localStorage, but export is the safest way to preserve and move data.

V8: Fixed per-category colors shared by pie chart and legend. Added Electronics, Tools, Clothes, Furniture, and Gun Stuff.

V9: Added individual Delete buttons for transactions, with confirmation before deletion.

V10: Monthly-budget overspending now rolls forward as debt and is deducted from the next month's base budget. Carryover stays separate and is only spent when Pay From: Carryover Balance is selected. Debt larger than one month's budget continues rolling forward until future monthly budgets absorb it.

V11: Added Previous, Next, and Current month navigation. Historical months show their own budget, spending, remaining balance, category chart, transactions, carryover, and rollover debt. Current jumps back to the present month. Existing backup/import and transaction editing remain intact.
