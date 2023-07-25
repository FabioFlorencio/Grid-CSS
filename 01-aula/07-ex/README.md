# :books: Exemplo 7

<p>Nesse exemplo foi usado as seguintes propriedades:</p>

## :package: Grid Container
<p> 
    :heavy_check_mark: Grid-template-areas;<br>    
    :heavy_check_mark: Grid-template-columns;<br>
    :heavy_check_mark: Grid-template-rows;<br>                              
</p>

## :pencil: Grid Item

<p>     
    :heavy_check_mark: Grid-area;<br>                 
    :heavy_check_mark: Grid-column;<br>    
    :heavy_check_mark: Grid-row;<br>    
</p>

---

## :art: Imagem 

#### :package: Container ilustrativo

<img alt="container" src="./../img/img-ex-7.png">

#### :package: Propriedade Grid Container / Grid Item :pencil:

<img alt="container" src="./../img/img-ex-7.1.png">


---

## :keyboard: Código simplificado

```css
* * {
    margin: 0;
    padding: 0;
    outline: 0;
    box-sizing: border-box;
    background:#0077FF;    
}
html {
    /* A cada 1rem será considerado 10px */
    font-size: 62.5%;
}
.container {
    display: grid;  
    grid-template-columns:1fr 1fr 1fr 1fr;
    grid-template-rows:20vh 40vh 10vh 20vh;   
    grid-template-areas: 
        "header header header header"
        "main main . aside"       
        "footer footer footer footer"
    ;                              
    color:#FFF;
    font-size: 2rem;
}
header {
    grid-area: header;
    background-color: rgb(255, 99, 71);          
}
main {        
    grid-area: main;
    background-color:#ffff00;    
}
aside {     
    grid-area: aside;     
    background-color:black;    
}
footer {    
    grid-area: footer; 
    background-color:#008000;
}

    
```