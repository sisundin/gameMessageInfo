# gameMessage — Support

gameMessage is an iOS app with an iMessage extension for playing **chess**, **battleship** and **Gobang** (five in a row) with a friend. Every move is a plain text message made of emoji — there are no servers and no accounts.

## How to get help

- **Open an issue on this repository** (the *Issues* tab above) and describe what happened. Include your iOS version and, if possible, the board text of the game where the problem occurred.
- Or email **YOUR-SUPPORT-EMAIL-HERE**.

We aim to answer within a few days.

## Frequently asked questions

### The game panel in Messages opens empty

This can happen right after the app is installed or updated. **Force-quit the Messages app and open it again** — the panel will load normally. This is an iOS behavior around newly installed extensions, not something the app can fix from inside.

### How do moves actually travel?

Each move is an ordinary iMessage text containing the emoji board. You send it like any other message; your friend copies the received text and pastes it into the app (or just opens the extension — if a board is on the clipboard it's picked up automatically). The app contains **no networking code at all**.

### Can I play with someone who doesn't have the app?

Both players need the app to make moves, but the messages themselves are plain text — anyone can read them. Use the **Invite a friend** button to send an App Store link.

### Why does the app say a message is invalid?

The app checks every pasted board for correct format and legal moves, so a typo or an edited message is caught instead of corrupting the game. Ask your friend to re-copy and resend their last message exactly as the app produced it.

### Can we play more than one game at the same time?

You and a given friend play **one game at a time** (chess, battleship or Gobang) until it ends. You can have games going with different friends simultaneously.

### Does the app work outside iMessage?

Yes. The **Play** tab in the app hosts the same gameplay; its Send button copies the message text to the clipboard so you can paste a move into any chat app.

---

# Privacy Policy

**Effective date: October 17, 2026**

gameMessage is built so that we cannot see your data, because the app never talks to us — or to anyone else.

## What we collect

**Nothing.** The app contains no networking code. It makes no network requests, has no servers, no accounts, no analytics, no advertising, and no third-party SDKs. We receive no information about you or your games.

## What stays on your device

- **Games and statistics** are stored locally on your device, encrypted. They never leave your device except as the text messages you choose to send.
- **Your player identity** is a short ID derived from a key pair generated on your device. The key is stored in your iCloud Keychain, so it syncs between your own devices through your Apple account. It is protected by Apple's Keychain security and is never sent to us.

## Messages

Moves travel as ordinary iMessage (or other messaging app) text messages that you send yourself. Those messages are handled by your messaging provider (for iMessage, Apple) under its own privacy policy, exactly like any other text you send. The app only reads board text that you paste into it.

## Children

The app collects no data from anyone, including children.

## Changes

If this policy ever changes, the new version will be published at this same address with an updated effective date. Since the app has no way to collect data, any change would require a new app version and would be reflected here first.

## Contact

Questions about this policy: open an issue on this repository or email **YOUR-SUPPORT-EMAIL-HERE**.
