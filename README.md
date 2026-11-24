# House maps

The houses for the "Our House" walkthrough app. The app downloads `index.json`, then every house that is new or has a
higher version, and keeps it on the phone.

- `index.json` - the list (id, name, version, file)
- `<id>.json` - one house each (walls, doors, lights, furniture pieces)
- `furniture.json` - the furniture library for the app's "Add piece" menu

These files are made by the tools in the game project (`tools/publish.py`). Do not edit them by hand.
