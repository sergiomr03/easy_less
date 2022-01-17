# less_css

Antes de comenzar, tenemos que instalarnos la extensión llamada "Easy Less" para Visual Studio. Una vez instalada, reiniciamos el programa
y continuamos con esta práctica.

Para realizar toda la práctica, la información necesaria se ha explicado en la presentación anterior.
Para cualquier consulta, hacer uso de la página "https://lesscss.org/".

Las siguientes reglas deberán aplicarse en el archivo "styles.less". Nunca tocar "styles.css".

1 - Crear una variable llamada "sizeP" y asignarle el valor de "1rem".


2 - A la etiqueta "p" asignarle el tamaño de letra que hemos usado en la variable creada anteriormente.


3 - A la etiqueta "H1" asignarle el valor de la variable multiplicada por 6. 


4 - A la etiqueta "H2" asignarle el valor de la variable multiplicada por 5. 


5 - A la etiqueta "H3" asignarle el valor de la variable multiplicada por 4. 


6 - Crear una clase llamada "border" y asignarle los siguientes atributos:
    border-style:solid;
    border: @sizeP / 2;
    border-color: black;
    border-radius: @sizeP * 6;

7 - Crear una clase llamada "margins" y asignarle los siguientes atributos:
    margin: 3%;

8 - Crear una clase llamada "flex" y asignarle los siguientes atributos:
    display: flex;
    align-items: center;
    justify-content: center;

9 - A la etiqueta "Body", asignarle el color de fondo "burlywood".

10 - Crear una clase llamada "div1" y hacer que su fondo sea de color "yellowgreen".

11 - En la clase "div1", haciendo uso de Mixins, hacer uso de las clases "border" y "margins" dentro de esta.

12 - En la clase "div1", haciendo uso de Nestings, decir que si dentro existe un "h2", su letra sea de color gris, y si existe un "h3", que su letra sea de color blanca.

13 - Crear una clase llamada "div2" y hacer que su fondo sea de color "yellow".

14 - En la clase "div2", haciendo uso de Mixins, hacer uso de las clases "border", "margins" y "flex" dentro de esta.

15 - En la clase "div2", haciendo uso de Nestings, decir que si dentro existe un "p", su letra sea de color roja.
