# Tab Out

Tab Out is a Chrome popup that cleans up the current window in one click.

Open the extension and it immediately organizes repeated sites into Chrome tab groups. Single tabs stay ungrouped, pinned tabs stay untouched, and you still keep the useful cleanup tools from the original project.

## What It Does

- groups only repeated sites in the current window
- leaves one-off tabs alone
- keeps pinned tabs and browser pages untouched
- lets you jump to tabs, close tabs, and remove duplicates
- keeps the save-for-later list inside the popup
- uses a dark, compact popup layout instead of replacing the new tab page

## Install

```bash
git clone https://github.com/meetshukla/tab-out.git
cd tab-out
```

Then:

1. Open `chrome://extensions`
2. Turn on **Developer mode**
3. Click **Load unpacked**
4. Select the `extension/` folder

## How It Works

1. Click the **Tab Out** extension icon
2. The popup opens and immediately scans the current window
3. Any site with more than one tab gets grouped together
4. Single tabs remain loose so the tab strip stays readable
5. Use the popup cards to focus, close, dedupe, or save tabs for later

## Tech

- Chrome Manifest V3
- `chrome.tabs`
- `chrome.tabGroups`
- `chrome.storage.local`

## Notes

- No server
- No account
- No external API calls

## License

MIT
