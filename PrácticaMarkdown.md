# MARKDOWN

Markdown es un lenguaje de marcado ligero, una forma de agregar formatos como encabezados, negritas, cursivas, listas... a un texto sin formato utilizando un editor de texto simple. Es decir, una forma rápida de coger apuntes con ordenador y pasarlos a limpio en un solo paso.


- Elementos de bloque
  - Párrafos
  - Saltos de línea
  - Encabezados
  - Citas
  - Listas
  - Códigos de bloque
  - Líneas horizontales
- Elementos de línea
  - Énfasis
  - Links o enlaces
  - Código
  - Imágenes
- Otro elementos
  - Links automáticos
  - Omitir Markdown
  - Símbolos matemáticos


# ENCABEZADOS

Las almohadillas o hashtag `#` es el método utilizado en Markdown para crear encabezados. Debes usarlos añadiendo uno por cada nivel y dejando un espacio en blanco `Ejemplo: `

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

# Enfatizar: negritas y/o cursivas

Para poner cursivas encierra entre 1 asterisco Para poner negritas encierra entre 2 asteriscos Para poner negritas y cursiva encierra entre 3 asteriscos `Ejemplo:`

Lorem ipsum *dolor* sit **amet** consectetur adipiscing elit.  Eligendi voluptas harum nostrum, dolores iusto dolorum eveniet similique quos dolorem porro ducimus voluptate, temporibus, reincendis ***voluptatem modi explicabo*** ea. Eius, totam?

# Líneas horizontales

Para crearlas, en una línea en blanco deberás icluir  `tres` de los siguientes elementos: 3 asteriscos, 3 guiones, o 3 guiones bajos. `Ejemmplo:`

***

# Citas

Las citas se generar utilizando el carácter mayor que `>` al comienzo del bloque de texto. `Ejemplo:`

>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Enim quibusdam reprehenderit eum magni minima eaque impedit reiciendis ullam asperiores fugit

# Listas

Para crear listas desordenadas podemos utilizar 3 tipos de simbolos por cada item de la lista: Un asterisco `*`, un guión medio `-` o un símbolo más `+`. `Ejemplo;`

* Ítem 1
* Ítem 1
* Ítem 1

Para crear listas ordenadas debes utilizar la sintaxis de tipo: `1.`.

1. Ítem 1
2. Ítem 1
3. Ítem 1

Para generar listas anidadas (desordenadas u ordenadas) dentro de otras, simplemente tendrás que añadir `dos (o cuatro) espacios en blanco`.`Ejemplo:`

* Ítem 1  
  * Ítem 12
    * Ítem 121
* Ítem 2

1. Ítem 1 
  i. Ítem 12
    a. Ítem 121
1. Ítem 2

# Links o enlaces

Se crean escribiendo la palabra o texto enlazada entre `[]` corchetes, y el link en cuestión entre `()` paréntesis.

Sin texto enlazado escribe la URL entre ángulos `<URL>` Enlace de ejemplo como referencia: [3con14](https://youtube.com), y al final del texto escribir la etiqueta seguida de dos puntos.

# Imágenes

Insertar una imagen con Markdown se realiza de una manera idéntica a insertar links. En este caso, debes añadir un símbolo de `!` excalamación al principio y el enlace que es la ubicación de la imagen.

`![Texto alternativo](ruta/imagen.jpg "Título alternativo")`

`Ejemplo:`

![Moto Yamaha](https://cdn2.yamaha-motor.eu/prod/product-assets/2022/XMAX300ASP/2022-Yamaha-XMAX300ASP-EU-Dark_Petrol-Studio-001-03_Mobile.jpg  "Moto Yamaha")

# Tablas

Markdown permite dibujar tablas mediante plecas `|`. Cada celda está separada por uno de estos caracteres, Para crear encabezados que se distingan visualmente del resto del contenido, se subrayan las celdas correspondientes con guiones -. `Ejemplo:`

| Columna 1 | Columna 2 |
| -- | -- |
| uno | dos |
| tres | cuatro |
| cinco | seis |

# Línea de Código

Encerrando el códigp entre acentos graves `<html lang"es">`

# Bloque de Código

Para crear un bloque entero que contenga código lo único que tienes que hacer es encerrar dicho párrafo entre dos líneas formadas por tres ~ vrgulillas o tres acentos grave. La otra manera de añadir código en Markdown es comenzar el párrafo con `cuatro espacios en blanco`. `Ejemplo:`
~~~ Html
<head>
    <meta charset="UTF-8">    
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>Document</title>
</head>
~~~
~~~ Java
System.out.println("Hola Mundo");
~~~
~~~ c
#include <conio.h>
#include <stdio.h>

int main()
{
    printf( "Hola mundo." );

    getch(); /* Pausa */

    return 0;
}
~~~

# Omitir Markdown
Cómo escribir ciertos símbolos como `*` o `#`, sin que Markdown los interprete para convertirlos en negritas,...
Escribiendo justo delante del símbolo la barra invertida `\`. `Ejemplo:` Esto es un asterisco \*

# Escritura matemática

En línea encerrando la fórmula entre signo de $ En párrafos centrados, encerrando las fórmula entre dos signos de $$

* Fórmulas en línea: $(a+b)² = a² + b² + 2ab$
* Fórmulas centradas: 
$$a² - b² = (a+b) · (a b)$$
* Radicales:
$$\sqrt{a²-b²}$$
* Fracciones: 
  $$ x = \frac {-b ± \sqrt{b² - 4ac}} {2a} $$
* Paréntesis grandes:
  $$ \left(\sqrt{x²}\right)²$$
* Colores:
$$ {\color{yellow} {A}}aBb123 $$ 
