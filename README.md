# Minefall – tartalom (hírek + mod-frissítések)

Ez a repo tárolja a Minefall kliens **frissíthető tartalmát**. A módosítások
automatikusan eljutnak a játékosokhoz (újratelepítés nélkül).

## Hírek szerkesztése
A `news.json` fájlt szerkeszd. Minden hír egy `title` + `body` pár.
A kliens induláskor letölti és megjeleníti a hírfalon.

## Mod-frissítés kiadása
1. Tedd az új `.jar`-t a `mods/` mappába (és a régit cseréld le / töröld).
2. A `manifest.json`-ban frissítsd a `mods` listát (név + url).
3. **Növeld a `version` számot** (pl. 1 → 2). Csak ekkor töltik le a kliensek az újat.

## Mappaszerkezet
```
news.json        – hírfal tartalma
manifest.json    – mod-csomag verzió + mod-lista
mods/            – a letölthető mod .jar fájlok
```
