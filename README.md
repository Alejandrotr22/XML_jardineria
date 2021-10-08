# XML_jardineria
Este repositorio está dedicado a una tarea de xml

## Se pide


Se necesita un formato de archivo para intercambiar productos entre almacenes de productos de jardinería y se desea una DTD que incluya estas restricciones:

Debe haber un elemento raíz pedido que puede constar de plantas, flores y/o utensilios. Los tres elementos pueden aparecer repetidos y en cualquier orden. También pueden aparecer por ejemplo 4 plantas, 2 flores y luego 4 utensilios de nuevo.

   - Todo planta tiene un atributo obligatorio nombre.
   - Los elementos flores tiene un atributo optativo color.
   - Todo elemento utensilio debe tener dentro un elemento obligatorio número.

## Ejercicio 

Lo primero que se tiene que hacer el dtd correspondiente

<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=12NczbGK3z-GRJ17pc9eVXLDx5oZprO1v">
</div>

<br>

En este dtd simple se utilizan pocas restricciones, donde pueden aparecer desde 0  hasta n, pedidos,flores, planas y utensilios , siendo cada atributo no obligatorio menos el numero de la herramienta

<br>

Después de hacer el dtd así quedó el xml que completé a continuación 


<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=11S4f5JP0OgA6c7vUnIJP5c9aPpVNiGx0">
</div>
<br>
Y para ver si el código estaba correcto, utilicé una herramienta de comprobación dada por el profesor.

<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1C53SpAjEWOokSB03B7CXRbRjzkEdoYGQ">
</div>



Dando 0 errores en el código.



