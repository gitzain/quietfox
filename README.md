# Quietfox 🦊
A minimalist Zen Firefox userChrome style that streamlines context menus for a cleaner, distraction-free browsing experience.

## Table of Contents
- [Motivation](#bulb-motivation)
- [Installation & Usage](#rocket-installation--usage)
- [Contributing](#handshake-contributing)
- [History](#scroll-history)
- [Credits](#clap-credits)
- [License](#receipt-license)

## :bulb: Motivation
Quietfox is designed to simplify and declutter Firefox’s interface, giving users a minimalist browsing experience. By hiding rarely used context menu items and toolbar elements, it reduces distractions and streamlines common workflows.

The style targets Zen-like productivity, making your Firefox environment feel cleaner and more focused without altering core functionality.

## :rocket: Installation & Usage
1. Locate your Firefox profile folder:  
   - Type `about:support` in the address bar.  
   - Click **Open Folder** next to "Profile Folder".  
   - Create a `chrome` folder if it doesn’t already exist.

2. Save this file as `userChrome.css` inside the `chrome` folder.

3. Enable custom stylesheets:  
   - Go to `about:config`  
   - Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`

4. Optional — enable live editing (for developers/debugging):  
   - Enable `devtools.chrome.enabled` → `true`  
   - Enable `devtools.debugger.remote-enabled` → `true`  
   - Open Developer Tools (⌘+⇧+⌥+I on Mac or Ctrl+Shift+Alt+I on Windows/Linux)  
   - Use the "Style Editor" tab to edit `userChrome.css` live.

5. Restart Firefox to apply the changes.

## :handshake: Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Added some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## :scroll: History
07/10/25: v1 published to github.  

## :clap: Credits
- Created by <a href="https://iamzain.com">Zain Khan</a>
- Template for this README is <a href="https://github.com/gitzain/template-README">template-readme</a> created by <a href="https://iamzain.com">Zain Khan</a>

## :receipt: License
See the LICENSE file in this project's directory.
