# DOM-elementen ophalen en de basis voor je js-bestand aanmaken
## function MaakKoppelingsCode
Deze function voert de volgende taken uit:
- alle DOM-elementen uit de body in een array opslaan
- de bovenstaande array alfabetisch sorteren op id
- een call uitvoeren naar StelJsTekstSamen
- de return van deze call tonen in de console.

## function GeefChildren
Op basis van een doorgegeven DOM-element en een array waarin de geselecteerde DOM-elementen opgeslagen moeten worden, voert deze function de volgende acties uit:
- de children van het DOM-element opslaan in de opgegeven array, voor zover ze er nog niet in voorkomen. 
  In dat geval volgt er een boodschap in de console.
- bij deze children worden via recursieve programmatie ook de id's van eventuele children opgehaald
