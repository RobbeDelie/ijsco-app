# Ijsco-app
ijscokar (uber) app

## beschrijving
De klant moet op zijn smart-phone een knop kunnen drukken. Nadat op deze knop is gedrukt krijgt de ijsverkoper een melding dat de klant een ijsje wilt.
De verkoper krijgt een overzicht van adressen waar hij langs moet rijden en een mogelijke route.
Op de app van de klant komt ook te staan hoelnag het nog duurd eer de ijskar er zal zijn.

##technologiën

* Xamarin voor user applicatie
  * Ijsco chauffeur
    * Google Maps API
      * Markers
      * Routes
  * Client
    * Locatie logging  

* Azure voor online server (compatibiliteit met Xamarin is optimaal aangezien deze beide van microsoft zijn)
  * Google Maps API
    * bereken snelste routes naar clients 
  * database, opslaan van:
    * users (drivers/clients)
    * bestelling log
  

How to [markdown](https://en.wikipedia.org/wiki/Markdown#Example).

