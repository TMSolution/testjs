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
let  property="";
property="Ala ma kota";
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
  console.log(property)
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


## 12. Co wyświetli program?

 ```javasrcript
const user = { name: "Ala", lastname:"Ma kota", age: 12}
const clientType = { type: "gold"}
const client={...user,...clientType}

for( let property in client )
{
  console.log(client[property])
}
```