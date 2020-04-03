Vraag:
- Hoe krijg ik de namen van de director en actors onder een film?
- Hoe krijg ik meer informatie over de film erin?

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

![interactie schetsen](https://github.com/lidwien1/frontend-voor-designers-1920/blob/master/opdracht3/iteratie/screen2.jpg)

De carousel ziet er weer uit zoals die eruit hoort te zien! :) 

Het is mij gelukt om de bolletjes mee te laten bewegen als je van film veranderd. Ook is het mij gelukt om de carousel te bedienen met de pijltjes van mijn toetsenbord. 

# stap 3: Meer informatie over de film laten zien
Nu wil ik dus de director en de actors van de film laten zien onder de film. Ik heb wat geprobeerd maar het lukt niet helemaal. Ik heb voor de rest geen idee waar ik kan beginnen zodat dit werkt.

Ook wil ik graag meer informatie weergeven per film (en dat dan bv alleen maar laten zien als je ergens op klikt, dat het dan uitschuift). De informatie uit de link van 'info over 1 film'.
