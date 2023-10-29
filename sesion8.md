<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->
# Actividad: Aplicando estilos con selectores CSS

**El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.**

# Solución:

    <html>
    <head>
    <style>
        
        h1 {
            color: red;
        }
        
        p {
            color: blue;
        }
        
        img {
            border: 2px solid black;
        }
        .destacado {
            color: green;
        }

        .grande {
            font-size: 24px;
        }

    
        #principal {
            color: yellow;
        }

        #sombras {
            text-shadow: 2px 2px 2px gray;
        }

        /* Selectores descendientes */
        div p {
            color: gray;
        }

        section {
            text-align: center;
        }
    </style>
    </head>
    <body>
    <header>
        <h1>Hola soy nicolas</h1>
    </header>

    <section>
        <p>De 19 años
            Vivo en bello
            Y estudio en el cesde
        </p>
        <div>
            <p>Y estoy en el 1 semestre</p>
        </div>
        <p>Cada dia me gusta mas este mundo de la programacion.</p>
        <img src="https://c.files.bbci.co.uk/48DD/production/_107435681_perro1.jpg" alt="Imagen">
    </section>

    <footer>
        <p>Nicolas.com</p>
    </footer>
    </body>
    </html>




