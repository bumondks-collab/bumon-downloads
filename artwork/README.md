# BM product artwork

Images BM Central shows (fetched at start-up, cached; only changed files are downloaded):

- `<name>.jpg` — screenshot of the plugin's current interface
- `<name>-box.png` — product box (1100x1400, transparent), made by `branding/boxes/make_boxes.py` in bumon-central
- `bundle-box.png` — all BM plugins

When a plugin's interface changes, replace its `<name>.jpg`, regenerate the box and commit here: every BM Central
shows the new images on its next start, without an update.
