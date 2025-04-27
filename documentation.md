# Proyecto: Combinaciones de Colores y Diseños en Prendas de Vestir

## Introducción

Los resultados de las combinaciones máximas posibles sin repetición para un conjunto de dos piezas desmontables de un color y/o diseño para cada prenda, conlleva un impacto directo en la programación de la producción de este sistema de prendas si se desea aprovechar esta herramienta.

Por ejemplo, puesto que dicho resultado no toma en cuenta el lado donde estará ubicada cada pieza, sean estos el lado izquierdo o derecho, es necesario establecer parámetros de producción para realmente aplicar dichas combinaciones en los productos manufacturados.

## Ejemplo Aplicado

Aplicando lo explicado anteriormente a un prototipo de 2 piezas, se tiene lo siguiente:

Suponga que hay 2 camisetas (total de 4 piezas), una con los colores amarillo y café (2 piezas), y la otra con los colores anaranjado y azul (2 piezas). En este caso, el dato de las combinaciones máximas posibles sin repeticiones afirma que la cantidad de apariencias es igual a 6.

Sin embargo, se debe tener en cuenta en cuál lado (izquierdo o derecho) de la prenda se encuentran cada una de las piezas de colores. Teniendo en cuenta los colores de este ejemplo:

- Amarillo (lado izquierdo) y café (lado derecho)
- Amarillo (lado izquierdo) y azul (lado derecho)
- Anaranjado (lado izquierdo) y café (lado derecho)
- Anaranjado (lado izquierdo) y azul (lado derecho)

**Figura 1:** Cuatro piezas de colores distintos.

Por lo tanto, ¿cuántas piezas y de qué colores, sea del lado izquierdo o del derecho, se deben producir para poder lograr la cantidad plena de combinaciones sin repetición? El siguiente subtema analiza este punto.

## Combinaciones sin Permutación Aplicadas al Prototipo

| Colores/Diseños | Combinaciones |
|------------------|---------------|
| 1               | 0             |
| 2               | 1             |
| 3               | 3             |
| 4               | 6             |
| 5               | 10            |
| 6               | 15            |
| 7               | 21            |
| 8               | 28            |
| 9               | 36            |
| 10              | 45            |
| 11              | 55            |
| 12              | 66            |

**Tabla 1:** Combinaciones sin repetición para diferentes colores y/o diseños.

Ahora, imaginemos que deseamos obtener las 3 combinaciones para 3 colores diferentes. Es un hecho que con 3 piezas de colores y/o diseños diferentes no se pueden lograr las 3 combinaciones posibles sin repetición para dichos colores.

...

## Potenciación y Raíz Cuadrada Aplicada al Prototipo

La cantidad de apariencias posibles sin repetición para un conjunto de prendas con piezas desmontables de 2 piezas es igual al cuadrado de la cantidad del número de piezas que la conforman.

Por ejemplo, si se tienen 2 prendas de vestir bajo este concepto de piezas intercambiables (2 piezas para cada prenda), de 2 colores o diseños para una prenda, los cuales pueden ser: amarillo y blanco, para la primera prenda, y rojo y celeste, para la segunda prenda; entonces, las 4 apariencias posibles diferentes serían:

1. Amarillo y blanco
2. Amarillo y celeste
3. Rojo y blanco
4. Rojo y celeste

...

## Círculo Cromático y Combinaciones Naturales

El principio básico del círculo cromático se basa en los colores primarios rojo, azul y amarillo. De estos, se desprenden los colores secundarios y terciarios. La variación de tonos y matices permite una gama ilimitada de combinaciones, que aplicados en diseños brindan un aspecto visual atrayente y revitalizante.

**Figura 1:** El círculo cromático.

### Clasificaciones de Colores

1. **Colores complementarios:** Están en posición contraria en el círculo de color, tales como el amarillo y el violeta, el naranja y azul. Si se usan juntos producen un gran contraste.
2. **Colores complementarios adyacentes:** Son los colores análogos de su color complementario.
3. **Tríada de colores:** Se obtiene al combinar tres colores cuando sus tonos se encuentran a igual distancia en el círculo cromático.

...

## Inspiración en la Naturaleza

Relacionado con el hallazgo mencionado anteriormente acerca de las combinaciones de colores en la naturaleza basadas en el círculo cromático, se tienen los siguientes casos:

- **Figura 6:** Carraca lila, diseño inspirado en los colores del plumaje del ave Carraca lila.
- **Figura 7:** Guardabarranco, diseño inspirado en los colores del plumaje del Guardabarranco.
- **Figura 8:** Diamante de Gould, diseño inspirado en los colores del plumaje del Diamante de Gould.

## Conclusión

Una idea que he tenido es diseñar algoritmos en Python para generar combinaciones de colores que tengan en cuenta este y otros patrones de la naturaleza. Con estas combinaciones se tienen los elementos necesarios que se pueden usar de base para generar combinaciones armoniosas y de buen gusto en prendas de vestir que usen mi concepto de piezas armables tipo rompecabezas. De hecho, la marca que tengo pensada para mi proyecto es **Puzzle**.