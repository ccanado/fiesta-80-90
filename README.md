# 🎉 Fiesta 80·90 — Feliz Medio Siglo

Una invitación-experiencia interactiva para celebrar los 50 de **Meri**, llena de la música, los recuerdos y la estética de finales de los 80 y principios de los 90. Pensado como remember de aquella época en la Comunidad Valenciana: las noches de **CocoLoco**, **Bacarrá** y la playa de Gandía.

## 🌐 Cómo usarla

Solo abre el `index.html` en cualquier navegador moderno, o visita la URL pública del sitio. No hay servidor ni instalación: todo funciona desde un único archivo HTML autocontenido.

> Para que los reproductores de Spotify se vean enteros y no como recortes de 30 segundos, conviene tener una sesión de Spotify activa en el navegador.

## ✨ Qué incluye

- **🎵 La Lista Sonando** — La playlist completa de la fiesta embebida con reproductor de Spotify.
- **🎲 Tocadiscos Aleatorio** — Selecciona un tema al azar de los 67 incluidos y lo reproduce in situ.
- **💿 El Vinilo de Aquellos Veranos** — Tres pestañas (*Dance/Eurodance/House*, *Pop/Rock*, *Italo/Bakalao*) con himnos clasificados como Cara A, Cara B y "El resto de la caja" — siguiendo el formato de un vinilo de la época (máximo 22 minutos por cara).
- **📅 Línea del Tiempo (1984–1995)** — Visualización SVG interactiva con cada éxito colocado en su año, filtrable por estilo.
- **🎂 El Nº1 del año que cumplías** — Para cada año entre 1984 y 1995, la edad que Meri tenía entonces y un nº1 representativo. La tarjeta de 1992 (sus 16 años) destacada con "¡TENÍAMOS 16!".
- **🕹️ ¿Te suena? · El juego de la fiesta** — Trivial con pistas progresivas (dato curioso → frase famosa → estilo+año → título a medias) sobre los 27 himnos icónicos. Marcador de aciertos y pistas gastadas.
- **🛋️ Para que la noche sea perfecta** — Detalles de ambientación: carta de barra, dress code, rincón recreativo, guiños a Madrid y Valencia, cierre al amanecer...
- **📺 La tele de aquella época** — 22 sintonías de dibujos y series (Bola de Dragón, La Abeja Maya, D'Artacán, Heidi, Marco, Sailor Moon, Candy Candy, Chicho Terremoto...) con reproductor único + 10 jingles de anuncios míticos en texto.
- **✉️ La Invitación** — Disponible en tres estilos elegibles, con campos editables que se actualizan en vivo en los tres:
  - 🕹️ **Recreativa Arcade** — Inspirada en una máquina recreativa con HUD "SCORE/PLAYER".
  - 🌴 **Postal Neón** (por defecto) — Postal vertical con sol pixelado de neón.
  - 📼 **Cassette TDK** — Una cinta de cassette con etiqueta y texto manuscrito.
  - QR a la playlist incluido. Imprimible o exportable a PDF (solo se imprime la invitación seleccionada).

## 🎯 Lo que sonaba en Gandía 88·95

La selección musical reúne 67 temas reales que sonaban en las discotecas mediterráneas, repartidos en tres estilos:

- **Dance / Eurodance / House** (24 temas) — Snap!, Haddaway, Corona, 2 Unlimited, Black Box, Crystal Waters, Robin S, Moby...
- **Pop / Rock** (27 temas) — R.E.M., Nirvana, U2, Depeche Mode, The Cranberries, Lenny Kravitz, The Cure, Pearl Jam...
- **Italo / Bakalao patrio y europeo** (16 temas) — Chimo Bayo, Megabeat, Energy 52 (Café del Mar), Jones & Stephenson, Sensity World, M&H Band (Popcorn), Freddie Mercury (Living on My Own remix)...

## 🛠️ Detalles técnicos

- **Stack:** HTML + CSS + JavaScript vanilla, en un único archivo. Sin frameworks, sin build, sin dependencias.
- **Fuentes:** Monoton, Audiowide, Press Start 2P, Caveat, Outfit (vía Google Fonts).
- **Reproductores:** 7 reproductores de Spotify incrustados (`/embed/`) repartidos por las secciones, con fallback a búsqueda para temas sin track ID.
- **Carátulas:** se cargan dinámicamente desde la API oficial de Spotify (oEmbed) con fallback a iTunes.
- **QR:** generado como imagen base64 incrustada, funciona sin conexión y al imprimir.
- **Responsive:** adaptado a móvil; los grids de tres columnas se apilan en pantallas estrechas.

## 🖨️ Imprimir la invitación

1. Elige el estilo que prefieras en el selector de la sección "La Invitación".
2. Personaliza los campos editables (Player, Score, Lugar, Dirección, Fecha, Horario).
3. Pulsa "🖨 Imprimir / Guardar PDF".
4. Solo se imprime la invitación seleccionada (las otras secciones del HTML se ocultan automáticamente).

## 📝 Créditos

- Música: la pandilla de Meri y la memoria colectiva del Mediterráneo.
- Diseño y código: hecho con cariño para el cumpleaños del medio siglo.
- Algunos datos verificados con búsquedas en fuentes públicas; las anécdotas son las que recordábamos quienes estuvimos allí.

---

★ COCOLOCO · BACARRÁ · GANDÍA · TENÍAMOS 16 ★
