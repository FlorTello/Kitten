# Kitten Flexbox scrset & medias queries

Esta lección consiste en aplicar el display: flex,srcset y medias y lograr el objetivo de la pagina  [website](https://flortello.github.io/Leccion32-Kitten/).

Para ello usamos flexbox para la maquetación.Se piden las siguientes funcionalidades:
- Cuando la pagina se encuentra en un tamaño pequeño entonces la pagina mostrara en un fondo de noche y un gatito durmiendo .
- Cuando la pagina empice a crecer y se mostrará el fondo de un amanecer y gatito estará despertando
- Para el último caso cuando la pantalla tenga un ancho mayor a aprox. 1100px se mostrar un fondo con sol radiante y el gatito feliz.

## Funcionalidades en J
------------------------

### Function scroll.
 Esta función se encarga de hacer cambios de acuerdo al evento scroll, así si colocamos la section about, en el navegador este "boton" cambiará de background-color y color de texto. A continuación la función:

</pre>
   </td>
   <td class="get">
<css>
body {
    font: 75% georgia, sans-serif;
    color: #555753;
    background: #fff;
    margin: 0;
    padding: 5px;
}

### Funcionalidad del modal.
 Esta función llama al modal que se encuentra oculto y utiliza el target para detectar quien es el objetivo de esta llamada, en este caso sera su "nextElementSibling" (hermano en el DOM).

![function del modal](assets/images/modal.png)

### Function de validación.
Esta función se encarga de validar el correcto llenado del formulario, de estar completo se vaciaran los casilleros. Se usan los eventos keypress, blur y click. Se muestra por partes cada una las funciones a continuación:

![function validar](assets/images/validar.png)

Como se ve en el navegador:

![function validar en el navegador](assets/images/validado.png)


![function letras](assets/images/letras.png)


![function correo](assets/images/correo.png)


![function numeros](assets/images/numeros.png)


![function validar todo al click](assets/images/validaTodo.png)
