# 100 Days Of Code - Log

### Day 1: September 27, 2020

**Today's Progress**: Learning debugging techniques in JS. 

**Thoughts:** Useful practice, and mostly basic with many simlarities to debugging in other languages. I came across the concept of 'pass by refernce' and 'pass by value' in the form of a bug. Really interesting. I now know that JS is a 'pass by reference' language, but I need to educate myself a little further. 

### Day 2: September 28, 2020

**Today's Progress**: Learnt about JS as a 'pass by reference'. 

**Thoughts:** I have consolidated my thoughts into a lesson. Here it is. 

Definition of a 'pass by reference' (PBR) language: 
- If you mutate a varibale within a function, the mutation **will be** inflected back to the variable outside the function. 

Definition of a 'pass by value' (PBV) language: 
- If you mutate a variable within a function, the mutation will **not** be inflected back to the variable outside the function. 

Here is **EXAMPLE 1: Primitive value reassignment**: 
```
let a = 1; 

let change = (val) -> { 
   val = 2;
};

change(a); 
console.log(a); \\ 1
```
The output, ```1```, gives the impression that it's a case of PBV... but this is not the case!  

JS always uses PBR... some people say that primitive values (data like the number 1) use PBV, whereas objects use PBR. Again, this is wrong. **JS always uses PBR**.  

Why? Hang in there. We need another couple of examples first. 

Here is **EXAMPLE 2: Object reassignment**: 
```
let a = {num:1}; 

let change = (val) -> { 
   val = {};
};

change(a); 
console.log(a); \\ {num:1}
```

Again... it looks like PBV, right? Surely if JS if PBR, the variable ```a``` should have changed to an empty object, like ```{}```.  

This is not the case. The next exampe proves that JS is PBR. 

Here is **EXAMPLE 3: Object mutation **: 
```
let a = {num:1}; 

let change = (val) -> { 
   val.num = 2;
};

change(a); 
console.log(a); \\ {num:2}
```  
As we can see, this example demonstrates PBR, as the variable ```a``` (found within a scope outside of the function) **is** changed (from within the scope of the function).  

But why didn't a change reflect in example 2?  

Becuase, we weren't **mutating** the object, we were completely **reassigning** it to an empty object. This is key. Within the function, for PBR to work, the ```=``` operator needs to be able to **mutate** the object in question. When it is forced to **reassign** the object, as in example 2, then the reference to that 'computer address' breaks, and a completely new varibale is made within the function. In this case, ```val``` was reassigned to store ```{}```.  

Ok, but what about example 1. That still looks like PBV, right? Nope, still PBR. 

In example 1, JS does indeed pass a reference of the primitive value (the number 1) into the function. However, JS cannot mutate primitive numbers, it can only ever reassign them when the ```=``` is used. Therefore, JS has to reassign the value of ```a```. As with the last example, when reassignment is used, the 'reference' to the variable address cannot be kept. As a result, a new, unrelated variable is made within the scope of the function ```val```.  

So during reassignment, it looks like we loose the refernce, the address to the data of the variable in question.  

Here is a **Final EXAMPLE:**
```
let a = {num:1};
let b = a;

console.log(a); \\ {num:1} 
console.log(b}; \\ {num:1} 
```
Unsuprisingly, ```b``` adopts the identity of ```a```. 
Upon mutation of ```a```... 
```
a.num = 2; 
console.log(a); \\ {num:2} 
console.log(b}; \\ {num:2} 
```
... ```b``` adopts the value of ```a```, as JS works via PBR, and we've just done a mutation, which allows for PBR. 
But here, we now reassign ```a```...
```
a.num = {}; 
console.log(a); \\ {} 
console.log(b}; \\ {num:2} 
```
... The value of ```a``` changes, as it has been reassigned to an empty object. ```b``` stays exactly the same though! Reassignment has been used, and so it's link to ```a``` is lost. 
