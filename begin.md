
# Het begin: variabelen.

Je herinnert je misschien nog wel het stukje code wat we in ons eerste voorbeeld hebben gebruikt:

```typescript
for (i = 0; i < 10; i++) {
    console.log("Hallo wereld");
}
```

Hierin wordt eigenlijk al een *variabele* gebruikt. In dit geval een getal met de naam **i**. Een variabele is een stukje geheugen waar je een *waarde* in kunt zetten en uit kunt lezen.

Een waarde kan bijvoorbeeld een tekst zijn of een getal. Er zijn een aantal **typen variabelen** die we kunnen gebruiken in TypeScript:

* string (een tekst, bijvoorbeeld: "dit is een string")
* booleaanse waarde (waar of onwaar, bijvoorbeeld: *true* of *false*)
* number (een getal met of zonder decimale punt, bijvoorbeeld *4* of *4.75*)

## Variabelen declareren

Omdat TypeScript een taal is die let op variabelen typen, moeten we een variabele altijd *declareren*. Declareren is een moeilijk woord voor "bekend maken", zodat TypeScript kan onthouden wat voor variabele *type* het is en je dus ook kan waarschuwen als je dingen doet die niet bij elkaar passen.

Een voorbeeld van een declaratie en het gebruik van een variabele is:

```typescript
// declareer variabelen
var getal: number;
var tekst: string;

// initialiseer variabelen
getal = 5;
tekst = "Dit is een tekst";

// gebruik variabele
getal = getal + 4;

// en laat zien wat het doet
console.log("5 + 4 = ", getal);
console.log(tekst);
```

**Probeer dit kleine programma uit in de playground.**

## Opdracht: De tafel van 6

Probeer nu zelf, met het voorbeeld uit het vorige hoofdstuk én de informatie die je nu weet over variabelen, een programma te maken die de tafel van 6 afdrukt op de javascript console.

De structuur is:

* declareer een variabele, waarmee je
* een **for** lus maakt
* om de waarden een voor een via een `console.log()` op de console te laten zien.

Ben je klaar? Laat het dan maar zien aan een van de mentoren en probeer daarna anderen hiermee te helpen.

## Extra moeilijke opdracht: Laat alle tafels van 1 - 10 zien.

Verander nu je programma zodat hij niet alleen de tafel van 6 laat zien, maar *alle tafels van 1 tot 10*.
