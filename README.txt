VERSION: 1.0.3

Hebrew Ulpan Flashcards
VERSION: 1.0.1

CHANGES IN 1.0.1
- Front-side Hebrew text automatically shrinks to fit the available card area.
- Front-side English prompts automatically shrink to fit the available card area.
- Recalculates after resize, rotation, and automatic phone/desktop UI switching.
- PWA cache version updated so installed iPhones can receive this release.

DEPLOYMENT
Upload the contents of this folder to the root of your static website / GitHub Pages branch.

IPHONE UPDATE
After deployment, open the site once in Safari while online. The new service worker will replace the old cached app shell.

v1.0.2 CHANGES
- Front text is capped to a percentage of the flashcard width, rather than the whole screen.
- Hebrew uses up to about 88% of the card width on desktop and 96% on phones.
- English uses up to about 82% of the card width on desktop and 94% on phones.
- Short words can now render substantially larger on large monitors.
- Long words and phrases still shrink automatically until they fit.
- Text sizing is based on the actual card dimensions.
- Updated PWA service-worker cache to v1.0.2.

v1.0.3 CHANGES
- Hebrew and English prompts on the front of cards are forced to one line.
- No word wrapping, hyphenation, or automatic line splitting.
- Font size shrinks only until that single line fits the permitted percentage of card width.
- Hebrew keeps up to about 88% of desktop card width and 96% on phones.
- English keeps up to about 82% of desktop card width and 94% on phones.
- Updated PWA cache to v1.0.3.
