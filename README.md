# Tic2 - Práctica 1

Práctica 01 de TIC II (2.º A Bachillerato).

Entrenamiento de HTML, CSS y Bootstrap con el propósito de que investiguemos sobre las salidas profesionales (en mi caso 3 carreras) que nos interesan para poder informarnos sobre ellas.

## Objetivo y opciones

Web para comparar tres grados universitarios:

1. Doble Grado en Matemáticas e Ingeniería Informática (USC, Santiago o US/UCA).
2. Grado en Ingeniería en Tecnologías Industriales (UDC, Ferrol o US/UCA).
3. Grado en Ingeniería Naval y Oceánica (UDC, Ferrol o US/UCA).

## Estructura y contenidos

- `index.html`: presentación y tres tarjetas, una por grado.
- `opciones.html`: tabla comparativa.
- `salidas.html`: salidas profesionales y conclusión.
- `css/estilos.css`: mis estilos.
- `img/`: imágenes.

Se abre con `index.html` en el navegador. Y está en el servidor de `salescoruna.ddns.net`.

Entre las diferentes páginas existe un menú en la parte superior que te reconduce de manera directa a cada una de ellas.

## Bootstrap

Versión 5.3.8, en las tres páginas.

Bootstrap me da las tarjetas, los botones, el menú y los acordeones. Yo he hecho el contenido, la tabla y mi CSS.

## Fuentes

1. USC, Doble Grado en Matemáticas e Ingeniería Informática: [https://www.usc.gal/es/estudios/grados/ingenieria-arquitectura/doble-grado-ingenieria-informatica-matematicas-2a-edicion](https://www.usc.gal/es/estudios/grados/ingenieria-arquitectura/doble-grado-ingenieria-informatica-matematicas-2a-edicion)

2. Consejo General de Colegios Oficiales de Ingenieros Industriales: [https://www.google.com/goto?url=CAESXwHEIkXXFi-0TWRSaH1h2DT6Ur1c0eoMigWTe-TonjyKYG1mVXlEyjTYs8BfNnvLyIITsVWs50Z5kYa4D80H1W6CSgzWsvHjb2tWxl5mrzAw7LkT1M3CvbQa2eqARn4O](https://www.google.com/goto?url=CAESXwHEIkXXFi-0TWRSaH1h2DT6Ur1c0eoMigWTe-TonjyKYG1mVXlEyjTYs8BfNnvLyIITsVWs50Z5kYa4D80H1W6CSgzWsvHjb2tWxl5mrzAw7LkT1M3CvbQa2eqARn4O) (4/11/2026).

3. UDC, Ingeniería en Tecnologías Industriales: [https://www.udc.gal/es/centros_departamentos_servizos/departamentos/departamento/?codigo=D117](https://www.udc.gal/es/centros_departamentos_servizos/departamentos/departamento/?codigo=D117) (30/10/2026).

4. UDC, Naval y Oceánica: [https://www.udc.gal/es/centros_departamentos_servizos/centros/centro/?codigo=632](https://www.udc.gal/es/centros_departamentos_servizos/centros/centro/?codigo=632) (30/10/2026).

5. Colegio Oficial de Ingenieros Navales y Oceánicos (COIN): [https://www.seio.es](https://www.seio.es) (4/11/2026).

6. UDC, notas de corte: [https://www.udc.gal/export/sites/udc/futuros_estudantes/_galeria_down/notas-corte.pdf_2063069294.pdf](https://www.udc.gal/export/sites/udc/futuros_estudantes/_galeria_down/notas-corte.pdf_2063069294.pdf) (4/11/2026).

## Imágenes

| **Imagen** | **Autor** | **Enlace** |
|---|---|---|
| carrera1.jpg | Ceu San Pablo | [Enlace](https://www.uspceu.com/en/academic-programs/degree/mathematical-engineering-data-science-and-engineering) |
| carrera2.jpg | UNIR | [Enlace](https://www.unir.net/revista/ingenieria/ingenieria-industrial/) |
| carrera3.jpg | JackF | stock.adobe.com |

## Tres decisiones técnicas

- **HTML:** hice la comparación con una tabla con `caption`, `thead`, `tbody` y `th scope`, para que se entienda qué dato corresponde a cada grado.
- **CSS:** enlacé `estilos.css` después de Bootstrap para poder cambiar sus estilos sin tocar sus archivos. Por ejemplo, la clase `.salida` cambia la letra y el fondo de los títulos de cada salida.
- **Bootstrap:** usé acordeones para las asignaturas, porque cada grado tiene muchos cursos y asignaturas por semestre.

## Un error que corregí

Los acordeones de la tabla tenían todos el mismo `id`, y al abrir uno se abrían todos. Bootstrap enlaza cada botón con su panel por el `id`, y si se repite actúa sobre todos. Lo arreglé poniendo un `id` distinto a cada panel (`flush-collapseC11`, `C12`...).

## Ayudas

Apuntes de clase, código de Bootstrap ([https://getbootstrap.com/docs/5.3/getting-started/introduction/](https://getbootstrap.com/docs/5.3/getting-started/introduction/)) y etiquetas y su uso de ([https://www.w3schools.com/css/](https://www.w3schools.com/css/)).

Ayuda con la estructura del Read me: [https://claude.ai](https://claude.ai).

## Autores

Martina Martínez Porto – 2.º A BACH Salesianos A Coruña.