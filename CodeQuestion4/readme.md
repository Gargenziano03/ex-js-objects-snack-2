## Code Question 4
const chef = {
    name: "Chef Hyur",
    age: 29,
    makeBurger: (num = 1) => {
        console.log(`Ecco ${num} hamburger per te!`);
    },
}
​
const restaurant = {
    name: "Hyur's Burgers",
    address: {
        street: 'Main Street',
        number: 123,
    },
    openingDate: new Date(2025, 3, 11),
    isOpen: false,
};


Qual è il metodo migliore per clonare l’oggetto chef, e perché?
- Il metodo migliore per clonare l’oggetto chef è "Spread (...)", perchè è un'ottima scelta per clonare oggetti semplici e poco profondi 
Qual è il metodo migliore per clonare l’oggetto restaurant, e perché?
- il metodo migliore per clonare l’oggetto restautant "structuredClone()", perchè è un'ottima scelta nel clonare oggetti complessi, inclusi oggetti annidati e tipi speciali come Date()