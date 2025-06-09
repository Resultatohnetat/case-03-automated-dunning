
# Case 3: Automated Dunning Agent

## 📄 Szenario

Das Unternehmen verschickt regelmäßig Rechnungen. Manche werden nicht pünktlich bezahlt. Ziel ist ein smarter, automatisierter Mahnprozess mit Eskalationslogik.

## 🧾 Beispielhafte Rechnungsdaten

Dateien:
- `invoice_data.csv` – strukturierte Rechnungsdaten als CSV
- `invoice_data.json` – identische Daten im JSON-Format

## ⏱ Eskalationslogik

- +3 Tage nach Fälligkeit → freundliche Erinnerung
- +7 Tage → formale Mahnung mit Frist
- +14 Tage → letzte Mahnung mit rechtlichem Hinweis
- +21 Tage → Übergabe an Inkasso / formale Eskalation

## 🔔 Optional zu berücksichtigen

- Slack-Benachrichtigung bei Eskalation
- CRM-Integration (z. B. Tagging nach Mahnstufe)

## 🧠 Deine Aufgabe

1. How would you structure and build this dunning agent?
2. Which tools would you use?
3. How would you avoid duplicates or missed reminders?
4. How would you test it safely?
5. What would your MVP look like after one day?

