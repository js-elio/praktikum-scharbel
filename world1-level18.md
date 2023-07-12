# Level 18 
## Der Gefangene 
![Alt text](18.png)
```js
// Befreie den Gefangen, besiege den Wächter und schnappe dir den Edelstein.

// Befreie Patrick, welcher hinter der "schwachen Tür" ist.
hero.moveRight();
hero.attack("Weak Door");
hero.attack("Weak Door");
hero.moveRight(2);
hero.moveDown(3);
hero.attack("Two");
hero.attack("Two");
hero.attack("Two");
hero.moveRight();

// Erhalte den Edelstein.
