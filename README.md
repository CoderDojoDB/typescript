# Typescript

(let op: we maken tijdens deze workshop gebruik van Chrome!)

## Wat is typescript

Typescript is een programmeertaal die de opvolger is van javascript. Javascript wordt momenteel veel gebruikt om websites mee te maken. 

Het bijzondere van typescript is dat een typescript programma omgezet wordt naar javascript voordat het gestart kan worden.

Typescript is een programmeertaal die je gewoon in een tekst editor kan intypen. Dat is anders bij bijvoorbeeld Scratch. Daar sleep je blokjes en koppel je deze aan elkaar.

Toch lijken typescript en scratch heel erg op elkaar! Elk blokje dat je kent vanuit Scratch, kan je ook in typescript gebruiken door het juiste in je tekst editor in te typen.

## De typescript playground

Wij gaan, om voorlopig niets te hoeven installeren, gebruik maken van de **typescript playground**. Deze kan je (hier|(https://www.typescriptlang.org/play/) vinden. Open deze link maar eens in een nieuwe tab en zet ze naast elkaar zodat je aan de ene kant kunt lezen en aan de andere kant meteen kunt uitproberen.

Elke keer als je op "run" drukt dan wordt je Typescript programma omgezet naar Javascript en wordt deze op een nieuwe tab in je browser geopend.

![De run knop ziet er zo uit](images/run.png)

## Een klein voorbeeld

Type dit programma link in het typescript venster (dus links) in:

```typescript
for (i = 0; i < 10; i++) {
    console.log("Hallo wereld");
}
```

Als je nu op "Run" drukt, opent er een venster maar lijkt er nog niets te gebeuren. Hoe kan dit?

Jou programma in Typescript wordt omgezet naar javascript, dan opent er een venster in je browser om dit stuk javascript uit te gaan voeren. Maar omdat de `console.log("Hallo wereld");` instructie de computer zegt dat hij iets op de "javascript console" moet zetten, doet hij dit netjes, maar toont hij niets in het venster.

*De javascript console is een hulpmiddel voor programmeurs om te kijken wat er tijdens het uitvoeren van javascript code op een web pagina allemaal gebeurt*

Open dus de javascript console door in het menu op `Weergave|Ontwikkelaar|Javascript-console` te drukken.

Je ziet nu de console:

![console](images/console.png)
