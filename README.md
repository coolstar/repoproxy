# repoproxy
Project Repo-Unclutter. Packages file is automatically updated by a script based on whitelists (see json files for the whitelists used)

#### DO NOT EDIT Packages, Packages.bz2, Release, whitelist.json, or tweakcompatible.json manually as they are automatically generated*

## Adding packages to the whitelist

**To whitelist individual packages:**
  
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
