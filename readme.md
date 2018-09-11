# DSA New Orleans Mobilizer Program Webapp

This is a webapp for tracking progress of mobilizers in activating new members.

## Requirements

* Clasp - used to automatically push files from your local environment to your Google Apps Script project.
    
    ```bash
    npm install @google/clasp -g
    ```

## Setup

Push this repo to your project. In the web interface, create `AppSettings.gs` with the follwing contents:

```javascript
function getAppSettings() {
  return {
    spreadsheetId: "",
    appPassword: "",
  }
};
```

Fill in your spreadsheet ID and a password you mobilizers can use to login.