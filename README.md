## Medial AI Group Website Repository

This website is built with [Quarto](https://quarto.org), an open source scientific and technical publishing system.

It was forked from the Masiello Group Website: https://github.com/MasielloGroup/MasielloGroupWebsite

## Carry-over notes from original repo

Note CB: I have not tested those. 

### Adding publications
use `just newpub` for creation of new directory and input prompts for new record.

### Adding new people
use `just newperson` for creation of new directory and input prompts for new record.

## Deployment 

- Use `quarto render` and `quarto preview` to test the site locally. 
- Use `quarto publish gh-pages` to publish the website.
- Under the repo settings in the section "Pages", the Branch needs to be set to `gh-pages` and the folder needs to be `/ (root)`.

