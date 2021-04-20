# Curso de Desarrollo Web
## Proyecto 1: Sitio Freelancer

Bienvenido al Curso de Desarrollo Web!

Este es el primer proyecto que desarollaremos en el Curso

------

Empezaremos con un Sitio Freelancer

* Crearemos el index.html del proyecto

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Freelancer Site</title>
</head>
<body>
	<h1>
        Empezamos bien!
    </h1>
</body>
</html>
```

## Commit Nro 1 - v0.2

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados** |
| ------------------- | --------------------- |
| index.html          | index.html            |

### Explicación 

* Inicio del proyecto **Freelancer Site.

------

## Commit Nro 2 - v0.3

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados** |
| ------------------- | --------------------- |
| None                | index.html            |

### Explicación

* Adicion de las primeras etiquetas de **Headings** y **Parrafos** para empezar a estructurar el contenido.


------

## Commit Nro 3 - v0.4

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados** |
| ------------------- | --------------------- |
| None                | index.html            |

### Explicación

* Estructuracion completa de los elementos en el index.html

	```html
	<!-- Se usa header para el primer H1-->
	<header>
		<h1>Free-Lancers</h1>
	</header>
	
	<!-- Si empieza con un heading debe ir un section-->
	<section>
		<h2>Una Comunidad de  Freelancers</h2>
		<p>Caracas, Venezuela </p>
	</section>
	
	<!-- El main tiene nuestro contenido principal -->
	<main>
		<h2>Nuestros Servicios</h2>
		<section>
			<h3>Diseño Web</h3>
			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus, quibusdam.</p>
		</section>
	</main>
	
	<!-- El footer para pie de pagina -->
	<footer>
		<p>All Rights Reserved. Luisfer Doria, 2021</p>
	</footer>
	```


------

## Commit Nro 4 - v0.5

### Cambios realizados 

| **Archivos Nuevos** | **Archivos Editados** |
| ------------------- | --------------------- |
| None                | index.html            |

### Explicación

* Se agrego el nav de la pagina web junto a 3 enlaces

	```html
	<!-- El nav se usa para agregar una barra de navegacion. Generalmente usa enlaces -->
	<nav>
		<a href="#">Home</a>
		<a href="#">About Us</a>
		<a href="#">Contact</a>
	</nav>
	```

------

## Commit Nro 5 - v0.6

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados** |
| ------------------- | --------------------- |
| None                | index.html            |

### Explicación

* Se agrego una imágen y 4 iconos

	```html
	<!-- Agregamos una imagen -->
	<img src="img/header.jpg" alt="">
	
	<!-- Agregamos un icono #7D05D0 -->
	<img src="img/map-solid-60.png">
	```

------

## Commit Nro 6 - v0.7

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados** |
| ------------------- | --------------------- |
| None                | index.html            |

### Explicación

* Agregamos el formulario a la pagina web

	```html
	<!-- Agregamos un formulario con form-->
	<form action="">
	
	    <!-- Agrupamos cada input en un div (divider) -->
	    <div>
	        <input type="text" placeholder="Nombre">
	    </div>
	
	    <div>
	        <input type="email" placeholder="Correo">
	    </div>
	
	    <div>
	        <input type="text" placeholder="Teléfono">
	    </div>
	
	    <div>
	        <input type="textarea" placeholder="Mensaje">
	    </div>
	
	    <div>
	        <input type="submit" value="Enviar">
		</div>
	
	</form>
	```

------

## Commit Nro 7 - v0.8

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados**        |
| ------------------- | ---------------------------- |
| index.css           | index.html   <br />index.css |

### Explicación

Hemos creado un archivo CSS index.css, lo hemos enlazado al index.html y hemos creado algunos estilos para definir lo siguiente:

- Tamaño Predeterminado de Fuente
- Familia Tipográfica
- Color de la Tipografía
- Tamaño de la Tipografía para un H1

```css
/* Para tener un mejor manejo del tamaño de las tipografias, definir un tamaño estandar */
html {
	font-size: 18px;
}

/* Establecemos la familia de la fuente y el color */
body {
	font-family: Roboto;
	color: #09001A;
}

