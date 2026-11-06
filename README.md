#Tic2- Practica1
Práctica 01 de TIC II (2.ºA  Bachillerato). 

##Objetivo y opciones
Web para comparar tres grados universitarios:
-Doble Grado en Matemáticas e Ingeniería Informática (USC, Santiago o US/UCA)
-Grado en Ingeniería en Tecnologías Industriales (UDC, Ferrol o US/UCA)
-Grado en Ingeniería Naval y Oceánica (UDC, Ferrol o US/UCA)

##Estructura y cómo abrirla
-index.html: presentación y tres tarjetas, una por grado.
-opciones.html: tabla comparativa.
-salidas.html: salidas profesionales y conclusión.
-css/estilos.css: mis estilos.
-img/: imágenes.
Se abre con **index.html** en el navegador. Y está en el servidor de salescoruna.ddns.net

##Bootstrap
Versión 5.3.8, en las tres páginas.
Bootstrap me da las tarjetas, los botones, el menú y los acordeones. Yo he hecho el contenido, la tabla y mi CSS.

##Fuentes (fecha de consulta)
USC, doble grado: https://www.usc.gal/es/estudios/grados/ingenieria-arquitectura/doble-grado-ingenieria-informatica-matematicas-2a-edicion ([fecha])
[segunda fuente oficial USC] (27/10/2026)
UDC, Tecnologías Industriales: https://www.udc.gal/es/centros_departamentos_servizos/departamentos/departamento/?codigo=D117 ([fecha])
[segunda fuente oficial Tecnologías Industriales] (27/10/2026)
UDC, Naval y Oceánica: https://www.udc.gal/es/centros_departamentos_servizos/centros/centro/?codigo=632 ((27/10/2026))
UDC, notas de corte: https://www.udc.gal/export/sites/udc/futuros_estudantes/_galeria_down/notas-corte.pdf_2063069294.pdf (4/11/2026)

##Imágenes


| Imagen | Autor | Enlace |
|---|---|---|
| carrera1.jpg |Ceu San pablo | https://www.uspceu.com/en/academic-programs/degree/mathematical-engineering-data-science-and-engineering | 
| carrera2.jpg |UNIR|https://www.unir.net/revista/ingenieria/ingenieria-industrial/ |
| carrera3.jpg |JackF| stock.adobe.com |



##Tres decisiones técnicas
**HTML**: hice la comparación con una tabla con caption, thead, tbody y th scope, para que se entienda qué dato corresponde a cada grado.
**CSS**: enlacé estilos.css después de Bootstrap para poder cambiar sus estilos sin tocar sus archivos. Por ejemplo, la clase .salida cambia la letra y el fondo de los títulos de cada salida.
**Bootstrap**: usé acordeones para las asignaturas, porque cada grado tiene muchos cursos y asignaturas por semestre. 

##Un error que corregí
Los acordeones de la tabla tenían todos el mismo id, y al abrir uno se abrían todos. Bootstrap enlaza cada botón con su panel por el id, y si se repite actúa sobre todos. Lo arreglé poniendo un id distinto a cada panel (flush-collapseC11, C12...).

##Ayudas
Apuntes de clase ,código de Bootstrap (https://getbootstrap.com/docs/5.3/getting-started/introduction/) y etiquetas y su uso de (https://www.w3schools.com/css/). 

 
