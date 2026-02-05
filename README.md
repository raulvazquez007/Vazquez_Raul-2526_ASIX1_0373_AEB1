# AE1b Mi documentación (apuntes) [REVISIÓN 1] Raul Vazquez

## Etiquetas basica MarkDown
### **Encabezados:** 
Los encabezados vienen con un formato propio y sirven para dividir y organizar secciones dentro de un documento.
Cuantas más almohadillas uses (#), más pequeño será el título.
Por ejemplo, una sola # genera el título principal (H1), dos ## el siguiente nivel (H2), y así hasta seis.

Ej: 

# Hola
## hola
### hola
#### hola

### **Estilos de letra**

· **Negritas:** 
Para poner texto en negrita, se pueden usar dos guiones bajos(__) o dos asteriscos(**) antes y después del texto, sin espacios.

Ej:
Esto esta en __negrita__ 
Esto esta en **negrita** tambien

· _Cursiva_: Se puede poner el tenxto en cursiva utilizando 1 barra baja delante y 1 detras de la palabra o poniedo 1 asteriscos delante y 1 detras "_ algo _ o * algo *" sin seperacion!!

Ej:
Esto esta en _cursiva_
Esto esta en *cursiva*

### Enlaces

Para poner un enlace tenemos que utilizar esta estructura [] (), Dentro de los corchetes escribiremos el nombre del sitio y dentro de los parentesis pondremos el enlace y si quermeos escribir un texto adicional pondremos entre comillas el texto "Aqui dentro el texto".

Ej: 
[Periodico oficial del Pais](https://elpais.com/ "Texto adicional")

### Imagenes

Para poner una imagen usaremos la estructura ! []   (). Primero escribiremos ! junto a los corchetes es decir asi ! [] dentro del corchete escribirmeos alt tex, despues dentro de los parentesis pondremos la ruta donde esta la imagen  y si quermeos escribir un texto adicional pondremos entre comillas el texto "Aqui dentro el texto".

Ej:![alt tex](./Imagenn1.jpg "Imagen bandera")

### Tablas

Las tablas se crean usando la barra vertical | para separar columnas.
Se deben incluir tres guiones --- debajo de los encabezados para definirlos, y los dos puntos (:) se usan para alinear el texto (izquierda, centro o derecha).

| *Jugador* | Equipo | Nombre |
|:---------|:-------------:|:--------------|
| 32 | Lakers | Magic Johnson |
| 33 | Celtics| Boston Celtics |
| 23 | Bulls | Michael Jordan |

### Notas al pie de pagina:

Para poner un texto con pie de pagina utilizaremos los corchetes [] y dentro de los corchetes ^1.

Ej: Texto con enlace a nota de pie de pagina [^1]

## HTML

### Introduccion a HTML

· **HTML** (HyperText Markup Language)es el lenguaje estándar que sirve para crear páginas web. Lenguaje más importante de Internet dado que sin HTML no se vería nada en el navegador.

· **HTML** define la estructura y el contenido (es decir, si hay una imagen, una lista de elementos, un enlace, un párrafo, un titular, etc...) de las páginas web mediante etiquetas, es muy adaptable, tiene una estructura lógica y es muy fácil de entender e interpretar. DESCRIBE EL CONTENIDO.

· No se dedica a ver cómo se interactúa con el contenido (Javascript, PHP, etc...), ni se preocupa por la presentación o estilizado del contenido, es decir, de cómo se ve el contenido (para eso tenemos CSS).

· Los elementos HTML son los bloques de construcción de las páginas HTML.

· Cada elemento HTML está delimitado por etiquetas, como &lt;body&gt;, &lt;head&gt;, &lt;p&gt;, &lt;h1&gt;, etc.

Las siglas de HTML corresponden con **“HyperText Markup Language”**, que tiene el siguiente significado:

· **HyperText**, su significado es hipertexto, que no es más que un texto que enlaza con otros contenidos, que pueden ser otro texto u otro archivo. Esto es la base del funcionamiento de la web tal y como la conocemos, que no es más que páginas y recursos interconectados.

· **Markup**, que significa marca o etiqueta, ya que todas las páginas web están construidas en base a etiquetas, desde las primeras versiones hasta las últimas etiquetas de HTML5. Un ejemplo de una etiqueta HTML es la que identifica un párrafo, que se compone de la etiqueta, el contenido de la etiqueta y el cierre del párrafo: &lt;p&gt;HOLA&lt;/p&gt;. 

· **Language**, cuyo significado es lenguaje, porque HTML es un lenguaje, es decir, tiene sus normas, tiene su estructura y una serie de convenciones que nos sirven para definir tanto la estructura como el contenido de una web. Algo importante a tener en cuenta y con lo que no hay que confundirse, es que porque HTML sea un lenguaje no quiere decir que sea un lenguaje de programación.

#### Introduccion a HTML (elementos)

Es decir, que HTML no es un lenguaje de programación; es un lenguaje que define la estructura de su contenido. HTML consiste en una serie de elementos que usarás para encerrar diferentes partes del contenido para que se vean o comporten de una determinada manera.

Esto implica que la información a mostrar ha de ir “etiquetada” para formar elementos que el navegador web sepa interpretar de qué tipo de información se trata y cómo tal sepa cómo representarlos.

##### Las partes principales del elemento son:
· **La etiqueta de apertura:** consiste en el nombre del elemento (en este caso, p), encerrado por(< >) de apertura y cierre. Establece dónde comienza o empieza a tener efecto el elemento —en este caso, dónde es el comienzo del párrafo—.

· **La etiqueta de cierre:** es igual que la etiqueta de apertura, excepto que incluye una barra de cierre (/) antes del nombre de la etiqueta. Establece dónde termina el elemento —en este caso dónde termina el párrafo—.

· **El contenido:** este es el contenido del elemento, que en este caso es sólo texto.

· **El elemento:** la etiqueta de apertura, más la etiqueta de cierre, más el contenido equivale al elemento.

#### Introduccion a HTML (atributos)

Los elementos pueden también tener atributos.

Los atributos contienen información adicional acerca del elemento, la cual no quieres que aparezca en el contenido real del elemento.
En el siguiente ejemplo:

&lt;p class="gato">Mi gato es muy gruñón&lt;/p&gt;

· class es el **nombre del atributo**

· gato es el **valor del atributo**

*Los atributos siempre se incluyen en la etiqueta de apertura de un elemento y deben tener:*

· Un espacio entre el nombre del elemento y el atributo (o entre atributos, si hay varios).

· El **nombre del atributo**, seguido de un signo igual (=).

· Comillas de apertura y cierre que encierran el **valor del atributo**.

Puedes también colocar elementos dentro de otros elementos. Esto se llama **anidamiento**.

Algunos elementos no poseen contenido y son llamados **elementos vacíos**.
Por ejemplo:

&lt;img src="images/firefox-icon.png" alt="Mi imagen de prueba"&gt;
Este elemento posee atributos, pero no tiene etiqueta de cierre (&lt;/img&gt;) ni contenido encerrado.

### Estructura básica de un fichero HTML

· Una página **HTML** básica incluye una declaración **DOCTYPE**, un elemento html, y dentro de este, un head y un body.

· El **head** contiene metadatos y enlaces a hojas de estilo y scripts, mientras que el **body** contiene el contenido principal de la página web.

&lt;!DOCTYPE html&gt;

&lt;html&gt;

&lt;head&gt;

&lt;meta charset="utf-8"&gt;

&lt;title&gt;Mi página de prueba&lt;/title&gt;

&lt;link rel="icon" href="favicon.png"&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;img src="images/firefox-icon.png" alt="Mi imagen de prueba"&gt;

&lt;/body&gt;

&lt;/html&gt;


· **&lt;!DOCTYPE html&gt;** indica el tipo de documento.

· **&lt;html&gt;&lt;/html&gt;** el elemento &lt;html&gt;. Este elemento encierra todo el contenido de la página entera y, a veces, se le conoce como el elemento raíz (root element).

· **&lt;head&gt; &lt;/head&gt;** el elemento &lt;head&gt;. Este elemento actúa como un contenedor de todo aquello que quieres incluir en la página HTML que no es contenido visible por los visitantes de la página.

### Estructura básica de un fichero HTML (2)

&lt;!DOCTYPE html&gt;

&lt;html&gt;

 &lt;head&gt;

  &lt;meta charset="utf-8"&gt;

  &lt;meta name="description" content="Esta es una página web de ejemplo que demuestra el uso de metadatos, estilos CSS y otras características básicas de HTML."&gt;

  &lt;meta name="keywords" content="HTML, CSS, ejemplo, metadatos, favicon"&gt;

 &lt;title&gt;Mi página de prueba&lt;/title&gt;

  &lt;link rel="icon" href="favicon.png"&gt;

  &lt;link rel="stylesheet" href="styles.css"&gt;

  &lt;script src="script.js"&gt;&lt;/script&gt;

  &lt;style&gt;

   body {

    font-family: Arial, sans-serif;

    background-color: #f4f4f9;

   }

  &lt;/style&gt;

 &lt;/head&gt;

 &lt;body&gt;

  &lt;img src="images/firefox-icon.png" alt="Mi imagen de prueba"&gt;

 &lt;/body&gt;

&lt;/html&gt;

1. ### ESTRUCTURA BÁSICA DE UN FICHERO HTML

Un documento HTML define la estructura básica de una página web. Contiene dos secciones principales:

   - &lt;head&gt;: incluye metadatos, información adicional y enlaces a archivos externos 
      (como CSS o scripts).

   - &lt;body&gt;: contiene todo el contenido visible de la página (texto, imágenes, enlaces, etc.).

## Ejemplo básico:

&lt;!DOCTYPE html&gt;

&lt;html&gt;

 &lt;head&gt;

  &lt;meta charset="utf-8"&gt;

  &lt;title&gt;Mi página web&gt;/title&gt;

 &lt;/head&gt;

 &lt;body&gt;

  &lt;h1&gt;Título principal&lt;/h1&gt;

  &lt;p&gt;Este es un párrafo.&lt;/p&gt;

 &lt;/body&gt;

&lt;/html&gt;

**Dentro del** &lt;head&gt; **pueden incluirse etiquetas importantes como:**

&lt;meta name="viewport" content="width=device-width"&gt; 

**-Permite que el sitio sea adaptable a diferentes dispositivos.**
    
&lt;meta name="description" content="Descripción del sitio"&gt; 

**-Utilizada por los motores de búsqueda.**
    
&lt;meta name="robots" content="index, follow"&gt; 

**-Indica a los buscadores si deben indexar la página.**


2. **ELEMENTOS DE BLOQUE Y DE LÍNEA**

    Los elementos HTML dentro del &lt;body&gt; se dividen en dos tipos:

    · Elementos de bloque:

    - _Ocupan todo el ancho que pueda utilizar y comienzan en una nueva línea._

    - Ejemplos:

    &lt;h1&gt; a &lt;h6&gt;, &lt;p&gt;, &lt;div&gt;, &lt;blockquote&gt;, &lt;pre&gt;, &lt;ul&gt;, &lt;table&gt;.

    - _Se usan para estructurar secciones grandes del contenido._

    · _Elementos de línea:_

    - _Solo ocupan el espacio necesario y no crean una nueva línea._

    - **Ejemplos:**

    &lt;em&gt;, &lt;strong&gt;, &lt;span&gt;, &lt;a&gt;, &lt;img&gt;, &lt;code&gt;, &lt;q&gt;.

    - _Se usan para resaltar o enlazar partes del texto._


3. **NORMAS BÁSICAS DE LAS ETIQUETAS HTML**

    · _Las etiquetas vienen en pares:_

    &lt;p&gt;Texto&lt;/p&gt;

    · _Algunas etiquetas son vacías (no tienen cierre):_

    &lt;img&gt;, &lt;br&gt;, &lt;input&gt;

    · _Deben anidarse correctamente:_

    &lt;b&gt;&lt;i&gt;Texto&lt;/i&gt;&lt;/b&gt; es correcto.

    &lt;b&gt;&lt;i&gt;Texto&lt;/b&gt;&lt;/i&gt; es incorrecto.

    · _Los atributos se colocan en la etiqueta de apertura:_

    &lt;img src="imagen.jpg" alt="Descripción"&gt;


4. **COMENTARIOS**

    Los comentarios permiten añadir anotaciones que no se muestran en el navegador.

    _Sintaxis:_

    &lt;!-- comentario --&gt;

    Ejemplo de uso:

    &lt;!DOCTYPE html&gt;

    &lt;html&gt;

     &lt;head&gt;

      &lt;title&gt;Título&lt;/title&gt;

      &lt;/head&gt;

      &lt;body&gt;

       <!-- Cabecera -->

       <!-- Menú de navegación -->

       <!-- Contenido principal -->

       <!-- Pie de página -->

    &lt;/body&gt;

     &lt;/html&gt;


5. **LEGIBILIDAD Y ORGANIZACIÓN DEL CÓDIGO**

    Es fundamental que el código sea claro y legible para otros desarrolladores.

    · _Recomendaciones:_

    - Usar comentarios claros.

        - Mantener sangrías correctas.

        - Organizar los archivos por carpetas (css, images, js).

        - Evitar líneas demasiado largas.

    · _Motivo:_

    Facilita la colaboración y el mantenimiento del proyecto.


6. **ETIQUETAS BÁSICAS DE HTML**

    · _Encabezados:_

    &lt;h1&gt; a &lt;h6&gt; - Títulos y subtítulos (bloque).

    · _Párrafos:_

    &lt;p&gt; - Agrupa frases relacionadas (bloque).

    · _Saltos de línea:_

    &lt;br&gt; - Inserta un salto de línea.

    · _Separadores:_

    &lt;hr&gt; - Crea una línea horizontal divisoria.

    · _Énfasis:_

    &lt;em&gt; - Texto en cursiva.

    &lt;strong&gt; - Texto en negrita.

    · _Span:_

    &lt;span&gt; - Contenedor en línea para aplicar estilos dentro de un texto.


7. **RUTAS EN HTML**

    · **Ruta absoluta:**

    Especifica la dirección completa del archivo en la web.

     _Ejemplo:_

    &lt;img src="https://www.example.com/imagen.jpg" alt="Ejemplo"&gt;

    · **Ruta relativa:**

    Especifica la ubicación del archivo respecto al documento actual.

    _Ejemplo:_

    &lt;img src="images/logo.png" alt="Logo del sitio"&gt;


8. **ENLACES (&lt;a&gt;)**

    · _Permiten navegar entre documentos mediante el atributo href._

    _Ejemplo:_

    &lt;a href="https://www.ejemplo.com"&gt;Ir al sitio&lt;/a&gt;

    · _Enlaces externos:_

    Conectan con páginas fuera del sitio.

    · _Enlaces locales:_

    Conectan con documentos del mismo sitio (usando rutas relativas).

    · _Atributos comunes:_

    - href: destino del enlace.

    - title: texto informativo al pasar el cursor.


9. **FORMULARIOS**

    · Sirven para interactuar con el usuario y enviar información al servidor.

    · _Tipos de controles:_

    - &lt;input type="text"&gt; - campo de texto.

    - &lt;input type="password"&gt; - contraseña.

    - &lt;input type="radio"&gt; - botón de opción.

    - &lt;input type="checkbox"&gt; - casilla de verificación.

    - &lt;button&gt; - botón de envío.

    - &lt;select&gt; - lista desplegable.

    - &lt;textarea&gt; - área de texto.

    - &lt;input type="file"&gt; - subida de archivos.

    · Cada control debe tener un atributo name para identificar el dato enviado.


10. **ETIQUETA &lt;form&gt;**

    · Se utiliza para crear formularios.

    · _Atributos principales:_

    - action: URL a la que se enviarán los datos.

    - method: método de envío (GET o POST).

    - enctype: cómo se codifican los datos.

    - target: dónde se mostrará la respuesta (_self o _blank).

    · _Ejemplo completo:_

    &lt;form action="process.php" method="post" enctype="multipart/form-data"&gt;

     &lt;label for="name"&gt;Nombre:&lt;/label&gt;

     &lt;input type="text" id="name" name="name"&gt;

     &lt;label for="email"&gt;Correo electrónico:&lt;/label&gt;

     &lt;input type="email" id="email" name="email"&gt;

     &lt;label for="file"&gt;Subir archivo:&lt;/label&gt;

     &lt;input type="file" id="file" name="file"&gt;

     &lt;button type="submit"&gt;Enviar&lt;/button&gt;

    &lt;/form&gt;

### GitHub

1. Primero en el buscador de nuestro navegador escribiremos GitHub
2. Una vez dentro iniciamos sesion con nuestra cuenta y si no tenemos nos registramos.
3. Despues clicams en el boton New que sale de color verde.
4. Ahi dentro escribirmeos el nombre del repositiorio y eligiremos si queremos que sea visible o privado.
5. No es necesario pero yo siempre activo la opcion del README.md
6. Una vez tengamos el repositorio hecho si queremos hacer el pages iremos a ajustes y luego a pages.
7. Una vez dentro nos aparece una seccion que dice Branch, donde dice None clicamos y cambiamos a main, clicamos en save y esperamos a que se genere el pages de nuestro repositorio.

### Git 

1. Para clonar un repositorio del GitHub con el git deberemos copiar el code que nos sale en la pantalla principal del repositorio dentro del GitHUb.
2. Una vez el codigo este copiado abriremos la carpeta donde tengamos todos los repositorios creados.
3. Una vez dentro arriba donde sale la ruta la eliminaremos y escribiremos cmd y clicaremos enter.
4. Despues en el cmd escribiremos git init y el codigo del Repositorio.
5. Luego cerraremos ese cmd y entraremos en la carpeta del repositorio que se ha clonado con el comando anterior. En la ruta de arriba escribiremos cmd y enter.
5. Dentro del cmd escribiremos git init, despues git add .
6. Una vez hecho eso cuando queramos subir cambios que hemos realizado en el visual escribiremos git commit -m "texto informativo"
7. Y por ultimo escribiremos git push origin main y ya estaran subidos los cambios.



# Apuntes de HTML 

---

## 1. ¿Qué es HTML?
**HTML (HyperText Markup Language)** es el lenguaje estándar para crear páginas web.  
Se encarga de **definir la estructura y el contenido** que se muestra en el navegador.

HTML **no es un lenguaje de programación**, ya que no tiene bucles, condiciones ni funciones.
- El **estilo** se aplica con **CSS**
- El **comportamiento** se controla con **JavaScript**

---

## 2. Significado de las siglas HTML
- **HyperText**: texto que permite enlazar con otros documentos o recursos.
- **Markup**: el contenido se organiza mediante etiquetas.
- **Language**: tiene reglas y estructura propias.

---

## 3. Elementos HTML
Un elemento HTML está compuesto por:
1. **Etiqueta de apertura**
2. **Contenido**
3. **Etiqueta de cierre**

Ejemplo:
```html
<p>Hola</p>
4. Etiquetas HTML
Las etiquetas indican al navegador qué tipo de contenido se está mostrando.

Etiquetas básicas de estructura
<html>: contiene todo el documento HTML.

<head>: contiene información no visible de la página.

<body>: contiene el contenido visible.

5. Atributos HTML
Los atributos añaden información adicional a las etiquetas.

Características:

Van en la etiqueta de apertura

Formato: nombre="valor"

Ejemplo:

<img src="imagen.jpg" alt="Descripción de la imagen">
6. Atributos más comunes 
id: identificador único de un elemento.

class: permite agrupar elementos para aplicar estilos o scripts.

src: indica la ruta de un recurso (imagen, vídeo, etc.).

alt: texto alternativo para imágenes.

href: destino de un enlace.

title: información adicional que aparece al pasar el ratón.

name: nombre del dato enviado en formularios.

value: valor de un campo de formulario.

placeholder: texto de ayuda dentro de un campo.

required: obliga a rellenar un campo.

disabled: desactiva un elemento.

readonly: campo solo lectura.

7. Anidamiento de elementos
HTML permite colocar etiquetas dentro de otras.

Ejemplo correcto:

<p><strong>Texto importante</strong></p>
8. Elementos vacíos
Son etiquetas que no tienen contenido ni cierre.

Ejemplos:

<img>: imagen

<br>: salto de línea

<hr>: línea divisoria

<input>: campo de formulario

9. Estructura básica de un documento HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Mi página web</title>
  </head>
  <body>
    <h1>Hola mundo</h1>
    <p>Mi primera página web</p>
  </body>
</html>
10. Etiquetas de la estructura 
<!DOCTYPE html>
Indica el tipo de documento. Es obligatorio y va al inicio.

<html>
Elemento raíz que contiene todo el contenido HTML.

<head>
Contiene información no visible:

<meta>: define metadatos (charset, descripción, autor).

<title>: título de la pestaña del navegador.

<link>: enlaza archivos externos (CSS, favicon).

<style>: estilos CSS internos.

<script>: código JavaScript.

<body>
Contiene todo el contenido visible de la web.

11. Tipos de elementos HTML
Elementos de bloque
Ocupan todo el ancho disponible y crean salto de línea.

<h1> a <h6>: encabezados.

<p>: párrafos.

<div>: contenedor.

<blockquote>: citas largas.

<pre>: texto preformateado.

Elementos de línea
No crean saltos de línea.

<span>: contenedor en línea.

<em>: énfasis.

<strong>: importancia.

<a>: enlaces.

<code>: código.

12. Etiquetas de texto
Encabezados
<h1>Título principal</h1>
<h2>Subtítulo</h2>
Se usan para estructurar el contenido jerárquicamente.

Párrafos
<p>Texto del párrafo</p>
Énfasis
<em>Texto enfatizado</em>
<strong>Texto importante</strong>
Span
<span>Texto en línea</span>
Se usa para aplicar estilos sin romper la línea.

13. Saltos y separadores
<br>: salto de línea.

<hr>: línea horizontal separadora.

14. Listas
Lista desordenada (<ul>)
<ul type="circle">
  <li>Elemento</li>
</ul>
Atributo type:

disc

circle

square

Lista ordenada (<ol>)
<ol type="A" start="2">
  <li>Paso</li>
</ol>
Atributos:

type: tipo de numeración.

start: valor inicial.

value: valor concreto de un elemento.

15. Rutas
Ruta absoluta
Indica la dirección completa:

<img src="https://www.example.com/logo.png">
Ruta relativa
Indica la ruta desde el archivo actual:

<img src="images/logo.png">
16. Imágenes
Etiqueta:

<img src="media/logo.png" alt="Logo de la web">
Atributos:

src: ubicación de la imagen.

alt: texto alternativo.

17. Enlaces (<a>)
<a href="https://example.com" title="Ejemplo">Enlace</a>
Atributos:

href: destino del enlace.

title: información adicional.

18. Enlaces a anclas
Crear ancla:

<h2 id="seccion1">Sección 1</h2>
Enlazar:

<a href="#seccion1">Ir a la sección</a>
19. Contenedores (<div>)
<div class="seccion">
  <p>Contenido</p>
</div>
Sirve para agrupar elementos y aplicar estilos o scripts.

20. Formularios
Etiqueta <form>
<form action="procesar.php" method="post" target="_self">
Atributos:

action: URL de envío.

method: get o post.

enctype: tipo de codificación.

target: destino de la respuesta.

Etiqueta <input>
<input type="text" name="usuario" placeholder="Nombre" required>
Atributos:

type: tipo de campo.

name: nombre del dato enviado.

id: identificador único.

value: valor del campo.

placeholder: texto orientativo.

required: obligatorio.

disabled: desactivado.

readonly: solo lectura.

Radio y checkbox
<input type="radio" name="opcion">
<input type="checkbox" name="condiciones">
21. Tablas
Estructura
<table border="1" width="50%">
  <caption>Título de la tabla</caption>
  <thead>
    <tr>
      <th>Nombre</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ana</td>
    </tr>
  </tbody>
</table>
Etiquetas de tablas
<table>: tabla completa.

<thead>: encabezado.

<tbody>: cuerpo.

<tfoot>: pie.

<tr>: fila.

<th>: celda de encabezado.

<td>: celda de datos.

<caption>: título.

Atributos de tablas
border: grosor del borde.

width: ancho.

align: alineación horizontal.

valign: alineación vertical.

colspan: número de columnas.

rowspan: número de filas.

CSS

![CSS Logo](./descarga.png)

## ¿Qué es CSS?

CSS (**Cascading Style Sheets**) es el lenguaje que se utiliza para dar estilo a las páginas web.  
Mientras que HTML se encarga de la estructura y el contenido, CSS controla el diseño visual.

Con CSS podemos cambiar:

- Colores
- Tamaños de letra
- Márgenes y espacios
- Posición de los elementos
- Fondos y bordes

---

## ¿Cómo se aplica CSS?

Hay **tres formas** de aplicar CSS a un documento HTML.

---

### CSS en línea

Se escribe directamente dentro de una etiqueta HTML usando el atributo `style`.

```html
<p style="color: red;">Texto en rojo</p>
```

No es la forma más recomendable, pero sirve para pruebas rápidas.

---

### CSS interno

Se escribe dentro de la etiqueta `<style>` en el `<head>` del documento.

```html
<style>
  p {
    color: blue;
  }
</style>
```

---

### CSS externo (el más usado)

Se escribe en un archivo `.css` aparte y se enlaza desde HTML.

```html
<link rel="stylesheet" href="styles.css">
```

Esto permite tener el código más ordenado y fácil de mantener.

---

## Sintaxis básica de CSS

```css
selector {
  propiedad: valor;
}
```

### Ejemplo

```css
p {
  color: green;
  font-size: 16px;
}
```

---

## Selectores básicos

### Selector de etiqueta

Selecciona todas las etiquetas iguales.

```css
p {
  color: black;
}
```

### Selector de clase

Se usa con `.` y puede repetirse en varios elementos.

```css
.texto {
  color: blue;
}
```

### Selector de id

Se usa con `#` y es único.

```css
#titulo {
  font-size: 24px;
}
```

---

## Colores en CSS

Los colores se pueden definir de varias formas:

```css
color: red;
color: #ff0000;
color: rgb(255, 0, 0);
```

---

## Tipografía

```css
p {
  font-family: Arial, sans-serif;
  font-size: 18px;
  font-weight: bold;
}
```

---

## Modelo de caja (Box Model)

Todos los elementos HTML se comportan como una caja formada por:

- **Content**: el contenido
- **Padding**: espacio interno
- **Border**: borde
- **Margin**: espacio externo

### Ejemplo

```css
div {
  margin: 10px;
  padding: 15px;
  border: 2px solid black;
}
```

---

## Display

Define cómo se muestra un elemento en la página.

```css
display: block;
display: inline;
display: inline-block;
display: none;
```

---

## Posicionamiento básico

```css
position: static;
position: relative;
position: absolute;
position: fixed;
```

---

## Conclusión

HTML se encarga de la **estructura** y CSS del **diseño**.  
Usarlos juntos permite crear páginas web completas, ordenadas y visualmente atractivas.
