---
layout: post
title:  "Haciendo pruebas con Markdown"
date:   2016-09-07 11:00:00 +0100
categories: jekyll update
---

Esta página la voy a usar para hacer pruebas con [Markdown][Markdown]. 

[Markdown]: https://daringfireball.net/projects/markdown

Nota: También se puede enlazar una web con la estructura [enlace](https://enlace_link).

Esto es un link a la web de [markdown](https://daringfireball.net/projects/markdown "Enlace a Markdown") con atributo.

Otro ejemplo. I get 10 times more traffic from [Google][1] than from
[Yahoo][2] or [MSN][3].

[1]: http://google.com/        "Google"
[2]: http://search.yahoo.com/  "Yahoo Search"
[3]: http://search.msn.com/    "MSN Search"


Además, vemos que si introducimos una tabulación, mantenemos el texto plano, si transformar a html.

	Esto es un link con [atributo](https://daringfireball.net/projects/markdown "Enlace a Markdown")

## ¿Qué es Markdown?

Markdown permite transformar texto plano a HTML de forma sencilla. Por ejemplo, el texto precido por dos "almohadillas" y un espacio (## ) será convertido a un texto de jerarquía h2 (<h2> texto </h2>)

>Nota: Además, Markdown y HTML se pueden mezclar.
>
><h2> Título h2 HTML </h2>
>
>Comprobamos que se puede mezclar. Esto será interesante a la hora de insertar imagenes y vídeos.

## Enfatizando frases

Para enfatizar frases, podemos usar:

	Asterisco: Esto es *una prueba*

	Barra baja: Esto es _una prueba_

	Doble asterisco: Esto es **una prueba**

	Barra baja: Esto es __una prueba__

## Creando listas.

Simplemente tenemos que preceder cada item de la lista por un *,+,- (seguido de una tabulacion) en función de la estetica que busquemos:
>
*	Tomates
*	Patatas
*	Azucar
>
+	Tomates
+	Patatas
+	Azucar
>
-	Tomates
-	Patatas
-	Azucar

>
1.	Tomates
2.	Patatas
3.	Azucar

Ejemplo listas con parrafos.

*   Cita médico.

	No olvidar la cita con el doctor.No olvidar la cita con el doctor.No olvidar la cita con el doctor.No olvidar la cita con el doctor.

    With multiple paragraphs.

*   Recoger la ropa.
	
	No olvidar recoger la ropa esta semana.

Ejemplo listas con parrafos y subpuntos.

*   Cita médico.

	-	No olvidar la cita con el doctor.

		Esto es un subparrafo dentro de un subpunto

    -	With multiple paragraphs.

*   Recoger la ropa.
	
	-	No olvidar recoger la ropa esta semana.

		Esto es otro subparrafo dentro de un subpunto

		-	Otro subpunto

## Introduciendo imágenes.

En una linea:

	![alt text](http://jsequeiros.com/sites/default/files/imagen-cachorro-comprimir.jpg?1399003306 "Foto de tigre")

![alt text](http://jsequeiros.com/sites/default/files/imagen-cachorro-comprimir.jpg?1399003306 "Foto de tigre")

Estilo referenciado:

	![alt text][Foto 1]

	[Foto 1]: http://2.bp.blogspot.com/_EZ16vWYvHHg/S-Bl2fuyyWI/AAAAAAAAMKc/DNayYJK8mEo/s1600/www.BancodeImagenesGratuitas.com-Fantasticas-20.jpg "Foto de Paisaje"

![alt text][Foto 1]

[Foto 1]: http://2.bp.blogspot.com/_EZ16vWYvHHg/S-Bl2fuyyWI/AAAAAAAAMKc/DNayYJK8mEo/s1600/www.BancodeImagenesGratuitas.com-Fantasticas-20.jpg "Foto de Paisaje"

/////////////////////////

This is Ingenio.xyz website. To get into it, do click [here][here]

[here]: http://ingenio.xyz


