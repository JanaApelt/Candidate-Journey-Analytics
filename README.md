# Candidate Journey Analytics

## Projektüberblick

In diesem Projekt analysiere ich einen synthetischen Recruiting-Datensatz mit rund **5.000 Bewerbungen auf 150 Jobs**. Ziel war es, die Candidate Journey vom Bewerbungseingang bis zur Einstellung zu untersuchen und herauszufinden, welche Faktoren die **Time to Hire** und die **Offer Acceptance Rate** beeinflussen.

## Business-Fragen

- Wo entstehen Drop-offs im Recruiting-Prozess?
- Welche Faktoren beeinflussen die Time to Hire?
- Welche Faktoren beeinflussen die Annahme eines Jobangebots?
- Welche Ansatzpunkte zur Optimierung des Recruiting-Prozesses lassen sich aus den Daten ableiten?

## Vorgehen

Die Analyse wurde mit **Python in Jupyter Notebook** durchgeführt und umfasste:

- Datenaufbereitung und explorative Datenanalyse
- Berechnung und Visualisierung zentraler Recruiting-KPIs
- Analyse von Prozesslaufzeiten und Funnel-Stufen
- statistische Hypothesentests
- multiple lineare Regression

## Zentrale Erkenntnisse

- Der **Standort** zeigte einen signifikanten Einfluss auf die Time to Hire; insbesondere Frankfurt wies deutlich längere Prozesszeiten auf.
- Recruiting Channel, Kandidatenlevel, Arbeitsmodell und Fachbereich zeigten keinen statistisch signifikanten Einfluss auf die untersuchten Zielgrößen.
- Das Regressionsmodell erklärte zunächst rund **70 % der Varianz der Time to Hire**.
- Nach Ausschluss des dominierenden Standorteffekts Frankfurt sank die erklärte Varianz auf nur noch **11 %**. Dies deutet darauf hin, dass wichtige Einflussfaktoren auf die Prozessdauer im Datensatz nicht enthalten waren.

## Wichtigstes Learning

Im Verlauf der Analyse wurde deutlich, dass die Qualität einer Datenanalyse bereits **vor dem ersten Python-Code** beginnt: Business-Frage, Zielgrößen und Datengrundlage müssen konsequent aufeinander abgestimmt sein.

Für die ursprüngliche Frage nach dem Einfluss der Prozessgeschwindigkeit auf die Angebotsannahme wäre beispielsweise **Time to Offer** die geeignetere Kennzahl als Time to Hire gewesen.

Das Projekt hat mir damit vor allem gezeigt: **Data Analytics bedeutet nicht nur, Daten auszuwerten, sondern die richtigen Fragen zu stellen und Ergebnisse kritisch zu hinterfragen.**

## Tools

`Python` · `Pandas` · `SciPy` · `Statsmodels` · `Plotly` · `Jupyter Notebook`
