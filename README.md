# FP11_P3
Tercera práctica de FPII
Se quiere implementar un sistema de gestión de pedidos y recetas en una pastelería. Todos los 
pasteles tienen un sabor, un relleno, y pueden prepararse con o sin azúcar. Se debe poder 
consultar todos estos datos, así como mostrarlos en un mismo mensaje por pantalla. 
Hay dos tipos de pasteles (bizcochos y bollos), ambos con las mismas características
mencionadas anteriormente.
El horneado en esta pastelería se realiza de forma general a una temperatura constante de 
180°C, aunque el tiempo de horneado es variable según el producto (supongamos que en esta 
pastelería hay más productos además de pasteles). En el caso concreto de los pasteles, ese 
tiempo es de 30 minutos para un pastel de vainilla, 45 minutos para uno de chocolate, y 60 
minutos para el resto de sabores. Si, además, el pastel lleva azúcar, el tiempo de horneado se 
incrementa 10 minutos.
Además, existe un recetario general que se puede utilizar para anotar recetas de cualquier tipo 
de pastel. En dicho recetario se puede comprobar si una nueva receta que queremos añadir ya 
está repetida o si, por el contrario, no existe en el listado, informando con un mensaje del 
resultado. Se considera que la receta candidata ya está repetida si el sabor, relleno y contenido 
de azúcar son iguales.
Se pide: 
a) Diseñar en UML en diagrama de clases e interfaces y las relaciones entre ellas.
b) Implementar el horneado como una interfaz, con un valor constante de temperatura y un 
método para calcular el tiempo de horneado.
c) Implementar las clases.
d) Implementar el recetario como una clase genérica, con un método para comprobar si el 
elemento nuevo que se quiere añadir ya existe en la lista.
e) Escribir un programa principal donde se ejecuten los siguientes pasos:
1) Crear los pasteles.
2) Ordenarlos en una estructura con el siguiente orden de preparación en el día
3) Mostrar una lista completa de los pasteles de la estructura, indicando la información 
sobre los atributos del pastel y sobre el tiempo y temperatura del proceso de horneado. 
Al finalizar la lista, mostrar el total de pasteles preparados, y el tiempo que ha estado el 
horno en funcionamiento.
4) Crear un recetario de bizcochos y otro de bollos con los creados anteriormente. Crear 
un nuevo pastel de cada tipo como los que se indican en la siguiente tabla, y comprobar 
si ya existen o no en su recetario correspondiente, mostrando el resultado por pantalla.
# Nota: 10/10
Documentacion: https://drive.google.com/drive/folders/1fvbgSA9u5ERRCnNXzvpoHjsklIz6twI4?usp=sharing
