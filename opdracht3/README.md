Vraag:
- Hoe krijg ik mijn buttons terug?
- Hoe krijg ik de afbeeldingen weer zoals bij opdracht 2?

Dit filmpje heb ik gebruikt bij opdracht 2:
https://www.youtube.com/watch?v=gBzsE0oieio

# frontend voor designers - opdracht 3: Een interactie uitwerken met externe data

Ik heb ervoor gekozen om verder te gaan met de carousel, wat ik hiervan nog moest verbeteren:
- de knoppen
- de bolletjes mee laten bewegen
- bedienen met toetsenbord

# stap 1: Data ophalen
Het is mij gelukt om ipv de foto's die ik in opdracht 2 had gebruikt voor de carousel de afbeeldingen van de films te hebben. Nu was het alleen geen carousel meer maar stonden de foto's horizontaal op de pagina en kon je er doorheen scrollen. 

(Ik heb even de width van het beeld veranderd zodat je de foto's iets dichter naast elkaar ziet staan.)

![interactie schetsen](https://github.com/lidwien1/frontend-voor-designers-1920/blob/master/opdracht3/iteratie/screen1.jpg)


# stap 2: Het weer op een carousel laten lijken
Als je op de bolletjes klikt wordt je nog steeds verwezen naar de afbeelding waar het bolletje bij hoort. Echter zijn mijn buttons aan de zijkanten verdwenen en ik heb echt alles geprobeerd maar ik krijg ze niet terug. 

Toen ging ik proberen om de afbeeldingen weer op elkaar te krijgen zoals ik dat ook bij de carousel heb gedaan. Dit lukt wel soort van maar de laatste afbeelding kwam bovenop en de bolletje deden het niet meer.

Ik heb in 'script.js' het volgende veranderd:
- regel 52 verwijderd
- regel 55 veranderd naar: var slides = newImg

Dan komt het er zo uit te zien:

![interactie schetsen](iteratie/screen2)

ALs het mij lukt om de carousel er weer uit te laten zien zoals bij opdracht 2 ga ik verder werken aan het uiterlijk van de carousel en met toetsenbord.
