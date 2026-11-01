---
name: Shuaaay.party
description: One-page marketing consultancy site built as a neighborhood street-party poster.
colors:
  cream: "#FFF1E0"
  bone: "#FFFCF6"
  ink: "#23102B"
  cobalt: "#2447D8"
  marigold: "#FFC02E"
  teal: "#0B6B63"
  pink: "#FFC2D1"
typography:
  display:
    fontFamily: "Bricolage, system-ui, sans-serif"
    fontSize: "clamp(2.75rem, 7.6vw, 6rem)"
    fontWeight: 800
    lineHeight: 0.9
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "Bricolage, system-ui, sans-serif"
    fontSize: "clamp(2.1rem, 4.6vw, 3.75rem)"
    fontWeight: 800
    lineHeight: 0.98
    letterSpacing: "-0.03em"
  title-lg:
    fontFamily: "Bricolage, system-ui, sans-serif"
    fontSize: "clamp(1.75rem, 3.2vw, 2.75rem)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.025em"
  title:
    fontFamily: "Bricolage, system-ui, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  invite:
    fontFamily: "Bricolage, system-ui, sans-serif"
    fontSize: "1.75rem"
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.03em"
  body-lg:
    fontFamily: "Bricolage, system-ui, sans-serif"
    fontSize: "clamp(1.125rem, 1.5vw, 1.3rem)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "Bricolage, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: "Bricolage, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.5
  control:
    fontFamily: "Bricolage, system-ui, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 700
    lineHeight: 1.3
  label:
    fontFamily: "Bricolage, system-ui, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 800
    lineHeight: 1.35
    letterSpacing: "0.14em"
  wordmark:
    fontFamily: "Bricolage, system-ui, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.04em"
rounded:
  control: "4px"
  card: "14px"
spacing:
  xs: "0.5rem"
  sm: "1rem"
  md: "2rem"
  lg: "3.5rem"
  xl: "6rem"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.cream}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0.9rem 1.5rem"
    height: "3.1rem"
  button-primary-hover:
    backgroundColor: "{colors.teal}"
    textColor: "{colors.cream}"
  invitation:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "1.35rem"
  ticket:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "2rem"
  service-row:
    textColor: "{colors.ink}"
    padding: "1.6rem 0"
---

# Design System: Shuaaay.party

## Overview

**Creative North Star: "La fiesta del barrio"**

La página es el cartel de una fiesta de barrio que, al leerla, resulta ser una consultoría de marketing seria. El dominio `.party` da permiso para celebrar; el contenido no lo usa para prometer de más. Por eso hay banderines, una invitación y un ticket; el color se concentra en el programa, el método y la nota honesta, y el resto es hueso y crema para que la lectura mande. También hay reglas de 2px, cifras tabulares y una sección que dice exactamente lo que la página todavía no puede probar.

La tensión es el diseño: una superficie festiva que no se vuelve infantil, y una oferta clara que no se vuelve aburrida. La fiesta es el envoltorio; el plan es el producto.

**Key Characteristics:**
- Hueso y crema para leer; cobalto, marigol, verde y rosa en objetos y bandas. El color no compite con el texto.
- Una sola familia, Bricolage Grotesque, con contraste por peso, tamaño y caja. Sin segunda voz tipográfica.
- Reglas de 2px, bordes de 2px y esquinas de 4px o 14px. Nada de sombras duras ni degradados.
- Objetos de papel: invitación girada, ticket perforado, banderín SVG, borde festoneado.
- Un solo momento de entrada: la invitación cae y se asienta. El resto se mueve al interactuar.

## Colors

- **The Field Rule.** El hero, el cierre y las secciones de lectura son hueso `#FFFCF6`; las tarjetas son crema `#FFF1E0`. El color se concentra en bandas y objetos: marigol en el programa, ciruela en el método, verde botella en la nota honesta, y cobalto, marigol, verde y rosa en el banderín, la invitación y el ticket.
- **The Ink Rule.** Sobre hueso, crema y marigol, todo el texto va en tinta. Sobre ciruela y verde botella, todo va en crema. El cobalto es acento de marca y de estado: no se usa como campo ni como texto de cuerpo (2.5:1 sobre sí mismo).
- Contraste medido: tinta/hueso 17.4:1, tinta/crema 16.0:1, tinta/marigol 10.9:1, crema/ciruela 16.0:1, crema/verde 5.7:1, cobalto/hueso 6.9:1 (marca y titulares), cobalto/crema 6.4:1 (solo display), tinta/rosa 11.8:1.
- **The No-Gray Rule.** No existe gris en el sistema. El texto secundario se resuelve con tamaño, caja o el color de la sección, nunca con un gris ajeno a la paleta.

## Typography

**The One Voice Rule.** Bricolage Grotesque variable, autohospedada, para titulares y cuerpo. Su carácter (curvas cerradas, contraformas grandes) hace el trabajo que en otra identidad haría una segunda familia.

