# Brief de la marca

> **Estudiante:** este archivo lo genera la IA (fase 2) a partir de tu plan aprobado. Revísalo antes de usar Cline: todo lo que dice aquí es lo que se va a construir.
> Si algo dice `POR DEFINIR`, decídelo tú y pídele a la IA que lo actualice.

> **Agente:** este brief es la única fuente de decisiones de diseño y contenido.
> Si un campo que necesitas dice `POR DEFINIR` o está vacío, **detente y pregunta**: no inventes, no busques en otros archivos, no supongas.
> Copia los textos tal cual están escritos (no los reescribas ni "mejores").

## 1. Marca

| Campo | Decisión |
| --- | --- |
| Nombre de la marca | YOKÓ — Coffee & Matcha |
| Tipo | Ficticia. |
| Qué hace, en una frase | YOKÓ es una cafetería y restaurante especializado en café artesanal, bebidas a base de matcha, repostería y opciones gastronómicas para desayunos, brunch y comidas ligeras. |
| Para quién es (público) | YOKÓ está dirigida a un público amplio, principalmente jóvenes, adultos y familias que disfrutan del café, el matcha y la buena gastronomía. Es un espacio pensado para personas que buscan compartir con amigos o familiares, estudiar, trabajar o disfrutar de un momento de tranquilidad, sin restricciones de edad. |
| Personalidad (3 adjetivos) | Moderna. Acogedora. Serena. |
| Eslogan | Un momento de paz en cada taza. |
| Descripción para Google (máx. 155 caracteres) | YOKÓ Coffee & Matcha: café artesanal, matcha, brunch y repostería en un espacio acogedor donde cada taza invita a disfrutar de un momento de paz. |

## 2. Referencias

Qué tomar de cada sitio de referencia (las capturas están en el plan, `pack/plan.pdf`).

| Ref | Sitio | Detalle que tomamos | Dónde se aplica |
| --- | --- | --- | --- |
| 1a | BENCHTIME BAKERY & COFFEE | Una sección que presenta las categorías de panes, pasteles y bebidas mediante fotografías, títulos y descripciones breves. | Página Inicio, sección Nuestras especialidades. |
| 1b | BENCHTIME BAKERY & COFFEE | Una sección informativa que describe la identidad de la cafetería, sus especialidades y su propuesta gastronómica. | Página Nosotros, sección Nuestra esencia. |
| 2a | DIFFLELOVE | Un menú digital que clasifica los productos en bebidas calientes, bebidas frías, lattes, bebidas asiáticas, postres y otras opciones gastronómicas. | Página Menú, sección Nuestra carta. |
| 2b | DIFFLELOVE | Una presentación de productos que incluye fotografías, nombres, descripciones y precios. | Página Menú, sección Productos. |

## 3. Paleta de color

Exactamente estos 7 colores, en hex (`#1a1a1a`). No se agregan otros.
`npm run verificar` exige contraste 4.5:1 o más en: `texto` sobre `fondo` y `superficie`, `texto-suave` sobre `fondo`, `marca-contraste` sobre `marca`.

| Token | Hex | Para qué se usa |
| --- | --- | --- |
| `fondo` | #FAF8F3 | Fondo de toda la página |
| `superficie` | #F1ECE3 | Tarjetas, bloques destacados |
| `texto` | #4B352A | Texto principal |
| `texto-suave` | #7A6557 | Texto secundario, etiquetas |
| `borde` | #D0C8B8 | Líneas y bordes |
| `marca` | #6F8B5E | Color principal: botones, resaltados |
| `marca-contraste` | #FFFFFF | Texto que va encima de `marca` — ADVERTENCIA: contraste 3.80:1, insuficiente para 4.5:1; requiere decisión de la estudiante |

## 4. Tipografías

Archivos (`.woff2`, `.woff`, `.ttf` u `.otf`) en `pack/fuentes/`. Solo fuentes con licencia libre.

| Uso | Nombre de la fuente | Archivo(s) en `pack/fuentes/` | Grosores |
| --- | --- | --- | --- |
| Títulos | Cormorant Garamond | POR DEFINIR (archivo no incluido en el pack aportado) | Regular (400) y Semibold (600) |
| Texto | DM Sans | `pack/fuentes/dm-sans-regular.ttf`, `pack/fuentes/dm-sans-medium.ttf`, `pack/fuentes/dm-sans-bold.ttf` | Regular (400), Medium (500), Bold (700) |

## 5. Forma

