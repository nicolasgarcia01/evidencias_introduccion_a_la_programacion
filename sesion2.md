<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->

**Actividad: Creando mi primer sitio web**
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

° Index o página de inicio
° Acerca
° Contacto

**Solucion**

**indexx.hmtl**

     <!DOCTYPE html>
     <html>
    <head>
    <title>ACTIVIDAD 3</title>
    </head>
    <body>
    <header>
        <h1>MI ACTIVIDAD</h1>
    </header>
    <nav>
        <a href="about.html">Acerca</a>
        <a href="contact.html">Contacto</a>
    </nav>
    <main>
        <p>Bienvenidos a mi pagina de la 3 actividad</p>
        <p>Aqui encontraras el desarrollo de la actividad 3 </p>
    </main>
     <footer>
        <p>Copyright 2023 - Nicolas Garcia</p>
        <p>Garciaossanicolas@gmail.com</p>
     </footer>
     </body>
    </html>

**about.html**

     <!DOCTYPE html>
     <html>
     <head>
    <title>Encargados de ejecutar la actividad 3 </title>
     </head>
     <body>
     <header>
        <h1>Desarrollar las actividades encargadas</h1>
     </header>
     <nav>
        <a href="index.html">inicio</a>
        <a href="contact.html">contacto</a>
     </nav>
     <section>
      <h2>Nuestra historia empieza,cuando el profesor Jhon fredy nos da a realizar una actividad en la clase de introduccion a la programación. </h2>
      <p>Fundada en el 2023</p>
      <article>
         <h3>Misión: Desarrollar nuestras actividades de la mejor manera
            Visión: En 1ymedio tener la mejor capacidad para realizar cada actividad 
         </h3>

      </article>
     </section>
         <footer>
            <p>Copyright 2023 - Nicolas Garcia</p>
         </footer>
         </body>
        </html>

**contact.html**

       <!DOCTYPE html>
      <html>
     <head>
     <title>Nicolas Garcia</title>
     </head>
    <body>
    <header>
        <h1>Nicolas Garcia</h1>
    </header>
    <nav>
        <a href="index.html">inicio</a>
        <a href="about.html">acerca</a>
    </nav>
    <main>
        <form>
            <label for="nombre">Nombre</label>
            <input type="text" id="nombre"><br>

            <label for="email">email:</label>
            <input type="email" id="email"><br>

            <label for="mensaje">mensaje:</label><br>
            <textarea id="mensaje"></textarea><br>

            <input type="submit" value="enviar">
         </form>

         <aside>
            <h3>Medellin</h3>
            <p>Cra 57 #59-90</p>
       </aside>

    </main>
    <footer>
        <p>Copyright 2023 - Nicolas Garcia</p>
    </footer>  
      </body>
     </html>



