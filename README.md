# Firefox Customisation

## Enable
### Enable custom stylesheets
1. Navigate to `about:config`
2. Find `toolkit.legacyUserProfileCustomizations.stylesheets`
3. Toggle option to `true`

### Create custom stylesheet
1. Navigate to `about:support` or `about:profiles`
2. In section `Profile Folder`, select `Open Folder`
3. In `Profile Folder`, create `chrome/userChrome.css`

### Add custom styles
1. Update `userChrome.css`
2. Restart Firefox

## Disable
1. Rename or remove `userChrome.css`
2. Restart Firefox

## Create
Enable [Browser Toolbox](https://firefox-source-docs.mozilla.org/devtools-user/browser_toolbox/index.html) to inspect browser window code.