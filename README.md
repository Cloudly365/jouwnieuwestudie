# jouwnieuwestudie
Dit zijn de stappen om de chat toe te voegen aan de website.

Door de limitaties van de chat widget van Trengo moet deze geladen worden in een <iframe> element. Dit element moet op de komen waar de chat moet worden geimplementeerd.

<iframe src=”https://jouwnieuwestudie.nl/chat/” width=”100%” height=”600px” style=”border:none;”></iframe>

Vervang "https://jouwnieuwestudie.nl/chat/" met de link naar de bijgaande chat.html. Voor het gemak raad ik aan om voor elk instituut een ander chat.html bestand te gebruiken (het is natuurlijk ook mogelijk om dit dynamisch te maken).

Dit element laadt de pagina in met de volgende code (zie chat.html). Vervang de api key met je eigen Trengo API key.
