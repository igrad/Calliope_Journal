### Description
We have to load one or more pages on startup if they are prescribed by the temp (session) data file.

---
### Steps
1. Manually create demo temp file in project /Demo dir
2. Manually create demo Page.md file in project /Demo dir
3. In SessionDataManager, hardcode the path to the demo temp file
4. In MainWindow, call SessionData load func
5. Parse the cachedOpenPages and cachedActivePages
6. Make sure MainWindow maintains the openPages and ActivePages
7. Load page data into pageEditView

---
### Additional Notes
For now, we can just make a demo filei in the project directory and hard-code it to load. Later on, we can dynamically fetch prescribed file(s) on boot.

---
**Metadata**

| Data            | Value                     |
| --------------- | ------------------------- |
| Submitted by    | Ian                       |
| Submission date | April 20, 2022            |