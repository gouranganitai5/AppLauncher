# Static-Final-Web-Apps

A GitHub Pages-ready package containing an animated launcher and 11 independent static web applications, generated with Crate.

## Structure

```
Static-Final-Web-Apps/
index.html        # animated launcher (this repo's root page)
apps.json         # launcher manifest
README.md
apps/
  teacher-s-class-routine-timetable/
    index.html
  unit-test-result-sheet-maker-v1-0/
    index.html
  stackroom-school-library-system/
    index.html
  question-generator-v8/
    index.html
  sp125-care/
    index.html
  khata-daily-expense-manager/
    index.html
  martingale-risk-strategy-calculator/
    index.html
  crate-static-web-app-launcher-builder/
    index.html
  image-to-svg-converter/
    index.html
  json-student-data-to-excel/
    index.html
  universal-github-gist-sync-module/
    index.html
```

## Applications

- **Teacher's Class Routine & Timetable** — `apps/teacher-s-class-routine-timetable/` — A static web application for Teacher's Class Routine & Timetable.
- **Unit Test Result Sheet Maker v1.0** — `apps/unit-test-result-sheet-maker-v1-0/` — A static web application for Unit Test Result Sheet Maker v1.0.
- **Stackroom — School Library System** — `apps/stackroom-school-library-system/` — Stackroom — School Library System.
- **Question Generator v8** — `apps/question-generator-v8/` — Question Generator v8.
- **SP125 Care** — `apps/sp125-care/` — Honda SP125 Motorcycle Maintenance & Service Manager
- **Khata — Daily Expense Manager** — `apps/khata-daily-expense-manager/` — Khata — Daily Expense Manager, packaged as an independent static app.
- **Martingale Risk Strategy Calculator** — `apps/martingale-risk-strategy-calculator/` — Martingale Risk Strategy Calculator
- **Crate — Static Web App Launcher Builder** — `apps/crate-static-web-app-launcher-builder/` — App Launcher Builder
- **Image to SVG Converter** — `apps/image-to-svg-converter/` — Convert images to vector SVG, customize background color, and resize by dragging or manual inputs
- **JSON Student Data to Excel** — `apps/json-student-data-to-excel/` — Upload your JSON file to filter Roll No and Student Name into an Excel spreadsheet.
- **Universal GitHub Gist Sync Module** — `apps/universal-github-gist-sync-module/` — Open Universal GitHub Gist Sync Module to get started right away.

## Deploy to GitHub Pages

1. Extract the ZIP.
2. Copy the contents of `Static-Final-Web-Apps/` into the root of your GitHub repository.
3. Commit and push.
4. In the repository's **Settings → Pages**, enable GitHub Pages for the branch you pushed to.
5. Open the published GitHub Pages URL — `index.html` at the root loads the animated launcher.
6. Select any application from the launcher to open it; each one runs independently from its own folder under `apps/`.

The launcher reads `apps.json` at load time, so adding, removing, or reordering applications later only requires editing that file and the `apps/` folder — no launcher code changes needed. The footer application count and the category filter chips are built from it too, so they stay correct without a rebuild.
