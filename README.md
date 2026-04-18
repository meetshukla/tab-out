# Tab Out

**Keep tabs on your tabs.**

Tab Out is now a Chrome popup instead of a new-tab replacement.

Click the toolbar icon and it will:

- regroup the current window into Chrome tab groups by site
- keep the original Tab Out cleanup UI, duplicate cleanup, save-for-later list, and quick tab actions
- show the result in the same familiar layout, now tuned into a darker, more minimal popup

## Install

1. Clone the repo

```bash
git clone https://github.com/zarazhangrui/tab-out.git
cd tab-out
```

2. Open `chrome://extensions`
3. Turn on **Developer mode**
4. Click **Load unpacked**
5. Select the `extension/` folder

## How it works

- Click the **Tab Out** icon in Chrome
- The popup opens and immediately groups the current window by site
- Use the cards to jump to tabs, close them, remove duplicates, or save them for later
- Click **Group again** in the popup banner any time you want to rerun the grouping pass

## Notes

- Built with Chrome Manifest V3
- Uses `chrome.tabs`, `chrome.tabGroups`, and `chrome.storage.local`
- No server, no account, no external API calls

## License

MIT
