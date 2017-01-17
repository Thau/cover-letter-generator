# Cover Letter Boilerplate

## Dependencies

1. LaTeX with the following extra packages: `fontspec` `geometry` `ragged2e` `enumitem` `xunicode` `xltxtra` `hyperref` `polyglossia` `footmisc` (also, `datetime2` plus its language modules if you want to use a custom date, see below in the settings section)
2. [Pandoc](http://pandoc.org/), the universal document converter.
3. Open Sans

To install LaTeX on Mac OS X, I recommend getting the smaller version BasicTeX from [here](https://tug.org/mactex/morepackages.html) and installing the additional packages with `tlmgr` afterwards. Same goes for Linux: install `texlive-base` with your package manager and add the needed additional packages later.

To install pandoc on Mac OS X, run `brew install pandoc`. To install it on Linux, refer to the [official docs](http://pandoc.org/installing.html).

To install Open Sans on Mac OX X, run `brew install font-open-sans`.

## Getting started

1. Copy `letter.example.md` to `letter.md` and fill the YAML frontmatter with your details, your recipient's details, optional subject line, and the desired settings.
2. Write your letter in markdown below.
3. Run `make` to compile the PDF.

**Note**: this template needs to be compiled with XeTeX.

## License

[MIT](https://opensource.org/licenses/MIT)
