## Code Question 1
const hamburger = { name: "Cheese Burger", weight: 250 };
const secondBurger = hamburger;
secondBurger.name = 'Double Cheese Burger';
secondBurger.weight = 500;

console.log(hamburger.name); // ?
console.log(secondBurger.name ); // ?
const hamburger = { name: "Cheese Burger", weight: 250 };
const secondBurger = hamburger;
secondBurger.name = 'Double Cheese Burger';
secondBurger.weight = 500;
​
console.log(hamburger.name); // ?
console.log(secondBurger.name ); // ?


Senza lanciare il codice, riesci a prevedere cosa viene stampato in console?
- In console viene stamapato 'Double Cheese Brger' sia per hamburger.name che per secondBurger.name.

Quanti oggetti sono stati creati in memoria durante l'esecuzione di questo codice?
- In memoria è stato creato un singolo oggetto "hamburger".