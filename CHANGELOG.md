# SDQC: Änderungsprotokoll

## Version 2016-11-04 (geplant)

```
in Entwicklung
```

**Geplant**
- WENN - Dann Regel zur Prüfung eines Einkaufsinfosatzes [\#282](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/282)

## Version 2016-10-07 (geplant)

```
in Entwicklung
```

**In Bearbeitung**
- Anzeige des Fehlerprotokolls in neuem Modus und Auto-Korrektur [\#268](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/268)
- Regelerstellung im Dialog mit Hilfe der Tabelle MAKT [\#263](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/263)
- Fehler beim Sichern einer Regel - ZSDQC_EINZELWERT [\#258](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/258)
- Regelerstellung mit div. Textprüfungen [\#242](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/242)
- In der Wenn-Bedingung wird der Reguläre Ausdruck weder im Feld Vergleichsart noch im Feld Wert angezeigt. [\#225](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/225)
- mehrere DANN Verknüpfungen [\#215](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/215)
- Einzelwerte [\#211](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/211)

**Behobene Fehler**

- Shortdump bei Textprüfung [\#281](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/281)
- Langtextprüfungen zur MAKT mit Oder-Verknüpfung arbeiten weder online noch offline korrekt [\#256](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/256)
- SDQC - keine Fehlerausgabe mit dem neuen Fehlerprotokoll für Fehler in Varianten [\#245](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/245)
- Vermischung der Jobs [\#201](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/201) (seit Fix 2016-09-21)
- Langtext wird nicht exportiert. [\#180](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/180)

## Fix 2016-09-21

```
K901996.TES
R901996.TES
```

**Information:**

- Alle SDQC-Versionen ab diesem Fix benutzen für die Prüflaufstatistiken das neue Nummernkreisobjekt `ZSDQC_LAUF`. Diesem Nummernkreisobjekt muss initial ein Nummernkreisintervall vergeben werden, z.B. von 0000005000 bis 0000049999.

**Behobene Fehler**

- Vermischung der Jobs [\#201](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/201)

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

- Anzeige des Fehlerprotokolls in neuem Modus [\#268](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/268)

## Fix 2016-09-14

```
K901965.TES
R901965.TES
```

**Information:**

- Dieser Fix repariert einen Fehler in der Korrektur zu Ticket [\#190](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/190), der auftritt, wenn eine Wenn-Dann-Regel in einen Customizing-Transport gespeichert wird.

**Behobene Fehler:**

- Löschen von Bedingungen funktioniert nicht [\#190](http://ec2-54-72-131-21.eu-west-1.compute.amazonaws.com/redmine/issues/190)

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
