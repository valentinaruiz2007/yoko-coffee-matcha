# CAMBIOS — YOKÓ

## 2026-11-03 · Avance E2

- Integración del pack de YOKÓ con plan, imágenes, tipografía DM Sans, brief y prompts.
- Identidad aplicada según el plan: paleta, bordes de 1 px, esquinas de 8 px, ancho amplio y animación sutil.
- Marco compartido, navegación responsive y rutas de Inicio, Menú, Nosotros y Contacto.
- Inicio dividido en componentes: Portada, Especialidades y Bebidas.
- Imágenes con textos alternativos descriptivos.
- Datos del brief utilizados sin inventar ubicación ni perfiles de redes.

## Pendientes del plan

- Incluir archivo local Cormorant Garamond para los títulos (actualmente usa Georgia de respaldo).
- Decidir tono de texto sobre el verde matcha; blanco no supera 4.5:1.
- Confirmar qué imágenes deben representar productos específicos: las fotografías ilustrativas no muestran todos los productos del menú.
- Confirmar qué contenido adicional o enlaces debe llevar Contacto.
- Confirmar sombras y encabezado fijo.
- Ejecutar `npm install` y `npm run verificar` en el equipo con acceso a las dependencias.

## Entrega final E3 - Mejoras realizadas

- Se corrigió un error de código en Contacto.
- Se agregaron descripciones a las cuatro especialidades de Inicio.
- Se añadieron descripciones a los seis productos del Menú.
- Se mejoró la visualización del Menú en celulares.
- Se revisó el diseño responsive en 360, 768 y 1280 píxeles.
- Se comprobaron las páginas Inicio, Menú, Nosotros y Contacto.
- Se comprobó la navegación con las teclas Tab y Enter.

## 18 de noviembre de 2026 — Correcciones E3

### Prompt 1: Navegación activa

Se corrigió el menú para identificar la página actual en Inicio, Menú, Nosotros y Contacto.

### Prompt 2: Accesibilidad

Se agregó un foco visible para navegar con el teclado mediante la tecla Tab.

### Prompt 3: Animación de entrada

Se implementó una animación suave de opacidad, respetando las preferencias de movimiento reducido.

### Prompt 4: Imágenes de Astro

Se reemplazaron las etiquetas img por el componente Image de Astro en las secciones corregidas.

### Prompt 5: Componentes de Menú

Se organizaron el encabezado y los productos del Menú en componentes independientes.

### Prompt 6: Componentes de Nosotros

Se creó ContenidoNosotros.astro para separar el contenido de la página.

### Prompt 7: Componentes de Contacto

Se creó ContenidoContacto.astro, manteniendo la estructura visual y los estilos.

### Prompt 8: Información de contacto

Se identificaron los canales de contacto no confirmados para evitar presentarlos como información oficial.