- Titular: 6rem máximo, línea 0.9, tracking -0.035em, medida 12ch forzada con salto de línea.
- Titular de sección: 3.75rem máximo, 0.98 de interlineado, 22ch de medida.
- Nombre de servicio: hasta 2.75rem; título de paso: 1.5rem; control de pregunta: 1.125rem.
- Cuerpo: 1rem/1.6, 68ch. Entrada: hasta 1.3rem/1.5. Secundario: 0.875rem.
- Rótulos: 0.75rem, 800, tracking 0.14em, versalitas. Nunca por debajo de 12px.
- **The Marker Rule.** La única forma de énfasis es una barra de marigol detrás de la palabra (`inset 0 -0.16em`), como un rotulador. Sobre marigol, la barra es crema. No hay degradados de texto.
- **The Tabular Rule.** Números de paso y de ticket usan `font-variant-numeric: tabular-nums`.

## Layout

Contenedor de 1200px con 1.25rem de margen (2.5rem desde 1000px). El hero respira con una rejilla de 1.12/0.88 desde 960px; por debajo, la invitación cae debajo del texto y se alinea a la izquierda.

- El banderín SVG ocupa el ancho completo del hero con `preserveAspectRatio="none"` y 76px de alto; en móvil se comprime y sigue leyéndose.
- Borde festoneado de 12px en marigol bajo el hero, dibujado con un radial-gradient repetido de 24px.
- Secciones a 6rem de padding vertical (3.5rem en móvil), sin reglas entre secciones: el cambio de color es la separación.
- Filas de servicio y pasos se apilan por debajo de 880px y 760px; las comparativas de dos columnas se apilan a 860px.
- Ticket: dos columnas (contenido + talón de 150px) desde 760px; el talón pasa a franja inferior con perforación horizontal.
- Saltos: 600 (campos), 620 (filas), 700 (nada), 760 (ticket, pasos), 860 (comparativas), 960 (hero), 1000 (contenedor). Los anclajes dejan 5rem para la cabecera fija.

## Elevation & Depth

**The Flat Paper Rule.** La página es plana. Solo la invitación y el ticket llevan sombra, larga, difusa y con desplazamiento vertical: `0 30px 55px -26px rgba(35,16,43,.65)` y `-28px` respectivamente. No hay sombras duras, ni halos de color, ni cristal.

## Shapes

Botones de 4px; tarjetas de 14px; bordes de 2px; reglas de 1px o 2px; talón separado por línea discontinua de 2px. Triángulos de banderín, borde festoneado de semicírculos y una invitación girada -2°. Sin píldoras, sin clip-path poligonal y sin iconos.

## Components

- **Ticker.** Franja ciruela con texto crema en versalitas que envuelve en móvil; estática, sin movimiento continuo. En pantallas pequeñas conserva solo la marca y la promesa.
- **Cabecera fija.** Hueso, borde inferior de 2px, marca de 1.5rem con `.party` en cobalto, navegación de tres enlaces y botón ciruela.
- **Botón primario.** Bloque ciruela, texto crema, 4px de radio, rótulo de 0.875rem en versalitas; hover verde botella y desplazamiento de 2px al pulsar.
- **Invitación.** Tarjeta crema de 14px, borde ciruela de 2px, girada -2°, franja superior ciruela, tres filas de datos con regla de 1px, botón completo y talón marigol con RSVP.
- **Filas de programa.** Cada acto lleva una etiqueta con cuadro verde, nombre a 2.75rem, problema y «Te llevas»; reglas de 2px arriba y abajo.
- **Pasos.** Número marigol a 1.125rem, título crema de 1.5rem, cuerpo crema y «Te llevas» en marigol, separados por reglas marigol de 1px.
- **Preguntas.** `details/summary` nativo, indicador de más dibujado con dos barras de 2px que gira 45° al abrir; respuesta a 66ch.
- **Ticket de reserva.** Crema con borde ciruela de 2px, campos subrayados, botón ciruela y talón marigol con marca vertical; el formulario compone un correo, no inventa un backend.
- **Pie.** Ciruela, marca crema con `.party` en marigol, correo y enlace de vuelta.

## Do's and Don'ts

### Do
- **Do** reservar hueso y crema para las secciones de lectura y usar el color en el programa, el método, la nota honesta y los objetos.
- **Do** usar tinta sobre hueso, crema y marigol; crema sobre ciruela y verde.
- **Do** mantener la barra de rotulador como único recurso de énfasis.
- **Do** conservar el borde festoneado y el banderín como geometría, no como imagen.
- **Do** respetar `prefers-reduced-motion` en la entrada de la invitación.

### Don't
- **Don't** añadir fotos de stock, iconos, degradados, cristal, sombras duras ni una segunda tipografía.
- **Don't** usar cobalto como campo ni tinta sobre cobalto; tampoco crema sobre marigol.
- **Don't** convertir la fiesta en infantilismo: nada de emojis, confeti aleatorio ni globos.
- **Don't** inventar clientes, testimonios, métricas, precios ni plazos. La página dice lo que aún no puede probar.
- **Don't** usar grises ni texto por debajo de 12px.
