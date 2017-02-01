# SDQC: Änderungsprotokoll

## Version 2017-xx-xx (geplant)

```
in Entwicklung
```

**Geplant**

- Der Kommentar im Dialog "MARA-MATNR:0136" durch Button "Regel überprüfen" sollte korrigiert werden [\#251](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/251)

## Version 2017-02-24

```
in Entwicklung
```

**Geplant**

- Für W_SYNC erscheint kein korrekter Test bei der Fehlermeldung zu Regel 611 [\#261](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/261)

**Realisiert**

- Button Einzelwerte ist grau [\#311](http://bitnami-redmine-58c6.cloudapp.net/issues/311)
- Button Fehlerbeschreibung ist grau [\#309](http://bitnami-redmine-58c6.cloudapp.net/issues/309)
- Regel zurücksetzen beim Ändern des Regeltyps [\#305](http://bitnami-redmine-58c6.cloudapp.net/issues/305)
- Button zum Anzeigen von Wenn-/Dann-Bedingungen hinzufügen [\#302](http://bitnami-redmine-58c6.cloudapp.net/issues/302)
- Vorbedingungen werden bei einigen Regeln nicht angepasst, Pos. nicht gelöscht [\#287](http://bitnami-redmine-58c6.cloudapp.net/issues/287)
- Die Klasse wird nicht bei Anlage des ABAP-Prüfregels erkannt [\#271](http://bitnami-redmine-58c6.cloudapp.net/issues/271)
- Der Text der Fehlermeldung zu Regel 74 erscheint nicht richtig. [\#260](http://bitnami-redmine-58c6.cloudapp.net/issues/260)

## Version 2016-12-16

```
K902048.TES
R902048.TES
```

**Behobene Fehler**

- "Regel löschen" löscht nicht die zugehörigen Einzelwerte [\#304](http://bitnami-redmine-58c6.cloudapp.net/issues/304)

## Version 2016-11-18

```
K902044.TES
R902044.TES
```

**Behobene Fehler**

- Performance-Probleme und Shortdumps durch Löschung von A-Tabelleneinträge ohne Sperre [\#301](http://bitnami-redmine-58c6.cloudapp.net/issues/301)
- Regulärer Ausdruck bei Vergleichsregel wird nicht exportiert und kann somit auch nicht importiert werden [\#299](http://bitnami-redmine-58c6.cloudapp.net/issues/299)
- Transport von Einzelwerten [\#296](http://bitnami-redmine-58c6.cloudapp.net/issues/296)
- WENN - Dann Regel zur Prüfung eines Einkaufsinfosatzes [\#282](http://bitnami-redmine-58c6.cloudapp.net/issues/282)
- Regeltyp Vergleich / Fehlermeldung erscheint, läßt sich aber nicht entfernen [\#275](http://bitnami-redmine-58c6.cloudapp.net/issues/275)

## Version 2016-11-07

```
K902040.TES
R902040.TES
```

**Behobene Fehler:**

- Fehlerprotokoll neuer Modus: In bestimmten Konstellationen werden die Fehlermeldungen zum falschen Artikel angezeigt [\#285](http://bitnami-redmine-58c6.cloudapp.net/issues/285)

## Version 2016-11-04

abgesagt

## Fix 2016-10-17

```
K902036.TES
R902036.TES
```

**Behobene Fehler:**

- In der Wenn-Bedingung wird der Reguläre Ausdruck weder im Feld Vergleichsart noch im Feld Wert angezeigt. [\#225](http://bitnami-redmine-58c6.cloudapp.net/issues/225)

## Version 2016-10-07

```
K902029.TES (Modifikation MGMW)
R902029.TES (Modifikation MGMW)
K902031.TES (ZRSAG_SDQC Paket)
R902031.TES (ZRSAG_SDQC Paket)
```

**Erinnerung:**

- Alle SDQC-Versionen ab Fix 2016-09-21 benutzen für die Prüflaufstatistiken das neue Nummernkreisobjekt `ZSDQC_LAUF`. Diesem Nummernkreisobjekt muss initial ein Nummernkreisintervall vergeben werden, z.B. von 0000005000 bis 0000049999.

**Behobene Fehler**

- Fehlerprotokoll beim Sammelartikel greift nicht [\#289](http://bitnami-redmine-58c6.cloudapp.net/issues/289)
- Fehlerprotokoll neuer Modus: Meldung „Maximale Anzahl der SAP GUI Modi erreicht“ kommt nicht. [\#286](http://bitnami-redmine-58c6.cloudapp.net/issues/286)
- Fehlerprotokoll neuer Modus: In bestimmten Konstellationen werden die Fehlermeldungen zum falschen Artikel angezeigt [\#285](http://bitnami-redmine-58c6.cloudapp.net/issues/285)
- Fehlerprotokoll neuer Modus: Der Hinweis "Keine weiteren Fehlermeldungen" sollte nicht kommen, sondern der Modus sollte sich sofort schließen. [\#284](http://bitnami-redmine-58c6.cloudapp.net/issues/284)
- Shortdump bei Textprüfung [\#281](http://bitnami-redmine-58c6.cloudapp.net/issues/281)
- Anzeige des Fehlerprotokolls in neuem Modus und Auto-Korrektur [\#268](http://bitnami-redmine-58c6.cloudapp.net/issues/268)
- Regelerstellung im Dialog mit Hilfe der Tabelle MAKT [\#263](http://bitnami-redmine-58c6.cloudapp.net/issues/263)
- Fehler beim Sichern einer Regel - ZSDQC_EINZELWERT [\#258](http://bitnami-redmine-58c6.cloudapp.net/issues/258)
- Langtextprüfungen zur MAKT mit Oder-Verknüpfung arbeiten weder online noch offline korrekt [\#256](http://bitnami-redmine-58c6.cloudapp.net/issues/256)
- SDQC - keine Fehlerausgabe mit dem neuen Fehlerprotokoll für Fehler in Varianten [\#245](http://bitnami-redmine-58c6.cloudapp.net/issues/245)
- Regelerstellung mit div. Textprüfungen [\#242](http://bitnami-redmine-58c6.cloudapp.net/issues/242)
- In der Wenn-Bedingung wird der Reguläre Ausdruck weder im Feld Vergleichsart noch im Feld Wert angezeigt. [\#225](http://bitnami-redmine-58c6.cloudapp.net/issues/225)
- mehrere DANN Verknüpfungen [\#215](http://bitnami-redmine-58c6.cloudapp.net/issues/215)
- Einzelwerte [\#211](http://bitnami-redmine-58c6.cloudapp.net/issues/211)
- Vermischung der Jobs [\#201](http://bitnami-redmine-58c6.cloudapp.net/issues/201) (seit Fix 2016-09-21)
- Langtext wird nicht exportiert. [\#180](http://bitnami-redmine-58c6.cloudapp.net/issues/180)

## Fix 2016-09-21

```
K901996.TES
R901996.TES
```

**Information:**

- Alle SDQC-Versionen ab diesem Fix benutzen für die Prüflaufstatistiken das neue Nummernkreisobjekt `ZSDQC_LAUF`. Diesem Nummernkreisobjekt muss initial ein Nummernkreisintervall vergeben werden, z.B. von 0000005000 bis 0000049999.

**Behobene Fehler**

- Vermischung der Jobs [\#201](http://bitnami-redmine-58c6.cloudapp.net/issues/201)

## Fix 2016-09-20

```
K901986.TES
R901986.TES
K901988.TES
R901988.TES
```

**Information:**

- `901986` beinhaltet den Include `LZRSAG_SDQC_ERRLISTO01`.
- `901988` beinhaltet den Funktionsbaustein `ZRSAG_SDQC_ART_CHECK_PERF` und die Klasse `ZRSAG_SDQC_ERRLIST`.
- Zusätzlich zu den beiden Transporten müssen noch Modifikationen in der Funktionsgruppe `MGMW` vorgenommen werden (vgl. Modifikationsdokument für "Neuer Modus").

**Behobene Fehler:**

- Anzeige des Fehlerprotokolls in neuem Modus [\#268](http://bitnami-redmine-58c6.cloudapp.net/issues/268)

## Fix 2016-09-14

```
K901965.TES
R901965.TES
```

**Information:**

- Dieser Fix repariert einen Fehler zu den u.g. Tickets, der auftritt, wenn eine Wenn-Dann-Regel in einen Customizing-Transport gespeichert wird.

**Behobene Fehler:**

- Dump beim Anlegen einer Vorbedingung. [\#279](http://bitnami-redmine-58c6.cloudapp.net/issues/279)
- Die Vorbedingungen für Regel 625 wurden nicht von D15-320 nach T15-010 übernommen [\#262](http://bitnami-redmine-58c6.cloudapp.net/issues/262)
- Trotz richtige Customizing erscheint keine Fehlermeldung zu Regel 554 [\#255](http://bitnami-redmine-58c6.cloudapp.net/issues/255)
- Löschen von Bedingungen funktioniert nicht [\#190](http://bitnami-redmine-58c6.cloudapp.net/issues/190)

## Version 2016-09-12

```
K901956.TES
R901956.TES
```

**Behobene Fehler:**

- Bei Aktivieren/Deaktivieren von Prüfregeln gibt es kein Feld "Kundenapplikationen" (Es gibt keine Möglichkeit Feld Kundenapplikationen zu aktivieren oder deaktivieren) [\#273](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/273)
- Die Vorbedingungen für Regel 625 wurden nicht von D15-320 nach T15-010 übernommen [\#262](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/262)
- Trotz richtige Customizing erscheint keine Fehlermeldung zu Regel 554 [\#255](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/255)
- Zweite "Wenn-Bedingung" Feldname wird nicht übernommen [\#228](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/228)
- In der Wenn-Bedingung wird der Reguläre Ausdruck weder im Feld Vergleichsart noch im Feld Wert angezeigt. [\#225](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/225)
- Im-/Export Feldinhalt Regulärer Ausdruck [\#204](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/204)
- Löschen von Bedingungen funktioniert nicht [\#190](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/190)

**Neue Features:**

- Anzeige des Fehlerprotokolls in neuem Modus [\#268](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/268)

## Version 2016-08-12

```
K901907.TES
R901907.TES
```

**Behobene Fehler:**

- Änderung einer WENN Bedingung [\#269](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/269)
- Jobeinplanung Parametereinstellungen [\#264](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/264)
- Offline Report liefert eine Anzahl geprüfter und fehlerhafter Artikee von '0' [\#250](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/250)
- PRICAT Verbuchung [\#244](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/244)
- Zweite "Wenn-Bedingung" Feldname wird nicht übernommen [\#228](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/228)
- Selektion in Fehlerdatenbank nach Datum des Offline-Check, Prüflauf und Regelnummer [\#200](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/200)
- Pflege von mehr als 8 Regelspezifischen Bedingungen [\#199](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/199)
- die Tabelle MAKT greift nicht [\#185](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/185)

## Version 2016-07-22

```
K901885.TES
R901885.TES
```

**Behobene Fehler:**

- Regel schlägt zu, wenn nur die Logistik VZ-Sicht geöffnet wird [\#257](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/257)
- Offline Report liefert eine Anzahl geprüfter und fehlerhafter Artikee von '0' [\#250](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/250)
- PRICAT Verbuchung [\#244](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/244)
- Vermischung der Jobs [\#201](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/201)
- die Tabelle MAKT greift nicht [\#185](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/185)

## Version 2016-07-11

```
K901870.TES
R901870.TES
```

**Behobene Fehler:**

- Performance Probleme [\#246](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/246)

## Version 2016-06-10

```
K901860.TES
R901860.TES
```

**Neue Features:**

- Performance-Optimierung für Prüftabellen in Wenn-Dann-Bedingungen (Prüftabellen werden in einem applikationseigenen Puffer zwischengespeichert)
- BAdI `ZRSAG_SDQC_PRE_CHECK` wurde um zusätzliche Parameter erweitert


## Version 2016-06-07

```
K901856.TES
R901856.TES
```

**Information:**

- Version 2015-06-06 wurde in dem Dateiformat .dat ausgeliefert. Da es dabei zu Problemen kam, wurde diese neue Version 206-06-07 im Dateiformat .TES nachgeliefert.

## Version 2015-06-06

```
K901856.dat
R901856.dat
```

**Neue Features:**

- Online-Fehlermeldungsprotokoll: Layout auswählen/ändern/sicher/verwalten [\#208](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/208)

**Behobene Fehler:**

- SDQC Tool: Die gelbe Regel ist aktiv aber keine Kennzeichnung für "Offline-Report" [\#218](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/218)
- Allgemeine Vorbedingungen: Kurzcode für Include und Exclude vertauscht [\#217](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/217)
- Trotz eingeschränkter Berechtigung können ausgeschlossene Funktionalitäten genutzt werden. [\#205](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/205)
- Im-/Export Feldinhalt Regulärer Ausdruck [\#204](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/204)
- Selektion in Fehlerdatenbank nach Datum des Offline-Check, Prüflauf und Regelnummer [\#200](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/200)
- Pflege von mehr als 8 Regelspezifischen Bedingungen [\#199](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/199)
- Es wird der Änderungsmodus einer Regel geöffnet. [\#198](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/198)
- Aufruf Grapfische Darstellung: "Die Seite kann nicht angezeigt werden." [\#195](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/195)
