# FDT Calculator

Sand cone field density test calculator. It's an installable PWA that works fully offline.

Enter the lab parameters (MDD, OMC, sand bulk density, sand in cone, required compaction), then enter the field readings for each test point. The app works out moisture content, hole volume, wet and dry density and relative compaction, and marks each point pass or fail.

- Data is stored on the device (localStorage).
- Export results as CSV, share them, or print or save them as a PDF.
- After a change to any cached file, bump `VERSION` in `sw.js` so installed copies update.
