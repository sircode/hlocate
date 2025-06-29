
# hlocate

A tiny shell script to run `plocate` (or `locate`) and 🟥**highlight** search terms in color.

## Usage

```bash
hlocate [plocate options] searchterm 
````

Example:

```bash
hlocate searchterm
```

```text
hlocate --help

options same as plocate:

  -b  search only the file name portion of path names
  -c  print number of matches instead of the matches
  -d  search for files in DBPATH
      (default is /var/lib/plocate/plocate.db)
  -i  search case-insensitively
  -l  stop after LIMIT matches
  -0  delimit matches by NUL instead of newline
  -N  do not quote filenames, even if printing to a tty
  -r  interpret patterns as basic regexps (slow)
  -w  search the entire path name (default; see -b)
  --help  print this help

```

## Install

Copy `hlocate` somewhere in your `$PATH` (e.g. `/usr/local/bin`) and make it executable:

```bash
chmod +x hlocate
sudo mv hlocate /usr/local/bin/
```

Enjoy colorful searches!

---

## License

```

MIT License

Copyright (c) 2025 SirCode

Permission is hereby granted...

````

