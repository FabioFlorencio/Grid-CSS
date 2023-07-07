# :books: Estudos da linguagem batch :gear:

<p>O intuito desse estudo foi aprofundar o conhecimento da linguagem de lote e ter um domínio de usar o prompt que se faz necessário ainda nos tempos de hoje. Foi utilizado como base o canal <a href="https://www.youtube.com/playlist?list=PLO_mlVzHgDw02tItMApdR4MOpZB37162D">Instituto scripts</a> e outras fontes no youtube.</p>

<img alt="container" src="./../img/container.png">

## :unlock: Quer destravar os comandos básicos:question::old_key:
<br>

![ezgif com-gif-maker (5)](https://user-images.githubusercontent.com/78650091/220229632-d7f811a0-0762-4f6d-a3ea-81bdb561f1d3.gif)


* PDF :file_folder: https://bityli.com/7coed
* PDF :file_folder: [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:6976248550846283776/)

<br>

## :mag_right:  Pré-requisitos

<p>Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas: :octocat: <a href="https://git-scm.com/downloads">Git</a> e um editor de código <a href="https://code.visualstudio.com/download">VS Code.</a></p>

```html
    # Clone este repositório
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="container">
            <header>Header</header>
            <main>Main</main>
            <aside>aside</aside>
            <footer>Footer</footer>
        </div>
    </body>
    </html>
	
    #Acesse a pasta do projeto no terminal/cmd    
	
```

```css
    # Clone este repositório
    * {
        margin: 0;
        padding: 0;
        outline: 0;
        box-sizing: border-box;
        background:#0077FF;    
        }
    html {
        font-size: 62.5%;
    }
    .container{
        display: grid;    
        grid-template-columns:3fr 1fr;
        grid-template-rows:20vh 40vh 30vh 10vh;          
        color:#FFF;    
        font-size: 2rem;
    }
    header{
        grid-column-start:1;
        grid-column-end:4;
        background-color: #ff6347;
        height:auto;   
        
    }
    main{
        grid-column-start:1;
        grid-column-end:2;
        grid-row-start:2;
        grid-row-end:4;
        height:auto;    
        background-color:#ffff00;
        
    }
    aside{
        height:auto;
        background-color:black;    
        grid-row-start:2;
        grid-row-end:4;

    }
    footer{
        grid-column-start:1;
        grid-column-end:4;
        height:auto;
        background-color:#008000;
    }	
    #Acesse a pasta do projeto no terminal/cmd    	
```