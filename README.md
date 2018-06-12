# Typescript startproject

Dit is een leeg startproject voor de oefeningen in CMTTHE01-4 en PRG01-8. 

## Het project

- De **docs** map bevat de client side:html en css. De js file wordt hier automatisch in gezet door de compiler.
- De **dev** map bevat de typescript files.
- **game.ts** is het startpunt van de app. Hierin staat de window listener die een `new Game()` maakt.

## Compileren
- Druk op CMD+SHIFT+B en kies voor `watch mode`. Je `.ts` files worden nu samengevoegd in `main.js`.
- tsconfig.json bevat instellingen voor het compileren.

## Bekijken
Open index.html in `localhost`

## Peer Review
- Ik review de game van Hugo. [Link](https://github.com/Hugocaminada/mijnGame)
- Hij heeft goed gebruik gemaakt van **Encapsulation** en maakt gebruik van private en public variablen/methods
- Maakt ook goed gebruik van Composition bijvoorbeeld dit `this.game.showScreen(new Lizardlevel(this.game))` en `private game : Game` , `constructor(g:Game){..}` , `this.game = g`
- Overerving nog todo.