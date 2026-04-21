<h1 align="center" id="title">Area42 accommodatie</h1>

<p align="center">
  <img src="https://imgs.search.brave.com/Y73YOvpn0hvFg1XGqHEhPli0wmzNdvXSiLTwI91GDhU/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5pc3RvY2twaG90/by5jb20vaWQvOTEx/OTk1MTQwL3Bob3RvL2NhbXBpbmctdGVu/dC1pbi1hLWNhbXBp/bmctaW4tYS1mb3Jl/c3QtYnktdGhlLXJp/dmVyLmpwZz9zPTYx/Mng2MTImdz0wJms9/MjAmYz1WVEtfNFBR/MWZJUm9sOVM0MC0z/dVhqSkV2ZTlId2JL/T2VnaW5ERGJwWVpr/PQ" alt="project-image">
</p>

<p id="description">
Voor vakantieparken, campings en recreatiebedrijven is het belangrijk dat accommodaties zoals bungalows, chalets en kampeerplaatsen binnen één systeem beheerd en gereserveerd kunnen worden. In dit project wordt daarom een softwaresysteem ontwikkeld waarmee verschillende accommodatietypen centraal kunnen worden opgeslagen, beheerd en gebruikt voor reserveringen.

De uitdaging zit vooral in de prijsberekening. Niet elk accommodatietype heeft dezelfde prijsopbouw: een kampeerplaats kan bijvoorbeeld werken met een prijs per dag en een bedrag per persoon, terwijl een bungalow een basisprijs heeft met eventueel extra toeslagen. Het systeem moet deze verschillen kunnen ondersteunen zonder dat de code onoverzichtelijk wordt of vol raakt met veel if- en switch-logica.

Om dit op te lossen worden accommodatietypen op databaseniveau beheerd, zodat nieuwe typen later eenvoudig kunnen worden toegevoegd. In de software wordt vervolgens gekeken naar de gekozen start- en einddatum van een reservering, waarna de prijs per dag wordt berekend en opgeteld tot de eindprijs. Afhankelijk van het accommodatietype kunnen hier extra regels aan worden toegevoegd, zoals een starttarief of een toeslag per persoon.

Het doel van dit project is het bouwen van een onderhoudbare en uitbreidbare webapplicatie. De basisoplevering bestaat uit een CRUD-beheerscherm voor accommodaties, een webapplicatie in C# met ASP.NET MVC en een database waarin de gegevens van accommodaties en prijsinstellingen worden opgeslagen. Daarnaast wordt gekeken naar de gebruikersflow, de datastroom en de structuur van het systeem, zodat de oplossing niet alleen technisch werkt, maar ook logisch en gebruiksvriendelijk is.

Door de logica zoveel mogelijk los te koppelen van de gebruikersinterface en databasegegevens flexibel op te slaan, blijft het systeem beter uitbreidbaar en eenvoudiger te onderhouden wanneer er in de toekomst nieuwe accommodatietypen of prijsregels toegevoegd moeten worden.
</p>

<h2>🚀 Demo</h2>

[https://accommodatie.bergthaler.dev](https://accommodatie.bergthaler.dev)

<h2>🧐 Functionaliteiten</h2>

Hieronder staan de belangrijkste functionaliteiten van het project:

* Accommodatiebeheer
* Beheer van accommodatietypen
* Reserveringen aanmaken en beheren
* Beschikbaarheid controleren
* Prijsberekening op basis van datumperiode
* Prijsberekening per dag
* Prijsberekening per persoon
* Basisprijs en starttarief ondersteunen
* CRUD-functionaliteit voor beheer
* Login voor beheerders
* Overzicht van bestaande accommodaties
* Overzicht van reserveringen
* Mogelijkheid om nieuwe accommodaties toe te voegen
* Mogelijkheid om accommodaties te wijzigen
* Mogelijkheid om accommodaties te verwijderen
* Uitbreidbare structuur voor nieuwe accommodatietypen
* Onderhoudbare scheiding tussen interface, logica en database

<h2>💻 Gebouwd met</h2>

Technologieën die in het project zijn gebruikt:

* C#
* ASP.NET MVC
* HTML
* CSS
* Bootstrap
* jQuery
* PostgreSQL

<h2>⚙️ Technische opzet</h2>

Het project is opgezet als een webapplicatie met een MVC-structuur. De gebruikersinterface zorgt voor het beheren en tonen van accommodaties en reserveringen, terwijl de businesslogica de prijsberekening uitvoert op basis van de gekozen accommodatietypes en de ingevoerde datums.

De database bevat gegevens over accommodaties, typen, prijzen en reserveringen. Hierdoor kunnen accommodatietypen centraal worden beheerd en kan de prijsberekening flexibel worden aangepast per type. Door deze aanpak blijft de applicatie overzichtelijk, uitbreidbaar en beter onderhoudbaar.

<h2>📌 Doel van het project</h2>

Het doel van dit project is om een praktisch en schaalbaar reserveringssysteem te bouwen waarin accommodaties op een duidelijke manier beheerd kunnen worden. Het systeem moet niet alleen voldoen aan de functionele eisen, maar ook technisch logisch zijn opgebouwd, zodat toekomstige uitbreidingen eenvoudig kunnen worden toegevoegd.
