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
