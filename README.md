# Text-Corpus vom Corona-Liveticker von NDR.de
Textcorpus der Corona-Liveticker-Meldungen von NDR.de 2020-2023

Datei: https://github.com/NorddeutscherRundfunk/NDRData-Corona-Liveticker/blob/main/ndr_corona_liveticker.csv

Drei Jahre lang, vom 28.2.2020 bis zum 28.2.2023, informierte die Nachrichtenredaktion des NDR auf einem täglichen Liveblog über die Lage in Norddeutschland. 

Das Team von NDR Data hat die Meldungen nun in einem Dokument gesammelt. Vor allem Wissenschaftlerinnen und Wissenschaftler sollen dadurch die Möglichkeit bekommen, einen Blick auf die Corona-Zeit und die Berichterstattung zu werfen.

Der Datensatz enthält 32.405 Meldungen mit insgesamt 19.335.904 Zeichen.


| Feld       | Information                                                                                                                                                |
|------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 'datetime' | Datum und Uhrzeit der Meldung als datetime-Objekt. Wichtig: Zeitzonen werden nicht beachtet, der Zeitstempel stellt die jeweilige Ortszeit in Hamburg dar. |
| 'headline' | Überschrift der Meldung                                                                                                                                    |
| 'text'     | Text der Meldung. Sollten an der Stelle Videos oder Audios eingebunden gewesen sein, kann es sein, dass Felder leer bleiben. In seltenen Fällen wird der Text der vorangegangenen Meldung wiederholt.                              |
| 'length'   | Länge der Meldungen (Zeichen)                                                                                                                              |
| 'url_ndr'  | URL zur Originalseite-Meldungsseite auf NDR.de                                                                                                             |
| 'day'      | Tag                                                                                                                                                        |
| 'month'    | Monat                                                                                                                                                      |
| 'year'     | Jahr                                                                                                                                                       |
| 'date'     | Datum ohne Uhrzeit                                                                                                                                         |
| 'hour'     | Uhrzeit                                                                                                                                                    |

Auf Grundlage des Datensatzes sind quantitative Auswertungen möglich...
![](/images/meldungen_nach_monat.png)
![](/images/meldungen_nach_stunde.png)

...aber auch qualitative, wie zum Beispiel eine Text-Analyse.

## Lizenz

Alle Daten können frei und kostenlos unter der [Open Data Datenlizenz Deutschland – Namensnennung – Version 2.0](https://www.govdata.de/dl-de/by-2-0) genutzt werden. Die Quellenvermerke sind bei den jeweilige Datensäten genannt (s.u.). Beachten Sie bitte auch den [Haftungsausschluss unten](#Haftungsausschluss).

Fragen und Anregungen nehmen wir gerne unter [data@ndr.de](mailto:data@ndr.de "Link: Link zur E-Mail-Adresse data@ndr.de") entgegen.

## Haftungsausschluss

*Haftungsausschluss: Die Inhalte dieser Seite dienen ausschließlich der allgemeinen Information der Öffentlichkeit. Der NDR übernimmt keine Verantwortung für die Richtigkeit und Vollständigkeit der Daten und Informationen, ob auf dieser Seite angegeben oder verlinkt, für Abweichungen von Originaldaten, Übertragungsfehler oder Veränderung der Informationen durch Dritte.*

