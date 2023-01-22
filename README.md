# Net Admin Assignment

Author: _hzhu20_

## Entrypoint: `./main`

**Only after `src/un-3.txt` and `src/un-4.txt` are generated: Run `./addusers` and/or `./delusers`**

## Requirements

1. Ensure the `csv` library is pre-built with your Python version
2. Ensure you are on a Linux OS

## Formatting of Usernames Decision

- Excluding duplicates of first, last, and middle names, the format in `src/un-3.txt` is `[Maximum of 8 characters of first name][Full l_name]` (e.g `hzhu` or `harrisonzhu` or `harriszhu`)

- The format in `src/un-4.txt` is `[Maximum of 8 characters of first name][Maximum of 2 characters of middle name][Full l_name]` (e.g `Mjozhu` from `Mike Jo Zhu` or `harryjezhu` from `Harry Jerry Zhu`)

## Other Notes

- The `./src/working/` folder has `src/un-3.txt` and `src/un-4.txt` backups.
- `src/un-3.txt`: All usernames without duplicate first, last, and middle names
- `src/un-4.txt` Resolved duplicate usernames which was by first, last, middle name
