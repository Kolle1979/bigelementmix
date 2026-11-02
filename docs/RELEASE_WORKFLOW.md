# Release-Workflow

## Versionen

- `x.y.z-rc.n`: Testversion
- `x.y.z`: offizielle Version

## Ablauf

1. Idee als Issue erfassen.
2. Änderung in einem eigenen Branch umsetzen.
3. Code und Inhalte prüfen.
4. Testversion nach `test/index.html` übernehmen.
5. Testaufgaben formulieren und Testlink weitergeben.
6. Testergebnis dokumentieren.
7. Bei Fehlern korrigieren und erneut testen.
8. Nach erfolgreichen Tests und ausdrücklicher Freigabe die getestete Fassung in `index.html` übernehmen.
9. Changelog und Versionsnummer aktualisieren.

## Freigabe

Eine Freigabe muss ausdrücklich erfolgen, zum Beispiel:

> „Ich habe getestet. Du kannst Version 0.1.0 offiziell veröffentlichen.“

Ein „funktioniert“ allein ist keine Veröffentlichungsfreigabe.

## Rückweg

Bei Problemen wird die letzte funktionierende `index.html` aus der Git-Historie wiederhergestellt. Kein Force-Push.
