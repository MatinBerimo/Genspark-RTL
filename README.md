# RTL Toggle Extension for Deepseek & Genspark

This Chrome extension allows users to toggle the text direction on websites chat.deepseek.com and genspark.site from LTR (Left-to-Right) to RTL (Right-to-Left) for better readability in languages like Persian or Arabic.

## Extension Purpose

This extension addresses the RTL display issues on Deepseek and Genspark platforms, making them more accessible for users of right-to-left languages such as Persian and Arabic. By toggling the text direction, it provides a better reading and interaction experience when using these platforms in RTL languages.

## How It Works

- After installing the extension, a browser icon will appear in the Chrome toolbar.

- When visiting deepseek.com or genspark.site, click the extension icon.

- The extension will switch the website's text direction to RTL, making it more suitable for right-to-left languages.

- Clicking the icon again will reset the text direction to its default LTR layout.

- The extension's icon changes to indicate the current text direction state.

## Features

- Simple one-click toggle between RTL and LTR text directions
- Visual indicator through icon change to show current direction setting
- Preserves LTR direction for code blocks to maintain proper code display
- Automatically applies settings when revisiting supported websites
- Works specifically with chat.deepseek.com and genspark.site domains

## How to Install the Extension

### Method 1: Install from Chrome Web Store
1. Visit the Chrome Web Store (link to be added when published)
2. Click "Add to Chrome"
3. Confirm by clicking "Add extension" in the popup

### Method 2: Install in Developer Mode
1. Download the extension files to your computer
2. Open Chrome and go to `chrome://extensions/`
3. Enable "Developer mode" using the toggle in the top-right corner
4. Click "Load unpacked" and select the folder containing the extension files
5. The extension should now appear in your browser toolbar

## Usage Instructions

1. Navigate to either chat.deepseek.com or genspark.site
2. Click the extension icon in the toolbar to toggle RTL mode
3. The icon will change to indicate the current text direction
4. Refresh the page if necessary for the changes to take full effect
5. Click again to switch back to LTR mode

## Technical Notes

- The extension uses Chrome's storage API to remember your preference for each domain
- It specifically targets chat.deepseek.com and genspark.site domains
- Code blocks are automatically kept in LTR direction for proper code display
- The extension applies changes to the page's CSS direction property

## Troubleshooting

If the extension doesn't seem to be working:
- Make sure you're on a supported website (chat.deepseek.com or genspark.site)
- Try refreshing the page after clicking the extension icon
- Check if the extension is enabled in your Chrome extensions page
- Clear browser cache and reload the page

## Privacy

This extension:
- Does not collect any user data
- Does not communicate with external servers
- Only accesses and modifies content on the specified domains
- Requires minimal permissions (storage, scripting, activeTab)

## Feedback and Contributions

For bugs, feature requests, or contributions, please open an issue or pull request on the GitHub repository.

---

Developed to improve accessibility for RTL language users on AI conversation platforms.