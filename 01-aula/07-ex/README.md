# :books: Exemplo 7

<p>Nesse exemplo foi usado as seguintes propriedades:</p>

## :package: Grid Container
<p>    
    :heavy_check_mark: Grid-template-columns;<br>
    :heavy_check_mark: Grid-template-rows;<br>                 
</p>

## :pencil: Grid Items

<p>     
    :heavy_check_mark: Grid-area;<br>                 
    :heavy_check_mark: Grid-column;<br>    
    :heavy_check_mark: Grid-row;<br>    
</p>

---

## :art: Imagem 

#### :package: Container ilustrativo

<img alt="container" src="../../img/01-AULA-ex-7-container-7.png">

#### :pencil: Propriedade Grid Item: Grid Area

<img alt="container" src="../../img/explicacao-ga.png">


---

## :keyboard: Código simplificado

```css
* {
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
    grid-template-columns:3fr 1fr;
    grid-template-rows:20vh 40vh 10vh 30vh;   
    color:#FFF;
    font-size: 2rem;
}
header {
    grid-area:1/1/3/2;
    background-color: rgb(255, 99, 71);          
}
main {
    height:15rem;    
    background-color:#ffff00;    
}
aside {
    height:15rem;
    background-color:black;    
}
footer {     
    height:15rem;
    background-color:#008000;
}
    
```