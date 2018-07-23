# repoproxy
Project Repo-Unclutter. Packages file is automatically updated by a script based on whitelists (see json files for the whitelists used)

#### DO NOT EDIT Packages, Packages.bz2, Release, whitelist.json, or tweakcompatible.json manually as they are automatically generated*

## Adding packages to the whitelist

**To whitelist individual packages:**

Via Spreadsheet:
  1. Join the jailbreak discord
  2. Ask for one of the volunteers there to add your package to https://docs.google.com/spreadsheets/d/10cLGau96ptKSjRcPg5tuyuIp5ZoLrlwgQVjypqY_Wsc/edit#gid=0
  3. Wait for the closest weekend for the whitelist here to be updated
  
Via TweakCompatible:
  1. Submit it to TweakCompatible
  2. Wait for the weekend for the spreadsheet & whitelist here to be automatically updated
  
Via BigBoss:
  1. Submit an update or new package on/after April 3, 2015
  2. Wait 24 hours for it to get whitelisted and to show up here

**To whitelist entire categories:**
  1. Create a fork of this repo
  2. Edit whitelistcategories.json
  3. Send a pull request
  4. Explain why the entire category/categories should be whitelisted
  
**To whitelist packages that depend on another package (or contain a pattern in their Depends: field):**
  1. Create a fork of this repo
  2. Edit whitelistdependencies.json
  3. Send a pull request
  4. Explain why all packages that depend on this package should be whitelisted
