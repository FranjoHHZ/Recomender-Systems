# Recomender-Systems

In dieser Übung geht es darum, ein einfaches Empfehlungssystem zu erstellen, das Filme basierend auf ihren Bewertungen miteinander vergleicht und Empfehlungen generiert.

# Ausfürhung

Um dieses Jupyter Notebook auszuführen, müssen Sie dem Link des oben genannten Binder-Badges folgen. Öffnen Sie das Notebook „3-Logistische_Regression_Projekt-Loesung.ipynb“. Sobald das Notbook geöffnet wurden, gehen Sie bitte auf den Reiter "Edit" und drücken Sie "Clear Outputs of all Cells". Nachdem Sie das gemacht haben, können Sie auf "Run all Cells" klicken um den Code auszuführen.

Schritte im jupyter Notebooks:

Daten einlesen und zusammenführen:
Zunächst werden die Daten von Filmbewertungen und Filmtiteln eingelesen und in einem DataFrame zusammengeführt. Dies ermöglicht die Analyse und Aggregation der Bewertungen nach Filmtiteln.

Datenexploration und Visualisierung:
Anschließend erfolgt eine erste explorative Datenanalyse, um die Verteilung der Bewertungen zu verstehen. Hier werden z.B. die am besten bewerteten Filme und die Filme mit den meisten Bewertungen identifiziert. Visualisierungen wie Histogramme werden verwendet, um diese Verteilungen darzustellen.

Erstellen einer Nutzungsbewertungsmatrix:
Eine Matrix wird erstellt, die die Benutzer-IDs als Zeilen und die Filmtitel als Spalten enthält. Die Zellen der Matrix repräsentieren die Bewertung, die ein Benutzer einem Film gegeben hat. Diese Matrix wird verwendet, um die Korrelation zwischen den Bewertungen verschiedener Filme zu berechnen.

Berechnung der Ähnlichkeit zwischen Filmen:
Für einen ausgewählten Film (z.B. "Star Wars") wird die Korrelation zwischen den Bewertungen dieses Films und den Bewertungen anderer Filme berechnet. Diese Korrelation gibt an, wie ähnlich andere Filme zu "Star Wars" sind, basierend auf den Bewertungen der Nutzer.

Filtern der Ergebnisse:
Um sinnvolle Empfehlungen zu geben, wird die Liste der ähnlichen Filme gefiltert, sodass nur Filme mit einer ausreichenden Anzahl an Bewertungen (z.B. mehr als 100) berücksichtigt werden. Dies hilft, verlässliche und relevante Empfehlungen zu erstellen.

# Ergbnisse

Nach der Ausführung des Codes erhalten Sie eine Liste von Filmen, die in Bezug auf die Nutzerbewertungen am ähnlichsten zu einem ausgewählten Film (z.B. "Star Wars" oder "Liar Liar") sind. Diese Liste zeigt die Korrelationen und die Anzahl der Bewertungen, wodurch Sie nachvollziehen können, welche Filme von den Nutzern ähnlich bewertet wurden. Das einfache Empfehlungssystem gibt somit Empfehlungen basierend auf der Ähnlichkeit der Nutzerbewertungen ab.


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FranjoHHZ/Recomender-Systems/HEAD?labpath=1-Recommender_Systems.ipynb)
