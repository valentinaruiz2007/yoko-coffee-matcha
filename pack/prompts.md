# Prompts

## Prompt 01 · Identidad

**Tarea:** Aplicar únicamente la paleta, tipografías, bordes, esquinas, sombra, ancho máximo y animación definidos en el brief.
**Datos:** brief, secciones 3, 4, 5 y 6.
**Archivos:** los archivos de estilos, configuración de identidad y carga de fuentes que existan en la plantilla (Cline debe identificar los nombres reales antes de editar).
**Terminado cuando:**
- Los colores, fuentes y demás tokens coinciden exactamente con el brief.
- No se agregan decisiones no aprobadas; si hay `POR DEFINIR`, detenerse y preguntar.
- Se ve bien a 360, 768 y 1280 px, sin scroll horizontal.
- `npm run verificar` termina sin errores.

## Prompt 02 · Marco

**Tarea:** Configurar datos del sitio y navegación, crear las cuatro páginas del mapa y retirar los componentes de ejemplo de Inicio.
**Datos:** brief, secciones 1, 7, 8 y 10.
**Archivos:** configuración del sitio y componentes de layout, menú y pie de página existentes; `src/pages/index.astro`, `src/pages/menu.astro`, `src/pages/nosotros.astro`, `src/pages/contacto.astro`; eliminar los ejemplos `src/components/inicio/Portada.astro`, `Comprobacion.astro`, `Pasos.astro` si son los de la plantilla.
**Terminado cuando:**
- El menú muestra Inicio, Menú, Nosotros y Contacto y enlaza a las cuatro páginas.
- Se retiran los componentes de muestra y cada página tiene su título de pestaña aprobado.
- No se inventan logo, redes, pie ni encabezado fijo: si no están definidos, detenerse y preguntar.
- Se ve bien a 360, 768 y 1280 px, sin scroll horizontal.
- `npm run verificar` termina sin errores.

## Prompt 03 · Inicio · Portada

**Tarea:** Construir únicamente la sección Portada de la página Inicio, usando el contenido aprobado del brief.
**Datos:** brief, sección 9, Página Inicio, Sección Portada.
**Archivos:** `src/components/inicio/Portada.astro` (crear), `src/pages/index.astro` (modificar para integrar la sección).
**Disposición:** celular: título, texto e imagen apilados / computadora: texto a la izquierda e imagen a la derecha.
**Referencia:** ninguna.
**Terminado cuando:**
- La sección se muestra en su página y sigue el orden previsto.
- Los textos e imágenes corresponden a rutas y datos aprobados del brief; no completar `POR DEFINIR` mediante suposiciones.
- Se ve bien a 360, 768 y 1280 px, sin scroll horizontal.
- `npm run verificar` termina sin errores.

## Prompt 04 · Inicio · Nuestras especialidades

**Tarea:** Construir únicamente la sección Nuestras especialidades de la página Inicio, usando el contenido aprobado del brief.
**Datos:** brief, sección 9, Página Inicio, Sección Nuestras especialidades.
**Archivos:** `src/components/inicio/NuestrasEspecialidades.astro` (crear), `src/pages/index.astro` (modificar para integrar la sección).
**Disposición:** celular: tarjetas apiladas / computadora: tarjetas en fila o cuadrícula.
**Referencia:** 1a.
**Terminado cuando:**
- La sección se muestra en su página y sigue el orden previsto.
- Los textos e imágenes corresponden a rutas y datos aprobados del brief; no completar `POR DEFINIR` mediante suposiciones.
- Se ve bien a 360, 768 y 1280 px, sin scroll horizontal.
- `npm run verificar` termina sin errores.

## Prompt 05 · Inicio · Bebidas destacadas

**Tarea:** Construir únicamente la sección Bebidas destacadas de la página Inicio, usando el contenido aprobado del brief.
**Datos:** brief, sección 9, Página Inicio, Sección Bebidas destacadas.
**Archivos:** `src/components/inicio/BebidasDestacadas.astro` (crear), `src/pages/index.astro` (modificar para integrar la sección).
**Disposición:** celular: tarjetas apiladas / computadora: cuadrícula de tarjetas.
**Referencia:** ninguna.
**Terminado cuando:**
- La sección se muestra en su página y sigue el orden previsto.
- Los textos e imágenes corresponden a rutas y datos aprobados del brief; no completar `POR DEFINIR` mediante suposiciones.
- Se ve bien a 360, 768 y 1280 px, sin scroll horizontal.
- `npm run verificar` termina sin errores.

## Prompt 06 · Menú · Nuestra carta

