#Dancing Script
by Pablo Impallari

Dancing Script is a lively casual script where the letters bounce and change size slightly. Caps are big, and goes below the baseline.

Dancing Script references popular scripts typefaces from the 50's.

It relates to Murray Hill (Emil Klumpp. 1956) in his weight distribution, and to Mistral (Roger Excoffon. 1953) in his lively bouncing effect.

Use it when you want a friendly, informal and spontaneous look.

# Completed tasks:
- Updated version number to V2.000
- Fixed vertical metrics
- Added Regular and Bold instances

# Todo:
- Improve README.md
- Fix glyphs, anchors and components
- Run fonts through Font bakery and Ship fonts
- Add TRADEMARKS.md

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you particularly want to build fonts manually on your own computer, you will need to install the [`yq` utility](https://github.com/mikefarah/yq). On OS X with Homebrew, type `brew install yq`; on Linux, try `snap install yq`; if all else fails, try the instructions on the linked page.

Then:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

## License

Copyright (c) 2020, Omnibus-Type (www.omnibus-type.com | omnibus.type@gmail.com)

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at
http://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.