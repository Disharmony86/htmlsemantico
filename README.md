README

M1. Actividad de aprendizaje para RA1
Implementación de una página HTML5 básica siguiendo buenas prácticas de semántica y accesibilidad

Esta página corresponde a una presentación personal y utiliza estilos CSS.
El propósito principal es demostrar cómo, al diseñar una estructura web moderna, podemos aplicar etiquetas semánticas de HTML5 para mejorar la organización del contenido y reforzar las buenas prácticas de accesibilidad.

El uso de etiquetas como main, article, header, footer, section permite establecer una estructura más clara y comprensible tanto para los usuarios como para los navegadores y tecnologías asistivas. Gracias a ello, se reduce la necesidad de depender excesivamente de atributos ARIA-label, ya que el propio HTML semántico cumple la función de describir la intención de cada bloque.

Los atributos ARIA son útiles para complementar información cuando la semántica no es suficiente; sin embargo, una buena estructura semántica disminuye su uso innecesario y favorece una accesibilidad más limpia.

Uso de header para el título principal:

Se empleó esta etiqueta para identificar de forma inmediata el encabezado de la página. Esto le indica a los lectores de pantalla y a los navegadores que este bloque contiene información introductoria o relevante para el contenido global.

Incorporación de main como contenedor del contenido central:

main permite separar visual y semánticamente la información más importante del documento. Esto mejora la navegación para usuarios que utilizan tecnologías asistivas y facilita la lectura estructural del HTML.

División del contenido en section y article:

Cada sección agrupa información relacionada y facilita futuras expansiones del documento.

section se utilizó para delimitar bloques temáticos.

article se reservó para contenido que tiene sentido por sí mismo, como descripciones o bloques de texto que podrían ser reutilizados o referenciados de forma independiente.

Uso de footer para la información complementaria:
Esta etiqueta define claramente la parte final del documento, donde se podría incluir autoría, enlaces de contacto o créditos, manteniendo una organización natural del flujo del contenido.

Reducción del uso de atributos ARIA innecesarios:
Se optó por priorizar etiquetas semánticas para evitar depender de atributos ARIA cuando no son requeridos. Los elementos semánticos ya comunican su propósito, mejorando la accesibilidad sin sobrecargar el código.

Estructura simple y limpia para facilitar el mantenimiento:
La página fue diseñada evitando etiquetas redundantes o estructuras anidadas innecesariamente. Esto hace el código más legible, más fácil de mantener y adecuado para un aprendizaje sólido de buenas prácticas.

Para concluir, se realizaron validaciones en https://validator.w3.org/ con el fin de localizar errores semanticos o de sintaxis, se realizaron las correcciones oportunamente.

Instrucciones para visualizar la página: 

OPCION 1:

1. Localiza el archivo index.html.

2. Haz clic derecho sobre él.

3. Selecciona Abrir con… y elige el navegador de tu preferencia.

OPCION 2:

1. Visita la pagina en Github Pages:

https://disharmony86.github.io/htmlsemantico/

Gracias!