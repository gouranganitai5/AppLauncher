# My-App-Hub

A GitHub Pages-ready package containing an animated launcher and 6 independent static web applications, generated with Crate.

## Structure

```
index.html        # animated launcher (this repo's root page)
apps.json         # launcher manifest
README.md
apps/
  unit-test-result-sheet-maker-v1-0/
    index.html
  khata-daily-expense-manager/
    index.html
  martingale-risk-strategy-calculator/
    index.html
  sp125-care/
    index.html
  question-generator-v8/
    index.html
  json-student-data-to-excel/
    index.html
```

## Applications

- **Unit Test Result Sheet Maker v1.0** — `apps/unit-test-result-sheet-maker-v1-0/` — Select two or more Marks Columns to enter their marks for the same student together, one student at a time.
- **Khata — Daily Expense Manager** — `apps/khata-daily-expense-manager/` — This action cannot be undone.
- **Martingale Risk Strategy Calculator** — `apps/martingale-risk-strategy-calculator/` — Martingale Risk Strategy Calculator
- **SP125 Care** — `apps/sp125-care/` — Honda SP125 Bike Maintenance Manager
- **Question Generator v8** — `apps/question-generator-v8/` — A static web application for Question Generator v8.
- **JSON Student Data to Excel** — `apps/json-student-data-to-excel/` — Upload your JSON file to filter Roll No and Student Name into an Excel spreadsheet.

## Deploy to GitHub Pages

1. Extract the ZIP.
2. Copy the extracted files into the root of your GitHub repository.
3. Commit and push.
4. In the repository's **Settings → Pages**, enable GitHub Pages for the branch you pushed to.
5. Open the published GitHub Pages URL — `index.html` at the root loads the animated launcher.
6. Select any application from the launcher to open it; each one runs independently from its own folder under `apps/`.

The launcher reads `apps.json` at load time, so adding, removing, or reordering applications later only requires editing that file and the `apps/` folder — no launcher code changes needed.
