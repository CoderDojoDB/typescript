
# Het begin: variabelen.

Je herinnert je misschien nog wel het stukje code wat we in ons eerste voorbeeld hebben gebruikt:

```typescript
for (i = 0; i < 10; i++) {
    console.log("Hallo wereld");
}
```

Hierin wordt eigenlijk al een *variabele* gebruikt. Een variabele is een stukje geheugen waar je een *waarde* in kunt zetten.

Een waarde kan bijvoorbeeld een tekst zijn of een getal, er zijn een aantal **typen variabelen** die we kunnen gebruiken in TypeScript:

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

![Probeer dit uit.](https://www.typescriptlang.org/play/#src=var%20getal%3A%20number%3B%0D%0Avar%20tekst%3A%20string%3B%0D%0A%0D%0Agetal%20%3D%205%3B%0D%0Atekst%20%3D%20%22Dit%20is%20een%20tekst%22%3B%0D%0A%0D%0Agetal%20%3D%20getal%20%2B%204%3B%0D%0A%0D%0Aconsole.log(%225%20%2B%204%20%3D%20%22%2C%20getal)%3B%0D%0A%0D%0A#src=%2F%2F%20declareer%20variabelen%0D%0Avar%20getal%3A%20number%3B%0D%0Avar%20tekst%3A%20string%3B%0D%0A%0D%0A%2F%2F%20initialiseer%20variabelen%0D%0Agetal%20%3D%205%3B%0D%0Atekst%20%3D%20%22Dit%20is%20een%20tekst%22%3B%0D%0A%0D%0A%2F%2F%20gebruik%20variabele%0D%0Agetal%20%3D%20getal%20%2B%204%3B%0D%0A%0D%0A%2F%2F%20en%20laat%20zien%20wat%20het%20doet%0D%0Aconsole.log(%225%20%2B%204%20%3D%20%22%2C%20getal)%3B%0D%0Aconsole.log(tekst)%3B%0D%0A)
