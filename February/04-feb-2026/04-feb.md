  ## <b>Template literals </b>
- Template literals  is also known as   Template String.
- Template literals is Introduce in ES6 Version.
- Template literals Re the modern way to work with Strings.
## Advantages :-
```
We can embed variables or any valid javascript expression directly inside the string using the ${expression} syntac.
```
```
Template Literal will allow strings to span multiple lines without needing escape characters like \n .
```

#### Ex:-
<b>1. </b>
 ```
    function main(){
        let a = 10;
        console.log("a value is "+a);
        console.log(`a value is ${a}`);
        console.log(`Addition Is ${a+10}`);       console.log(a)
        let str = `Subhadeep 
        Ghosh`
        console.log(str)
        }
 ```
 <b>2.</b>
 ```
        function main(){
            let a = 10;
            let b = 12;
            let res = a + b;
            console.log(a+" + "+b+" = "+res);
            console.log(`${a} + ${b} = ${res}`);
        }
 ```

 ### Compound Operator
 - When two operator used in same type.

 ## Ex :- 
 ```
    n+=1  < n= n+1 >
 ```

-   4 + "5 = "45"
-   4 * "5" = 20
-   4 * "Ro" = NaN
-   1 + 8 = 9
-   9 + "Ro" = "9Ro"
-   5 - "3" = 2
-   Number("5") = 5
-   Number(true) = 1
-   true + 3 = 4-     
-   Number("jsp") = NaN

