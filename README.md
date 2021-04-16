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

