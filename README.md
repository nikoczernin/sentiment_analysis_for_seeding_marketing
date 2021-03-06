# Bachelorarbeit

## Automatische Verwertung von Mikro-Influencer-Feedback durch Sentimentanalyse

<div>

#### Eingereicht bei:

Ulrike Phieler  
Institute for Interactive Marketing & Social Media Wirtschaftsuniversität Wien</div>

<div>

#### Eingereicht von:

Nikolaus Czernin  
Mail: h11721138@s.wu.ac.at</div>

<div>

#### Studium:

Wirtschafts- & Sozialwissenschaften — Wirtschaftsinformatik Fachsemeter: W2021  
Matrikelnummer: 11721138</div>

<div>

### [>>> Zur Arbeit >>>](Czernin_Bachelorarbeit.pdf)

#### Abstract

Sentimentanalysen wurden bereits in vielerlei Kontexten angewandt, diese Arbeit behandelt die wenig erforschte Nutzung solcher Analysen für Seeding-Kampagnen und Potenzial bei der Messung derer Effektivität. Um die impliziten Informationen in den Kommentaren von Produkttestern bei solchen Kampagnen ausnutzen zu können, wurde eine lexikon-basierte Sentimentanalyse durchgeführt. Grundlage für das Analysemodell war das Modul GerVADER, welches durch, von der Literatur empfohlene, Regeln erweitert wurde. Die Kommentare wurden Satz für Satz auf ihre Sentimente untersucht. Somit konnten Einblicke in die Emotionalitäten der Tester geboten werden, was bei Evaluierung der Effektivität einer Kampagne hilft. Es wurden positive Korrelationen zwischen den Kundenbewertungen, den Weiterempfehlungsquoten und den Sentimenten der Kommentare entdeckt. Die Sentimente korrelierten außerdem positiv mit der Länge der Kommentare und negativ mit der Nummer des Blogs, auf die sie antworteten. Durch die Quantisierung von Sentimenten konnte außerdem ermittelt werden, welche Kampagnenmanager emotionale Reaktionen ihrer Teilnehmer hervorbrachten. Darüber hinaus konnten für verschiedene Domänen die Varianzen der Sentimente ermittelt werden, sowie deren Implikationen für die Effektivität der Kampagnen. Außerdem ließen sich die emotionalen Erfahrungen über den Kampagnenverlauf und Anomalien durch solche Analysen visualisieren. Letztlich erlaubte die Sentimentanalyse, Schwachpunkte der Kampagnen und ihrer Durchführung ersichtlich zu machen, was Kampagnenmanager und Brandmanager über davor unbekannte Kundenprobleme informieren kann.

Die Daten, anhand derer die das Analysemodell der ursprünglichen Arbeit erstellt und getestet wurde, wurden vom Institute for Interactive Marketing & Social Media der Wirtschaftsuniversität Wien zur Verfügung gestellt. Die personen- und kampagnenbezogenen Daten wurden nicht veröffentlicht. In den in diesem Repository vorhandenen Daten wurden alle Markennamen, sowie Nutzernamen der Autoren und Teilnehmer arbiträr generiert.

</div>

### Ausführung
Die folgenden R-Notebooks müssen in der gegebenen Reihenfolge ausgeführt werden, da frühere die Daten für spätere erstellen.

## [Übersicht](http://bach.czernin.cc/)
1.  [Laden der Daten](http://bach.czernin.cc/01-daten-laden.nb.html)
2.  [Explorative Datenanalyse (optional)](http://bach.czernin.cc/02-explorative-datenanalyse_opt.nb.html)
3.  [Ausführung von GerVADER2](http://bach.czernin.cc/03-gervader2.nb.html)
4.  [Sentiment-Tendenzen objektiver Wörter](http://bach.czernin.cc/04-objektive-woerter.nb.html)
5.  [Sentiment-Analyse](http://bach.czernin.cc/05-sentiment-analyse.nb.html)

## Quellen
In der Arbeit werden zahlreiche Arbeiten zitiert und in der Quellenangabe angeführt. Im Code selber werden die folgenden Arbeiten und GitHub-Repositories zitiert und ihr Code genutzt:
- Karsten Michael Tymann, Matthias Lutz, Patrick Palsbröker and Carsten Gips: *GerVADER - A German adaptation of the VADER sentiment analysis tool for social media texts. In Proceedings of the Conference "Lernen, Wissen, Daten, Analysen" (LWDA 2019)*, Berlin, Germany, September 30 - October 2, 2019.
- Hung, Chihli, und Hao-Kai Lin. 2013. *„Using Objective Words in SentiWordNet to Improve Word-of-Mouth Sentiment Classification.“* Intelligent Systems, Vol. 28(2): 47-54.

