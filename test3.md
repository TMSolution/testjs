# Test - Tablice w Js

## 1. Co wyświetli program?
 
 ```javasrcript
const user=
{
  name: "Mariusz",
  hobby:"wędkarstwo"

}
const hobby =user.hobby.slice(0,1).toUpperCase()+user.hobby.slice(1)   
console.log(hobby)
```

## 2. Co wyświetli program?
 
 ```javasrcript
var text="Ala ma kota";
console.log( text.charAt(4)+text.charAt(2)+text.charAt(text.length-2) );
```


## 3. Co wyświetli program?
 
 ```javasrcript
const text = 'Albo melon, albo arbuz';

const words = text.split(',');
console.log(words[1].trim());
```



## 4. Co wyświetli program?
 
 ```javasrcript
 
const p = 'Mały pies, jak to pies, wie jak jest';
const regex = /pies/i;
console.log(p.replace(regex, 'kot'));
```


## 5. Co wyświetli program?
 
 ```javasrcript
const text = 'U prząśniczki siedzą jak anioł dzieweczki';
const searchTerm = 'siedzą';
const index = text.indexOf(searchTerm);
console.log(index)
console.log(text.slice(index))
```

## 6. Co wyświtli program?
 
 ```javasrcript
const paragraph = 'Black hole sun';
const regex = /HoLe/ig;

console.log(paragraph.search(regex));
```


## 7. Co wyświetli program?
 
 ```javasrcript
const paragraph = 'blue blue blue';

const searchTerm = 'b';
console.log(paragraph.lastIndexOf(searchTerm));
```

## 8. Co wyświetli program?
 
 ```javasrcript
const str1 = 'Hello';
const str2 = 'World';

console.log(str1.concat(' ', str2)===`${str1} ${str2}`);
```

## 9. Co wyświetli program?
 
 ```javasrcript
const str = 'Maczuga';
console.log(str.substr(0,2)+str.substr(0,1).toLowerCase()+str.substr(-1));
```

## 10. Co wyświetli program?
 
 ```javasrcript
const sentence = 'Baba mi koguta dała';

const word = 'koguta';

console.log(`Słowo "${word}" ${sentence.includes(word) ? 'znajuduje się ' : 'nie znajduje'} się w zdaniu`);
```



## 11. Co wyświetli program?
 
 ```javasrcript
console.log(Math.pow(2, 3))
```

## 12. Co wyświetli program?
 
 ```javasrcript

console.log(10%3)
```


## 13. Co wyświetli program? Uwaga!!

 ```javasrcript
console.log(Math.ceil(7.004))
```


## 14. Co wyświetli program?

 ```javasrcript
 
console.log(Math.abs(-2));
```


## 15. Co wyświetli program?

 ```javasrcript
const numbers= [-10,-20];
const result=Math.max(...numbers) + Math.min(...numbers)
console.log(result)
```


## 16. Co wyświetli program?

 ```javasrcript
console.log(Math.sqrt(9))
```

## 17. Co wyświetli program?

 ```javasrcript

console.log(Math.trunc(42.84));
```

## 18. Co wyświetli program?

 ```javasrcript
 console.log(Math.floor(5.95));

```

## 19. Wypisz zakres wartości jakie może zwrócić ten program?
 ```javasrcript
console.log(Math.floor(Math.random() *10))
```



## 20. Co robi funkcja x (jakie jest jej zastosowanie)?
 ```javasrcript
function x(radius) {
  return 2 * Math.PI * radius;
}

console.log(x(10))
```

