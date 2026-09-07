# Quirekeep

*[English](README.md)*

**[Abrir la app → quirekeep.pages.dev](https://quirekeep.pages.dev)**

Una biblioteca personal para las tres cosas que se llevan por separado y nunca
en el mismo sitio: **libros, pantalla (cine y series) y juegos**. Va en el
navegador, no pide cuenta ni servidor, y todo lo que escribes se queda en tu
dispositivo.

El nombre viene de ahí: un *quire* es el cuadernillo de hojas plegadas con el
que se encuaderna un libro. Esto guarda los tuyos.

---

## Qué hace

Cada uno de los tres **sectores** es una biblioteca entera, con las mismas seis
pantallas, y cada uno guarda sus ajustes, sus estantes y sus estadísticas:

| Pantalla | Para qué es |
|---|---|
| **Biblioteca** | Todo lo del sector. Filtra por estado, género, idioma, formato, estante o etiqueta; ordena; cambia entre rejilla de portadas y lista. |
| **Estantes** | Tus propios estantes. Un título puede estar en los que quieras. |
| **Estadísticas** | Cuántos, con qué nota, de qué géneros, en qué idiomas y cuánto de todo eso conoce cada aplicación conectada. |
| **Cola de sync** | Los títulos que le faltan a un servicio conectado, con sus datos listos para copiar y un enlace a su búsqueda. |
| **Importar y exportar** | CSV para entrar, JSON para salir, copias de seguridad en los dos sentidos. |
| **Añadir** | Un solo formulario, que se rellena casi entero buscando el título. |

Y tres pantallas que no son de un sector:

- **Inicio** — los tres sectores de un vistazo: lo empezado, lo que viene ahora
  y lo que sale pronto. Desde aquí se marca un episodio visto o un libro
  terminado.
- **Estante** — un único estante con los tres sectores: lo que tienes a medias,
  en una fila por sector.
- **Retos** — retos de lectura, de pantalla y de juego: una cifra ("24 libros
  en 2026") o una lista de consignas a las que vas asignando títulos. Cada uno
  pertenece a un sector y cuenta con los títulos de ese sector.

Además: nota sobre diez, avance por título (páginas, minutos, horas, episodios
o porcentaje a secas), historial con relecturas, notas privadas, una cola de
cinco siguientes, tema claro y oscuro, y español e inglés.

En el móvil aparece la barra de abajo y se cambia de pantalla deslizando de
lado; en pantalla ancha es una aplicación de escritorio a tres columnas.

---

## Cómo se instala

Quirekeep no está en la App Store ni en Google Play, y no hay ningún instalador
que descargar. Es una aplicación web: abres una dirección y le dices al
navegador que se la quede. A partir de ahí se queda con las demás aplicaciones,
se abre igual que ellas y funciona con el móvil en modo avión.

> **La dirección: https://quirekeep.pages.dev**

**En Android** — abre la dirección en Chrome, entra en el menú ⋮ de arriba a la
derecha y pulsa *Instalar aplicación* (en versiones antiguas pone *Añadir a
pantalla de inicio*). Acepta.

**En iPhone o iPad** — abre la dirección **en Safari**, no en otro navegador.
Pulsa el botón de compartir (el cuadrado con la flecha hacia arriba), baja por
la lista y pulsa *Añadir a pantalla de inicio*.

**En Windows o Mac** — abre la dirección en Chrome o en Edge. Al final de la
barra de direcciones hay un iconito de instalar (una pantalla con una flecha):
púlsalo, o busca *Instalar Quirekeep* en el menú ⋮ del navegador. Firefox no
instala aplicaciones: ahí funciona, pero se queda en una pestaña.

**Si no aparece la opción de instalar**, casi siempre es que el navegador está
en una ventana privada. Solo con eso ya no la ofrece.

### Una vez instalada

- Se abre sin las barras del navegador alrededor, desde su icono como cualquier
  otra aplicación.
- Funciona sin conexión. Solo hace falta para buscar un título nuevo.
- Se actualiza sola: la abres con conexión y ya tienes la última versión. No
  hay que reinstalar nada, nunca.
- No pide cuenta, ni correo, ni permisos.

---

## Tus datos son tuyos

Todo lo que escribes vive en el almacén de tu navegador, en ese dispositivo y
en ningún sitio más. No se manda nada a ninguna parte, no hay cuenta y no hay
donde entrar. Nadie tiene una copia —que es la gracia—, pero eso significa
también que nadie te la puede devolver.

Así que, en **Perfil**, en el recuadro que dice *Tu biblioteca solo vive en este
navegador*, dale a *Descargar copia* de vez en cuando: guarda un archivo pequeño
con todo. Ese archivo es lo que lo devuelve todo en un móvil nuevo (*Restaurar*)
o junta dos dispositivos en uno (*Combinar*). Ahí mismo te dice cuánto hace de
la última.

Y no borres los datos del navegador para esta dirección: se lleva la biblioteca
por delante. La copia guardada es la vuelta atrás.

Lo único que sale del navegador es una cuenta de visitas: la app carga
Cloudflare Web Analytics, que no pone cookies, no identifica a nadie y no ve lo
que hay en tu biblioteca. Dice cuánta gente abrió la página, y nada más.

Para traer una biblioteca, **Importar** lee los CSV de Goodreads, StoryGraph,
Pagebound y Letterboxd, con notas, fechas, estantes y reseñas.

---

## Las cuentas que llevas fuera

Quirekeep no se conecta a ninguna: ni entra, ni usa su API, ni pide permisos.
Lo que guarda es cuál de tus cuentas tiene ya cada título, para saber qué te
falta por subir. Cada título lleva una banda de color por cuenta —los lomos de
su costado—, y pulsar una banda dice «esta ya lo tiene».

Vienen puestas **Booktower, StoryGraph, Pagebound y Goodreads** para libros,
**IGN, Backloggd y Steam** para juegos, y **Letterboxd y Trakt** para cine y
series. Cualquiera se puede apagar o esconder, y puedes añadir las tuyas.

Con ellas encendidas, la **cola de sync** enseña lo que le falta a cada una con
los datos listos para copiar, las **estadísticas** dicen cuánto de un sector
conoce cada una, y **exportar** saca solo lo que a un servicio le falta.
Apágalas todas y no se rompe nada: la cola se queda vacía.

---

## De dónde salen los datos

Solo fuentes que no piden clave ni cuenta: **Open Library** para buscar libros,
consultar por ISBN y sacar portadas; **Wikidata** para cine, series y juegos
—quién lo hizo, género, año, duración, idioma, y el reparto con el personaje de
cada uno—; y **TVMaze** para temporadas y episodios con sus fechas de emisión,
que es lo que permite saber que un episodio todavía no ha salido.

Cine, series y juegos no tienen ninguna fuente de portadas sin clave, así que
enseñan una tarjeta de color con el título. Donde el navegador lo permite, el
ISBN se puede escanear con la cámara en vez de teclearlo.

---

## Apoyar el proyecto

Quirekeep es gratis, sin anuncios, sin cuentas y sin nada que desbloquear. Si
te sirve, puedes echar una mano en
**[ko-fi.com/alex_create](https://ko-fi.com/alex_create)**.

---

## Licencia

El código no está publicado; este repositorio tiene la documentación y el
enlace a la app. Tanto la aplicación como estos textos son propietarios, todos
los derechos reservados — está en [LICENSE](LICENSE).
