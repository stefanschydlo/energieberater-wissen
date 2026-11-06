# Energieberater – Wissensstand

Automatisch gepflegter Wissensstand (Meldungen, offene Punkte & Fristen, Förderparameter) für **EnergieBerater Pro**.

- `wissen.json` wird jeden Montag durch eine geplante Claude-Recherche aktualisiert (amtliche Quellen: BAFA, KfW, BMWE, Bundesregierung, Bundesanzeiger, GModG-Portal, dena, Gebäudeforum).
- Das lokale Programm lädt die Datei bei jedem Start über  
  `https://raw.githubusercontent.com/stefanschydlo/energieberater-wissen/main/wissen.json`  
  (Einstellungen → Automatischer Wissensabgleich → Abgleich-Adresse).
- Enthält ausschließlich öffentliche Informationen, keine Kunden- oder Projektdaten.

Hinweis: Automatisch zusammengestellte Angaben ersetzen nicht die Prüfung der Originalquelle vor einer Antragstellung.
