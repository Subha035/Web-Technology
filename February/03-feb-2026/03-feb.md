# <b>Javascript</b>
## Datatypes

```
Re Initilization is  possible .But re-Declearation is not possible
```

```
If we declear any  variable without initialization then javascript assign the default value.
```

```
In javascript default value is undefined .
```
```
Javascript is dynamic type programming language.
```

###  Ex :- 

```
    function declear() {
       let n = 10;
       console.log(n);
       n = 'jsp';
       console.log(n);
        n = true;
       console.log(n)
    }
```
### What is dynamic type programming language
- In dynamic type programming languages datatypes are not used at variable declearation.

- In dynamic type programming languages datatype are assign to variable at run time.

## <b>Data Types</b>
- There are two types of datatypes.
1. Primitive Datatype
2. Non-primitive (Object) Datatype.

### Primitive Datatype
- There are 7 types of Primitive Datatype.
```
    1. Number
    2. String
    3.Boolean
    4. Undefined
    5. Null
    6. BigInt
    7. Symbol
```
### Non-Primitive Datatype 
```
    1. Object
    2. Array(List)
    3. Class
```
### 1. <b>Number :-</b>
- Number is used to store decimal and non-decimal values.
#### Ex :- 
```
    let n = 10;
    console.log(n,typeof n);
    n = 10.4;
    console.log(n,typeof n);
```
#### Note :-
```
Typeof is a uniary operator which is used to check datatype of a given value or variable.
```
### 2.  <b>String  :-</b>
- String Type is used to store single letter or group of letters.
- In javascript String can be represented with single quote (' ') or double quote (" ") or backtick (` `)operator.

#### Ex:-
```
    let str = 'Subhadeep';
    console.log(str ,typeof str);

    let str = "Subhadeep";
    console.log(str ,typeof str);

    let str = `Subhadeep`;
    console.log(str ,typeof str);
```
### 3. <b>Undefined  :-</b>

- Undefined  is datatype of a variable which is decleared but not assigned any value.

 #### Ex:-
```
    let n;
    console.log(n ,typeof n);  //Undefined
```

### 3. <b>Null  :-</b>
- Null  value is used to make an object abandoned .
- An object which doesn't have any reference is known as abandoned object.
- Datatype of naull Is a Bug.

<h2>

</h2>

## <b>Operators </b> 
 - '/' operator return decimal value , if we want only number then it should be used some inbuilt function like - ceil , floor , trunc , roundoff.
 - '%' return reminder .
 - '+' is used to addition two variable .
 - '-' is used to substruction between two variable.
 - '*' is used to multiplication between two variable.

 ```
 '+' opeerator can be used for Concartination.
 ```

## Concartination : -
- Concartination means joining or combining two or more operands .
- To perform Concartination we use '+' operator .
- For Concartination atleast one operand should be String type .


```
    let a = 10 ;
    console.log("a value is : "+a);
```


# Diference between error and Bug.

## Error
```
1.  A human action or mistake that produces an incorrect result.	
2.  Made by programmers, analysts, or designers.	
3.  Often caught by the developer during coding or unit testing.	
4.  Syntax errors, typos, or misunderstanding a requirement.	
5.  A technical term used primarily  by developers.	
```
## Bug 
```
1.  A flaw or defect in the software that causes unexpected behavior.
3.  Result of an unresolved error in code or design.
2.  Typically identified by testers during the testing phase.	
4.  Crashing during upload, button not clicking, or logic flaws.
5.  An informal/colloquial term used primarily by QA and testers.
```
# What is the difference between null and undefined .
##  Undefined 
```
1.  Absence of a definition (unintentional)	
2.  Automatically assigned by JavaScript	
3.  (typeof)	"undefined"	
4.  Evaluates to NaN (Not a Number)	
5.  Omitted from JSON strings	
```

##  Null 
```
1.  Absence of an object (intentional)
2.  Manually assigned by the developer
3.  "object" (a historical bug)
4.  Evaluates to 0
5.  Preserved as null
```