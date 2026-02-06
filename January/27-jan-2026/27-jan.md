## <b>CASCADING STYLE SHEET (CSS)</b>

```
CSS is used to applying style to HTML element.
```
<b>There are 3 ways to apply the style to HTML Element</b>
- Inline Stylesheet
- Internal Stylesheet
- External Stylesheet

### Inline Stylesheet :-
```
    <h1 style="color: aqua;"> Subhadeep</h1>
```

### Internal StyleSheet :-
```
    <style>
        p{
            color: red;
        }
    </style>
```
### External Stylesheet :-
```
<link rel="stylesheet" href="style.css">
```
```
p{
    background-color: blue;
}
```

## Inline stylesheet Limitation

- Writing HTML & CSS code in same line.
- Because of Inline stylesheet code maintainance will be dificulty (Sudden changes takes time.)

## Internal Stylesheet Limitation
- Internal styles will be applicable for only one web page.

## Advantage of External Stylesheet
```
The Advantage of external stylesheet is one css file can be connected to multiple HTML files using link tag.
```
## CSS Selectors
```
A CSS Selector is a Pattern used to find the HTML elements
on a web page which you want to style.
```
# <b>Types of Selector</b>

- Bacis Selector
- Attribute Selector
- Pseudo class Selector
- Pseudo element selector
- Combinator Selector


##  Bacis selector are classified into 5 types
- Element Selector
- ID Selector
- Class Selector
- Universal Selector
- Group selector

## i. <b>Element Selector </b>
- Element Selector is also known as "Tag Selector".
- By Using Tag Name Selector , we can apply css style for selected html Element in webpage.

## Syntax
```
tagName
{
    propName : value ;
}
```
## ii.<b> ID Selector </b>:
- By Using ID  Selector , we can apply unique css style for same group of html Element in webpage.
- To use unique element we have to use id attribute.
- To represent ID names , we use '#'. 
- Id names must be unique.

## Syntax
```
#idName
{
    propName : value ;
}
```

## iii.<b> Class Selector </b>
- By using class selector we can apply same css styles for group of HTML element in webpage.
- To select multiple element , we have to use 'class' attribute.
- To represent class name we use '.'
- Class names can be duplicate.
## Syntax
```
.className
{
    propName : value ;
}
```

- For one HTML element we can use multiple className .
```
<h1 class="text-danger bg-yellow border-solid">Subhadeep</h1>
```
## iv.<b> Universal Selector  </b>

- Selects every single Every element on the page.
- It is represent by an '*'.

## Syntax
```
* {
    propName : Value ;
}
```
## Ex :-
```
<style>
 *  {
    color:blue
    }
</style>
```
## v. <b>Group selector</b>
- Group selector combines multiple selectors for applying same CSS tag.
- We combine selector by using ','
## Syntax
```
selector1 , selector2 ,....
    {
        propName : value ; 
    }
```
## Ex :-
```
 .text-danger , #header , h2  
    {
        color:red
    }
```

# <b> Attribute Selector </b>
- Selects element based on the presence or value of a specific attribute.
## syntax
```
selector[attName="value"]
    {
        propName : value ;
    }
```

## 
```
text-danger[align="left"]
    {
        color : orange ;
    }
```

# <b>  Pseudo Class Selector</b>
- Pseudo Class selector is a special selector which is used to apply CSS Style for Whole HTML element.
- Pseudo class selector is represent with single colon ':'.
## Syantax :- 
```
selector : PseudoClassName 
{
    propName : value ;
}
```

# <b> Pseudo Element Selector</b>
- Pseudo ELement is a special selector which is used to applying CSS style for Specific part of an HTML element.
- Pseudo element selector is represent with double colon '::'
## Syntax :-
```
selector :: PseudoElementName 
{
    propName : value ;
}
```
# Block Level Element : -
- The tag's which are occupied 100% width of web page is called block level element.
## Ex :-
- All Heading tag
- paragraph tag
- div tag
- nav tag

# Inline level Element
- The tag's which are occupied the width how much is required is known as inline level element.
## Ex :-
- Span tag
- Img tag
- Anchor tag
- Bold tag
- Strong tag
- Italic tag
- Underline tag 

# <b> CSS BOX MODEL </b>

- Box Model is used to create layout in the web pages.
- Every HTML tag is a box.
- Every box contain 4 points.
```
Content
Padding
Border
Margin
```


# <b>Combinator Selector</b>
- There are 4 combinator Selector : -
```
i.    Child Selector
ii.   Desecndant Selector
iii.  Adjacent Sibiling Selector
iv.   General Sibling Selector
```
### Note :-    
```
i. Combinator Selector must be used only when there is relation between HTML Element.

ii. We call Combinator Selector because we need to combine simple selectors to define the relation between HTML element.
```

## v. <b>Child selector</b>
- Child selector is represent with grater than'>'.
- By using child selector we can select HTML element which are only direct child of Specified Parent element.

## Syntax :-
```
selector1>selector2>.....>selectorn
{
    propName : value ;
}
```
## Ex :-
```
#section-one>h1>span
{
    color : blue  ;
}
```
### Note :- 
```
In all the combinator selectors style should be applied for nth Selector.
```
## Desencent Selector
- Descendent selector is represent by space 

## Adjacent Subling Selector 
- Adjucent  sibling selector is represent by '+'

## General sibling selector
- General sibling selector is represent by'`'.


