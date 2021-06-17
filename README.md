# sass-startercode
SASS Startercode für Frontend Development im Vertiefungsmodul Web Development

## Was ist dabei?
Diese Version trennt Source- und Distribution Code und stellt ein paar Funktionen bereit. 

## Ordnerstruktur
```
/dist     kompilierter Code … hier wird nix gemacht
/helper   Helferlein für's Kompilieren
/src      Quellcode … hier wird entwickelt

```
## Funktionen

`npm install`
Installiert die erforderlichen Abhängigkeiten.

`npm run watch`
Watchmode für den SASS Compiler.

`npm run build` kompiliert einen Build und speichert diesen im `dist` Folder.

`npm run dev` Watchmode für den SASS Compiler und kleiner Webserver, der die Inhalte im `src` Folders serviert.

`npm run live` erzeugt einen Build und startet den Webserver, der die Inhalte im `dev` Folder serviert.