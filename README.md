# 🎉 Fiesta 80·90 — Feliz Medio Siglo

Una invitación-experiencia interactiva para celebrar los 50 de **Meri**, llena de la música, los recuerdos y la estética de finales de los 80 y principios de los 90. Pensado como remember de aquella época en la Comunidad Valenciana: las noches de **CocoLoco**, **Bacarrá** y la playa de Gandía.

## 🌐 Cómo usarla

Solo abre el `index.html` en cualquier navegador moderno, o visita la URL pública del sitio. No hay servidor ni instalación: todo funciona desde un único archivo HTML autocontenido.

> Para que los reproductores de Spotify se vean enteros y no como recortes de 30 segundos, conviene tener una sesión de Spotify activa en el navegador.

## ✨ Qué incluye

- **🎵 La Lista Sonando** — La playlist completa de la fiesta embebida con reproductor de Spotify.
- **🎲 Tocadiscos Aleatorio con buscador** — Selecciona un tema al azar de los 114 incluidos y lo reproduce in situ. Además, un buscador incremental permite localizar cualquier tema concreto escribiendo título o artista (insensible a mayúsculas y acentos), con desplegable de resultados coloreados según su pestaña.
- **💿 El Vinilo de Aquellos Veranos** — Cinco pestañas con himnos clasificados como Cara A, Cara B y "El resto de la caja", siguiendo el formato de un vinilo de la época (máximo 22 minutos por cara):
  - *Dance / Eurodance / House* (26 temas)
  - *Pop / Rock de la época* (28 temas)
  - *Italo / Bakalao patrio y europeo* (17 temas)
  - *Cantábamos en castellano* (32 temas) — los himnos del pop-rock español que se canta en grupo
  - *🎧 Peticiones al DJ* (11 temas) — las que va pidiendo la gente
- **📅 Línea del Tiempo (1984–1995)** — Visualización SVG interactiva con cada éxito colocado en su año, filtrable por estilo (cinco colores: cian, rosa, amarillo, morado y verde lima).
- **🎂 El Nº1 del año que cumplías** — Para cada año entre 1984 y 1995, la edad que Meri tenía entonces y un nº1 representativo. La tarjeta de 1992 (sus 16 años) destacada con "¡TENÍAMOS 16!".
- **🕹️ ¿Te suena? · El juego de la fiesta** — Trivial con pistas progresivas (dato curioso → frase emblemática → estilo+año+álbum → título a medias) sobre los 37 himnos icónicos. Marcador de aciertos y pistas gastadas, con reproductor incrustado al revelar la respuesta.
- **🛋️ Para que la noche sea perfecta** — Detalles de ambientación: carta de barra, dress code, rincón recreativo, guiños a Madrid y Valencia, cierre al amanecer...
- **📺 La tele de aquella época** — 32 sintonías de dibujos y series (Bola de Dragón, La Abeja Maya, D'Artacán, Heidi, Marco, Sailor Moon, Mazinger Z, Willy Fog, El Equipo A, El Coche Fantástico, Juana y Sergio...) con sus carátulas reales de la serie, reproductor único + 10 jingles de anuncios míticos en texto.
- **✉️ La Invitación** — Disponible en tres estilos elegibles, con campos editables que se actualizan en vivo en los tres:
  - 🕹️ **Recreativa Arcade** — Inspirada en una máquina recreativa con HUD "SCORE/PLAYER".
  - 🌴 **Postal Neón** (por defecto) — Postal vertical con sol pixelado de neón.
  - 📼 **Cassette TDK** — Una cinta de cassette con etiqueta y texto manuscrito.
  - QR a la playlist incluido. Imprimible o exportable a PDF (solo se imprime la invitación seleccionada).
- **🏆 La Sala de Trofeos** — Dashboard final con seis bloques de visualización sobre todo el contenido recopilado:
  - 📮 **Postal de la fiesta**: tarjetas con cifras destacadas (total de temas, años representados, sintonías, año top, artista más representado, horas estimadas de música).
  - 🗺️ **Mapa geográfico**: SVG con los contornos reales de 23 países (Europa, Norteamérica y Australia) y una burbuja por cada ciudad de origen de los 85 artistas. Tamaño proporcional al número de temas, color del estilo dominante, halos pulsantes animados, líneas de conexión Madrid↔ciudades españolas y arcos transatlánticos NY↔Madrid/Londres. Hover y click muestran detalles por ciudad.
  - 📊 **Histograma de temas por año** apilado por estilo, con tooltip interactivo y el año 1992 destacado.
  - 🏆 **Top artistas**: ranking con barras horizontales proporcionales; click despliega los temas de cada artista.
  - 🍩 **Donut de distribución por estilo** con porcentajes y leyenda.
  - ✨ **Curiosidades de la era**: tarjetas con datos sueltos (tema más antiguo, más reciente, sintonía más vieja, año con más himnos, etc.).

## 🎯 Lo que sonaba en Gandía 88·95

La selección musical reúne **114 temas reales** (rango 1980–1997), repartidos en cinco estilos:

- **Dance / Eurodance / House** (26) — Snap!, Haddaway, Corona, 2 Unlimited, Black Box, Crystal Waters, Robin S, Moby, Double You, Aqua...
- **Pop / Rock anglosajón** (28) — R.E.M., Nirvana, U2, Depeche Mode, The Cranberries, Lenny Kravitz, The Cure, Pearl Jam, Wham!...
- **Italo / Bakalao patrio y europeo** (17) — Chimo Bayo, Megabeat, Energy 52 (Café del Mar), Jones & Stephenson, Sensity World, M&H Band (Popcorn), Freddie Mercury (Living on My Own remix), Locomía...
- **Cantábamos en castellano** (32) — Héroes del Silencio, El Último de la Fila, Mecano, Hombres G, Nacha Pop, Loquillo, Celtas Cortos, Sabina, Alaska, Duncan Dhu, Antonio Vega, Antonio Flores, Sergio Dalma, Luz Casal, Modestia Aparte, Los Secretos, Radio Futura, La Frontera, 091, Seguridad Social...
- **Peticiones al DJ** (11) — Los Rodríguez, Los Ronaldos, Alex y Cristina, Viceversa, OBK, Michael Jackson y más.

## 🛠️ Detalles técnicos

- **Stack:** HTML + CSS + JavaScript vanilla, en un único archivo (~195 KB). Sin frameworks, sin build, sin dependencias.
- **Fuentes:** Monoton, Audiowide, Press Start 2P, Caveat, Outfit (vía Google Fonts).
- **Reproductores:** múltiples reproductores de Spotify incrustados (`/embed/`) repartidos por las secciones (Lista, Tocadiscos, las 5 pestañas del Vinilo, Línea de tiempo, Nº1 por edad, Juego, La Tele), con fallback a búsqueda para temas sin track ID.
- **Carátulas musicales:** se cargan dinámicamente desde la API oficial de Spotify (oEmbed) con fallback a iTunes.
- **Carátulas de series:** URLs directas a TheTVDB ya incluidas en el HTML (sin necesidad de API key ni llamadas externas).
- **Mapa geográfico:** GeoJSON de Natural Earth simplificado con algoritmo Douglas-Peucker, incrustado en el HTML (~26 KB) sin dependencias externas. Proyección equirectangular custom en 3 viewports.
- **QR:** generado como imagen base64 incrustada, funciona sin conexión y al imprimir.
- **Responsive:** adaptado a móvil; los grids se reorganizan automáticamente y las secciones Top artistas + Donut se apilan en pantallas estrechas.

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
