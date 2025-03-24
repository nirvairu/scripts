## Assorted Scripts

  - [`ecmd`](./ecmd) will output the following command and it's arguements, it will qoute the
  arguements according to the shell, this is useful as the output can be redirected to a file
  and can be used to sync changes in filenames and deletions by sourcing through a shell
  `ecall` wraps symlinks of the form `e<cmd>` to `ecmd <cmd>`, `emv` and erm` are such examples

  - [`pdf`](./pdf) and [`html`](./html) Are wrappers around `mupdf` _(`mupdf-gl`)_ which can render
  piped html and pdf documents.

  - [`viewer`](./viewer) a generalization of the above scripts to wrap any command that supports a
  file with an extension to work with pipes.
  
  - [`manpdf`](./manpdf) and [`manhtml`](./manhtml) Are wrappers around `pdf` and `html` which view
  manpages in the respective formats

  - [`clipshot`](./clipshot)
    A tool for capturing screenshots for sway/other wayland compositors, it has options to either
    the captured image to a file and to either capture a rectangular region or the whole screen