/* Alineamos el h1 al centro y el tamaño será de 2.441rem, es decir el tamaño estandar de la fuente x los rem
Ej: 18px * 2.441 */
h1 {
	text-align: center;
	font-size: 2.441rem;
}

```

------

## Commit Nro 8 - v0.9

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados**     |
| ------------------- | ------------------------- |
| None                | index.html<br />index.css |

### Explicación

Hemos añadido en el archivo index.css algunos colores como variables, además hemos añadido algunos weight para las fuentes de título y párrafo.

```css
:root{
	--purpleOscuro: #09001A;
	--blancoBG: #F9F5FF;
	--blancotxt: #F0E4FE;
	--purple: #3A04A1;
}

.titulo {
	font-weight: 700;
	text-align: center;
	font-size: 2.441rem;
}
```

------

## Commit Nro 9 - v1.0

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados**                        |
| ------------------- | -------------------------------------------- |
| normalize.css       | index.html<br />index.css<br />normalize.css |

### Explicación

Hemos añadido Normalize a nuestro proyecto.
Este se encarga de "normalizar" el código y reglas CSS para que la página se vea igual en Chrome, Firefox, Edge, Safari, Brave, dispositivos móviles, tablets, etc.

```html
<!-- Preload del Normalize -->
<link rel="preload" href="stylesheet/normalize.css" as="style">

<!-- Link Normalize.css -->
<link rel="stylesheet" href="stylesheet/normalize.css">
```

------

## Commit Nro 10 - v1.1

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados**     |
| ------------------- | ------------------------- |
| None                | index.html<br />index.css |

### Explicación

Hemos editado el nav hasta tenerlo listo

* Primero, hemos cambiado la estructura del nav en HTML: 

	```html
	<div class="nav-bg">
		<nav class="main-nav container"> 
			<a href="#">Home</a>
			<a href="#">About Us</a>
			<a href="#">Contact</a>
		</nav>
	</div>
	```

	* Tenemos un div con clase **nav-bg** que engloba el nav completo.
	* Dentro, tenemos el nav con 2 clases: **main-nav** y **nav-container**.

* Luego, hemos añadido el siguiente código en el CSS: 

	```css
	/* Estilos para el nav*/
	.nav-bg {
		background-color: #3A04A1;
	}
	
	.main-nav {
		display: flex;
		justify-content: space-around;
	}
	
	.main-nav a {
		color: #F0E4FE;
		text-decoration-line: none;
		font-size: 1.5rem;
		padding: 1rem;
		font-weight: 200;
	}
	
	.main-nav a:hover {
		background-color: #F9F5FF;
		color: #09001A;
	}
	
	.nav-container {
		width: 75%;
		margin: 0 auto; 
	}
	
	```

	* el **.nav-bg** edita el div que engloba al nav.
	* el **main-nav** tiene el display flex con una alineación en modo *space-around*.
	* el **main-nav a** contiene las propiedades de los enlaces.
	* en el **main-nav a:hover** tenemos la pseudoclase del hover a cada enlace
	* el **.nav-container** edita las propiedades generales del nav, como el tamaño o el margen. 
		**Nota:** la clase **main-nav** tambien puede albergar esas propiedades, pero al colocar las en la clase **nav-container** podemos administrar dichas propiedades de una mejor manera mediante la metodología Utility First.

### Metodologías de Código CSS

* **BEM (Block, Element, Modifier):** Esta metodología indica que primero editamos los bloques, luego los elementos y luego los modificadores o pseudoclases. 

	* Código HTML:

		```html
		<div class="card-container">
		    <div class="card">
		        <h1 class="card__titulo">
		            Titulo del card
		        </h1>
		        <img class="card__imagen" src="imagen.jpg">
		        <p class="card__parrafo">
		            Lorem ipsum dolor sit amet.
		        </p>
		        <button class="card__button">
		            Boton 
		        </button>
		    </div>
		</div>
		```

	* Código CSS:

		```css
		/* Propiedades del container del card, respecto al documento */
		.card-container {
		    width: 25%;
		}
		
		/* Propiedades del card */
		.card {
		    width: 100%;
		}
		
		/* Propiedades del titulo */
		.card__titulo {
		    font-size: 2rem;
		    font-weight: bold;
		}
		
		/* Propiedades del parrafo */
		.card__parrafo {
		    font-size: 1rem;
		    font-weight: 300;
		}
		
		/* Propiedades del boton */
		.card__boton {
		    padding: 10px;
		    background-color: red;
		    color: white;
		}
		```

* **Utility First (UF):** Esta metodología puede ser un poco mas caótica al tener mucho mas código, pero resulta en una mejor administración y orden de los elementos y sus propiedades.

	En esta metodología, cada selector en CSS debe tener una sola propiedad con su respectivo valor, así, en el HTML solo debemos colocar la clase del selector que requerimos.

	* Código HTML:

		```html
		<h1 class="titulo rojo-050">
		    Bienvenido xd
		</h1>
		
		<p class="parrafo rojo-010">
		    Lorem ipsum dolor sit amet
		</p>
		
		<button class="boton bg-rojo-100">
		    Click aqui
		</button>
		```

	* Código CSS:

		```css
		.titulo {
		    font-size: 2rem;
		    font-weight: bold;
		}
		
		.parrafo {
		    font-size: 1rem;
		    font-weight: regular;
		}
		
		.boton {
		    padding: 10px;
		}
		
		.bg-rojo-100 {
		    color: #ff0000;
		}
		
		.rojo-050 {
		    color: #770000;
		}
		
		.rojo-010 {
		    color: #220000;
		}
		```

* **Módulos:** Esta metodología nos permite tener una organización estructurada en el CSS, jerarquizada desde el elemento padre al hijo.

	* Código HTML:

		```html
		<div class="nav-bg">
			<nav class="main-nav nav-container"> 
				<a href="#">Home</a>
				<a href="#">About Us</a>
				<a href="#">Contact</a>
			</nav>
		</div>
		```

	* Código CSS:

		```css
		/* Estilos para el nav*/
		.nav-bg {
			background-color: #3A04A1;
		}
		
		.main-nav {
			display: flex;
			justify-content: space-around;
		}
		
		.main-nav a {
			color: #F0E4FE;
			text-decoration-line: none;
			font-size: 1.5rem;
			padding: 1rem;
			font-weight: 200;
		}
		
		.main-nav a:hover {
			background-color: #F9F5FF;
			color: #09001A;
		}
		
		.nav-container {
			width: 75%;
			margin: 0 auto; 
		}
		```

		------

		

## Commit Nro 11 - v1.2

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados**     |
| ------------------- | ------------------------- |
| None                | index.html<br />index.css |

### Explicación

Agregamos los media queries para la barra de navegacion.

```css
.main-nav {
	display: flex;
	flex-direction: column;
	align-items: center;
}

