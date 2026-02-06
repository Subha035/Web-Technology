# TypeCasting

- There are two type of casting in javscript 
```
1. Type Conversion - Expilicit
2. Type Coercion - implicit
```

- Converting One type to another type Explicitly is known as type conversion .

- Converting one type to another type Implicitly is known as type Coercion .

- Explicit conversion is done by programmer.
- implicit conveersion done by javascript.

## <b>Relational Operator</b>
```
    <
    >
    <= 
    >=
    ===
    ==
    !=
    !==
```

### <b>' == '</b> :-
- it is a normal comparison operator .
- ' == ' Operator will check only the values but not the datatype .
- ' == ' Operator performs type Coercion.

### <b>' === '</b> :-
- it is a strict comparison operator .
- ' == ' Operator will check  values as well as datatype .
- ' == ' Operator doesn't performs type Coercion.

## <b>Logical Operator </b>:

## Ex  :-
```
    <script>
        function main(){
            let a = 5;
            let b = 6;
            console.log(a > 5);
            console.log(a > 5 && b > 5);
            console.log(a > 5 || b > 5);
            console.log(!a>5);
        }
        main()
    </script>
```

### Dry Run :-
```
1. !c Operator have high presendence than '>' operator .
2. a value is 5.
3. In javascript 5 is "truthly" value.
4. ! true become false so , false >5 .
5. false will be convert into 0.
6. 0 > 5 will give you result false.
```

### <b>Falsy Values</b>
```
The values which are returning false  whenever we convert into boolean type is known as falsy values
```

- There are 6 falsy values.
```
1. 0 
2.Undefine
3. " "
4. null
5. NaN
6. false
```

### <b>Truthy Values</b>
```
The values which are returning true  whenever we convert into boolean type is known as Truthy values .
```
- Appart from falsy values all other values are truthy values.

## Ex :-
```
    <script>
        function main(){
            let a = 5;
            let b = 6;

            console.log(a++ > 5 || b++ > 6);
            console.log(a , b)
        }
        main()
    </script>
```

## && :-
- If the first value is false the controller will return..
## OR :-
- If the first value is true the controller will return.

```
    true && false = false
    5 && 0 = 0
    "msd" && "vk" = "vk"
    null && NaN = null
    "msd" || 0 = "msd"
```

```
    let checked = false;

    checked = true;

    if(checked)
            show
    else
        hide
```
-    Or
```
    checked ? show : hide ;
```
- Or
```
    Checked && <div>
                        ----
                        ----
                        </div>
```