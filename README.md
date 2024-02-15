This is a fork of ArcFox intended to minimalism's lovers.
Expect less features, less buttons and less functionnalities.

If you prefer the original that aims to ressemble Arc Browser, project is here : https://github.com/betterbrowser/arcfox

# Installation

## Install Add-On

Use the official <a href="https://addons.mozilla.org/firefox/addon/zenfox/">Firefox Add-Ons</a> store.

## Install theme

For an immersive experience, you need to add a userChrome style in your Firefox profile.

Open your firefox configurations and turn style modification on by following this steps :

- Open <a href="about:config">"about:config"</a> on firefox (or type it in your address bar and click enter).
- On the search bar, search for "toolkit.legacyUserProfileCustomizations.stylesheets" and set the value to "true".

Now we'll add the userChrome in the right folder :

- Open <a href="about:support">"about:support"</a> and click on the “Open Folder” button on the right of "Profile Folder" to open it.
- When the folder opens, search for a folder called "chrome", if you don't find it create one.
- Inside the "chrome" folder, drop the "userChrome.css" file (from theme folder).
- Restart firefox.

# Uninstall

1. Remove `(Firefox Profile)/chrome/userchrome.css`

2. Remove the 'ZenFox' extension from Firefox

3. Restart your Firefox session

# Donate to the original project

Support ArcFox and BetterBrowser in a financial way : donate to the developer [ko-fi](https://ko-fi.com/nikollesan) page

# License

ZenFox is based on Arcfox so it is also distributed under [MIT License](/LICENSE).
