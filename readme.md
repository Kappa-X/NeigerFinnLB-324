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

