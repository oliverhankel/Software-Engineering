# Einführung in Software-Engineering (für Interessierte)

Software-Engineering ist ein sehr weites Feld, das einige Spezialisierungen hervorgebracht hat.
In den Lektionen finden sich Ansätze, wie man sich der Diszpling Software-Engineering pragmatisch nähern kann.

Folgende Tools sind verwendet worden:

- [Git](https://git-scm.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Obsidian](https://obsidian.md/)
- [Zotero](https://www.zotero.org/)
-  [Mermaid](https://mermaid-js.github.io/mermaid/#/)
- … more to come

## Lektion 01:

[Organisatorisches möchte geklärt sein](Lectures/Lecture-01/Organisatorisches.md)

[Was ist Software-Engineering](Lectures/Lecture-01/Was%20ist%20Software%20Engineering.md)



## Lektion 02:

[Dokumentation in Software-Projekten](Lectures/Lecture-02/Dokumentation%20in%20Software-Projekten.md)

[UML I: Einführung](Lectures/Lecture-02/UML-I-Einf%C3%BChrung.md)


## Lektion 03:

[UML — Verhalten](Lectures/Lecture-03/UML%20-%20Use%20Cases%20-%20Verhaltensdiagramme.md)

## Lektion 04:

[UML vs. SysML](Lectures/Lecture-04/UML%20-%20SysML.md)

## Lektion 05:

[Requirement Engineering mit SysML](Lectures/Lecture-05/Requirement%20Engineering%20mit%20SysML.md)

## Lektion 06:

[Version Control Management](Lectures/Lecture-06/Version%20Control%20Managment.md)

## Lektion 07:

[Code Reviews](Lectures/Lecture-07/Code%20Reviews.md)

## Lektion 08:

[Unit-Tests](Lectures/Lecture-08/Unit%20Test%20Me.md)

## Lektion 09: 

[Integrations- & Regressionstests](Lectures/Lecture-09/Integration%20und%20Regressionstest.md)

## Lektion 10: 

[Dependency Management](Lectures/Lecture-10/Dependency%20Management.md)

## Lektion 11:

[Build und Deploy](Lectures/Lecture-11/Build%20und%20Deploy%20Pipelines.md)

## Lektion 12:

[Code Analyse](Lectures/Lecture-12/Statische%20und%20dynamische%20Code%20Analyse.md)


## Lektion 13:
[Container Apps](Lectures/Lecture-13/Container%20Apps.md)

## Lektion 14: 

[Produktivität messen](Lectures/Lecture-14/Produktivit%C3%A4tsmetriken.md)

## Lektion 15:

[Wissen teilen](Lectures/Lecture-15/Wissen%20teilen%20und%20verbreiten.md)

## Lektion 16: 

[Mehrwert schaffen](Lectures/Lecture-16/Mehrwerte%20f%C3%BCr%20sich%20und%20andere%20schaffen.md)


---
```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Kursfahrplan
    excludes    weekends
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section Kultur
    Arbeiten im Team          :active,  des1, 2022-09-23
    Produktivität messen      :         des2, 2022-12-23, 5d
    Wissen verbreiten         :         des3, 2023-01-13, 5d
    Mehrwert schaffen         :         des4, 2023-01-20, 5d

    section Prozesse
    Dokumentation             :         des5, 2022-09-30, 5d
    Style Guides              :         des14, 2022-10-27, 5d   
    Code Reviews              :         des15, 2022-11-04, 5d 
    Unit Tests                :         des16, 2022-11-11, 5d
    Integrationstests         :         des17, 2022-11-18, 5d


    section Tools
    Version Control Management:         des13, 2022-10-27, 5d 
    Dependency Management     :         des18, 2022-11-25, 5d
    Build und Deploy          :         des19, 2022-12-02, 5d
    Code Analyse              :         des20, 2022-12-09, 5d   
    Container Apps            :         des21, 2022-12-16, 5d  
           

    section Notationssprachen
    UML - Einführung          :         des6, 2022-09-30, 5d
    UML - Use Cases Model     :         des7, 2022-10-07, 5d
    UML - Verhaltensdiagramme :         des8, 2022-10-07, 5d    
    UML - Strukturdiagramme   :         des9, 2022-10-14, 5d
    UML - SysML               :         des10, 2022-10-14, 5d
    Requirements mit SysML    :         des11, 2022-10-21, 5d
    Hardwarenahe Modelle mit SysML :    des12, 2022-10-21, 5d   
```