| Decisión | Opciones | Decisión |
| --- | --- | --- |
| Esquinas (`radio`) | `0px` recto · `4px` · `8px` · `16px` · `9999px` píldora | `8px` |
| Grosor de borde | `0px` sin borde · `1px` · `2px` · `3px` | `1px` |
| Sombra | `none` · suave `0 4px 12px rgb(0 0 0 / 0.12)` · dura `4px 4px 0 0 <hex de borde>` | POR DEFINIR |
| Ancho máximo del contenido | `max-w-3xl` estrecho · `max-w-5xl` medio · `max-w-7xl` ancho | `max-w-7xl` |

## 6. Animación

| Decisión | Opciones | Decisión |
| --- | --- | --- |
| Intensidad | `ninguna` · `sutil` · `marcada` | `sutil` |

## 7. Logo y menú

| Decisión | Opciones | Decisión |
| --- | --- | --- |
| Logo (archivo en `pack/logos/` + texto alternativo) | o "sin logo, solo nombre" | POR DEFINIR (el pack no tiene archivo de logo; el boceto presenta YOKÓ como texto) |
| Tipo de menú | `barra` (enlaces siempre visibles) · `desplegable` (botón "Menú" en celular y tablet, barra en computadora) · `desplegable-siempre` (botón en todas las pantallas) | `desplegable` |
| Encabezado fijo arriba al bajar | `sí` · `no` | POR DEFINIR |

## 8. Mapa del sitio

| Página | Ruta | Archivo | Texto en el menú | Título de la pestaña |
| --- | --- | --- | --- | --- |
| Inicio | `/` | `src/pages/index.astro` | Inicio | POR DEFINIR |
| Menú | `/menu` | `src/pages/menu.astro` | Menú | POR DEFINIR |
| Nosotros | `/nosotros` | `src/pages/nosotros.astro` | Nosotros | POR DEFINIR |
| Contacto | `/contacto` | `src/pages/contacto.astro` | Contacto | POR DEFINIR |

## 9. Contenido por página

### Página: Inicio (`/`)

#### Sección: Portada

- **id:** portada
- **Título:** Un momento de paz en cada taza.
- **Texto:** Disfruta del café, matcha y momentos especiales en YOKÓ.
- **Elementos** (lista: título + descripción de cada uno, o "ninguno"): Título y texto de presentación.
- **Imágenes** (archivo en `pack/imagenes/` + texto alternativo, o "ninguna"): POR DEFINIR (asignar una de las fotos existentes de `pack/imagenes/` según el boceto)
- **Botones** (texto → destino, o "ninguno"): POR DEFINIR (se aprecia un botón en el boceto, pero el plan no establece texto o destino)
- **Disposición** (celular / computadora): celular: marca y menú arriba; título, texto e imagen de producto en columna; computadora: navegación arriba, título y texto a la izquierda, imagen de bebida a la derecha.
- **Referencia aplicada** (1a, 1b, 2a, 2b o "ninguna"): ninguna

#### Sección: Nuestras especialidades

- **id:** nuestras-especialidades
- **Título:** Nuestras especialidades
- **Texto:** POR DEFINIR
- **Elementos** (lista: título + descripción de cada uno, o "ninguno"): Categorías de café, matcha, brunch y repostería (nombres en página Menú del plan; las descripciones por categoría están POR DEFINIR).
- **Imágenes** (archivo en `pack/imagenes/` + texto alternativo, o "ninguna"): POR DEFINIR (asignar fotos existentes a categorías).
- **Botones** (texto → destino, o "ninguno"): POR DEFINIR
- **Disposición** (celular / computadora): celular: tarjetas de especialidades apiladas; computadora: tarjetas con fotos dispuestas en una fila o cuadrícula, bajo la portada, según el boceto.
- **Referencia aplicada** (1a, 1b, 2a, 2b o "ninguna"): 1a

#### Sección: Bebidas destacadas

- **id:** bebidas-destacadas
- **Título:** Bebidas destacadas
- **Texto:** POR DEFINIR
- **Elementos** (lista: título + descripción de cada uno, o "ninguno"): POR DEFINIR (el plan identifica bebidas en el Menú, pero no cuáles son destacadas en Inicio).
- **Imágenes** (archivo en `pack/imagenes/` + texto alternativo, o "ninguna"): POR DEFINIR
- **Botones** (texto → destino, o "ninguno"): POR DEFINIR
- **Disposición** (celular / computadora): celular: productos apilados verticalmente; computadora: varias tarjetas de bebidas en cuadrícula debajo de especialidades.
- **Referencia aplicada** (1a, 1b, 2a, 2b o "ninguna"): ninguna

### Página: Menú (`/menu`)

