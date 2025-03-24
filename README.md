## Assorted Scripts

- [`ecmd`](./ecmd) will output the following command and it's arguements, it will qoute the
  arguements according to the shell, this is useful as the output can be redirected to a file
  and can be used to sync changes in filenames and deletions by sourcing through a shell. \
  [`callecmd`](./callecmd) wraps symlinks of the form `e<cmd>` to `ecmd <cmd>`, _`emv`_ 
  and _`erm`_ are such examples

- [`pdf`](./pdf) and [`html`](./html) Are wrappers around `mupdf` which can render html and
  pdf documents through a pipe.

- [`viewer`](./viewer) generic script similar to the one above that wraps any command which
  reads a file of a given extension to work with pipes.
  
- [`manpdf`](./manpdf) and [`manhtml`](./manhtml) use `pdf` and `html` to view manpages in those
  formats. 

- [`clipshot`](./clipshot)
  A tool for capturing screenshots for sway/other wayland compositors, it can either capture a
  rectangular region or the whole screen and can save it to either a file or the clipboard. 

