# Gros Xake Taldea · Propuesta de rediseño web (v2, versión clara)

Propuesta **no oficial** de rediseño de la web de Gros Xake Taldea, club de ajedrez de Donosti fundado en 1991. Los contenidos se tomaron de [grosxake.com](https://www.grosxake.com/) el 18/11/2026; la información válida es la que publica el club.

Es la segunda versión de la [propuesta original](https://github.com/enriquerodrigueztrenchsporta/gros-xake-taldea-propuesta): mismos contenidos, con un diseño más claro y fotos de Donosti.

## Qué cambia respecto a la v1

- Fondo claro y paleta más limpia, sin la intro 3D.
- Portada con un pase de fotos de La Concha con zoom lento, y una galería de fotos en el bloque «La Concha, nuestro tablero».
- En el resto de hojas, una foto de Donosti en segundo plano, detrás de la cabecera y con un movimiento suave, para que lo importante sea la información.
- Si el dispositivo tiene activado «reducir movimiento», las fotos se quedan quietas.

## Qué incluye

- Web de una sola página, bilingüe (castellano y euskera), con secciones de Club, Legado, Escuela, Torneos, Equipos, Noticias, Juego del caballo y Contacto.
- Tipografía Manrope (títulos) e Inter (texto), con tamaños fluidos.
- Formularios de consulta, inscripción a clases y alta de socio en la página de contacto.
- Aviso legal, privacidad, cookies, condiciones de inscripción e información sobre menores.

## Formularios

Los formularios envían los datos por correo a través de [FormSubmit](https://formsubmit.co/):

- Consultas → `contacto@grosxake.com`
- Inscripción a clases y alta de socio → `xakegros@telefonica.net`

El primer envío a cada dirección manda un correo de activación que alguien del club tiene que confirmar. Por seguridad, la ficha no pide el número de cuenta bancaria.

## Fotografías

Todas las fotos son de [Unsplash](https://unsplash.com/) y se usan bajo la [licencia de Unsplash](https://unsplash.com/license):

| Archivo | Autor | Foto |
|---|---|---|
| `hero-bahia.jpg` | David Vives | [2sxovJvkmHs](https://unsplash.com/photos/2sxovJvkmHs) |
| `hero-barcos.jpg` | Andrea Huls Pareja | [22k-RQexVT8](https://unsplash.com/photos/22k-RQexVT8) |
| `hero-urgull.jpg` | Hans-Jürgen Weinhardt | [jdEkLgP4WqM](https://unsplash.com/photos/jdEkLgP4WqM) |
| `barandilla.jpg` | Lucian Alexe | [maCNBAhdG_w](https://unsplash.com/photos/maCNBAhdG_w) |
| `entrada-bahia.jpg` | Alex Caza | [0sRqwncC87M](https://unsplash.com/photos/0sRqwncC87M) |
| `playa.jpg` | Kylie Paz | [P8YcW1vvjpE](https://unsplash.com/photos/P8YcW1vvjpE) |
| `puerto-bahia.jpg` | Andrea Huls Pareja | [CpvqyTPJ6qQ](https://unsplash.com/photos/CpvqyTPJ6qQ) |
| `desde-lo-alto.jpg` | David Vives | [WpEhWesE5wU](https://unsplash.com/photos/WpEhWesE5wU) |
| `arcos.jpg` | thomas cook | [ETxgegRI5xM](https://unsplash.com/photos/ETxgegRI5xM) |
| `velas.jpg` | sharon wright | [MlAqFBDJdeI](https://unsplash.com/photos/MlAqFBDJdeI) |
| `noche-igueldo.jpg` | Raúl Cacho Oses | [wxem-o1RMWs](https://unsplash.com/photos/wxem-o1RMWs) |
| `ciudad.jpg` | Quick PS | [ComgJww3q1U](https://unsplash.com/photos/ComgJww3q1U) |
| `playa-verano.jpg` | Hans-Jürgen Weinhardt | [qLrFMO_tg6g](https://unsplash.com/photos/qLrFMO_tg6g) |
| `puerto.jpg` | Andrea Huls Pareja | [lK-BljeH5bM](https://unsplash.com/photos/lK-BljeH5bM) |
| `bahia-barcos.jpg` | Andrea Huls Pareja | [9etLlD9f8BI](https://unsplash.com/photos/9etLlD9f8BI) |

## Estructura

```
index.html      página completa (estilos y textos incluidos)
js/app.js       navegación, idiomas, calendario, formularios y juego
js/scene.js     escena 3D de la v1 (se mantiene para que el repositorio sea idéntico al artifact; esta versión no la carga)
img/logo.png    logo del club
img/donosti/    fotografías de Donosti
```

La página no se indexa en buscadores (`noindex`) para no confundirse con la web oficial.
