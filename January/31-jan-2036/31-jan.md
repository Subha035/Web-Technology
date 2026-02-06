# <b> CSS  Position Property </b>
- By using CSS position property We can control the placement of HTML elemnt within The web page.

- There are 5 values of position properties
- HTML elements are positioned to their final location with the top, buttom , left and right properties.

```
1 . Static
2. Relative
3. Absolute
4. Sticky
5. Fixed
```

## <b>Position :</b> Static

- By default all the HTML element position is static.
- Static positioned elements are not affected by Top, Buttom , Left and Right Properties.

## Ex :-
    selector
    {
        position : static;
    }

## <b>Position :</b> Relative
- By using relative position we can change the place of an HTML element from it's normal flow.
- Relative position element are effected by Top , Left , Righ  t and Buttom Properties.

## Ex :-

    selector
    {
     position : relative;
        top : 10px;
        left : 100px
    }




## <b>Position :</b> absolute 
- Absolute position element will be placed to the nearest relative parent element.
- If there is no relative parent element than absolute element will be positioned from the body tag.

## Ex :-

    selector
        {
            position : absolute;
            top : 10px;
            left : 100px
        }