# Registro de cambios — PM/IA

Historial descriptivo del curso. La publicación sigue la rama `main` del repositorio [cecil-tst/curso-pm-ia](https://github.com/cecil-tst/curso-pm-ia), conectada automáticamente con Vercel.

## V5.7 — Filtros plegados, desplegable uniforme y plegado contextual (2026-11-13)

- «Búsqueda y filtros» aparece **cerrado al abrir el menú de móvil/tableta**, con apertura voluntaria.
- Selector de idioma armonizado con búsqueda/filtros: tarjeta de igual altura, tipografía, flecha y tonos de fondo.
- Barra flotante de progreso más ancha, centrada verticalmente; Menú y Herramientas con menor separación.
- «Plegar todo» solo se muestra si hay módulos de contenido o recursos reutilizables **efectivamente abiertos**. Se coloca aislado en el margen inferior izquierdo con icono de cheurones convergentes.
- El plegado ya no ejecuta `scrollIntoView`; intenta conservar la posición vertical, dentro de los límites de la altura del documento.
- Sin cambios en lecciones, PDFs, datos de usuario, tarjetas sociales ni versión de escritorio.

## V5.6 — Controles flotantes ordenados y aviso en flujo (2026-11-13)

- El botón Herramientas utiliza una **llave inglesa** en lugar de deslizadores.
- Fila flotante en dispositivos compactos: **progreso X / 9 → plegar todo → herramientas → menú**, manteniendo el menú al extremo derecho.
- Barra de progreso de **anchura compacta**, integrada en la misma fila flotante.
- El aviso «Selecciona el texto que quieras destacar…» se sitúa antes del itinerario y deja de ser flotante, sin duplicarse.
- La distribución se adapta a teléfonos estrechos, móviles horizontales, tabletas verticales y escritorio.
- No se alteran datos de progreso, anotaciones, PDFs ni metadatos Open Graph.

## V5.5 — Navegación responsive y progreso compacto (2026-11-13)

- Nueva interfaz para teléfonos en ambas orientaciones y tabletas en vertical: portada inmediata tras logotipo y lema.
- Dos botones flotantes siempre visibles: **Menú** (idioma, filtros, navegación) y **Herramientas** (uso, cuaderno y notas), con paneles a pantalla completa, escape y navegación con teclado.
- Botón flotante **Plegar todo**, representado con dos cheurones convergentes, que aparece al alcanzar el itinerario formativo.
- Progreso compacto **X / 9 módulos**, barra de avance fijada encima del itinerario durante el desplazamiento.
- Autoría y versión v5.5 reubicadas en el footer de los dispositivos compactos.
- Flecha del selector de idioma más grande, incluidos los escritorios.
- Preservados los contenidos, los tres PDFs, las anotaciones, las imágenes sociales y los estados guardados.

## V5.4 — Lectura más cómoda y menos información simultánea

- Aumento de la tipografía general y del texto de lección a 18 px (17 px en móvil).
- Los tres paneles de la columna derecha se abren a demanda y empiezan cerrados.
- Selector de idiomas trasladado a la parte superior derecha, con información en un botón ⓘ accesible por clic y hover.
- Navegación izquierda agrupada en «Itinerario formativo» y «Recursos reutilizables», ambas secciones plegadas al comenzar.
- Lema bajo el logo y versión de interfaz en el pie del menú izquierdo.
- Aplicado en español, inglés y catalán; sin alteraciones en PDFs, progreso ni anotaciones.

## 2026-11-10 — Actualización de documentación

- Se actualiza `README.md` para reflejar exactamente el estado publicado.
- Se añade este `CHANGELOG.md` para conservar la trazabilidad de versiones.
- **Sin cambios** en HTML, PDF, imágenes, favicon o anotaciones.

## V5.3 — Compartir enlaces e identidad visual

**Commit:** [707d8978](https://github.com/cecil-tst/curso-pm-ia/commit/707d8978a19705c2be51cdf77a94de68b0173ffb)

- Nuevas tarjetas Open Graph para **español, inglés y catalán** (`assets/og-es.jpg`, `og-en.jpg`, `og-ca.jpg`).
- Títulos y descripciones de las páginas corregidos y traducidos, sin fragmentos de código en las vistas previas.
- Metadatos canónicos, Open Graph y Twitter Card para compartir enlaces.
- Favicon definitivo: **cuadro verde con «P+»**, en formatos ICO, PNG y Apple Touch Icon.
- PDFs y datos de usuario intactos.

## V5.2 — Selector de idioma sin banderas

**Commit:** [dd5e3a4e](https://github.com/cecil-tst/curso-pm-ia/commit/dd5e3a4e436247102d2cd2cfdb3175a05dd3151c)

- Retiradas todas las banderas del selector; se mantienen las opciones «Español», «English» y «Català».
- Sin cambios en los tres PDFs ni en el cuaderno de notas.

## V5.1 — Destacados globales entre idiomas

**Commit:** [1c6c60ff](https://github.com/cecil-tst/curso-pm-ia/commit/1c6c60ff406d658563059e2ecb6fc12b5e579bd2)

- Los destacados y los comentarios pasan a ser globales entre los tres idiomas **dentro del mismo navegador**.
- Migración de notas locales anteriores, con conservación de la selección exacta en el idioma original.
- Las traducciones muestran la frase correspondiente completa; el comentario del lector no se traduce.

## V5 — Curso trilingüe

**Commit:** [aab39e9d](https://github.com/cecil-tst/curso-pm-ia/commit/aab39e9d018d6c0c19a9c0e7cb8e735feae1bb0c)

- Publicadas las versiones completas en español, inglés y catalán.
- Tres PDFs de 19 páginas, un PDF integrado en cada HTML.
- Contenidos, microprácticas, prompts, navegación y glosario traducidos.

## V4.2 — Niveles y filtro de progreso

**Commit:** [bd159f96](https://github.com/cecil-tst/curso-pm-ia/commit/bd159f9608b47dd2e1f39322d5b68c0bc9a49fff)

- Filtro «Progreso» separado de «Nivel».
- Niveles **Esencial**, **Avanzado** y **Técnico**.
- Mantenimiento de los identificadores de lección para preservar el progreso guardado.

## V4.1 — Primera versión publicada

**Commit:** [1830d3e4](https://github.com/cecil-tst/curso-pm-ia/commit/1830d3e42795fa691dd821e6e3a82a8c070decb8)

- Publicación del curso interactivo y su PDF integrado en GitHub + Vercel.
- Autoría atribuida a Cecil Servan y referencia a las siete fuentes de Javier Garzás.
