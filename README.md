# Studienprojekt: Zeit- und Ortsabhängigkeit bei der Emissionsbilanzierung von Standardlastprofilen


Dieses Repository enthält den Code für mein Studienprojekt, das sich mit der Analyse von ortsabhängigen Emissionen beschäftigt. Ziel des Projekts ist es, Emissionen basierend auf regionalen und zeitlichen Faktoren zu bewerten und die Unterschiede zwischen ortsabhängigen und ortsunabhängigen Emissionsfaktoren aufzuzeigen.

### Dateibeschreibungen:

- **calculate_emissions.ipynb**: In diesem Jupyter Notebook werden die Lastdaten mit den Emissionsfaktoren aus der Datei *emission_factors.csv* kombiniert. Dabei erfolgt die Berechnung sowohl mit ortsabhängigen als auch mit ortsunabhängigen Emissionsfaktoren.

- **evaluate_emissions.ipynb**: Hier werden die berechneten Emissionsdaten aus zwei verschiedenen Perspektiven aufbereitet: Einerseits wird eine länderbezogene Analyse durchgeführt, andererseits eine zeitbezogene. Die Ergebnisse werden im JSON-Format gespeichert und in die entsprechenden Ordner abgelegt:
  - Länderbezogene Auswertung: *Evaluate_Emissions_Country* (ortsabhängig) und *Evaluate_Emissions_Country_DE* (ortsunabhängig)
  - Zeitbezogene Auswertung: *Evaluate_Emissions_Timestamp* (ortsabhängig) und *Evaluate_Emissions_Timestamp_DE* (ortsunabhängig)

- **analyze_emissions**: Diese Datei enthält eine Sammlung von Funktionen zur detaillierten Analyse und Auswertung der in den JSON-Dateien gespeicherten Emissionsdaten. Mithilfe dieser Skripte werden Emissionen nach verschiedenen Kriterien untersucht, darunter zeitliche und geografische Aspekte. 

Dieses Repository enthält somit alle relevanten Skripte und Daten zur Reproduktion und weiteren Analyse der Ergebnisse.
