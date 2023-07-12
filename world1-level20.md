# Level 20 
## Schränke von Kithgard B (Übung)
![Alt text](20.png)
```js
// Da ist ringsherum vielleicht etwas, das dir hilft!

// Als erstes gehe zum Schrank.

// Dann greife den Schrank "cupboard" mit einer while Schleife an.
hero.moveRight();
hero.moveDown();
hero.moveRight();
hero.moveDown(2);
while(true) {
  hero.attack("Cupboard");  
}

