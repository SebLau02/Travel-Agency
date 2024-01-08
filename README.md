# Travel Agency

## Fr

### Description

Intégration d'une maquette figma.

### Détails

Ce projet est une intégration d'un maquette figma que j'ai trouvé sur figma community. C'était pour moi l'occasion de pratiquer l'inté. Il a été fait en simple HMTL, CSS. J'ai ajouté quelques effets personnel comme les effets de hover sur les companies aérienne et les services proposés, le responsive design, un petit effet blur sur la navbar quand on scroll vers le bas et un menu burger sur petit écran. Les éléments de déco à la section "subscribe" ne sont pas bien positionné, j'ai fais de mon mieux, ça a été la partie la plus difficile alors que ça ne parrait pas (comme quoi, don't judge a book by its cover).

Pour explication du hover sur les cartes et les companies aérienne, j'ai préféré animer opacity que de box-shadow due au fait que animer opacity est simplement plus performant que d'animer box-shadow. J'ai donc créer un pseudo élément after en dessous de chaque box de chaque élément à survoler avec une box-shadow (avec la même width et height) et quand je hover l'élément le pseudo élément passe en opacity 1 ce qui va afficher/cacher le box-shadow.

La maquette est [ici](https://www.figma.com/community/file/993910904620677970)

Vous pouvez le visiter [ici]()

## En

This project is a Figma model implementation that I found on the Figma community. It served as a practice for web design implementation and was built entirely using HTML and CSS. I added some personal effects, such as hover effects on airline companies and services cards, responsive design, a blur effect on the navbar when scrolling down, and a burger menu for small screens. However, there were challenges, and I couldn't implement the decorative element in the 'subscribe' section correctly; it was the most challenging part of this project.

To explain the hover effect on airline and services cards, I chose to animate opacity rather than using box-shadow directly because opacity is more efficient. To achieve this, I created an after element with the same width and height beneath my hovered element. This after element contains the box-shadow. Now, I toggle the opacity of the after element between 1 and 0 on hover of the parent element.

You can see the model [here](https://www.figma.com/community/file/993910904620677970)

Visit it [here]()

### Technologies: HTML, CSS, JS

### Images

<img src="./assets/images/illustrations/illustration1.png" alt="illustration" width="800">
<img src="./assets/images/illustrations/illustration2.png" alt="illustration" width="400">
<img src="./assets/images/illustrations/illustration3.png" alt="illustration" width="800">
