# Alias manager
This script allows you to do all CRUD (create, read, update, and delete) operations on shell alias or functions on your `.shellrc` file

## Setup

```bash
git clone https://github.com/andrexandre/alias-manager ; ./alias-manager/am setup
```

## Usage
- `am add ALIAS_NAME [ALIAS_COMMAND]` - create alias
- `am ls [ALIAS_NAME/OPTION]` - list alias
- `am edit [ALIAS_NAME] [ALIAS_COMMAND]` - edit alias
- `am rm ALIAS_NAME` - remove alias

## To-Do
- Change command documentation and implement -h flags for edit and ls
- Enchance info about success and failure of commands with gum
- Needs custom importation from cloud
