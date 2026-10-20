# Pinterest bulk upload: owner steps

Bulk upload only works on a **desktop browser** (pinterest.com) with a **Business account**.

## 0. Get the CSV
Download https://buckyproducts.github.io/pins/pinterest-bulk.csv to your computer (right-click → Save link as). Don't open it in Excel and re-save it, because that can break the accents and the dates.

## 1. Business account
If you don't have one yet: Profile → Settings → Account management → **Convert to business account**. Use the profile name "Bucky Little Shop | Printables & Party Kits".

## 2. Create the 6 boards (on desktop or in the app)
Go to your profile → **Saved** → **+** → **Board**. Type each name **exactly** as shown (copy and paste), and paste the description from boards.md under the board's ⋯ → Edit:
1. `Halloween Party Printables`
2. `Halloween y Día de Muertos Imprimibles`
3. `Day of the Dead - Día de Muertos`
4. `Christmas Party Printables`
5. `Navidad y Posadas Imprimibles`
6. `AI Prompts & Teacher Tools - Prompts IA`

(Boards 3 and 6 use " - " in place of the " / " in boards.md. In the CSV, Pinterest reads a "/" as "Board/Section", so a slash would create the wrong board.) If a board is missing, the upload creates it, but making the boards first lets you add descriptions.

## 3. Upload the CSV
1. On pinterest.com, click **Create** (top left, or the + in the sidebar) → **Create Pin** opens the Pin builder.
2. Choose the **Bulk create Pins** option (in the Create menu / Pin builder, or at business.pinterest.com → Create → Bulk create Pins).
3. Click **Upload .csv file** and select `pinterest-bulk.csv`.
4. Pinterest emails you when processing finishes. Check **Profile → Created / scheduled pins** (Create → Scheduled Pins).

## 4. Schedule built into the CSV
The 31 pins post 4 a day at 14:00, 17:00, 20:00 and 23:00 UTC (9am, 12pm, 3pm and 6pm Mexico City), Oct 21–28, 2026. Starts with Halloween micro products (treat toppers, door signs, kids pack, cupcakes), then Muertos, Christmas/Secret Santa, bingo, games, megapack and AI/teacher tools. Pins whose time has already passed when you upload go live immediately.
**If Pinterest reports a date error:** open the CSV in a text editor, clear the "Publish date" column, and upload in batches of 4 a day instead.

## 5. After uploading
Spot-check 2 or 3 pins: the image shows, the link opens Gumroad, and the pin is on the right board.
