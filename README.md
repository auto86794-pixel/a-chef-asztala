# A Chef asztala

Szezonális fogások, otthon is elkészíthető receptek.

## Helyi előnézet

Futtasd a projekt mappájából: `python -m http.server 8000 --directory public`.
Ezután nyisd meg a http://localhost:8000 címet.

## GitHub és Vercel

1. Bontsd ki a ZIP-et. A GitHub-repó gyökerébe a belső mappa tartalmát töltsd fel, a `vercel.json` fájllal és a `public` mappával együtt.
2. A Vercelen az Add New → Project menüben importáld a GitHub-repót.
3. A Framework Preset legyen Other. A kimeneti mappa `public`, a buildparancs üres. Ezeket a `vercel.json` beállítja.
4. Kattints a Deploy gombra. Környezeti változó és Neon-adatbázis nem kell.

A receptek a `public/index.html` fájl `recipes` tömbjében szerkeszthetők. A Chef bemutatkozása és fotója minta.
