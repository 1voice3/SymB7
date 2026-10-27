SymB7 – Symbio 700 Service App Simulator (Training Tool)
Independent training simulator – not the official Trane app. Always follow the unit nameplate and current Trane documents.

FILES (keep all in the same folder)
  index.html                         The simulator (board photo built in)
  manual.html                        User Guide viewer with highlighted wording (BAS-SVU054C-EN)
  BAS-SVU054C-EN.pdf                 Symbio 700 User Guide
  Foundation_ACC-APG004B-EN.pdf      Foundation application guide
  Odyssey_ACC-APG001C-EN.pdf         Odyssey application guide
  Precedent_ACC-APG002E-EN.pdf       Precedent application guide
  Voyager3_BAS-APG048D-EN.pdf        Voyager 3 application guide
  SymB7-index.txt                    Text copy of index.html
Each PDF is under GitHub's 25 MB browser-upload limit. Upload them one or a few at a time if the page is slow.

EASY START
  1. Home screen: pick Foundation, Odyssey, Precedent, Voyager or General Info.
  2. Data > Unit: type model, serial, firmware; pick the configuration (points, tests and alarms change to match).
  3. Data > Trend data: drag & drop or choose a trend .CSV, then tap "Simulate trends".
  4. Board / LEDs / App / Menu react to the trend. Data > Points lets you change any value, including WRITE-ONLY BAS commands.
  5. Learn is in every category. Files holds your own files, links, pictures and notes (any file type). Every category has a search bar.

NOTES
  - Starting values are typical defaults, not factory data. Edit them or let your trend override them.
  - Trend columns are matched to points by name; change any match under Data > Trend data > Columns -> points.
  - Your files, unit info and trends are saved in this browser (IndexedDB / local storage) on this device only.
  - Links open in the same tab: swipe from the left edge of the screen to come back.
