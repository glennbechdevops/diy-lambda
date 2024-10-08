# diy-lambda

## Formål ##   
Formålet med denne oppgaven er at du skal bli kjent med AWS Lambda-funksjonalitet og hvordan du kan lage et HTTP-endepunkt ved å bruke API Gateway som trigger for Lambda-funksjonen. Du skal selvstendig navigere gjennom prosessen med å opprette funksjonen og sette opp en trigger for å skape et fungerende API-endepunkt.

## Oppgave ##

* Logg inn på ditt **Cloud9-miljø**, og naviger videre til **AWS Management Console**.
* Gå til tjenesten **AWS Lambda** via søkefeltet i AWS Console. 
* Velg **Create Function** for å opprette en ny Lambda-funksjon.

* Du kan velge mellom to alternativer, du står fritt til å velge

    - **Author from scratch:** Opprett Lambda-funksjonen helt fra bunnen av.
    - **Velg et Blueprint:** Bruk en eksisterende mal som et utgangspunkt for din funksjon.

## Opprett en API Gateway Trigger ##
- For å gjøre Lambda-funksjonen tilgjengelig via et HTTP-endepunkt, opprett en **API Gateway**-trigger. (Hvis du brukte et Blueprint, fikk du kanskje API Gateway allerede er inkludert)
- Hvis du opprettet funksjonen fra scratch, velg API Gateway som trigger manuelt og konfigurer den til å eksponere Lambda-funksjonen som et HTTP-endepunkt.

Test funksjonen ved å bruke HTTP-endepunktet for å verifisere at den fungerer som forventet. 

* Kan du implementere noe nyttig utover bare hello world?
* Kan du prosessere en inkommende request?
* Kan du lage en kalkulator?
* Kan du kalkulere PI til n desimaler? 
* Post link på Canvas Chat for PGR301!

Når du er ferdig og har testet funksjonen, **slett Lambda-funksjonen** og API Gateway-oppsettet for å unngå unødvendige kostnader og ressursmangel
        
Lykke til!
