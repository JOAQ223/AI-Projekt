# AI-Projekt
Das Projekt  bezieht sich auf eine künstliche Intelligenz ,Die bearbeitet Audiodatei in Text.  

Dafür haben wir mit der Programmiersprache  python  Bearbeitet 

TEILEN : 

Tensorflow war die verantwortliche Bibliothek für die Modelerzeugung 

Pandas ist für die Dateiverwaltung zuständig 

Jiwer wird den Werkzeug für die modelevaluation  verwendet . Jiwer Vergleich den Text das den Model erzeugt mit den korrekten Text  dass kommen sollte .

It computes the minimum-edit distance between the ground-truth sentence and the hypothesis sentence of a speech-to-text API. The minimum-edit distance is calculated using the Python C module Levenshtein.


PROJET ENTWICKLUNG: 
1)  Die Notwendige wurden  biblbliotheken in den Python datei importiert und installiert. 
2)  Der dataset wurde  von  https://data.keithito.com/data/speech/LJSpeech-1.1.tar.bz2
3) Data wurde mit Pandas Zugriffen
4) Dataei wurde normalisiert, mit einen format von datei name, extension... etc 
5) VOrbereitung von der variablen :
  5.1 den Alphanet wurde zur integer Werte gemap .
  5.2 Nummern die Buchstaben  repräsentieren  werden in Buchstaben  wieder gewandelt. 

6)Dateset wurde  mit python getrennt zwischen Training und  Test 
