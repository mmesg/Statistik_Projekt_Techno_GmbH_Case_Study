# Projekt: Statistische Analyse für die Techno GmbH

## Projektbeschreibung

Die **Techno GmbH** möchte sich in wirtschaftlich herausfordernden Zeiten zukunftsorientiert aufstellen. Dafür benötigt das Unternehmen fundierte Erkenntnisse über potenzielle Veränderungsmöglichkeiten innerhalb verschiedener Geschäftsbereiche.

Im Rahmen dieses Projekts wurden unternehmensinterne Daten zu folgenden Themenbereichen analysiert:

- Lieferantenbewertungen  
- Energieverbrauch  
- Standzeit einzelner Komponenten in der Produktionskette  
- Produktionsprozesse

Die Datenauswertung erfolgte mithilfe **deskriptiver Statistik** und verschiedener **statistischer Testverfahren**, um valide Aussagen über die Zusammenhänge und Unterschiede in den Daten treffen zu können.

---

## Arbeitsumgebung

- **Sprache:** R  
- **Umgebung:** Jupyter Notebook

### Verwendete R-Pakete

```r
Rcmdr, BSDA, outliers, readxl, dplyr, ggplot2, tidyr, RcmdrMisc,
Rcompanion, rstatix, PMCMRplus, vegan
````

## Methodenübersicht

### Deskriptive Statistik

Zur ersten Orientierung und Analyse der Verteilungen und Zusammenhänge wurden folgende grafische und statistische Methoden eingesetzt:

- Gruppierte Balkendiagramme (Barcharts)

- Histogramme

- QQ-Plots

- Boxplots & Symmetry Boxplots

- Korrelationsmatrix

### Testverfahren

**Parametrische Verfahren:**
- t-Test (Mittelwertvergleiche)

- Grubbs-Test (Ausreißererkennung)

- Bartlett-Test (Varianzhomogenität)

- Shapiro-Wilk-Test (Normalverteilung)

**Nicht-parametrische Verfahren:**
- Unabhängigkeitstest

- Wilcoxon-Test

- Scheirer-Ray-Hare-Test

- PERMANOVA (Permutationale multivariate Varianzanalyse)

## Projektergebnisse
Alle Analysen wurden sorgfältig dokumentiert und sind im Jupyter Notebook nachvollziehbar.
Die Ergebnisse der statistischen Analysen ermöglichen es dem Unternehmen, datenbasierte Entscheidungen in Bezug auf Effizienzsteigerung, Prozessverbesserung und Ressourceneinsatz zu treffen.
