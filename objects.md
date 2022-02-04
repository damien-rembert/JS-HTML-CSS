# objects
let myObject = {type:"Fiat", model:"500", color:"white"};


const cafe = {
name: "Whitesheep",
seatingCapacity: 100,
hasSpecialOffers: true,
drinks: [
"Cappuccino",
"Latte",
"Filter coffee",
"Tea",
"Hot chocolate"
]
};



# classic function declaration
let pet = {
    name: "The Beast",
    typeOfPet: "cow",
    age: 45,
    colour: "blue",
    drink() {
        return `${this.name} is drinking`
    }
}

console.log(pet.drink());

# anonymous function declaration
let pet = {
    name: "The Beast",
    typeOfPet: "cow",
    age: 45,
    colour: "blue",
    drink: function() {
        return `${this.name} is drinking`
    }
}

console.log(pet.drink());

