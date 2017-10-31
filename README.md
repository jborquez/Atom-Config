##  PARA USAR COMPLEMENTO EMMET EN ATOM:
  1.- Para generar una estructura para pagina html --> Ingresamos '!' y luego presionamos 'CTRL +e'
      <!DOCTYPE html>
      <html lang="es">
      <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>MI PRIMERA PAGINA CON EMMET</title>
      </head>
      <body>
      </body>
      </html>

  2.- Para estructura de un DIV que incluye un id --> Ingresamos #contenedor CTRL + e
      <div id="contenedor"></div> --> <div id="contenedor">ID</div>

  3.- Para estructura de un DIV que incluye una clase --> Ingresamos un '.' CTRL + e
      <div class=""></div> --> <div class="mi-clase">CLASE</div>

  3.- Para estructura de un DIV que incluye un id con 2 clases --> Ingresamos #contenedor1>.clase1+.clase2 CTRL + e
      <div id="contenedor1">
        <div class="clase1"></div>
        <div class="clase2"></div>
      </div>>

  4.- Para una lista --> ul> CTRL +e --> <ul></ul>
      Para una lista de 8 elementos --> ul>li*8 CTRL + e
      <ul>
        <li>Escribo Ctrl + d 1, 2, 3, n veces hasta seleccionar lugares donde va el mismo texto</li>
        <li>Escribo Ctrl + d 1, 2, 3, n veces hasta seleccionar lugares donde va el mismo texto</li>
        <li>Escribo Ctrl + d 1, 2, 3, n veces hasta seleccionar lugares donde va el mismo texto</li>
        <li>Escribo Ctrl + d 1, 2, 3, n veces hasta seleccionar lugares donde va el mismo texto</li>
        <li>Escribo Ctrl + d 1, 2, 3, n veces hasta seleccionar lugares donde va el mismo texto</li>
        <li>Escribo Ctrl + d 1, 2, 3, n veces hasta seleccionar lugares donde va el mismo texto</li>
        <li>Escribo Ctrl + d 1, 2, 3, n veces hasta seleccionar lugares donde va el mismo texto</li>
        <li>Escribo Ctrl + d 1, 2, 3, n veces hasta seleccionar lugares donde va el mismo texto</li>
      </ul>

  5.- Cursores múltiples --> 'Ctrl + d' Ver ejemplo en 4.-

  6.- Repetir línea (Copiar lineas)--> 'Ctrl + Shift + d'

  7.- Generar código para HREF --> a> + 'Ctrl e'


  ## Sincronizar paquetes de ATOM

  Un paquete que me llamó la atención es sync-settings. Este paquete permite a través de GitHub y Gist sincronizar la configuración y paquetes en diferentes instancias de Atom (en mi caso, Atom en Linux y Atom en Windows). Es muy fácil de configurar y me ha funcionado perfectamente

    Lo pueden encontrar dentro de Atom: Settings -> Install -> En el search poner sync-settings
    Luego sólo se ocupa configurarlo dentro de Atom:
    Settings -> Packages-> Seleccionar Settings de sync-settings

    Es necesario tener una cuenta de GitHub.
    En GitHub se debe crear un Personal Access Token y copiar ese token en la configuración anterior.
    Además se ocupar crear un Gist y copiar su ID (es el GUID en la dirección de URL) también en la configuracion anterior. ¡Y listo!

    Para utilizarlo en Atom: Packages-> Synchronize Settings -> Se puede seleccionar Backup o Restore
