##TEORIA CSSS
1. VINCULACIÓN CSS
 1.1. Utilizando la etiqueta <style></style>, dentro del body.
 1.2. De manera inline como atributo del elemento.
 1.3. De manera externa mediante un archivo con extensión .css

 2. SINTAXIS CSS

     <h1>
        color:red;
     </h1>

     h1 es el selector
     color es la propiedad
     red es el valor

  3. CONCEPTOS IMPORTANTES DE CSS
    3.1. SELECTORES: Nos indica a que elementos html, se aplicará los estilos.
    3.2. Herencia: Que elementos ancestros heredan algunas propiedades a sus hijos.
    3.3. Cascada: Estilos que vienen en último lugar sobrescriben a los de antes.
    3.4. Especifidad: Es un valor que adquiere los selectores para determinar que regla css va prevalecer.

    Ejemplo

    Selector 1 ... Especifidad 10
    Selector 2 ... Especifidad 50

    NIVEL DE SELECTORES POR ESPECIFIDAD

    Etiqueta  1
    Clases    10
    id        100
    inline    1000
    !important infinito*/

4. USOS DE SELECTORES
    4.1. Selectores de etiqueta: Para normalizar estilos de manera general.
    4.2. Selector de clase: Para realizar estilos en la web.
    4.3. Selector de ID: No se recomienda usar para CSS.
    4.4. INLINE : Sólo para Javascript se usa.


