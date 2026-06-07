CL-604 Quiz Trainer 4.1.3

Fix:
- Behebt weiterhin auftretende Safari/iPad-Meldung:
  The string did not match the expected pattern
- Keine Verwendung von new URL() mehr für die Fragenbank-URL.
- Update-Feld ist normales Textfeld.

Wichtig nach Upload:
1. Alle Dateien aus diesem Paket nach GitHub hochladen.
2. In Safari/PWA die App einmal komplett neu laden.
3. Falls die alte Version weiter läuft:
   - PWA vom Home-Bildschirm löschen
   - Safari Website-Daten für deine GitHub-Pages-Seite löschen
   - App neu über Safari öffnen und erneut zum Home-Bildschirm hinzufügen

Update-Quelle in der App:
https://raw.githubusercontent.com/DEINNAME/DEINREPO/main/app_version.json

app_version.json:
"questionBankUrl": "question_bank.json"
