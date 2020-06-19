## API ontwerp principes

1. Als ontwerper van een API beschouw je deze API als een eindproduct en niet als een technisch tussenstuk. Wees een goed ***Product Owner***, net zoals je dat zou doen bij applicaties voor eindgebruikers.

2. Bij het ontwerp kijk je door de bril van de afnemers, ofwel een ***Outside-In perspective***.

3. Je ***afnemers van de API zijn developers***, leer hen kennen, net als klanten voor applicaties.

4. Maak goed leesbare - niet gegenereerde - ***documentatie*** met voorbeelden, edge cases, mogelijke fouten en oplossingen. *(Hier alvast enkele [tips](https://github.com/digipolisantwerpdocumentation/api-requirements/blob/master/swagger-docs.md))*.

5. Hou het ontwerp ***eenvoudig en intuïtief***, hoe minder externe documentatie er moet gelezen worden hoe beter het ontwerp.

6. Werk in ***iteraties*** en verbeter de consistentie en eenvoud op basis van feedback van de afnemers.

7. ***API Design First:*** Door eerst het ontwerp van de API te maken, voor we beginnen met de implementatie ervan, hebben we enkele voordelen:

    - Je kan vroeg in het proces feedback verzamelen.
    - Je kan iteratief te werk gaan. Bij elke sprint kan je het API ontwerp verfijnen en overmaken aan de ontwikkelaars.
    - Ontwikkelaars kunnen aan de hand van het precieze ontwerp meteen zien wat er van hen verwacht wordt.
    - Swagger files kunnen bezorgd worden aan afnemers, nog voor de API implementatie klaar is. Het werkt zo als een contract tussen beide van wat er gaat komen. M.a.w.: door eerst de API vast te leggen, kan er parallel gewerkt worden aan de ontwikkeling van de producer en de consumer. Je moet niet wachten tot de producer klaar is, om te starten met de ontwikkeling van de consumer.
    - Tools kunnen je helpen met de kwaliteit van je API ontwerp en zo bijdragen aan een betere analyse in het geheel.

Jeff Bezos van Amazon zei ooit `if you build it, you run it`, dit gaat hier ook op, toch gedeeltelijk. Na de bouw is er een commerciële en operationele bezigheid. Je brengt de API aan de man en je zorgt ervoor dat deze blijft draaien. Dit laatste laten we weliswaar liever over aan de gespecialiseerde mensen.
