# :building_construction: Projeto Grid :construction:

<p>Nesse projeto foi usado as seguintes propriedades:</p>

## :package: Grid Container

<p> 
    :heavy_check_mark: Display: grid;<br>      
    :heavy_check_mark: Grid-template-columns;<br>
    :heavy_check_mark: Grid-template-rows;<br>           
    :heavy_check_mark: Grid-template-areas;<br>    
</p>

## :pencil:  Grid Item
<p>                
    :heavy_check_mark: Grid-column-start;<br>
    :heavy_check_mark: Grid-column-end;<br>
    :heavy_check_mark: Grid-row-start;<br>
    :heavy_check_mark: Grid-row-end;<br>
    :heavy_check_mark: Grid-column;<br>
    :heavy_check_mark: Grid-row;<br>
    :heavy_check_mark: Grid-area;<br>
</p>

---

## :iphone: Media Queries :desktop_computer: 

![ezgif com-video-to-gif](https://github.com/FabioFlorencio/Grid-CSS/assets/78650091/2c8001fb-6611-4629-a62e-8c5fa6b16e92)

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
.container{
    width: 100vw;
    height: 100vh;
    display: grid;
    grid-template-areas: 
        "left right"
        "footer footer"
    ;
    grid-template-columns:1fr 1fr;
    grid-template-rows:4fr 1fr;
    color:#FFF;
    font-size: 4rem;    
}

/*========= Media queries ============*/

@media screen and (max-width: 820px){
    .container {
        grid-template-areas: 
        "left"    /* Linha-1 */
        "right"   /* Linha-2 */
        "footer"; /* Linha-3 */
        grid-template-columns: 1fr;
    }    
}

@media screen and (max-width: 480px) {
    .nav-left {
        display: none;
    }
    .container {
        grid-template-areas: 
            "right"   /* Linha-1 */
            "footer"  /* Linha-2 */
        ;
    }
}

```