#### Sección: Nuestra carta

- **id:** nuestra-carta
- **Título:** Nuestra carta.
- **Texto:** Café, matcha y algo delicioso para cada momento.
- **Elementos** (lista: título + descripción de cada uno, o "ninguno"): Café, Matcha, Brunch y Repostería.
- **Imágenes** (archivo en `pack/imagenes/` + texto alternativo, o "ninguna"): POR DEFINIR
- **Botones** (texto → destino, o "ninguno"): POR DEFINIR
- **Disposición** (celular / computadora): celular: título y categorías en columna sobre productos; computadora: título y categorías encima de cuadrícula de productos, según el boceto.
- **Referencia aplicada** (1a, 1b, 2a, 2b o "ninguna"): 2a

#### Sección: Productos

- **id:** productos
- **Título:** POR DEFINIR (el plan llama a esta sección Productos, pero no fija un título visible)
- **Texto:** POR DEFINIR
- **Elementos** (lista: título + descripción de cada uno, o "ninguno"): Matcha Latte ($4.50); Iced Latte ($4.00); Cold Brew ($3.75); Strawberry Matcha ($5.25); Croissant ($2.75); Avocado Toast ($5.50). Descripciones individuales: POR DEFINIR.
- **Imágenes** (archivo en `pack/imagenes/` + texto alternativo, o "ninguna"): POR DEFINIR (no hay correspondencia explícita entre los nombres de productos y las fotos).
- **Botones** (texto → destino, o "ninguno"): POR DEFINIR
- **Disposición** (celular / computadora): celular: tarjetas de productos una debajo de otra, con fotos, nombres y precios; computadora: tarjetas de producto en cuadrícula con fotografía, nombre y precio.
- **Referencia aplicada** (1a, 1b, 2a, 2b o "ninguna"): 2b

### Página: Nosotros (`/nosotros`)

#### Sección: Nuestra esencia

- **id:** nuestra-esencia
- **Título:** Nuestra esencia.
- **Texto:** YOKÓ es un espacio creado para disfrutar del café, el matcha y pequeños momentos de tranquilidad.
- **Elementos** (lista: título + descripción de cada uno, o "ninguno"): Título y párrafo informativo.
- **Imágenes** (archivo en `pack/imagenes/` + texto alternativo, o "ninguna"): POR DEFINIR
- **Botones** (texto → destino, o "ninguno"): ninguno (no se identifica un botón específico en el plan)
- **Disposición** (celular / computadora): celular: título y texto sobre fotos apiladas; computadora: texto a la izquierda y fotografías del café y matcha a la derecha, según el boceto.
- **Referencia aplicada** (1a, 1b, 2a, 2b o "ninguna"): 1b

### Página: Contacto (`/contacto`)

#### Sección: Encuéntranos

- **id:** encuentranos
- **Título:** Encuéntranos.
- **Texto:** Nos encantaría recibirte y compartir contigo un momento especial.
- **Elementos** (lista: título + descripción de cada uno, o "ninguno"): POR DEFINIR (ubicación, horarios y datos que se aprecian en el boceto no están especificados en el contenido definitivo)
- **Imágenes** (archivo en `pack/imagenes/` + texto alternativo, o "ninguna"): POR DEFINIR
- **Botones** (texto → destino, o "ninguno"): POR DEFINIR
- **Disposición** (celular / computadora): celular: contenido en columna; computadora: texto y datos a la izquierda e imagen a la derecha, según el boceto.
- **Referencia aplicada** (1a, 1b, 2a, 2b o "ninguna"): ninguna

#### Sección: Contacto y redes

- **id:** contacto-y-redes
- **Título:** POR DEFINIR
- **Texto:** POR DEFINIR
- **Elementos** (lista: título + descripción de cada uno, o "ninguno"): Correo `contacto@yoko.example.com` (correo de ejemplo en el plan); demás datos POR DEFINIR.
- **Imágenes** (archivo en `pack/imagenes/` + texto alternativo, o "ninguna"): ninguna
- **Botones** (texto → destino, o "ninguno"): POR DEFINIR
- **Disposición** (celular / computadora): celular: datos y enlaces en columna; computadora: área de contacto bajo el bloque principal, según el boceto.
- **Referencia aplicada** (1a, 1b, 2a, 2b o "ninguna"): ninguna

## 10. Contacto y pie de página

| Campo | Decisión |
| --- | --- |
| Correo | contacto@yoko.example.com (correo de ejemplo, no real) |
| Redes (nombre → enlace) | POR DEFINIR |
| Texto del pie | POR DEFINIR |
