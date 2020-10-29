# Create React App (Custom)

## This is a modified version

### react-scripts package
#### Installation
```
yarn add react-scripts-changed
```
#### Using
Add to package.json:
```
"scripts": {
    ...
    "web": "react-scripts-changed start",
    "web:build": "react-scripts-changed build",
}
```
#### Changes
1. Enabled to set up babel from configuration files.
2. Moved shared and built folder from root to web folder.
```javascript
P.S. All changes are in the comments block:

// #### CUSTOM START ####
...
// #### CUSTOM END ####
```