# Gantt
_Online Gantt-diagram voor betere planning._

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/carleslc)

Maakt gebruik van de [dhtmlxGantt](https://dhtmlx.com/docs/products/dhtmlxGantt/) bibliotheek. Gratis ondersteuning voor mijlpalen.

Exporteren naar *PDF*, *PNG*, *Excel*, *iCal* en opslaan als *JSON* om later te laden en te bewerken.

Bijdragers zijn welkom via pull-request.

## Wat is een Gantt-diagram?

Het *Gantt-diagram* is een visueel schema waarin we globaal de fasen van een project en de duur van elke fase kunnen zien. Het is handig om te plannen en in te schatten wanneer een project of een onderdeel daarvan naar verwachting klaar zal zijn, en om de voortgang op een bepaald moment te bekijken.

## Welke hulpmiddelen kunnen we gebruiken?

Voor snelle *prototyping* en voor simpele diagrammen kunnen we deze tool gebruiken. Hieronder staat een voorbeeld van gebruik.

Een andere optie is een **Excel**- of **Google Spreadsheets**-blad te gebruiken met een tabel en een staafdiagram. Voor complexere diagrammen of voor taakopvolging is het aan te raden geavanceerdere tools te gebruiken. Enkele specifieke tools voor dit soort diagrammen zijn **GanttProjct**, **Gantter** of **Microsoft Project**. Diensten zoals **Asana**, **Trello** of **Coda** bieden hun eigen kalenders die taken relateren aan een kalenderweergave of een Gantt-diagram, wat betere traceerbaarheid mogelijk maakt.

## Een eenvoudig diagram maken

Als we geen taaktraceerbaarheid nodig hebben en alleen een eenvoudig diagram willen, kunnen we de pagina [https://carleslc.me/Gantt/](https://carleslc.me/Gantt/) gebruiken. Daarmee krijgen we een resultaat zoals hieronder.

![Klik [hier](https://github.com/Carleslc/Gantt/blob/master/images/resultado.png?raw=true) om het beter te bekijken](images/resultado.png)

Bij het openen van de pagina zien we onze werkruimte, met verschillende opties om ons diagram te maken:

![](images/espacio_trabajo.png)

Om een **taak** toe te voegen drukken we op de "**+**" aan de linkerkant van de pagina, waar de *taken- en projectboom* met startdata en duur wordt weergegeven.

![](images/plus.png)

Wanneer we op de "+" drukken verschijnt een venster om de informatie van onze taak in te vullen.

![](images/task.png)

We voegen een korte beschrijving toe als **titel** (Description) van de taak en klikken op opslaan (Save). De **start-** en einddata kunnen we nu of later specificeren door de taak aan de zijkanten te *rekken*.

Hier beschouwen we een **project** als een verzameling taken, en het wordt in het diagram groen weergegeven. Projecten verbeteren de visualisatie van bredere fasen. Taken worden in blauw weergegeven. We kunnen een project maken door subtaken toe te voegen, zoals in de volgende afbeelding.

![](images/project.png)

Je kunt een taak **bewerken** door er dubbel op te klikken.

Als je wilt, kun je **afhankelijkheden** specificeren met pijlen, via de cirkels aan de zijkanten van de taken.

![](images/dependencias.png)

Je kunt *mijlpalen* (milestones) definiëren bij het aanmaken van een taak. Dit zijn **doelen**, en ze worden paars weergegeven.

![](images/milestone.png)

Je kunt de **zoom** van het diagram aanpassen om het meer globaal te bekijken. Er zijn drie zoomniveaus: wekelijks, maandelijks en jaarlijks. Zo ziet het diagram eruit in jaarniveau:

![](images/zoom.png)

De optie *"Show Today"* laat zien waar we ons momenteel bevinden.

Bij het toevoegen van taken kun je de optie *"Preference" Consecutive / Parallel* gebruiken om ze na de vorige toe te voegen of eronder overlappend. De functies *Indent / Outdent* zijn om bestaande taken aan projecten toe te voegen of eruit te halen. Je kunt taken verplaatsen vanuit de takenboom en je kunt ook meerdere taken tegelijk **selecteren** door Shift of Control ingedrukt te houden.

De opties "Expand Task/Project Titles" dienen om de titel van de taak of het project naast de balk weer te geven, zodat deze zichtbaar blijft ook als door de zoom of korte duur de titel wordt afgekapt.

In de volgende afbeelding hebben we de optie "Expand Task Titles" aangevinkt.

![](images/expand.png)

Je kunt ook de **stijl** van het diagram wijzigen.

![](images/style.png)

Als je klaar bent kun je het diagram **exporteren** naar diverse formaten (PNG, PDF, Excel of iCal). Het **iCal**-formaat is handig om toe te voegen aan een bestaand kalender zoals Google Calendar.

![](images/export.png)

Om het diagram te **opslaan** en later te **bewerken**, gebruik de optie "**Save**" bovenaan de pagina en klik dan op "**Download**". Dit downloadt een document in JSON-formaat dat je later kunt laden met de optie "Load" wanneer je terugkomt naar deze pagina.

![](images/save.png)