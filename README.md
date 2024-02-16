
![ZenFox Badge](assets/zenfox-repository-open-graph.png)

This is a fork of ArcFox intended to minimalism's lovers.
Expect fewer features, fewer buttons and fewer functionalities.

![ZenFox Screenshot](assets/zenfox-screenshot.png)

If you prefer the original that aims to resemble Arc Browser, project is here : https://github.com/betterbrowser/arcfox

# Installation

## Install Add-On

Use the official [Firefox Add-Ons store](https://addons.mozilla.org/firefox/addon/zenfox/).

## Install theme

For a fully immersive browsing experience, you'll want to incorporate a userChrome style into your Firefox profile.

To enable style modifications, simply follow these steps:

-    Open Firefox and type about:config into the search bar.
-    Locate "toolkit.legacyUserProfileCustomizations.stylesheets" and set its value to "true".

Next, let's integrate the userChrome file into the appropriate directory:

-    Type about:support into the Firefox search bar and click on the "Open Folder" button next to "Profile Folder".
-    If you don't already have a folder named "chrome" within the profile folder, create one.
-    Within the "chrome" folder, place the "userChrome.css" file (found in the theme folder).
-    Restart Firefox to apply the changes.

# Uninstall

1. Remove `(Firefox Profile)/chrome/userchrome.css`

2. Remove the 'ZenFox' extension from Firefox

3. Restart your Firefox session

# Donate to the original project

Support ArcFox and BetterBrowser in a financial way : donate to the developer [ko-fi](https://ko-fi.com/nikollesan) page

# License

ZenFox is based on Arcfox, so it is also distributed under [MIT License](./LICENSE).
