## Starten met github

### Inloggen en rondstruinen

* maak een account op [github.com](https://github.com) en log in via de 'Sign in' knop in de rechterbovenhoek op de hoofdpagina
* je komt nu op je persoonlijke hoofdpagina. In de linker kolom verschijnen straks updates over de repositories die je volgt en/of aan bijdraagt en de gebruikers die je volgt.  
* klik op je gebruikersnaam in de rechterbovenhoek om naar je profielpagina te gaan. Deze is openbaar.
* klik op het tandwiel om naar 'Settings' te gaan. In de 'Profile' tab kun je een foto uploaden en de informatie op je profielpagina instellen. In de 'Notification center' kun je instellen wanneer je push berichten en/of emails wilt ontvangen.
* Stuur, zodra je klaar bent met ontdekken en grasduinen, een bericht naar @ndkv of @lvdbrink met daarin je github gebruikersnaam. Zij voegen je dan toe aan de Geonovum organisatie 
* je bent nu klaar om te githubben!


### repositories en organisaties

Een repository is simpelweg een mapje met inhoud. Het bevat andere mapjes,  tekstbestanden (xml, json, html, etc.), plaatjes, geo-informatie (geojson), 3D informatie (Wavefront/obj), etc. Github kan een groot aantal bestanden in de browser tonen: broncode met gekleurde syntax, geo-informatie op een kaart en 3D bestanden worden in een WebGL viewer getoond. 

Naast repositories kent github het begrip *organisatie*. Een organisatie is een verzameling repositories. Organisaties ondersteunen gebruikersmanagement: leden hebben rechten en kunnen onderdeel zijn van een team. De Geonovum organisatie is te vinden op [https://github.com/geonovum](https://github.com).

* Surf naar de Geonovum repository
* Je ziet een lijst van repositories; de repo die als laatste is aangepast staat bovenaan. Je kan de lijst doorzoeken door een term in de zoekbalk te tikken. Je kan alleen op (delen van) de naam van een repository zoeken. 
* De Geonovum organisatie heeft een centrale repository waarin de "open werken" gedachte is beschreven en richtlijnen/handleidingen voor het gebruik van github staan
* open de centrale Geonovum repository: tik 'labs' in het zoekveld en open de 'geonovum-labs' repository
* je ziet een aantal bestanden. GitHub leest het README.md bestand automatisch uit en plaats de inhoud in het tekstveld eronder. 
* klik op README.MD om deze te openen, je ziet de gestyleerde inhoud. GitHub begrijpt [Markdown](https://help.github.com/articles/github-flavored-markdown/) en [reStructured Text](http://docutils.sourceforge.net/docs/user/rst/quickstart.html).
* klik op 'Raw' om het ruwe bestand te zien; klik op het potloodje om het bestand in je browser te bewerken.


### commits en issues
De [git](http://git-scm.com/) in GitHub is een versiebeheersysteem... TODO...


TODO

* ...
* je kan commits via verschillende manieren benadren 
* commits worden voorzien van een korte beschrijving. Dit helpt anderen om snel te kunnen zien wat de verandering teweeg heeft gebracht
* ...


TODO


### bestanden bewerken
GitHub repositories kun je downloaden, de bestanden ervan lokaal bewerken en weer uploaden. Het downloaden heet in GitHub taal *pull* en het uploaden heet *push*. Voordat je *pulls* en *pushes* kan uitvoeren moet je een repository *clonen* (voor het eerst downloaden). Dit gaat het makkelijkst met de Windows GitHub client. 

Let op: voordat je een van de Geonovum repositories kan clonen moet je lid zijn van de Geonovum organisatie. Nog geen lid? Stuur een bericht naar @ndkv of @lvdbrink.

* download de [GitHub client voor Windows](http://github-windows.s3.amazonaws.com/GitHubSetup.exe)
* open de client en klik op + in de linkerbovenhoek
* selecteer *Clone*, selecteer *Geonovum* en klik op de repository die je wilt clonen.
* de client haalt de repository op en slaat het lokaal op in de opgegeven locatie. Als het goed is staat het nu in de lijst aan de linker kant
* klik met je rechteremuisknop op de repository en klik op *Open in Explorer* 
* open een van de bestanden in je favoriete tekstbewerker
* pas het aan, sla het op en keer terug naar de GitHub Client
* als het goed is heeft de client gemekrt dat je een bestand aangepast hebt: boven de *History* lijst staat *Uncomitted changes*.
* klik op *Show* om de veranderingen te tonen. 
* om de veranderingen op te slaan in het versiebeheer systeem moet je ze eerst committen. 
* Typ een korte beschrijving van de veranderingen in *Summary* en klik op *Commit to master*. De veranderingen zijn nu in je lokale kopie gecommit. 
*  Druk op *Sync* in de rechterbovenhoek om de veranderingen te pushen naar GitHub en ze zichtbaar te maken voor anderen. 


### overige functionaliteit   


#### Grafieken

#### Commentaar op broncode


### Meer informatie

De [git Book](http://git-scm.com/book/en/v2) is een bijzonder toegankelijke en helder geschreven handleiding.