## Apuntes de M4

# Markdawn

este texto esta en *cursiva*
este texto esta en _cursiva_
este texto esta en **negrita**
este texto esta en __negrita__
este texto esta en _**negrita y cursiva**_

1. Primera opcion de menu
2. Segunda opcion de menu
3. Tercera opcion de menu

* Primera opcion de lista desordenada
* Segunda opcion de lista desordenada
- Tercera opcion de lista desordenada
    1. Primer submenu
    2. Segunda submenu
- Quarta opcion de lista desordenada
    * Tercer submenu
    * Quarto submenu
+ Quinta opcion de lista desordenada
+ Sexta opcion de lista desordenada

[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")


|Primera col.|Segunda col.|3 col.|
|---------------|:-------------:|---------:|
|COl 2 es|centrada|35€|
|COl 3 es|derecha|134€|
|Estilo cebra|Gris|Blanco|
|Clase|ASIX1|M4|

[x] Opcion A

[] Opcion B

[] Opcion C

# HTML

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>En el head se pone todo lo no visible para los visitantes</title>
    </head>
    <body>
        <h1>Apuntes</h1>
        <p class="">contenido</p>
        <img href="../imagen1.png">
        <br>
        <h4>Etiqueta de bloque</h4>
        <p>La P, cuando se dejan de utilizar hace un intro</p>
        <h4>Etiqueta de linea</h4>
        <p>La a, se pueden poner enlaces, tambien se pondria estilos, imagenes...</p>
    </body>
</html>
```

# HTML

**html**: Define el comienzo y el final de un documento HTML. Todo el contenido de la página web debe estar contenido dentro de esta etiqueta.

**head**; Contiene información sobre el documento, como el título de la página, metadatos, enlaces a hojas de estilo y otros elementos que no se muestran en la página.

**title**: Define el título de la página, que se muestra en la barra de título del navegador.

**meta**: Se utiliza para incluir metadatos en el documento, como el conjunto de caracteres utilizado y la descripción de la página.

**link**: Permite vincular a hojas de estilo externas, iconos y otros recursos relacionados con la página.

**style**: Se utiliza para incluir hojas de estilo CSS directamente en el documento HTML.

**script**: Se utiliza para incluir scripts JavaScript en la página web. Puede estar ubicado en la sección **head** o al final del cuerpo (**body**) para mejorar el rendimiento de carga.

**body**: Contiene el contenido visible de la página, como texto, imágenes, enlaces y otros elementos.

**h1, h2, h3, h4, h5, h6**: Definen encabezados de diferentes niveles, siendo **h1** el más alto y **h6** el más bajo. Estos se utilizan para estructurar el contenido y mejorar la accesibilidad.

**p**: Define un párrafo de texto.

**a**: Crea enlaces a otras páginas web o recursos. El atributo href especifica la URL de destino.

**img**: Inserta imágenes en la página web. El atributo src define la ubicación de la imagen.

**ul y ol**: Se utilizan para crear listas no ordenadas (viñetas) y listas ordenadas (números o letras), respectivamente. Los elementos de lista se definen con li.

**div**: Se utiliza para crear contenedores o divisiones en la página. Es comúnmente usado para aplicar estilos o estructurar el contenido.

**table**: Crea tablas en la página web. Se utiliza junto con etiquetas como **tr** (fila), **th** (encabezado de columna) y **td**(celda de datos) para definir la estructura de la tabla.

**form**: Define un formulario que permite a los usuarios enviar datos al servidor.

**input**: Se utiliza para crear campos de entrada de texto, casillas de verificación, botones de radio y otros elementos de formulario.

**select**: Crea listas desplegables de selección en formularios.

Estos son unos de los atributos mas utilizados en html.

```
witdh=""
class=""
type=""
id=""
alt=""
href=""
```

# Tabla HTML

```html
    <table border="1">
        <thead>
            <tr>
                <th>Puesto</th>
                <th>Atleta</th>
                <th>Tiempo</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1r</td>
                <td>Alejandro Pérez</td>
                <td>2:01:15</td>
            </tr>
            <tr>
                <td>2n</td>
                <td>Torcuato García</td>
                <td>2:12:10</td>
            </tr>
            <tr>
                <td>3r</td>
                <td>Wenceslao Durán</td>
                <td>2:13:59</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <th>Puesto</th>
                <th>Atleta</th>
                <th>Tiempo</th>
            </tr>
        </tfoot>
    </table>
```

**Ejemplo de la tabla**

![Ejemplo tabla](https://github.com/XaviMorenoTorres/ASIX_M4_UF1_M4_APUNTES/blob/main/tabla.png)


# GIT

**git init:** Inicializa un repositorio.

**git add**: Añade cambios al área de preparación.

**git commit**: Guarda los cambios en el repositorio.

**git push**: Sube cambios a un repositorio remoto.

**git pull**: Descarga cambios de un repositorio remoto.

**git branch**: Muestra y crea ramas.

# CSS

## Que es? ##

CSS, que significa "Cascading Style Sheets" (Hojas de Estilo en Cascada), es un lenguaje de programación utilizado para controlar la presentación y el diseño de documentos web, como páginas HTML.

![Ejemplo Css](https://github.com/XaviMorenoTorres/ASIX_M4_UF1_M4_APUNTES/blob/main/ejemploCSS.png)

## Estilo en línea:

Puedes agregar estilos CSS directamente en la etiqueta HTML utilizando el atributo style. Por ejemplo:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>En el head se pone todo lo no visible para los visitantes</title>
    </head>
    <body>
        <p style="color: blue; font-size: 16px;">Este es un párrafo azul.</p>
    </body>
</html>
```

## Bloque de estilo interno: ##

Puedes incluir un bloque de estilo CSS en la sección head de tu documento HTML utilizando la etiqueta style

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <style>
            p {
                color: red;
                font-size: 18px;
                }
        </style>
    </head>
    <body>
    <p>Este es un párrafo rojo.</p>
    </body>
</html>
```
## Archivo externo de CSS: ##

Puedes crear un archivo CSS por separado con extensión .css y luego enlazarlo con tu página HTML utilizando la etiqueta link en la sección head.

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="stylesheet" type="text/css" href="estilos.css">
    </head>
    <body>
        <p>Este es un párrafo con estilos desde un archivo externo.</p>
    </body>
</html>
```

**Unidades relativas**

Al definir dimensiones y márgenes, es preferible utilizar unidades relativas en lugar de unidades absolutas. Las unidades relativas se ajustan automáticamente al tamaño del dispositivo.

```
div {
  width: 50%;
  height: 60vh;
}
```
El **%** es una unidad relativa que se adapta al tamaño del contenedor padre, por lo que si el contenedor padre es más ancho, el elemento también lo será.

El **vh** es útil cuando se desea que un elemento ocupe una parte específica de la altura de la pantalla.

**Media Queries**


```
column-50 {
    width: 50%;
  }
```

```
@media only screen and (max-width: 700px) {
  column-50 {
    width: 100%;
  }
}
```
Esto lo que hara es que una columna que ocupa el 50% de la pantalla acabe ocupando el 100% cuando pase por el punto de corte que en este caso es 700px.

**Unidades EM y REM**

Otra práctica común es el uso de unidades em y rem para tamaños de fuente y márgenes. Estas unidades son relativas al tamaño del texto base, facilitando la adaptación a diferentes tamaños de pantalla.

```
body {
  font-size: 16px; /* Tamaño base del texto */
}

h1 {
  font-size: 2em; /* Tamaño del texto es el doble del tamaño base (32px) */
  margin-bottom: 1rem; /* Margen inferior es igual a 1 vez el tamaño base (16px) */
}
```

## Selectores

* **Selector de elementos:**

```
p {
   color: blue;
}
```

Afectara a todos los elementos ```<p>``` del documento ```HTML```.

* **Selecctor de clase:**

```
.example {
   propiedad1: value1;
   propiedad2: value2;
}
```

```
<a class="example">
<div class="example">
```

* **Selector de descendientes:**

```
div strong{
    color: black;
}
```

Un ejemplo para ver las diferencias entre un selector de hijos y de descendientes:

* **Selector de hijos:**

```
h3>strong {
    color: blue;
}
```

![Selector hijo y descendiente](https://github.com/XaviMorenoTorres/ASIX_M4_UF1_M4_APUNTES/blob/main/selectores.png)

* **Selector universal:**

```
* {
    background-color: red;
}
```

Todo el documento estara de fondo de color rojo

* **Selector de id:** 

```
#example {
   property: value;
   property2: value2;
}
```

```
<p id="ejemplo1">
```

Afecta a todos los elementos ```HTML``` que tienen un atributo ```id=""``` con el valor especificado.