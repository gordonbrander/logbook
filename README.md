Logbook
=======

Have you ever wanted an easy way to timestamp your notes? Well, here you go!

Logbook timestamps your notes and appends them to the end of a TSV (tab-separated value) file.

Use
---

```bash
logbook ~/output.tsv -m "My message"
```

Or use stdin:

```bash
echo "Hello from stdin" | logbook ~/output.tsv
```

Or timestamp and log every line of a file:

```bash
logbook ~/output.tsv -r ~/input.txt
```

Install
-------

Requirements:

- Python 2.x