# Ziyarat quotes

Per za'ir quotes for Karbala, Najaf and Cairo groups. Enter the group size and flights, and the app works out nights, transport, visas and the Cairo Lawazim package, then gives the price per adult, child and infant for every stay and takhfeef option. **Download Excel** produces the quote sheet in the usual layout, with live formulas.

The whole app is one file, `index.html`, served by GitHub Pages from the `main` branch.

## Where data is saved

| What | Where |
| --- | --- |
| The app | `main` branch, `index.html` |
| Rates | `data` branch, `rates.json` |
| Saved quotes | `data` branch, `quotes/<id>.json` |

Quotes and rates save on their own a couple of seconds after you stop typing. They always save in the browser first, so nothing is lost when offline, and then to the `data` branch once a computer is connected.

Because data lives on its own branch, you can edit, recommit and redeploy `main` as often as you like without touching saved quotes or causing merge conflicts. Don't delete the `data` branch.

## Connecting a computer

Each computer connects once:

1. Open the app and click **Saved on this device** at the top right.
2. Create a fine-grained token at <https://github.com/settings/personal-access-tokens/new>:
   - Repository access: **Only select repositories**, then pick this repository.
   - Permissions: **Contents**, set to **Read and write**.
3. Paste the token into the app and click **Connect**.

The token is stored only in that browser and is never written to the repository.

## Rates

Rates come from the Faiz-e-Haakimi Qahera Lawazim (effective 29/08/2026 to 02/02/2027) and the Faiz e Husaini Iraq transport circular. Change them from **Rates** in the app. Changes apply to everyone once saved.
