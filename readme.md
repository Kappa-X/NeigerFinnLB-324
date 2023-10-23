# LB 324

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.

# Automatisierte Code-Tests und -Formatierung

Dieses Repository verwendet `pre-commit` für automatisierte Code-Tests und -Formatierung. Bevor Sie Änderungen committen, stellen Sie sicher, dass Sie die folgenden Schritte befolgen:

# Automatisierte Code-Tests und -Formatierung

Dieses Repository verwendet `pre-commit` für automatisierte Code-Tests und -Formatierung. Bevor Sie Änderungen committen, stellen Sie sicher, dass Sie die folgenden Schritte befolgen:

1. Installieren Sie `pre-commit` (wenn nicht bereits installiert):
   ```bash
   pip install pre-commit
Führen Sie den Befehl aus, um pre-commit in Ihrem Repository zu initialisieren:

bash
Copy code
pre-commit install
Sie können nun wie gewohnt Änderungen an Ihrem Code vornehmen. Beim Commit-Vorgang werden automatisch die folgenden Aktionen ausgeführt:

Ihr Code wird auf Stilfehler mit Flake8 überprüft.
Falls nötig, wird Ihr Code automatisch mit Black formatiert.
Wenn pre-commit Fehler meldet, korrigieren Sie diese, bevor Sie fortfahren. Sie können pre-commit manuell ausführen, um die Tests und die Formatierung zu erzwingen:

bash
Copy code
pre-commit run --all-files
Durch die Verwendung von pre-commit wird sichergestellt, dass der Code stets den definierten Stilrichtlinien entspricht und automatisch formatiert wird.




## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
