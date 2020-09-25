# Test - Tablice w Js

## 1. Jakie wartości zawiera tablica indexes.
 
 ```javasrcript
const numbers=[1,2,3,4,5,6];

const index1=numbers.indexOf(3);
const index2=numbers.indexOf(5);
const index3=numbers.indexOf(6);

const indexes=[index1,index2,index3]

console.log(indexes)
```

## 2. Jaką wartosć zawiera zmiena index i dlaczego?
 
 ```javasrcript
const index=[1,2,3,4,5,6].lastIndexOf("kotek")
console.log(index)
```


## 3. Co wyświetli program?
 
 ```javasrcript
const numbers=[1,2,3];
const newArray=[...numbers,...numbers]

console.log(newArray)
```



## 4. Co wyświetli program?
 
 ```javasrcript
const numbers=[1,2,3,2,3,5].filter((value)=>{
  return value<3;
});
console.log(numbers)
```


## 5. Co wyświetli program?
 
 ```javasrcript
let words=["ala","ma", "kota"];
words.pop() ;
words.push("psa");
words.shift();

console.log(words)
```

## 6. Co wyświtli program?
 
 ```javasrcript
const names=["ania","basia","ola"];

for(let i=0; i<names.length;i++)
{
  names[i]=names[i].toUpperCase();

}
names.reverse();
console.log(names)
```


## 7. Co wyświetli program?
 
 ```javasrcript
var numbers = [1, 2, [3, 4]];
numbers.flat(); 
console.log(numbers);
```

## 8. Co wyświetli program?
 
 ```javasrcript
array = [2, 5, 9, 2,5];
index = array.lastIndexOf(2);
console.log(index)
```

## 9. Czy program wykona się poparwnie? Uzasadnij
 
 ```javasrcript
var  letters = ['A', 'B', 'C', 'D'];
console.log(letters.toString());
```

## 10. Co wyświetli program?
 
 ```javasrcript
var months = ['Styczeń', 'Luty', 'Marzec', 'Kwiecień'];
console.log(months.join("|"));
```



## 11. Co wyświetli program?
 
 ```javasrcript
var numbers = [1, 5, 10, 15];
var result = numbers.map(function(item) {
    return item -1;
});
console.log(result);
```

## 12. Co wyświetli program?
 
 ```javasrcript

let text="";

function printElt(element, index, array) {
    if(index!==0)
    {
    text+=element.name;
    }
}
[{ name:"Ala"}, {name:"da"}, {name:"kota"}].forEach(printElt);

console.log(text)
```


## 13. Co wyświetli program? Uwaga!!

 ```javasrcript
const arr=[1,40,2,3,4,5]

console.log(arr.sort())
```


## 14. Co wyświetli program?

 ```javasrcript
 
const arr=[1,40,2,3,4,5]

const sortFunction=(a,b)=>
{
   if (a <b)
      return -1
   if (a >b)
      return 1
   return 0
}

console.log(arr.sort(sortFunction))
```


## 15. Co wyświetli program?

 ```javasrcript
 const animals = ['ant', 'bison', 'camel', 'duck', 'elephant'];

console.log(animals.slice(3));
```


## 16. Co wyświetli program?

 ```javasrcript
function greaterThanTen(element, index, array) {
  return element > 10;
}
const result=[2, 5, 8, 1, 4].some(greaterThanTen); 

console.log(result)
```

## 17. Co wyświetli program?

 ```javasrcript

console.log([1, 2, 3].includes(4))
```

## 18. Co wyświetli program?

 ```javasrcript
const num1 = [1, 2, 3];
const num2 = [1, 2, 3];
nums = num1.concat(num2.reverse()) 
console.log(nums)
```

## 19. Co wyświetli program?
 ```javasrcript
const fish = ["płoć", "okoń", "sieja", "jesiotr"];
fish.splice(3, 1, "szczupak")
console.log(fish)
```



## 20. Co wyświetli program?
 ```javasrcript
const reducer=(previousValue, currentValue)=> {
  return previousValue + currentValue;
}

const result=[0, 1, 2, 3, 4].reduce(reducer);
console.log(result);
```

