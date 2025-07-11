
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

  -b, --basename         search only the file name portion of path names
  -c, --count            print number of matches instead of the matches
  -d, --database DBPATH  search for files in DBPATH
                         (default is /var/lib/plocate/plocate.db)
  -i, --ignore-case      search case-insensitively
  -l, --limit LIMIT      stop after LIMIT matches
  -0, --null             delimit matches by NUL instead of newline
  -N, --literal          do not quote filenames, even if printing to a tty
  -r, --regexp           interpret patterns as basic regexps (slow)
      --regex            interpret patterns as extended regexps (slow)
  -w, --wholename        search the entire path name (default; see -b)
      --help             print this help

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

