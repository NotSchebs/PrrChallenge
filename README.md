
# 📊 Die Wahrscheinlichkeit, die Schweizer Super League zu gewinnen

Dieses Projekt untersucht die Gewinnwahrscheinlichkeit der einzelnen Teams in der Schweizer Super League anhand historischer Daten. Ziel ist es, durch statistische Methoden und Simulationen datenbasierte Aussagen über den Ausgang der Meisterschaft zu treffen.

## 🔍 Projektbeschreibung

Basierend auf Spielresultaten und Tabellenpositionen wurden Wahrscheinlichkeitsmodelle entwickelt, die über Simulationen visualisiert und ausgewertet wurden. Die zentrale Frage lautet:

**Wie wahrscheinlich ist es, dass ein bestimmtes Team die Schweizer Super League gewinnt?**

Die Analyse wurde vollständig in R durchgeführt. Die Ergebnisse umfassen:

- Import und Bereinigung historischer Daten,
- Anwendung statistischer Modelle,
- Durchführung von Monte-Carlo-Simulationen,
- visuelle Darstellung der Meisterschaftswahrscheinlichkeiten aller Teams.

## 🛠️ Voraussetzungen

Für die lokale Ausführung werden folgende Tools benötigt:

- R (Version ≥ 4.0.0)
- RStudio (empfohlen)
- Das R-Paket `renv` zur Verwaltung der Abhängigkeiten

## 🚀 Ausführen des Projekts

1. Projekt in RStudio öffnen.

2. Falls noch nicht vorhanden, das Paket `renv` installieren:

   ```r
   install.packages("renv")
   ```

3. Die Projektumgebung wiederherstellen:

   ```r
   renv::restore()
   ```

4. Die Analyse rendern:

   ```r
   rmarkdown::render("Die Wahrscheinlichkeit die Schweizer Superleague zu gewinnen.Rmd")
   ```

Dadurch wird die HTML-Datei generiert, die die gesamte Auswertung samt Visualisierungen enthält.

## 📁 Enthaltene Dateien

- **Die Wahrscheinlichkeit die Schweizer Superleague zu gewinnen.Rmd** – Das zentrale RMarkdown-Dokument mit Code, Text und Visualisierungen.
- **Die Wahrscheinlichkeit die Schweizer Superleague zu gewinnen.nb.html** – Die fertige HTML-Version des Berichts.
- **renv.lock** – Lock-Datei mit den verwendeten R-Paketversionen für eine reproduzierbare Analyse.

## 👥 Autoren

- Alejandro Scheifele  
- Sébastien Bagdasarianz  

*Projektarbeit im Rahmen des Moduls PRR, Januar 2025*

## 📜 Lizenz

Diese Analyse wurde im Rahmen eines Schulprojekts erstellt. Eine Weiterverwendung bedarf der Zustimmung der Autoren.
