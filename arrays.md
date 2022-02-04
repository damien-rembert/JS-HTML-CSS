# arrays


let myArray = [5 , 'hello', ['another array', 89]];

myArray[0] = 1;

As for it’s items we can
also add, remove,
append, modify, copy..

## .push()

let coffeeOrder = [
"Alex - Cortado",
"Ben - Cortado",
"Charlie - Whatever's new"
];
coffeeOrder.push("Donna - espresso");

## .pop()
let coffeeOrder = [
"Alex - Cortado",
"Ben - Cortado",
"Charlie - Whatever's new"
];
coffeeOrder.pop();

## other methods to look into/describe
.map()
.shift()
.splice()
.slice()
.unshift()
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array




const customer = [
        {first_name:    "Aleshia",    last_name:    "Tomkiewicz",    phone:    11835703597},
        {first_name:    "France",    last_name:    "Andrade",    phone:    1347368222},
        {first_name:    "Ulysses",    last_name:    "Mcwalters",    phone:    11912771311},
        {first_name:    "Tyisha",    last_name:    "Veness",    phone:    11547429341},
        {first_name:    "Eric",    last_name:    "Rampy",    phone:    11969886290},
        {first_name:    "Marg",    last_name:    "Grasmick",    phone:    11865582516},
        {first_name:    "Laquita",    last_name:    "Hisaw",    phone:    11746394243},
        {first_name:    "Lura",    last_name:    "Manzella",    phone:    11907538509},
        {first_name:    "Yuette",    last_name:    "Klapec",    phone:    11903649460},
        {first_name:    "Fernanda",    last_name:    "Writer",    phone:    11630202053},
        {first_name:    "Charlesetta",    last_name:    "Erm",    phone:    11276816806},
        {first_name:    "Corrinne",    last_name:    "Jaret",    phone:    11625932209},
        {first_name:    "Niesha",    last_name:    "Bruch",    phone:    11874856950},
        {first_name:    "Rueben",    last_name:    "Gastellum",    phone:    11976755279},
        {first_name:    "Michell",    last_name:    "Throssell",    phone:    11967580851},
        {first_name:    "Edgar",    last_name:    "Kanne",    phone:    11326532337},
        {first_name:    "Dewitt",    last_name:    "Julio",    phone:    11253528327},
        {first_name:    "Charisse",    last_name:    "Spinello",    phone:    11719831436}];
// Create an array of Customers first names with .map()

        const cust1stName = customer.map(function(customer){
                return customer.first_name;
});

        console.log(cust1stName)




