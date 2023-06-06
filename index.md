---
layout: default
---


# Bewegende beelden coderen

Betreed de wereld van creatieve code en verleg de grenzen van je verbeelding met Hydra, een live codeer omgeving gemaakt om creatief te zijn met bewegende beelden. Maak je eigen visuele werken door je webcam, kleuren, vormen en nog veel meer samen te mixen tot een kunstwerk met eindeloze mogelijkheden.

Je hebt helemaal geen codeer ervaring nodig om ermee te beginnen. Beelden coderen met Hydra is toegankelijk voor iedereen en helemaal gratis te gebruiken rechtstreeks in je browser.

## De Basis

- Ga naar [hydra.ojack.xyz](http://hydra.ojack.xyz) in je internet browser
- Druk op de prullenbak rechtsboven om met een lege pagina te beginnen
- Je code begint altijd met een bron (zie voorbeelden verderop)
- Daarna kan je de bron vervormen met transformaties, deze beginnen altijd met een punt
- Transformaties en bronnen kunnen totaal verschillende resultaten geven afhankelijk van welke cijfers je gebruikt voor de waarden tussen de haakjes
- Onderaan je code moet je altijd een einde toevoegen *.out()*
- Om je code te activeren druk je op *ctrl+shift+enter*
- Aarzel niet om te experimenteren!

```jsx
osc(10,0.1,0.5)
.color(1,0.89,0.55)
.out()
```

Probeer het voorbeeld uit en wijzig de nummers om te kijken wat er gebeurd. Vergeet niet de code te activeren met *ctrl+shift+enter*

Vervolgens kun je kijken wat er gebeurd als je andere transformaties toevoegt of de bron veranderd.

### Error

Wat te controleren als je code niet werkt

- Heb je typfouten gemaakt?
- Begint je code met een bron?
- lege regels? zorg dat de code aansluit
- Beginnen al je transformaties met een punt?
- Heb je `.out()` op het einde staan?
- Als het beeld is vastgelopen nadat je de code hebt geactiveerd; kopieer jouw code door alles te selecteren, *ctrl-C*, en ververs dan de browser. Klik op de prullenbak om  alles te verwijderen, plak je eigen code door *ctrl-V*  


## Bouwstenen

Hieronder staan een aantal bronnen en transformaties om je op weg te helpen. De volledige lijst is in het engels te vinden op [hydra.ojack.xyz/functions/](https://hydra.ojack.xyz/functions/)

### Bronnen
`osc(40,0.1,0)`
`gradient(1)`
`voronoi(5,0.3,0.3)`
`noise(10,0.1)`
`shape(4,0.5,0)`
`solid(1,0,0)`

### Transformaties
`.rotate(10,1)`
`.pixelate()`
`.kaleid(4)`
`.scroll()`
`.scale(0.5)`
`.colorama(0.005)`
`.color(0,1,1)`

## Maak je eigen webcam effect

1. Voordat je de webcam als bron kunt gebruiken moet deze eerst worden geïnitialiseerd met behulp van `s0.initCam()`. Dit creëert een bron met de naam `s0` die aan de webcam wordt gekoppeld.
```jsx
s0.initCam()
```

2. Nu ga je de webcam weergeven door middel van de `src()` bron. Hierin selecteer je `s0` die in de vorige stap aan de webcam is gekoppeld.
3. Voeg ook `.out()` toe en controleer met *`ctrl+shift+enter`* of het werkt.
```jsx
s0.initCam()

src(s0)
.out()
```

Kun je jezelf zien? Dan kunnen we verder met het beeld transformeren!

4. Gebruik de transformatie `.colorama(0.5)` om de kleuren te beïnvloeden. Speel met de waarden tussen de haakjes totdat je een leuk resultaat hebt.
```jsx
s0.initCam()

src(s0)
.colorama(0.1)
.out()
```
