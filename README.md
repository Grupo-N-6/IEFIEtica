
#ACCESIBILIDAD WEB.
___
##En la barra de navegación, lo que no es accesible es el logo, la imagen "Logo.png", que contiene el enlace al index pero no funciona. 

___
##Intentos de corrección en página  Index.
___
1. Posee sólo 4 errores de contraste.
	Se cambia el color a los elementos con error para que quede un contraste bajo.

___

##Intentos de corrección en página Sobre-nosotros.

___

###Primer error detectado:
1.Los links no tienen texto.

	Se agrega texto a los links ( Se eliminan 2 íconos para que entren armónicamente ).
___
2.Error " Contraste muy bajo" ( 28 Errores)
	Se procede a cambiar el color de los links  implementando(class="text-primary")
___
3-Quedan 13 errores de contraste.
	Se intenta cambiar color, del span que contiene el texto " Estudiante de desarrollo web". Pero no era posible porque se chocaba con los estilos ya provistos.
Se encuentra en: templatemo-style.css
.sobre-nosotros .featured-item .down-content span.
	Se elimina span para que pueda tomar el color de los nuevos estilos aplicados. Funciona.
___
4.Quedan 9  errores de contraste.
	Se corrije el color del texto en los párrafos de la sección de cada integrante.
___
5.Quedan 3 errores de contraste.
	Se corrige tamaño y color del texto " Grupo de estudiantes"
6.Quedan 2 errores de contraste.
	Se corrijen los 2 errores de contraste faltantes en el footer.
___
7. Falta barra navegación de index.
	Se pega la barra de navegación del index en sobre-nosotros.
___
8. " Falta título a la página".
	Se agrega título a la página mediante <title>
___
9."Falta especificar idioma mediante atributo "lang"
	Se corrige, se agrega atributo lang="es".
___
10."La página no tiene encabezado H1".
	Se corrije, se cambia span por h1 en  "grupo de estudiantes".
___

####Finalizado.