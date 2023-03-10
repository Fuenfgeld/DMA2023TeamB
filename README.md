#  **ANTICOVIS - Anticoagulation impact on COVID-19 disease severity**


## Direktverlinkung zu zentralen Elementen des Projekts
### [Datenmanagementplan](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Datenmanagementplan)
### [Datenschutzfolgeabschätzung](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Datenschutzfolgeabsch%C3%A4tzung)

## Einleitung

ANTICOVIS ist ein Datenmanagement-Projekt im Rahmen des Zertifikatskurses [Datenmanagement und Archivierung im Umfeld der Forschung](https://www.master-bids.hs-mannheim.de/studienangebot/datenmanagement-und-archivierung-im-umfeld-der-forschung.html), welcher als Modul in den berufsbegleitenden Masterstudiengang  [Biomedizinische Informatik und Data Science](https://www.master-bids.hs-mannheim.de/) der Hochschule Mannheim in Kooperation mit dem [MIRACUM-Konsortium](https://www.medizininformatik-initiative.de/de/konsortien/miracum) und der [Graduate School Rhein Neckar](https://gsrn.de/) integriert ist.

ANTICOVIS basiert auf Patient:innendaten, die durch Synthea erzeugt wurden (Walonoski et al. 2017). Das Projekt hat zum Ziel, ausgehend von erhobenen Quelldaten, den Prozess von Sichtung dieser und einer Formulierung von Fragestellungen bzw. Hypothesen über eine Datenverarbeitung bis hin zur Analyse sowohl in Form von Codes, als auch in Form einer dezidierten und klar nachvollziehbaren Dokumentation darzustellen.

Das Projekt orientiert sich dabei an der Data Roadmap nach Briney et al., welche 2015 im Buch "Data Management for Researchers" erstmals vorgestellt wurde. Sie beschreibt den Lebenszyklus der Daten, beginnend von der [Planung](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Planung-und-Organisation) über [Datenverarbeitung](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Datenverarbeitung) und [-auswertung](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Datenauswertung), lässt dabei die zunehmend wichtiger werdenden Aspekte einer [Langzeitaufbewahrung und Nachnutzbarkeit](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Data-Sharing,-Access-und-Archivierung) nicht außer acht. Diese Elemente sind in unserem Wiki, wie [nachfolgend diskutiert](https://github.com/Fuenfgeld/DMA2023TeamB#dokumentation-des-projekts-im-anticovis-wiki), nachvollziehbar dokumentiert.

![Data Roadmap](https://github.com/Fuenfgeld/DMA2023TeamB/blob/main/Darstellungen/Data_Roadmap_Briney.png)

## Dokumentation der Codes

Im obenstehenden [GitHub Repository des Projekts](https://github.com/Fuenfgeld/DMA2023TeamB) sind die Codes des Projekts zum Aufbau einer initialen SQL-Datenbank, dem ETL-Prozess mit Aufbau eines Datawarehouses sowie der Auswertung der in das erstellte Datawarehouse geladenen Daten aufgelistet.

## Dokumentation des Projekts im ANTICOVIS Wiki

Das [ANTICOVIS-Wiki](https://github.com/Fuenfgeld/DMA2023TeamB/wiki) ist für eine intuitive Einsicht von Sekundärnutzer:innen und Interessierten gemäß unseres Vorgehens im Rahmen des Moduls Datenmanagement und Archivierung aufgebaut:

1) [Datenmanagementplan](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Datenmanagementplan)

2) [Datenschutzfolgeabschätzung](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Datenschutzfolgeabsch%C3%A4tzung)

3) [Planungs- und Datenerhebungsphase](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Planung-und-Datenerhebung): Beschreibt unsere initiale interne Quelldatensichtung und darauf basierende Formulierung von Forschungsfrage bzw. Hypothesen.

4) [Quelldatenverarbeitungs- und Datenbankerstellungsphase](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Quelldatenverarbeitung-und-Datenbankerstellung): Beinhaltet hochrelevante Überlegungen vor der eigentlichen Datenverarbeitung ergänzend zu dem oben aufgeführten Datenmangementplan und der Datenschutzfolgeabschätzung zu unserer Datenbankerstellung aus selektierten Synthea-Quelldaten.

5) [ETL-Prozess und Data Warehouse-Erstellung](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/ETL-Prozess-und-Data-Warehouse-Erstellung): Diese umfasst den ETL-Prozess des ANTICOVIS-Projekts. Oben beschriebene Quelldaten werden exploriert und hinsichtlich ihrer Datenqualität analysiert. Es werden das Star-Schema sowie die Verwendung externer Daten (MED_Classification und COV_Grading), "Pseudonymisierung" sowie die Implementierung der Mapping-Tabellen in das ANTICOVIS Data Warehouse beschrieben.

6) [Datenauswertungsphase](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Datenauswertung): Überlegen zielführender Analysepfade und Exploration von Methoden, diese zu realisieren. Ebenfalls werden in unserem Wiki die hieraus resultierenden Ergebnisse beschrieben.

7) [Projektübersicht](https://github.com/Fuenfgeld/DMA2023TeamB/wiki/Projekt%C3%BCbersichten): Nach Abschluss der Phasen soll eine um- und zusammenfassende Übersicht des gesamten Prozesses (Datenflussdiagramm), unserer Codes (Übersicht GitHub Repository) sowie unserer benutzten Methoden (Systemumgebung) erstellt werden. Ferner sind hier zentrale Ausführungen zu Data Sharing, Access Management und Archivierung zu hinterlegen.


## Visuelle Projektzusammenfassung

Untenstehend ist die visuelle Projektzusammenfassung von **ANTICOVIS** zu finden. Im [**ANTICOVIS**-Wiki](https://github.com/Fuenfgeld/DMA2023TeamB/wiki) sind projektspezifische technische Details, Datenmanagementplan sowie Forschungsergebnisse aufgeführt.

# **Visuelle Projektzusammenfassung von ANTICOVIS**

![Projektübersicht](https://github.com/Fuenfgeld/DMA2023TeamB/blob/main/Darstellungen/ANTICOVIS%20Projekt%C3%BCbersicht.jpg)
