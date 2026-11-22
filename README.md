# Stimmen

**Español** · [Deutsch](#deutsch)

## Español

**Stimmen** («voces», en alemán) es una galería web interactiva de vídeos breves en los que antiguos estudiantes de alemán cuentan qué les ha aportado estudiar esta lengua. Cada persona aparece como una ficha de color con una palabra alemana que la representa; al pulsarla se abre su vídeo.

🔗 **Web:** https://javiermunoz-acebes.github.io/stimmen/

### Objetivos

- Mostrar al alumnado de Bachillerato y de grado, desde la voz de quienes ya han pasado por ahí, qué se puede hacer con el alemán.
- Reunir testimonios sobre las razones para estudiar alemán y sus salidas profesionales y personales.
- Servir de base para ampliar el proyecto con otros grupos y universidades.

### Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `index.html` | La página completa (HTML, CSS y JavaScript en un solo archivo) |
| `voz-01.mp4` … `voz-06.mp4` | Vídeos, comprimidos para web |
| `voz-01.jpg` … `voz-06.jpg` | Imagen de cartel de cada ficha |

### Cómo añadir un vídeo

1. Comprime el vídeo (recomendado: H.264, unos 800 kbit/s, audio AAC mono) y llámalo `voz-07.mp4`. Los archivos subidos desde la web de GitHub no pueden superar los 25 MB.
2. Prepara una imagen de cartel `voz-07.jpg` (por ejemplo, 480×480 o 480×640 px).
3. Abre `index.html` y, dentro de la lista `VOCES`, copia un bloque y cambia los datos:

```js
{ nombre: "Nombre Apellido", promocion: "2018-2022", ahora: "Ocupación actual",
  palabra: "Brücke", significado: "Puente", cita: "",
  etiquetas: ["Docencia"], duracion: "2:22",
  archivo: "voz-07.mp4", enlace: "", cartel: "voz-07.jpg" },
```

   - `etiquetas`: sirven para los filtros de la página. Los textos van **siempre entre comillas**.
   - `destacado: true`: la ficha ocupa doble ancho.
   - `enlace`: alternativa si el vídeo está alojado fuera de este repositorio.
4. Sube los archivos nuevos a la raíz del repositorio (**Add file → Upload files**) y confirma con **Commit changes**. Tras un minuto, recarga la web con Ctrl+F5.

> Si la página se queda en blanco, abre la consola del navegador (F12): casi siempre es una coma o unas comillas que faltan en `VOCES`.

### Publicación

La web se sirve con **GitHub Pages** desde la rama `main`, carpeta raíz. El repositorio tiene que ser público.

### Protección de datos

La página es pública. Antes de publicar un vídeo hay que contar con la **autorización por escrito de la persona** para el uso de su imagen y su voz. Quien desee retirar su vídeo puede pedirlo en cualquier momento y se eliminará del repositorio.

### Autoría y contacto

Proyecto de Javier Muñoz-Acebes, Departamento de Filología Francesa y Alemana, Universidad de Valladolid, GIR Filología Digital.
Contacto: fjavier.munoz@uva.es

Los vídeos pertenecen a las personas que aparecen en ellos y se publican con su permiso.

---

## Deutsch

**Stimmen** ist eine interaktive Web-Galerie mit kurzen Videos, in denen ehemalige Deutschstudierende erzählen, was ihnen das Studium der deutschen Sprache gebracht hat. Jede Person erscheint als farbige Karte mit einem deutschen Wort, das sie vertritt; ein Klick öffnet das Video.

🔗 **Webseite:** https://javiermunoz-acebes.github.io/stimmen/

### Ziele

- Schülerinnen und Schülern sowie Studierenden zeigen, was man mit Deutsch machen kann – erzählt von denen, die diesen Weg bereits gegangen sind.
- Zeugnisse über die Gründe für das Deutschlernen und seine beruflichen und persönlichen Perspektiven sammeln.
- Eine Grundlage schaffen, um das Projekt mit weiteren Gruppen und Universitäten auszubauen.

### Inhalt des Repositorys

| Datei | Beschreibung |
|---|---|
| `index.html` | Die gesamte Seite (HTML, CSS und JavaScript in einer Datei) |
| `voz-01.mp4` … `voz-06.mp4` | Videos, für das Web komprimiert |
| `voz-01.jpg` … `voz-06.jpg` | Vorschaubild jeder Karte |

### Ein Video hinzufügen

1. Das Video komprimieren (empfohlen: H.264, etwa 800 kbit/s, Audio AAC mono) und `voz-07.mp4` nennen. Dateien, die über die GitHub-Weboberfläche hochgeladen werden, dürfen höchstens 25 MB groß sein.
2. Ein Vorschaubild `voz-07.jpg` erstellen (z. B. 480×480 oder 480×640 px).
3. `index.html` öffnen, in der Liste `VOCES` einen Block kopieren und die Angaben ändern:

```js
{ nombre: "Vorname Nachname", promocion: "2018-2022", ahora: "Aktuelle Tätigkeit",
  palabra: "Brücke", significado: "Puente", cita: "",
  etiquetas: ["Docencia"], duracion: "2:22",
  archivo: "voz-07.mp4", enlace: "", cartel: "voz-07.jpg" },
```

   - `etiquetas`: dienen den Filtern der Seite. Die Texte stehen **immer in Anführungszeichen**.
   - `destacado: true`: die Karte wird doppelt so breit.
   - `enlace`: Alternative, falls das Video extern gehostet wird.
4. Die neuen Dateien in das Hauptverzeichnis des Repositorys hochladen (**Add file → Upload files**) und mit **Commit changes** bestätigen. Nach etwa einer Minute die Seite mit Strg+F5 neu laden.

> Bleibt die Seite leer, die Browser-Konsole öffnen (F12): Meist fehlt in `VOCES` ein Komma oder ein Anführungszeichen.

### Veröffentlichung

Die Seite wird mit **GitHub Pages** vom Branch `main` (Hauptverzeichnis) ausgeliefert. Das Repository muss öffentlich sein.

### Datenschutz

Die Seite ist öffentlich. Vor der Veröffentlichung eines Videos muss die **schriftliche Einwilligung der Person** zur Verwendung von Bild und Stimme vorliegen. Wer sein Video entfernen lassen möchte, kann das jederzeit verlangen; es wird dann aus dem Repository gelöscht.

### Urheberschaft und Kontakt

Ein Projekt von Javier Muñoz-Acebes, Departamento de Filología Francesa y Alemana, Universidad de Valladolid, gemeinsam mit der Forschungsgruppe GIR Filología Digital.
Kontakt: fjavier.munoz@uva.es

Die Videos gehören den abgebildeten Personen und werden mit deren Erlaubnis veröffentlicht.
