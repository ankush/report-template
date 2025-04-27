# Simple template for writing report in Markdown

I use this template to write my reports.

## Requirements:
- `texlive-full`, you might get away with base install but just install full version and forget about it.
- `pandoc`
- GNU `make`
- `inotify-tools` (optional) to use `watch` mode
- `zathura` PDF viewer that supports live update.

## Setup
- Edit `Makefile` to add additional reports or begin editing `report.md` and use `make` to generate report.
- `make watch` can be used to regenerate the PDF based on saving the source file
