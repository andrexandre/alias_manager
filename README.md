# Alias manager
This script allows you to do all CRUD (create, read, update, and delete) operations on shell alias or functions on your `.shellrc` file

## Setup

```bash
wget -q https://raw.githubusercontent.com/andrexandre/alias-manager/refs/heads/main/am ; bash am setup
```

## Usage
- `am add ALIAS_NAME ALIAS_COMMAND` - create alias
- `am ls [ALIAS_NAME]` - list alias
- `am edit [ALIAS_NAME] [ALIAS_COMMAND]` - edit alias
- `am rm ALIAS_NAME` - remove alias

## To-Do
- Needs custom importation from cloud
