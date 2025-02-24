## Code Question 3
const hamburger = { 
    name: "Cheese Burger", 
    weight: 250,
    maker: {
        name: "Anonymous Chef",
        restaurant: {
            name: "Hyur's Burgers",
            address: "Main Street, 123",
            isOpen: true,
        },
        age: 29
    }
};
​
const secondBurger = structuredClone(hamburger);
const thirdBurger = structuredClone(hamburger);

Quanti oggetti sono stati creati in memoria durante l'esecuzione di questo codice?

- In memoria sono stati creati 9 oggetti: 1"hamburger" al suo interno 2"marker", che a sua volta ha al interno 3"restaurant", copia di "hamburger" in "secondBurger" cosi vengo creati in memoria altri 3 oggetti e un'altra copia di "hamburger" in "thirdBurger" cosi vengo creati in memoria altri 3 oggetti. 