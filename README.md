# AC Complaint Dashboard — 2nd Floor A Zone

## Use
1. Open the GitHub Pages site.
2. Click **Upload Excel**.
3. Select the monthly complaint file.
4. The dashboard reads these columns from your current file format:
   `date`, `time`, `zone`, `desk`, `NAME`, `HOT/COLD`.
5. Review the AC markers and the **Unmapped complaints** warning.

## Important
The Desk → AC master is in `mapping.json`. It must be validated against the engineering drawing before operational use. Any desk not in the master is deliberately shown as **unmapped** instead of being silently assigned.

## GitHub Pages
Upload all files to the repository root, then Settings → Pages → Deploy from branch → `main` / root.

## Privacy
Complaint rows are processed in the browser. The app does not send the uploaded Excel to a backend.
