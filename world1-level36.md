#  Level 36
## Das finale Kith Labyrinth
![Alt text](38.png)
```js
while(true) {
    hero.moveRight();
    hero.moveUp();
    var enemy1 = hero.findNearestEnemy();
    hero.attack(enemy1);
    hero.moveRight();
    hero.moveDown(2);
    hero.moveUp();
 }l 

