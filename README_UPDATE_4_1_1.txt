CL-604 Quiz Trainer 4.1.1

Fix:
- Behebt den Fehler: question_bank.json cannot be parsed as a URL against ./app_version.json

Empfohlene app_version.json:
{
  "appVersion": "4.1.1",
  "bankVersion": "1.0.1",
  "questionBankUrl": "question_bank.json",
  "changes": ["Fragenbank aktualisiert"]
}

In der App unter Updates sollte als Update-Quelle die vollständige Raw-URL deiner app_version.json stehen:
https://raw.githubusercontent.com/DEINNAME/DEINREPO/main/app_version.json
