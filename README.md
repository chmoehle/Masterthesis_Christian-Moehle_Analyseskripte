# Masterthesis – Python-Auswertungsskripte

Dieses Repository dient als zentrale Übersicht über alle im Rahmen meiner Masterarbeit entwickelten Python-Skripte. Die einzelnen Auswertungsskripte wurden thematisch in eigenständigen GitHub-Repositories organisiert und sind von hier aus direkt erreichbar.

Die Skripte wurden entwickelt, um die im Forschungsprojekt **RETForst** erhobenen Messdaten automatisiert auszuwerten und eine transparente sowie reproduzierbare Analyse retentiver Speichersubstrate im ungebundenen Forstwegebau zu ermöglichen.

Ich bin kein Softwareentwickler oder Informatiker, sondern habe die Skripte als Hilfsmittel für meine wissenschaftliche Arbeit erstellt. Die Programmierung erfolgte mit Unterstützung von **ChatGPT (OpenAI)**. Dabei habe ich die fachlichen Anforderungen, Berechnungsmethoden und die gewünschte Darstellung der Ergebnisse definiert sowie sämtliche Funktionen getestet und schrittweise angepasst.

---

# Übersicht der Repositories

## Sensorkalibrierung

| Repository | Beschreibung |
|------------|--------------|
| **SMT-100_Bodenfeuchtesensor-_Kalibrierung** | **[SMT-100_Bodenfeuchtesensor-_Kalibrierung](https://github.com/chmoehle/SMT-100_Bodenfeuchtesensor-_Kalibrierung)** | Polynomische Kalibrierung der SMT100-Bodenfeuchtesensoren der Fa. TRUEBNER einschließlich Modellvergleich, Residuenanalyse, statistischer Modellbewertung und Excel-Export. |

---

## Materialcharakterisierung

| Repository | Beschreibung |
|------------|--------------|
| **Masterthesis_Sieblinie_Substrate_Rosalia** | Auswertung der Korngrößenverteilungen einschließlich Berechnung geotechnischer Kennwerte und Darstellung kumulativer Sieblinien. |
| **Korrelationsanalyse_Substratkennwerte_zwei-Parameter** | Pearson- und Spearman-Korrelationsanalysen zwischen ausgewählten geotechnischen und hydraulischen Materialkennwerten einschließlich automatischer Erstellung von Scatterplots. |

---

## Hydraulische Eigenschaften

| Repository | Beschreibung |
|------------|--------------|
| **Masterthesis_Infiltration-Rosalia_Boxplots** | Statistische Auswertung der Infiltrationsmessungen mit Vergleich verschiedener Materialien, Spuren und Messbedingungen (mit und ohne Vorsättigung). |

---

## Mechanische Eigenschaften

| Repository | Beschreibung |
|------------|--------------|
| **Masterthesis_Tragfaehigkeit-Rosalia_Boxplot** | Statistische Auswertung und Visualisierung der Tragfähigkeitsmessungen (Evd) verschiedener Materialien, Messzeitpunkte sowie Fahr- und Mittelspuren. |

---

## Bodenfeuchte

| Repository | Beschreibung |
|------------|--------------|
| **Masterthesis_Bodenfeuchte-Rosalia_monatliche-Auswertung** | Monatliche statistische Auswertung kontinuierlicher Bodenfeuchtedaten mittels Boxplots und deskriptiver Statistik. |
| **Masterthesis_Bodenfeuchte_Rosalia_monatliche-Unterschiede** | Berechnung und Darstellung der monatlichen Unterschiede des volumetrischen Wassergehalts zwischen Deck- und Tragschicht. |
| **Masterthesis_Bodenfeuchte-Niederschlag_Rosalia_Einzelereignisse** | Analyse ausgewählter Niederschlagsereignisse und deren Einfluss auf den zeitlichen Verlauf der Bodenfeuchte. |
| **Masterthesis_Niederschlag-Bodenfeuchte_Rosalia_Jahresbilanz** | Jahresübersicht des Bodenfeuchteverlaufs in Kombination mit den täglichen Niederschlagssummen. |

---

## Kombinierte Auswertungen

| Repository | Beschreibung |
|------------|--------------|
| **Masterthesis_Bodenfeuchte-Tragfaehigkeit_Rosalia_Vergleich** | Gemeinsame Auswertung von Tragfähigkeit (Evd) und Bodenfeuchte (VWC) zur Untersuchung möglicher Zusammenhänge zwischen beiden Messgrößen. |

---

# Workflow der Datenauswertung

```text
Feld- und Laboruntersuchungen
               │
               ▼
  Kalibrierung der SMT100-Sensoren
               │
               ▼
Kontinuierliche Bodenfeuchtedaten
               │
     ┌─────────┼─────────┐
     ▼         ▼         ▼
Siebanalyse  Infiltration Tragfähigkeit
     │         │         │
     └─────────┼─────────┘
               ▼
      Korrelationsanalyse
               │
               ▼
 Gemeinsame Auswertung von
 Tragfähigkeit und Bodenfeuchte
               │
               ▼
 Ergebnisse der Masterarbeit
```

---

# Entwicklungsumgebung

Die Skripte wurden entwickelt und getestet mit:

- Python 3.14
- pandas
- numpy
- matplotlib
- scipy
- seaborn
- statsmodels
- openpyxl

Jedes Repository enthält ein eigenes `README.md` mit einer detaillierten Beschreibung des jeweiligen Skripts, den erforderlichen Python-Bibliotheken, den verwendeten Eingabedaten, den erzeugten Ausgabedateien sowie einer Beispielabbildung.

---

# Masterarbeit

**Titel**

**Evaluierung von Retentions- und Speichersubstraten, Praxisanforderungen im Wald- und Feldwegebau, mit Labormethoden und im Feldversuch**

**Studiengang**

**M.Eng. Candidate in Landscape Architecture**

University of Natural Resources and Life Sciences, Vienna (BOKU University)

---

# Lizenz

Dieses Repository dient ausschließlich als zentrale Übersicht der im Rahmen meiner Masterarbeit entwickelten Python-Auswertungsskripte.

Die einzelnen Repositories enthalten jeweils eine eigene Dokumentation sowie Hinweise zur Nutzung. Sofern nicht anders angegeben, werden die Skripte zu wissenschaftlichen Zwecken veröffentlicht. Eine Nutzung, Anpassung und Weiterentwicklung unter Angabe der ursprünglichen Quelle ist willkommen.
