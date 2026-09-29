# Veld Studio · Sistema de diseño de la web

Fuente de verdad para cualquier página nueva de Veld (web, landings, secciones). Si algo no está acá, se decide con este criterio: una sola idea por pantalla, mucho aire, contraste fuerte.

Última actualización: 29/09/2026.

## Tipografía

Tres familias, cada una con un rol. Nunca las tres con el mismo peso visual: una domina, una estructura, una contrasta.

| Rol | Fuente | Dónde va | Reglas |
|---|---|---|---|
| El golpe | **Anton** | Logo, títulos de sección, nombres de programas y productos, números grandes | Siempre en minúscula. Tracking negativo (-0.02em a -0.025em). Interlineado apretado (0.88 a 0.95). El logo "veld" puede cortarse contra el borde. |
| El alma editorial | **Cormorant Garamond itálica** (300) | Subtítulo del hero, frases de destaque, citas, frase de transformación de cada caso | Solo frases cortas. Máximo una línea o frase por pantalla. Nunca en texto corrido, botones ni etiquetas. Color habitual: Warm Sand sobre oscuro, Obsidian sobre claro. |
| La estructura | **Inter** (300 y 400) | Cuerpo, navegación, botones, etiquetas, listas | Etiquetas y botones en mayúscula con tracking amplio (0.18em a 0.22em), 10 a 11 px. Cuerpo 13 a 15 px, interlineado 1.8 a 1.9. |

Carga (Google Fonts):

```
https://fonts.googleapis.com/css2?family=Anton&family=Cormorant+Garamond:ital,wght@0,300;1,300;1,400&family=Inter:wght@300;400&display=swap
```

En piezas impresas o de Canva, Neue Haas Grotesk y Cita reemplazan a Inter. En la web se usa Inter porque las otras dos son pagas.

Fuentes descartadas para siempre: Fraunces, Jost, Gloock, Jura, Space Grotesk, Impact, Bebas Neue, Weber's New.

## Paleta (cerrada)

| Nombre | Hex | Variable CSS | Uso |
|---|---|---|---|
| Obsidian | `#1c1c1a` | `--obsidian` | Fondo principal, texto sobre claro |
| Warm Sand | `#d4c5a9` | `--warm-sand` | Acento, botón principal, frases en Cormorant |
| Stone White | `#f5f2ec` | `--stone-white` | Fondo claro |
| Light Stone | `#ede9e1` | `--light-stone` | Fondo claro alterno (programas) |
| Ash | `#8c8070` | `--ash` | Texto secundario, etiquetas |
| Blanco | `#ffffff` | `--white` | Títulos sobre oscuro |

Forest (`#2a3d35`) está eliminado de la paleta. No se usa en ningún lugar.

Las fotos pueden tener su color natural. Fondos, textos y elementos de marca siempre dentro de la paleta.

## Botones y enlaces

- **Principal:** fondo Warm Sand, texto Obsidian, Inter 11 px en mayúscula, sin bordes redondeados. Hover: fondo transparente y texto Warm Sand.
- **Secundario:** borde fino Warm Sand al 40 %, fondo transparente.
- **Enlace de acción:** texto en mayúscula con subrayado de 1 px y flecha "→" al final.
- Un solo botón principal por bloque.

## Movimiento

- Curva estándar: `cubic-bezier(0.16, 1, 0.3, 1)`.
- Entradas cortas de 0.4 a 0.6 s. Nada que rebote ni que tarde más de 0.8 s.
- Respetar "reducir movimiento" del sistema.

## Espaciado

- Secciones: 120 px arriba y 130 a 140 px abajo en escritorio; 80 y 100 px en celular.
- Márgenes laterales: 48 px en escritorio, 28 px en celular.
- Grillas separadas por líneas de 1 px, no por sombras.

## Textos

- Español rioplatense, con vos.
- Sin guiones largos ni rayas en ningún texto.
- Sin adjetivos vacíos. Cada frase tiene que poder defenderse con un dato o un ejemplo.
