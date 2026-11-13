# PM/IA — Project & Product Management con IA

**Curso interactivo trilingüe** creado por **Cecil Servan**, a partir de **7 vídeos públicos de Javier Garzás**. Los vídeos originales se mantienen en español.

**Producción:** https://curso-pm-ia.vercel.app  
**Código:** https://github.com/cecil-tst/curso-pm-ia  
**Hosting:** Vercel, desplegado automáticamente desde la rama `main`.

## Idiomas y enlaces públicos

| Idioma | Página | PDF |
| --- | --- | --- |
| Español | [Inicio](https://curso-pm-ia.vercel.app/) · [`index.html`](index.html) | [PDF ES](Curso_PM_IA_formacion_es_v5.pdf) |
| English | [English course](https://curso-pm-ia.vercel.app/en.html) · [`en.html`](en.html) | [PDF EN](Curso_PM_IA_formacion_en_v5.pdf) |
| Català | [Curs en català](https://curso-pm-ia.vercel.app/ca.html) · [`ca.html`](ca.html) | [PDF CA](Curso_PM_IA_formacion_ca_v5.pdf) |

El selector de idioma muestra **solo nombres** («Español», «English», «Català»), **sin banderas**.

## Interfaz v5.7 — Refinamientos responsive

En móvil (vertical y horizontal) y tableta vertical, el menú de pantalla completa ahora muestra **«Búsqueda y filtros» plegado al abrirse**, incluso si el lector lo había abierto antes. El selector de idioma tiene tipografía, altura de tarjeta y tamaño de flecha alineados con el panel de búsqueda y filtros.

La barra de progreso flotante es **más ancha y está centrada verticalmente**. El botón de Herramientas (llave inglesa) queda más próximo al de Menú, que sigue situado en el extremo derecho.

El botón **Plegar todo** usa dos cheurones orientados hacia el centro, ligeramente separados, con el mismo color y grosor de trazo que la llave inglesa de Herramientas. Comparte la fila flotante y se coloca **inmediatamente a la izquierda del progreso**, seguido de Herramientas y Menú. Solo aparece cuando hay algún módulo de contenido o sección de navegación desplegada y, al activarlo, cierra esos elementos **sin desplazar deliberadamente la lectura al comienzo**. Si el contenido se acorta, el navegador puede limitar la posición vertical al final disponible.

No cambia ningún contenido formativo, PDF, anotación compartida, metadato social ni favicon. El diseño de escritorio se conserva.

## Interfaz v5.6 — Barra compacta y aviso de destacados

En móviles de ambas orientaciones y tabletas verticales, los elementos flotantes aparecen **en una única fila, de izquierda a derecha**:

1. Barra pequeña de progreso **X / 9 módulos**.
2. **Plegar todo**, cuando se alcanza el itinerario.
3. **Herramientas** con icono de **llave inglesa**.
4. **Menú**, situado en el extremo derecho.

El bloque de ayuda **«Selecciona el texto que quieras destacar…»** aparece entre la portada y el itinerario, **dentro del flujo de la página y sin posición flotante**. En escritorio permanece en su ubicación anterior, junto a las opciones de búsqueda y filtros.

Esta versión conserva las lecciones, los filtros, los comentarios y destacados compartidos, las descargas PDF y las imágenes de vista previa.

## Interfaz v5.5 — Experiencia móvil y tableta vertical

En **móvil (vertical y horizontal) y tableta en vertical** la portada empieza inmediatamente después del logotipo y «Aprender · Construir · Verificar». Se ocultan las columnas laterales y los controles originales se trasladan sin duplicarse a dos paneles de **pantalla completa**:

- **Menú** (icono de lista): selección de idioma, búsqueda/filtros e itinerario de navegación.
- **Herramientas** (icono de deslizadores): «Cómo usar este curso», «Tu cuaderno» y «Mis notas».
- **Plegar todo** (icono de cheurones convergentes): aparece al desplazarse hasta el itinerario y contrae los módulos, sin texto junto al icono.
- **Tu progreso**: barra compacta y contador **módulos completados / 9**, situada inmediatamente encima del itinerario y fijada durante el desplazamiento.
- **Pie de página**: autoría, fuentes y **versión de interfaz v5.5** al final del contenido.
- **Idioma**: flecha del desplegable ampliada en todas las pantallas.

En **escritorio** se conserva la disposición de tres columnas de la v5.4. Se mantienen los mismos datos de progreso, destacados globales, los tres PDF y los metadatos para compartir.

## Interfaz v5.4 — Legibilidad y navegación

Esta versión incorpora las primeras mejoras de experiencia de lectura solicitadas por los participantes:

- **Textos significativamente más grandes** en lectura, navegación, botones y paneles; contenido principal a **18 px** en escritorio y **17 px** en móvil.
- **Panel derecho simplificado:** «Cómo usar este curso», «Tu cuaderno» y «Mis notas» son desplegables **cerrados por defecto**.
- **Selector de idioma arriba a la derecha**, siempre visible, sin etiqueta redundante ni banderas; el icono **ⓘ** revela la explicación al pasar el cursor o pulsar.
- **Menú izquierdo reorganizado:** «Itinerario formativo» y «Recursos reutilizables» son desplegables independientes y cerrados inicialmente; el segundo agrupa prompts, glosario, guías, lista de verificación y fuentes.
- «Aprender · Construir · Verificar» aparece inmediatamente **debajo del logotipo**.
- La **versión visible al final del menú izquierdo** es `v5.4`.
- Se conserva la misma estructura de **36 lecciones**, los PDF, los enlaces temporales, el cuaderno global de destacados y los metadatos Open Graph.

## Contenidos y características

- **9 módulos**, **36 lecciones**, **59 enlaces a momentos concretos** de los vídeos originales y **29 términos** de glosario.
- Tres niveles de dificultad: **Esencial (27)**, **Avanzado (5)** y **Técnico (4)**.
- Filtros por tema, nivel y progreso, más navegación y búsqueda.
- Microprácticas, prompts, enlaces a vídeos, cuaderno de notas y descarga del PDF en cada idioma.
- Cada HTML incorpora su PDF, de modo que también se puede abrir por separado sin backend.

## Imágenes y metadatos para compartir

Las tres páginas contienen **`<title>`**, descripción, URL canónica, etiquetas **Open Graph** y **Twitter Card**, con texto fijo en su idioma. No dependen de JavaScript para que los robots de WhatsApp y redes sociales los lean correctamente.

| Idioma | Imagen de vista previa |
| --- | --- |
| Español | [`assets/og-es.jpg`](assets/og-es.jpg) |
| English | [`assets/og-en.jpg`](assets/og-en.jpg) |
| Català | [`assets/og-ca.jpg`](assets/og-ca.jpg) |

Las tres tarjetas tienen formato **1200 × 630** y utilizan la identidad gráfica **P+ PM/IA**.

Iconos del sitio, con **solo el cuadro verde y «P+»**, sin adornos:

- [`assets/favicon.ico`](assets/favicon.ico)
- [`assets/favicon.png`](assets/favicon.png)
- [`assets/apple-touch-icon.png`](assets/apple-touch-icon.png)

**Nota sobre cachés:** WhatsApp y otras plataformas pueden conservar metadatos anteriores de una misma URL. Si persiste una vista previa antigua, se puede probar el mismo enlace con un parámetro de versión, por ejemplo `?v=3`. Esto no cambia el contenido del curso.

## Progreso, destacados y comentarios

El progreso, los destacados y los comentarios están **compartidos entre los tres idiomas en el mismo navegador**, mediante `localStorage` del dominio.

- Las anotaciones existentes de las tres versiones se **migran y fusionan** en un cuaderno común.
- El destacado conserva la **selección exacta en el idioma original**; en otras traducciones se destaca la **frase correspondiente completa** para evitar desajustes por longitud del texto.
- Los comentarios no se traducen automáticamente.
- Se pueden exportar anotaciones a Markdown o PDF y hacer/restaurar copias de seguridad en JSON, incluidas las anteriores compatibles.

**Privacidad y límites:** no hay cuentas ni servidor de notas; no existe sincronización entre navegadores, dispositivos o usuarios. Cada lector conserva sus datos en su propio navegador y debe exportarlos si desea respaldarlos.

## Desarrollo y despliegue

La aplicación es **HTML, CSS y JavaScript estáticos**, sin build ni instalación de dependencias. Vercel está conectado con GitHub:

1. Los cambios de código se registran en GitHub.
2. Cada commit en **`main`** activa un despliegue de **producción** en Vercel.
3. La misma URL pública sirve la nueva versión, sin reemplazos manuales.

Los PDFs y las imágenes están incluidos en este repositorio. Los cambios en archivos Markdown también disparan un despliegue, aunque no modifiquen el comportamiento de la aplicación.

Historial de versiones y cambios: [`CHANGELOG.md`](CHANGELOG.md).

---

© Cecil Servan. Curso elaborado a partir de vídeos públicos de Javier Garzás; consulta los enlaces a los originales dentro de cada lección.
