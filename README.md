# Orange Juice Mods Utility

## What is this?

This repo is only to drop issues and releases. *Poke me if you hit the jackpot tho...*

## How to use this

Execute the file directly in terminal. For Windows user, suggested to use the `.exe`, otherwise its `.py` one.

```
ojmutil command [args...]

Commands:
  create  - create blank mod data
  migrate - perform mod data migration
  help    - show this
```

### Create
```
ojmutil create [options] [directories...]

Options:
  -n, Do not write to filesystem. (Dry run)
```

Create a blank template, if not exists.

### Migrate

```
ojmutil migrate [options] directory [directoryN...]

Options:
  -f, Do not write a backup file. (Destructive)
  -n, Do not write to filesystem. (Dry run)
```

This will migrate all the mods in given directories.

## Credits

- Rei_Fan49
