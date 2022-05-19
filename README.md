# Scriabin Club website

Repository of the [Scriabin Club website](https://scriabinclub.com/).

The website gets build automatically every week on Monday at 9:00am UTC+2.
If the build fails an older version is used.

## Requirements

You will need Hugo, which you can obtain from [the Hugo release page](https://github.com/gohugoio/hugo/releases).
The *extended* version is required.

## How to contribute to Scriabin Club

- You can submit general technical improvements to our website.
- You can submit translations of existing parts of the website.
- You can submit actual content, i.e. *publications* (see below for more information about this).

In exchange for this, Scriabin Club membership is granted.

###  Submitting content to Scriabin Club

**What is content?**

- Publication of Research Material about e.g. Scriabin or his world on our website.
- Providing of recordings, media etc.
- Pieces of own opinions about things that could be connected to Scriabin.
- Something else depending on you, which we can discuss in advance.

**How to submit new content?**

- Write in markdown, and link to static files (if applicable) relatively to that file.
- The markdown file should be named `index.md`.
- Initiate the markdown file with metadata from `archetypes/default.md` (or use `hugo new post/example/index.md`).
- For any other language than English, call this file e.g. for German `index.de.md`, of course this language needs to be defined in `config.toml` first, with the homepage preferably translated too.
- Edit this metadata to fill your needs, you will see examples in the file.
- Everything should be in one folder, which will become the slug of the page (e.g. `scriabinclub.com/post/example/`), no subfolders.
- Assets like pictures (please use `.jpg`) shall be minimized automatically.
- Place that folder with all files under `content/post/`.
- Submit a request in Github.
- If you are not sure please [contact us](https://scriabinclub.com/contact/).

Thank you for your contributions!
