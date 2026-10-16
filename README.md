# dues-tracker

A lightweight, browser-based tracker for recording shared dues and payments between you and other people. It keeps a running balance for each person and can create payment QR codes and PDF statements.

## Features

- Track multiple people and their individual balances.
- Record dues and payments in either direction, with an optional note and date.
- Correct an entry's direction or delete an entry.
- See per-person balances and combined totals.
- Add your name and UPI ID to generate a payment QR code when someone owes you.
- Download a PDF statement with the balance and transaction history.
- Switch between light and dark themes.
- Save data in your browser so it remains available when you reopen the page.

## Getting started

Open `Due.html` in a modern web browser. No installation or build step is required.

The PDF and QR-code features use libraries loaded from CDNs, so those features require an internet connection. The rest of the app can be used without a server.

## Using the app

1. Enter a person's name in **Add a person** and select **Add**.
2. Choose **Due** or **Payment**, then select the direction.
3. Enter an amount and, if useful, a note and date; select **Add** to save the entry.
4. Set your name and UPI ID under **From (you)** to personalize statements and enable payment QR codes.
5. Select **Download PDF** on a person's page to export their statement.

Use the direction-switch control on an entry to correct its direction. Removing a person requires a second confirmation.

## Data and privacy

People, entries, preferences, and theme settings are stored locally in the browser using `localStorage`. They are not synced between browsers or devices. Clearing the browser's site data will remove the saved information, so keep downloaded PDF statements if you need a separate record.
