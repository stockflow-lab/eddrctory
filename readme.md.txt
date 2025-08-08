
# ED Inventory Search

A simple, mobile-friendly search tool for locating consumable stock in the Emergency Department.  
Includes a quick link for staff to report low stock, expired items, or shortages via Microsoft Forms.

## How it works
- **index.html** → Main search interface
- **inventory.csv** → Inventory list (update as needed)
- **robots.txt** + `<meta name="robots" content="noindex, nofollow">` → Discourages search engine indexing

## Updating the inventory
1. Open the source Excel file.
2. Save As → **CSV UTF-8 (Comma delimited)**.
3. Replace the existing `inventory.csv` in this repo with the new file.
4. Commit changes — the site updates automatically.

## CSV format
The first row must have headers:

## Privacy Note
This site is public on the web via GitHub Pages.  
Do not include sensitive or patient-identifiable information.  

## GitHub Pages URL
https://github.com/mikhel-glitch/eddrctory/blob/main/Index1.html


## QR Code
Generate a QR code pointing to the URL above for staff convenience.

## License
Internal hospital use only.