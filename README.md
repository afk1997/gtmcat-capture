# GTMCat Capture — Chrome extension (beta · side-load)

**GTMCat Capture** reads Reddit through *your own* logged-in session and feeds high-intent conversations to [GTMCat](https://app.gtmcat.xyz). It is **read-only — it never posts, votes, or messages on your behalf.**

> ⏳ Beta build for testers while the Chrome Web Store review is pending. You install it manually as an *unpacked* extension — about a minute.

## Install (Chrome · Edge · Brave)

1. **Download** the latest **`gtmcat-capture-<version>.zip`** from **[Releases →](https://github.com/afk1997/gtmcat-capture/releases/latest)**.
2. **Unzip** it → you'll get a **`gtmcat-capture`** folder with a `manifest.json` inside.
3. Open **`chrome://extensions`** (paste it into the address bar).
4. Toggle **Developer mode** ON (top-right).
5. Click **Load unpacked** and pick the unzipped **`gtmcat-capture`** folder.
6. The GTMCat cat icon appears in your toolbar. ✅

## Connect your account

1. Sign up / log in at **[app.gtmcat.xyz](https://app.gtmcat.xyz)**.
2. Follow the in-app pairing prompt — it hands the extension a one-time token. **No passwords are ever shared with the extension.**
3. Stay **logged into reddit.com** in the same browser — the extension captures through your own session.

## Good to know

- Chrome may show a *"Disable developer-mode extensions"* notice on startup. That's expected for unpacked test builds — dismiss it.
- **To update:** download the newer zip, replace the folder, then hit **Reload** on the extension's card at `chrome://extensions`.
- **Permissions & ethics:** `reddit.com` (to read), `app.gtmcat.xyz` (its own backend), plus `storage`, `alarms`, `tabs`, `sidePanel`. It **reads only** — no posting, no voting, no other sites.

This repo hosts the ready-to-load build. The source lives in the private GTMCat monorepo.
