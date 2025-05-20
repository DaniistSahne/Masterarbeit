# Masterarbeit: Digitale Erschließung und Analyse der Baldaev-Sammlung

## Thema
Diese Masterarbeit befasst sich mit der **digitalen Modellierung, Annotation und Auswertung** der Zeichnungssammlung des burjatisch / sowjetischen Milizoffiziers *Danzig Baldaev*. Ziel ist die strukturierte Aufbereitung, Normierung und Analyse der Sammlung im Hinblick auf ihre ikonografischen und semantischen Merkmale.

## Zielsetzung
- Erstellung eines nachvollziehbaren Datenworkflows (von der Digitalisierung bis zur XML-Ausgabe)
- Nutzung von **LIDO (Lightweight Information Describing Objects)** zur normierten Metadatenausgabe
- Automatisierte Zuweisung von **ICONCLASS**
- Statistische Auswertung der ikonografischen Merkmalsverteilung

## Inhalt des Repositories
| Ordner / Datei                        | Beschreibung |
|--------------------------------------|-------------|
| `data/`                              | Original- und Zwischendaten (JSON, TXT, Excel) |
| `src/`                               | Jupyter-Notebooks, YAML |
| `README.md`                          | Diese Datei |
| `requirements.txt`                   | Python-Abhängigkeiten |

## Technologien
- **Python 3.10+** (Pandas, NumPy, lxml, Requests, Matplotlib)
- **ICONCLASS** (transformers-basierter Klassifikator)
- **LIDO XML-Schema** (Version 1.1)
- **LaTeX** für Dokumentation und Formatierung
- **GeoNames API** für automatische Georeferenzierung

## Analyse
Das Projekt schließt mit einer statistischen Untersuchung der häufigsten Motive, deren Verteilung (Lorenzkurve), sowie einer Bewertung über den **Gini-Koeffizienten** zur semantischen Streuung der Sammlung.

## Anhänge
- LIDO-XML-Stichproben
- Visualisierungen (z. B. Diagramme)
- 

## Lizenz / Hinweise
Diese Arbeit entstand im Rahmen einer Masterabschlussarbeit. Der Quellcode unterliegt keiner kommerziellen Lizenzierung, darf jedoch **nicht ohne Genehmigung weiterverwendet oder publiziert** werden.

> Teile dieser Arbeit wurden mithilfe von **KI-basierten Tools** wie *ChatGPT 4.0* (Textvorschläge, Codehilfe), *DeepL* (Übersetzungen) und *GeoNames API* (Regionserkennung) erstellt.

##  Autor
**Daniil Chekurov**  


