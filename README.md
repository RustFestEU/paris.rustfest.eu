# Adding an Organizer

Create a file by the name of `_organizers/nick.md` where `nick` is the nick of the organizer. Use the options detailed in `_organizers/_schema.md` to configure the details.

Then, save their image to `assets/organizers/nick.png`. It should be `660x660` at most. You can use this to configure it:

```bash
make images
```

The final PR should include:

* `_organizers/nick.md`
* `assets/organizers/nick.png`

# Adding a Sponsor

You can either ask them the details from `_sponsors/_schema.md` and fill it out for them, ask them to fill it out, or if they'd like, have them make a PR.

Ask them for an SVG version of their logo.

The final PR should incude:

* `_sponsors/company.md`
* `assets/sponsors/company.svg || assets/sponsors/company.png`

# Adding a Speaker

You can either ask them the details from `_speakers/_schema.md` and fill it out for them, ask them to fill it out, or if they'd like, have them make a PR. Their `nick` should either be their nickname or their first initial then last name.

Ask them for a PNG image which they'd like to be shown publicly.

The final PR should include:

* `_speakers/nick.md`
* `assets/speakers/nick.png`

# Adding a Session

Create a file by the name of `_sessions/snake-case-short-name.md`. Use the options detailed in `_sessions/_schema.md` to configure the details.

The final PR should include:

* `_sessions/nick.md`

# Social cards

After merging (or checking out locally) you can go to **<url>/meta/twitter-card-generator/** to see a list of cards showing up. You may edit the _layout file for different descriptions (there's a JSON object), and to change the visuals (e.g. the SVG). 

When you are done, you can just screenshot the cards and save them as a .png image into /assets/zurich/social/ under the same name as the speaker image is. I usually just use Firefox for this, in the devtools you can just right-click a card and click "Screenshot node", which saves a .png file of the correct size automatically into your "Downloads" folder.

**Note** that these files are recompressed by Twitter as .jpegs, so there is no harm in having large files.

The Twitter Card Validator service can be used for checking metadata (it also works on this page, it will show Ashley's card that is embedded in the metadata in <head>), but it only works for already-on-line pages, doesn't work with locally served devpages (as it uses Twitter's crawler). 
