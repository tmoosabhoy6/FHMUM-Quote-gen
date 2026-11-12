# Ziyarat quotes

Per za'ir quotes for Karbala, Najaf, Cairo and Umrah groups. Enter the group size and flights, and the app works out nights, transport, visas, the Cairo Lawazim package and the Umrah days, then gives the price per adult, child and infant for every stay and takhfeef option. **Download Excel** produces the quote sheet in the usual layout, with live formulas.

The whole app is one file, `index.html`, served by GitHub Pages from the `main` branch.

## Where data is saved

| What | Where |
| --- | --- |
| The app | `main` branch, `index.html` |
| Rates | `data` branch, `rates.json` |
| Saved flights | `data` branch, `flights.json` |
| Saved quotes | `data` branch, `quotes/<id>.json` |

Quotes, rates and saved flights save on their own a couple of seconds after you stop typing. They always save in the browser first, so nothing is lost when offline, and then to the `data` branch once a computer is connected.

Because data lives on its own branch, you can edit, recommit and redeploy `main` as often as you like without touching saved quotes or causing merge conflicts. Don't delete the `data` branch.

## Connecting computers

The token is entered once, on the first computer:

1. Open the app and click **Saved on this device** at the top right.
2. Create a fine-grained token at <https://github.com/settings/personal-access-tokens/new>:
   - Repository access: **Only select repositories**, then pick this repository.
   - Permissions: **Contents**, set to **Read and write**.
3. Paste the token into the app and click **Connect**.

Every other computer uses the setup link: on the connected computer, click **Saved to GitHub**, then **Copy link**, and open that link once on the other computer. Saving turns on there by itself, and from then on the normal address works on that computer too.

The token is stored only in each browser and is never written to the repository. It travels inside the setup link after `#`, which browsers never send to a server, and the app removes it from the address bar as soon as the link opens. Anyone who has the setup link can change quotes and rates, so only send it to office staff. To cut off every computer at once, delete the token on GitHub and connect again with a new one.

## Rates

Rates come from the Faiz-e-Haakimi Qahera Lawazim (effective 29/08/2026 to 02/02/2027) and the Faiz e Husaini Iraq transport circular. Change them from **Settings** in the app. Changes apply to everyone once saved.

## Umrah, riyals and hotel tiers

- **Umrah** is found from the flights: landing in Jeddah or Madinah is a stay in Saudi Arabia. Days are counted from the arrival date to the departure date. Faiz lawazim (130 SR adult, 65 SR child a day sharing; 170 SR and 85 SR for an exclusive room in Makkah) has 15% VAT and 2.5% municipal tax on top, so a day is SR 153.24 an adult. Transport is one fee per adult or child for every transfer, from the circular's six routes and five group sizes, plus 15% VAT. The route is picked from the airports and can be changed. The Saudi visa is ₹12,000 a head, infants included.
- **Riyals**: every quote has a riyal rate next to the dollar rate (₹25 to start). The Excel sheet has a **SAR EXPENSES** block with its own **TOTAL SAR @RS.** row, under the USD block. A line item under Other charges can be in riyals too.
- **Hotel Nizam tiers**: ticking Hotel Nizam opens tiers **B**, **A** and **A+**. The Hubb is the same for all three; only the bed changes, $10, $22 or $40 a night for adults and children (infants nothing). Tick more than one to quote them side by side.

## Cairo stopovers

A family in the group that stays longer in Cairo is added under **Cairo stopovers**. Give them their head count, then press **Change** on each group flight they take on a different day (or add a flight only they take). Their Cairo package and Egypt visa are worked out from their own flights and head count; Iraq and Umrah lawazim, visa and transport stay with the group, priced on the whole group's size. They can also have their own ticket fare and their own Iraq or Cairo stay.

The group's prices are for everyone else. **Download Excel** gives the whole group's sheet, with each family's columns after the group's and highlighted. **Download their Excel** on a family gives that family's sheet alone, with their own flights.

## Saved flights

Typing a flight number fills in its route and departure and arrival times; only the date is left to type. The first time a flight number is used, type its route and times in full once and the app remembers it for every quote and every computer. Changing a time on a quote changes it for that quote only. To change or remove a saved flight for good, use **Settings**, then **Saved flights**.
