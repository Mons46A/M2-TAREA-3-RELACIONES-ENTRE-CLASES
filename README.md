# TAREA 3: RELACIONES ENTRE CLASES

## Modelado de relaciones con UML

**Objetivo**

Identificar y modelar las clases involucradas en el enunciado especificando sus atributos,
responsabilidades y principalmente las relaciones entre las mismas. Especificar la multiplicidad en dichas
relaciones.

**Enunciado**

Una computadora consta de una marca, un modelo y un año de fabricación. Para distinguir entre las computadoras, se les ha asignado un tipo:

- Tipo D para **“desktop”**
- Tipo A para **“all-in-one”**
- Tipo L para **“laptop”**

Cada computadora posee 3 características básicas, independiente de su tipo. Todas poseen
un disco rígido, muchos procesadores y dos memorias. El disco rígido tiene marca, capacidad
en gigabytes, una velocidad de operación en RPM. Por su lado, los procesadores tienen marca, modelo y velocidad en gigahertz y cada memoria tiene capacidad en gigabytes y marca.

Entonces, **¿Cuáles son las clases dentro del problema?**

1. Lee detenidamente el enunciado buscando las posibles clases de objetos (recuerda que los objetos
generalmente se nombran con un sustantivo).
2. De cada clase de objeto vamos a pensar cuáles son las características, o sea, los atributos que la
representan.
3. Luego de cada clase identificaremos los comportamientos (generalmente es un verbo).
4. En este ejercicio en particular, inventa posibles comportamientos que puede tener cada clase, sé
creativo.


Luego, debes representar las clases en un diagrama que sirva para poder programar a futuro el sistema
necesario:
1. Con la herramienta de diagramación ( app.diagrams.net) genera un nuevo diagrama.
2. Agrega por cada clase de objeto un elemento de clase.
3. Para cada clase agrega todos sus atributos y métodos (responsabilidades).
Después, debes representar las relaciones entre las clases:
1. Primero, debes identificar si las clases que estás relacionando pueden sobrevivir una sin la otra. Si
es así, recuerda que puede ser una agregación.
2. Con la herramienta de diagramación, puedes arrastrar tanto asociaciones simples como
agregaciones.
3. Una vez plasmada la relación, vas a especificar su multiplicidad. Para esto, colócate primero sobre una de las clases y pregúntate **¿por cada instancia de esa clase cuántas instancias de la otra clase podría tener la relación?** Recuerda que si pueden ser muchas, lo especificamos con un **“*”** y este resultado lo ponemos en el extremo de la relación con la otra clase donde estamos parados.
Luego haces lo mismo colocándote con la otra clase de la relación.
