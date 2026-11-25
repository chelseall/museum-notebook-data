# Museum Notebook data

Ready-made catalogue files for the Museum Notebook app: museums, artworks and artists, built from Wikidata (CC0) with image pointers to Wikimedia Commons. No user data is stored here.

- `manifest.json`: every file with its size, gzipped size, sha256 and row count.
- `city/Q<id>.json`: a city's museum list. `museum/Q<id>.json`: a museum's pieces. `artist/Q<id>.json`: an artist's works worldwide. `index/artists.json`: artist names for offline search.
- Files are rebuilt by a script in the app repository; do not edit by hand. Format version 1; a breaking change would go under `v2/`.

Facts come from Wikidata (CC0). Short summaries of museums, artists and pieces are the first sentences of English Wikipedia articles (CC BY-SA 4.0) and carry the article title for the link. Images are not hosted here: each pointer carries the Commons licence and credit.
