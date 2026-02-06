# <b> Table </b> 
- table tage used to create table.
- Thead is used to define the column name.
- T Body is used to define body.
- tr stands for table row inside that.
- th is used to hold the data os table.

## <b> Span </b>


### <b>Colspan</b>
- colspan tag is used to merge the colum.

#### Syntax :
```
    <th colspan ="2"> Tabble-Header </th>
```

#### Ex:
```  
    <th colspan="2">Name </th>
```


### <b>Rowspan</b>
- rowspan is used to merge the rows.

#### Syantax :
```
    <td rowspan ="3"> ColumName </td>
```
#### Ex:
```  
    <th rowspan="2">Subhadeep </th>
```

## <b>FORM</b>
- Input tag use to take input from User.
- Take input from user on run time.



### Three Types of :
```
    Horizontal 
    Vertical 
    Inline
```

### Frorm has three Attribute

```
    Onsubmit()
    Method()
    Action()
```

### <b>Method : -</b>
- It is used to Specify the HTTPS method when we submitting the data to the server
- the default value of method attribute is "<b>GET</b>" , but the value should be "<b>POST</b>".
- <b>GET</b> Method is responsible to fetch the data from server.
- <b>POST</b> method is responsible to send the data to server.

#### Syntax :
```
<form method ="POST">
```

### <b> Action : -</b>
- It is specifies the <b>url</b> where the form data will be sent for processing when the form is submitted. 

#### Syntax :
```
<form Action ="URL">
```

### <b> OnSubmit : -</b>
- It is specifies a javascript function to be executed when the form is submitted.

- <b>onsubmit</b> attribute is primarily used to perform validation of the form data before it is actually sent to the server.
#### Syntax :
```
<form onsubmit="validate()">
```