**Tarea:** Construir únicamente la sección Nuestra carta de la página Menú, usando el contenido aprobado del brief.
**Datos:** brief, sección 9, Página Menú, Sección Nuestra carta.
**Archivos:** `src/components/menu/NuestraCarta.astro` (crear), `src/pages/menu.astro` (modificar para integrar la sección).
**Disposición:** celular: título y categorías apilados / computadora: categorías sobre cuadrícula.
**Referencia:** 2a.
**Terminado cuando:**
- La sección se muestra en su página y sigue el orden previsto.
- Los textos e imágenes corresponden a rutas y datos aprobados del brief; no completar `POR DEFINIR` mediante suposiciones.
- Se ve bien a 360, 768 y 1280 px, sin scroll horizontal.
- `npm run verificar` termina sin errores.

## Prompt 07 · Menú · Productos

**Tarea:** Construir únicamente la sección Productos de la página Menú, usando el contenido aprobado del brief.
**Datos:** brief, sección 9, Página Menú, Sección Productos.
**Archivos:** `src/components/menu/Productos.astro` (crear), `src/pages/menu.astro` (modificar para integrar la sección).
**Disposición:** celular: tarjetas apiladas / computadora: cuadrícula.
**Referencia:** 2b.
**Terminado cuando:**
- La sección se muestra en su página y sigue el orden previsto.
- Los textos e imágenes corresponden a rutas y datos aprobados del brief; no completar `POR DEFINIR` mediante suposiciones.
- Se ve bien a 360, 768 y 1280 px, sin scroll horizontal.
- `npm run verificar` termina sin errores.

## Prompt 08 · Nosotros · Nuestra esencia

**Tarea:** Construir únicamente la sección Nuestra esencia de la página Nosotros, usando el contenido aprobado del brief.
**Datos:** brief, sección 9, Página Nosotros, Sección Nuestra esencia.
**Archivos:** `src/components/nosotros/NuestraEsencia.astro` (crear), `src/pages/nosotros.astro` (modificar para integrar la sección).
**Disposición:** celular: título, texto y fotos apilados / computadora: texto a la izquierda y fotos a la derecha.
**Referencia:** 1b.
**Terminado cuando:**
- La sección se muestra en su página y sigue el orden previsto.
- Los textos e imágenes corresponden a rutas y datos aprobados del brief; no completar `POR DEFINIR` mediante suposiciones.
- Se ve bien a 360, 768 y 1280 px, sin scroll horizontal.
- `npm run verificar` termina sin errores.

## Prompt 09 · Contacto · Encuéntranos

**Tarea:** Construir únicamente la sección Encuéntranos de la página Contacto, usando el contenido aprobado del brief.
**Datos:** brief, sección 9, Página Contacto, Sección Encuéntranos.
**Archivos:** `src/components/contacto/Encuentranos.astro` (crear), `src/pages/contacto.astro` (modificar para integrar la sección).
**Disposición:** celular: contenidos apilados / computadora: texto y datos a la izquierda, imagen a la derecha.
**Referencia:** ninguna.
**Terminado cuando:**
- La sección se muestra en su página y sigue el orden previsto.
- Los textos e imágenes corresponden a rutas y datos aprobados del brief; no completar `POR DEFINIR` mediante suposiciones.
- Se ve bien a 360, 768 y 1280 px, sin scroll horizontal.
- `npm run verificar` termina sin errores.

## Prompt 10 · Contacto · Contacto y redes

**Tarea:** Construir únicamente la sección Contacto y redes de la página Contacto, usando el contenido aprobado del brief.
**Datos:** brief, sección 9, Página Contacto, Sección Contacto y redes.
**Archivos:** `src/components/contacto/ContactoYRedes.astro` (crear), `src/pages/contacto.astro` (modificar para integrar la sección).
**Disposición:** celular: datos apilados / computadora: bloque de contacto debajo de contenido principal.
**Referencia:** ninguna.
**Terminado cuando:**
- La sección se muestra en su página y sigue el orden previsto.
- Los textos e imágenes corresponden a rutas y datos aprobados del brief; no completar `POR DEFINIR` mediante suposiciones.
- Se ve bien a 360, 768 y 1280 px, sin scroll horizontal.
- `npm run verificar` termina sin errores.

## Prompt 11 · Revisión final

**Tarea:** Comprobar todas las páginas, enlaces, botones, textos alternativos y tamaños de pantalla; corregir solo errores sin añadir contenido nuevo.
**Datos:** brief completo, secciones 1 a 10.
**Archivos:** únicamente los archivos de páginas, componentes y configuración que presenten errores; `CAMBIOS.md` (actualizar registro).
**Terminado cuando:**
- Las cuatro páginas cargan, sus enlaces y botones aprobados funcionan y cada imagen tiene un texto alternativo aprobado.
- No hay contenido de muestra ni información inventada.
- Se ve bien a 360, 768 y 1280 px, sin scroll horizontal.
- `npm run verificar` termina sin errores.
