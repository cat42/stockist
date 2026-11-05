# stockist

A simple, phone-first app for keeping track of an emergency pantry and water supply.

Scan barcodes to add food, record expiry dates, and see at a glance how many days your supplies would last your household.

Current version: v0.1

Features
Barcode scanning with your phone camera. A USB barcode scanner also works by typing into the barcode box.
Product lookup from Open Food Facts. Items it doesn't know can be entered by hand once and are remembered after that.
Household setup: add each person's age, sex and activity level to get daily calorie estimates based on UK reference values. Pets count towards water needs.
Days of supply: total calories and litres of water in stock, and how long they would last.
Water tracking: containers, litres and refresh dates.
Expiry alerts: items are flagged as eat now (30 days) or use soon (90 days). Both periods can be changed.
Take out mode: scan an item to remove one, oldest date first, with undo.
Reduced rations setting: plan at, say, 75% of normal calories.
Backup export and import: save your data to a file or move it to another device.
Using it

Open the site on your phone, allow camera access, and choose Add to Home Screen from your browser menu so it opens like an app.

Camera scanning needs the page to be served over https. GitHub Pages does this automatically.

Your data

Everything is stored in your browser on the device you're using. Nothing is uploaded anywhere, apart from barcode numbers sent to Open Food Facts when you look up a product.

Clearing your browser data will erase your stock, so use Settings → Export backup regularly.

Planned
Nutrition breakdown and alerts for gaps (protein, fibre and so on)
Supplies checklist (batteries, medicines, gas, first aid) with check dates
Pantry station mode for a dedicated Linux laptop with a USB scanner
Shared stock between phone and laptop over home Wi-Fi
Credits
Product data from Open Food Facts, available under the Open Database Licence.
Barcode scanning by html5-qrcode, Apache 2.0 licence.
Licence

Released under the MIT Licence. You're free to use, change and share it, as long as the copyright notice is kept.
