# <b>JavaScript</b>
```
1. Javascript is a client side programming Language Which is used to create dynamic functionality on HTML pages.

2. Javascript can be used for frontend as well as nbackend development.

3. For Frontend development for Run Time env is browser and for backend development Run time Environment Node js.

4. To execute javascript code  on browser we must attech Hscript code to HTML file HTML.

5. Javascript is Multidigm Progamming Language.

6. Javascript is 
```

## Syntax :-
- <b> HTML </b>
```
    <!DOCTYPE html>
    <html lang="en">
    <head>
       <title>Document</title>
       <script src="./app.js"></script>
    </head>
    <body>
        <h1>Js Basic</h1>
    </body>
    </html>
```
- <b>Javascript</b> (app.js)
```
    console.log("Subhadeep Ghosh")
```

## Ex :-
```
 <!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    <!-- <script src="./02-feb.js"></script> -->
     <script>
        console.log("Subhadeep Ghosh - Console")

        function Printmsg() {
            console.log("Subhadeep Ghosh 🩵- Function")
        }
        class greet{
            static main(){
                console.log("Subhadeep Ghosh 🍻- class")
            }
        }
             Printmsg();
             greet.main();
     </script>
</body>
</html>
```

##  <b> Variables</b>
- Variable is a container which is used to store a single value.
## Syntax :-
```
    Keyword varName ;
    varName = value ;
```

## Ex :-
```function main(){
    var n1 ;
    n1 = 10 ;
    console.log(n1) ;

    let n2 ;
    n1 = 10 ;
    console.log(n2) ;

    const n3 = 10 ;
    console.log(n3) ;
}
main();
```

### <b> Note :- </b>

```
In javascript we can create a variable without using any keyword but it's a bad practiceing application development.

Its a valid but not good practice.
```
## Ex :
```
    <scrip>
            let passTest = false ;
            let gotJob = false ;
            passTest = true ; // re-initialization

            if(passTest){
            gotJb = true; // new Variable is created
            }
        console.log("got job = "+gotJob)
     </scrip>
```

  