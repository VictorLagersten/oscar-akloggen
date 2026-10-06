# Oscar / Åkloggen

Personlig, responsiv svensk träningssida för Oscars snowboard- och skateboardåkning, med siktet på snowboardgymnasiet i Malung.

Öppna `index.html` för sidan. Bilderna i repots rot visas direkt på sidan.

## Snowboardklipp

Sektionen **Analysera snowboardklipp** på startsidan läser `analyses.json` och visar klippen som en del av samma träningslogg. Datamodellen är versionsmärkt och append-only: nya analyser läggs till utan att historik ersätts. Den innehåller fält för trick, teknikpoäng, pop, rotation, grab, balans, landning, stil, progression, styrkor, förbättringspunkter och nästa träningsmål.

Nio videofiler från källchatten är listade men väntar på visuell granskning. Sex efterfrågade filer fanns inte bland de bilagor som gick att läsa. Videofiler publiceras inte i repot. IMG_1776.jpeg finns som platskontext och visar parkområdet, inte Oscars åkning. Inga trick- eller teknikpoäng har satts utan granskning av själva videobilderna.

Webbsidan tar inte emot eller analyserar videouppladdningar automatiskt. Klippen laddas upp i coachchatten, analyseras där och resultaten förs in i `analyses.json`.
