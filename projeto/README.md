# :building_construction: Projeto Grid :construction:

O projeto possui como intuito aplicar os conceitos abordados no curso de `Grid-CSS`

<p>Recuros CSS presentes no projeto:</p>

<p>
    :heavy_check_mark: Fundamentos do CSS <br>
    :heavy_check_mark: Grid Layout <br>
    :heavy_check_mark: Flexbox <br>
    :heavy_check_mark: Responsividade <br>
    :heavy_check_mark: Pseudo-elementos <br>
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




