# Ophia articles

Notes shown in the Ophia app. This repository is only the writing. The app code stays in [snake-finder](https://github.com/NipunSGeeTH/snake-finder).

The app reads `articles/index.json`, each `articles/<slug>.md` file, and the photos in `articles/images/`.

To publish a note, add the markdown file, add a photo, and add one entry to `articles/index.json` with an `author`. The app loads the change when a person taps Refresh. Name the public sources in the note.
