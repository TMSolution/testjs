# Test

## 1. Czy kod wykona się poprawnie? Uzasadnij dlaczego.
 
 ```javasrcript
let  property="Miś";
const property="Kotek";
```

## 2. Czy kod wykona się poprawnie? Uzasadnij dlaczego.
 
 ```javasrcript
let  property="Miś";

if(property==="Miś")
{
  const property="Kotek";
}
```


## 3. Czy kod wykona się poprawnie? Uzasadnij dlaczego.
 
 ```javasrcript
const  property="Miś";

if(property==="Miś")
{
  property="Kotek";
}
```



## 4. Co wyświetli program?
 
 ```javasrcript
const  property="";

if(property===null)
{
  console.log("1")
}

if(!property)
{
  console.log("2")
}
```


## 5. Co wyświetli program?
 
 ```javasrcript
const  property="";
const  property2=0;

if(property===property2)
{
  console.log("Hello")
}

if(property==property2)
{
  console.log("World")
}
```

## 6. Czy program wykona się poparwnie?
 
 ```javasrcript
const  property="";
const  property="Ala ma kota";
```


## 7. Czy program wykona się poparwnie? Uzasadnij
 
 ```javasrcript
let  property="";
let property="Ala ma kota";
```

## 8. Czy program wykona się poparwnie? Uzasadnij
 
 ```javasrcript
let  property="";
property="Ala ma kota";
```

## 9. Czy program wykona się poparwnie? Uzasadnij
 
 ```javasrcript
const  property="Miś";

if(property==="Miś")
{
   let property="Kotek";
}
```

## 10. Co wyświetli program?
 
 ```javasrcript
let user = { name: "Ala", lastname:"Ma kota", age: 12}

for( let property in user)
{
  console.log(property)
}
```



## 11. Co wyświetli program?
 
 ```javasrcript
let user = { name: "Ala", lastname:"Ma kota", age: 12}

for( let property in user)
{
  console.log(user[property])
}
```

## 12. Co wyświetli program?
 
 ```javasrcript
let values = [1,2,3,4,5] 

for( let x of values)
{
  console.log(x)
}
```


## 13. Co wyświetli program?

 ```javasrcript
const user = { name: "Ala", lastname:"Ma kota", age: 12}
const clientType = { type: "gold"}
const client={...user,...clientType}

for( let property in client )
{
  console.log(client[property])
}
```


## 14. Co wyświetli program?

 ```javasrcript
const girls=["Ania","Basia","Joanna"]

console.log(girls[1]);

```


## 15. Co wyświetli program?

 ```javasrcript
const girls=["Ania","Basia","Joanna"]

console.log(girls.length);

```


## 16. Co wyświetli program?

 ```javasrcript
const girls=["Ania","Basia","Joanna"]

console.log(girls[0]);

```


## 17. Co wyświetli program?

 ```javasrcript
const girls=["Ania","Basia","Joanna"]

console.log(girls[girls.length-1]);

```

## 18. Co wyświetli program?

 ```javasrcript
const girls=["Ania","Basia","Joanna"]
const boys=["Paweł","Robert","Rafał"]
const people=[...girls,...boys]

const fewPeople=[...people.slice(3,4),...people.slice(5,6)]

console.log(fewPeople);
```

## 19. Co wyświetli program?
 ```javasrcript
const girls={"Ania":1,"Basia":2,"Joanna":3}
const boys=["Paweł","Robert","Rafał"]
const people=[...Object.keys(girls),...boys]

console.log(people);
```

## 20. Co wyświetli program?
 ```javasrcript
const user={"name":"Jacek","Forname":"Łoziński"}
user["age"]=45;
const hobby=["Sport","Muzyka","oraz Gry"];
user.hobby=hobby;
hobby.shift();
console.log(user);
```




