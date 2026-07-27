# 🍽️ TrinkSplit

**TrinkSplit** combines the German word **Trink**geld (tips) and the English word **Split**, because that's exactly what it does. A fast, no-nonsense tool for splitting pooled tips fairly among restaurant staff based on hours worked.

No app install. No account. No internet required after loading. Just open the file and go.

## Features

- Enter shift times (e.g. `1130`, `17:30`) or hours directly, whichever you prefer
- Full **Teildienst / split shift** support, add a second shift per person
- Automatic **Küche Tax** deduction before splitting
- Rounds down to the nearest **€0.50** for clean cash payouts, remainders go to the kitchen
- Shows a single **total to hand to the kitchen** (tax + all remainders combined)
- Export to **Excel (.xlsx)** or **copy for Google Sheets** in one click
- **Import** previously exported data back into the calculator
- Saves history locally so you can browse and re-export past dates anytime
- Fully bilingual: **Deutsch / English** toggle
- Works on desktop and mobile

## How it works

1. Enter the date and total tips collected for the day
2. Set a kitchen tax percentage if applicable
3. Add each staff member and their shift times (or hours directly)
4. TrinkSplit calculates each person's share proportionally
5. Each payout is rounded down to the nearest €0.50 and the leftover cents are added to the kitchen total
6. Export or save the result

## Self-hosting

TrinkSplit is a single HTML file with no dependencies to install.

**Netlify (recommended, free):**
1. Rename the file to `index.html`
2. Go to [netlify.com/drop](https://netlify.com/drop)
3. Drag and drop the file onto the page
4. Done, you'll get a live URL in seconds

**GitHub Pages:**
1. Upload `index.html` to a public repository
2. Go to Settings → Pages → select branch `main` → Save
3. Your site will be live at `https://your-username.github.io/TrinkSplit`

**Local use:**
Just open `index.html` in any browser. No server needed.

## Built with

Made using [Claude Sonnet 4.6](https://www.anthropic.com) by **MNA**

## License

This project is licensed under the GNU General Public License. See the `LICENSE` file for details.