@media (min-width: 480px){
	.main-nav {
		flex-direction: row;
		justify-content: space-around;
	} 
}
```

* En el proyecto trabajaremos con el modelo Mobile First, por lo tanto, las propiedades que apliquemos al media querie seran para dispositivos mayores de 480px.
* Por lo tanto, en el **main-nav** hemos colocado las propiedades para movil (el **flex-direction: column** y el **align-items: center**)
* Por otra parte, el media querie estable el **flex-direction: row** y el **justify-content: space-around** para el nav

Los Media Queries permiten ejecutar codigo CSS cuando se cumple una condicion. Es ideal para el diseño responsivo.

```css
@media (max-width: 768px){
    background-color: red;
}
```

* Este código se ejecuta para pantallas que tengan una resolucion maxima de 768px hacia abajo.

```css
@media (min-width: 1368px){
	background-color: blue;
}
```

* Este codigo se ejecuta para pantallas que tengan una resolucion minima de 1368px hacia arriba.

En el Desarrollo Web se suele hablar del Mobile First, que consiste en desarrollar primero el sitio adaptado para moviles, y luego, con media queries en **min-width** adaptarlo a tablets y pantallas de escritorio.

### Tamaños estándar para pantallas

* **480px** --> Teléfonos Móviles
* **768px** --> Tablets 
* **1140px** --> Pantallas de Escritorio y Laptops
* **1368px** --> Pantallas de Escritorio y Laptops
* **1440px** --> Pantallas de Escritorio y Laptops

------

## Commit Nro 12 - v1.3

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados**     |
| ------------------- | ------------------------- |
| None                | index.html<br />index.css |

### Explicación

Hemos añadido el hero, que contiene un titulo un texto y un boton con enlace.

* Código HTML

```html
<!-- Hero (imagen con info principal -->
<section class="hero-container">
	<div class="hero-content">
		<h2>Una Comunidad de Freelancers</h2>
	<div class="ubic">
		<p>Caracas, Venezuela </p>
		<!-- Agregamos un icono #7D05D0 -->
		<img src="img/map-solid-60.png">
	</div>
		<a class="button" href="#">Contactar</a>
	</div>
</section>
```

* Código CSS

```css
.hero-container {
	background-image: url("../img/header.jpg");
	background-repeat: no-repeat;
	background-size: cover;
	height: 20rem;
	padding: 1rem;
	position: relative;
}

/* Al aplicar display flex, alineamos horizontalmente con justify-content y verticalmente con align-items 

Cuando cambias el flex-direction a column, las alineaciones se hacen de manera inversa*/
.hero-content {
	position: absolute;
	background-color: #00000033;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;

	/* Centrar vertical y horizontalmente al centro*/
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
}

.hero-content h2, 
.hero-content p,
.hero-content a {
	color: #F0E4FE;
}

.ubic {
	display: flex;
	flex-direction: row-reverse;
	align-items: center;
	margin-top: 1rem;
```

Con eso hemos dado unos buenos estilos al hero.

------

## Commit Nro 13 - v1.4

### Cambios realizados

| **Archivos Nuevos** | **Archivos Editados**     |
| ------------------- | ------------------------- |
| None                | index.html<br />index.css |

### Explicación

Hemos editado la seccion de **Nuestros Servicios**, usando CSS Grid para la estructura y Flexbox para la alineación de los elementos.

* Código HTML:

```html
<main class="container sombra">
	<h2>Nuestros Servicios</h2>

	<div class="services">
		<section class="service">
			<h3>Diseño Web</h3>
			<div class="icono">
				<!-- Icono para el section -->
				<img src="img/html5-logo-60.png" alt="">
			</div>
			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus, quibusdam.</p>
		</section >
	</div>
</main>
```

Aqui definimos un servicio dividido en el titulo (el h3), un icono y un parrafo.

* Código CSS:

```css
/* Servicios */

.services {
	display: grid;  
	grid-row-gap: 1rem;
}

@media (min-width: 768px){
	.services {
		grid-template-columns: repeat(3, 1fr);
		column-gap: 1rem;
	}
}

.service {
	display: flex;
	flex-direction: column;
	align-items: center;
}

.service p {
	text-align: center;
	line-height: 2;
}

.service .icono {
	height: 125px;
	width: 125px;
	background-color: #F0E4FE;
	border-radius: 5rem;
	display: flex;
	justify-content: center;
	align-items: center;
}
```

El **services** establece el **display: grid** para dispositivos moviles, y el media querie para dispositivos mayores.

Luego estan las propiedades de **service** para el servicio individual, que alinea los elementos hijos con Flexbox.

------

## Commit Nro 14 - v1.5

### Cambios realizados 

| **Archivos Nuevos** | **Archivos Editados**     |
| ------------------- | ------------------------- |
| None                | index.html<br />index.css |

### Explicación

Hemos editado el Formulario con sus respectivos estilos.

* Código CSS:

```css
/* Formulario */

.form-container h2{
	text-align: center;
}
.formulario {
	width: min(10rem, 100%); /* Usa el valor mas pequeño*/
	margin: 0 auto;
}

.field {
	margin-bottom: 1rem;
}

.field input{
	padding: 0.5rem;
}

.field input[type="textarea"] {
	height: 5rem;
}

.enviar .button {
	width: 125%;
}

/* Footer*/
.footer {
	text-align: center;
}
```

Son propiedades de alineación, margin y padding.

También hemos añadido el estilo para el **footer**, que es una alineación al centro.

------

