# PokedexDigital
Es un sitio web para una empresa, con una capacidad audio visual impresionante

2. Inspección en el mundo real:

![Imagen de los margenes que se ocupan en el sitio web de Nintendo](<Img/Nintendo Imagen.png>)

- Identificamos: En el margin exterior se le dio una puntuación de 0 en todos los lados y en el padding se le dio una asignación de 2px en los lados izquierdo y derecho, pero arriba y abajo se les dió una puntuación de 0px.

Auditoría Manual: 

1. La propiedad 'width' no tiene unidad de medida (debe ser 'px', '%', etc.) 
width: 300px;

2. El valor de 'text-align' está en español (debe ser 'center' en inglés)
text-align: center;

3. Falta el punto y coma (;) al final de la línea previa para cerrar la declaración correctamente
border-style: solid;

Investigación Técnica:

# Tipografías en CSS

## Diferencia entre Serif y Sans-Serif
* **Serif:** Letras con adornos o "patitas" en las puntas (ej. *Times New Roman*).
* **Sans-serif:** Letras limpias y sin adornos (ej. *Arial*).

## Recomendación para Pantallas
Se recomienda usar **`sans-serif`** en pantallas digitales porque se lee de forma más clara, no se distorsiona con los píxeles y genera menos fatiga visual.

Reto del modelado de caja:

Para hacer que haya un espaciado en el interior de la caja, se debe de usar padding en la clase "targeta-pokemon"

Conclusión: 
Es importante para llevar un orden, si todo se lleva como mezcla usualmente podemos confundirnos más facilmente y provocar más errores en el código, de igual forma si se producen errores es más fácil saber en que parte buscar, ya que, si es problema de estilo corregimos en el archivo de estilo y viceversa.