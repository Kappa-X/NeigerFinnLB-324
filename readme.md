# LB 324

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.

### Automatisierte Code-Tests und -Formatierung

Um `pre-commit`in diesem Repository für automatiesierte  Code-Tests und -Formatierung zu verwenden, müssen folgende Schritte befolgt werden:

1. Installiere `pre-commit` (wenn nicht bereits installiert):
   ```
   pip install pre-commit
2. Führen diesen Befehl aus, um pre-commit im Repository zu initialisieren:
   ```
   pre-commit install
3. Nun können gewünschte Änderungen am Code vorgenommen werden, wobei jetzt beim Commiten und Pushen automatisch Vorkehrungen getroffen werden.


4. Wenn jetzt der `pre-commit` Fehler meldet, müssen diese vorher korrigiert werden, beovr man fortfahren kann. Auch können `pre-commit`s manuell ausgeführt werden, um die Formatierung und Tests zu erzwingen.
   ```
   pre-commit run --all-files

## Aufgabe 4
#### Link zur Web App [hier](https://neigerfinnlb324.azurewebsites.net)

Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.

### Lokale .env Datei auf Azure übertragen

1. Bei seinem App Service bei Azure auf Konfiguration gehen.
   ![image](https://github.com/Kappa-X/NeigerFinnLB-324/assets/89085742/f6b3e627-dabf-404e-bd49-63a614225111)

2. Neue Anwendungseinstellung hinzufügen und dort sein Password, welches sich in der `.env` Datei befindet eingeben und speichern.
   ![image](https://github.com/Kappa-X/NeigerFinnLB-324/assets/89085742/1d811d68-8b4d-49b7-9a21-2f28b181bddc)
   ![image](https://github.com/Kappa-X/NeigerFinnLB-324/assets/89085742/a7a37fb2-d71e-4d45-913f-058d3db2b4d1)
   ![image](https://github.com/Kappa-X/NeigerFinnLB-324/assets/89085742/505285e9-f092-4c5e-8454-91d0ee604134)


4. Auf seine Webseite gehen und überprüfen, ob das login mit dem eingerichtetem Passwort funktioniert.
   ![image](https://github.com/Kappa-X/NeigerFinnLB-324/assets/89085742/cfa83b21-e087-4314-908c-d865658219ad)
   ![image](https://github.com/Kappa-X/NeigerFinnLB-324/assets/89085742/d22d19c6-cc71-4556-812b-51b2858b0542)




