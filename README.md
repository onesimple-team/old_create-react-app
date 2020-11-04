# Create React App (Custom)

## This is a modified version

### react-scripts package
#### Installation
```
yarn add react-scripts-os
```
#### Using
Add to package.json:
```
"scripts": {
    ...
    "web": "react-scripts-os start",
    "web:build": "react-scripts-os build",
}
```
#### Changes
1. Enabled to set up babel from configuration files.
2. Moved shared and built folder from root to web folder.
3. Added `__DEV__` variable for backwards compatibility with native platforms.
```javascript
P.S. All changes are in the comments block:

// #### CUSTOM START ####
...
// #### CUSTOM END ####
```