# GiveTouch — The Sandringham Shul (demonstration)

**Live demo:** https://givetouch-sandringham-demo.onrender.com/

An English-only, portrait-friendly, green/white/gold donation and Shabbat information kiosk prototype. This project is a **demonstration**, not an authorised or live payment product.

## Try the screens

- Default page: automatic mode (donations outside Shabbat, informational Shabbat screen during Shabbat in Johannesburg).
- `?preview=weekday`: sample weekday donation flow.
- `?preview=shabbat`: sample Shabbat information screen.
- `?admin=1`: type prayer times in English, one per line, and save them **on that device only**.

## Features in the demo

- "Tap to Donate" button, choose an amount in ZAR, review and **simulate** payment.
- No banking credentials are collected; no real payments or funds transfer.
- Shabbat information display shows prayer times and Hebcal-calculated candle-lighting/Havdalah for Johannesburg, when available.
- Shabbat Mevarchim information from Hebcal appears only when calendar events contain it; missing data is not invented.
- Automatic switch to a non-interactive Shabbat mode between candle-lighting and Havdalah. Uses conservative Friday/Saturday fallback while online calendars are unavailable.
- Home-screen support and basic offline cache.

## Before production or accepting real donations

1. Obtain authorisation from Sandringham Shul to use its official identity/logo, branding, donation programmes and banking details. The double-S and square-armed menorah are an original *placeholder motif*, not a verified reproduction of an official logo.
2. Confirm Shabbat candle lighting and Havdalah conventions, prayer schedule, holiday handling and rabbinic approval of the physical display.
3. Add authentication, multi-device synchronisation, audit history and a secure admin backend; browser-local schedule storage is not a production workflow.
4. Set up an approved FNB or other South African merchant acquiring account **in the beneficiary association's name**, complete bank onboarding, certified kiosk/contactless integration and bank-confirmed transaction callbacks.
5. Agree donation receipts (including Section 18A only if authorised), privacy, financial reporting, merchant fees, support and reconciliation.
6. Test on target 18.5-inch screen and any connected certified card reader.

### Important

**Simply entering a bank account number or IBAN does not enable tap-to-pay**. A contracted and certified merchant gateway or terminal integration is required. No payment should be represented as successful before bank confirmation.

Calendar times from https://www.hebcal.com/ are used under CC BY 4.0 (attribution is displayed within the app). Verify local custom independently.
