# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.

### Gamers

<img src="/assents/to-be-scenario-gamers.png" alt="to-be-scenario-gamers" />

### Desarrolladoras

<img src="/assents/to-be-scenario-desarrolladoras.png" alt="to-be-scenario-desarroladoras"/>

## 3.2. User Stories.

Este documento presenta un conjunto de **User Stories** y **Epics** para la plataforma de videojuegos orientada tanto a **Gamers Entusiastas** como a **Desarrolladores de Videojuegos**. Se incluye el formato de historias de usuario, donde cada una tiene criterios de aceptación en el formato Gherkin, y se presentan tanto las historias para la interfaz del usuario final como las **Technical Stories** para el RESTful API.

---

## Epics

### Epic 1: Recomendaciones Personalizadas (Gamers Entusiastas)
Como gamer entusiasta, quiero recibir recomendaciones personalizadas de juegos basadas en mi historial de juegos y mis preferencias, para descubrir juegos que puedan interesarme.

### Epic 2: Experiencia Social en la Plataforma (Gamers Entusiastas)
Como gamer, quiero poder conectarme con amigos y ver qué juegos están jugando, para compartir mis experiencias y descubrir nuevos juegos a través de mi red social.

### Epic 3: Publicación y Gestión de Juegos Indie (Empresa Desarrolladora de Videojuegos)
Como desarrollador indie, quiero publicar y gestionar mis juegos en la plataforma, para que lleguen a una audiencia más amplia de gamers interesados en juegos independientes.

### Epic 4: Análisis de Métricas de Juego (Empresa Desarrolladora de Videojuegos)
Como desarrollador, quiero tener acceso a métricas detalladas sobre el comportamiento de los jugadores en mis juegos, para poder ajustar y mejorar la experiencia de usuario.

---

## User Stories

| Epic/Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---------------|--------|-------------|-------------------------|---------------------------|
| US01 | Filtrado de Juegos por Género | Como gamer, quiero poder filtrar juegos por género para encontrar rápidamente aquellos que me interesan. | **Given** que estoy en la sección de búsqueda, **When** selecciono un género, **Then** solo se muestran los juegos del género seleccionado. | EPIC01 |
| US02 | Recomendaciones Basadas en Género Favorito | Como gamer, quiero recibir recomendaciones de juegos en mi género favorito para descubrir más juegos similares. | **Given** que he marcado un género como favorito, **When** accedo a mi perfil, **Then** veo una lista de juegos recomendados del mismo género. | EPIC01 |
| US03 | Recomendaciones Basadas en Popularidad entre Amigos | Como gamer, quiero ver los juegos más populares entre mis amigos para descubrir qué están jugando. | **Given** que tengo amigos en la plataforma, **When** accedo a la sección de recomendaciones, **Then** veo una lista de juegos populares entre mis amigos. | EPIC01 |
| US04 | Recomendaciones Basadas en Tiempo Jugado | Como gamer, quiero que me recomienden juegos similares a aquellos en los que he invertido más tiempo, para seguir disfrutando de ese tipo de juegos. | **Given** que he jugado un juego por más de 10 horas, **When** accedo a la sección de recomendaciones, **Then** veo juegos similares en términos de género y mecánicas. | EPIC01 |
| US05 | Invitación a Amigos para Jugar | Como gamer, quiero invitar a mis amigos a jugar un juego conmigo, para compartir experiencias de juego. | **Given** que estoy en la página de un juego, **When** selecciono "Invitar a un amigo", **Then** mis amigos reciben una notificación de invitación para unirse. | EPIC02 |
| US06 | Chat en Tiempo Real | Como gamer, quiero un sistema de chat en tiempo real, para comunicarme con mis amigos mientras jugamos juntos. | **Given** que estoy en una partida con amigos, **When** accedo al chat, **Then** puedo comunicarme con ellos en tiempo real. | EPIC02 |
| US07 | Compartir Reseñas de Juegos | Como gamer, quiero compartir reseñas de los juegos que he jugado, para ayudar a otros jugadores a decidir si quieren probarlos. | **Given** que he jugado un juego, **When** accedo a la sección de reseñas, **Then** puedo escribir y publicar mi opinión sobre el juego. | EPIC02 |
| US08 | Publicar Juego Indie | Como desarrollador, quiero poder publicar mi juego indie en la plataforma, para llegar a una audiencia más amplia. | **Given** que he desarrollado un juego indie, **When** subo los archivos del juego y los detalles de la descripción, **Then** el juego se publica en la sección de juegos indie. | EPIC03 |
| US09 | Actualización de Juegos Indie | Como desarrollador, quiero poder actualizar la información de mi juego indie para corregir errores o agregar nuevas características. | **Given** que he publicado un juego, **When** hago cambios en la descripción o archivos del juego, **Then** la información se actualiza en tiempo real en la plataforma. | EPIC03 |
| US10 | Visualización de Métricas de Jugadores | Como desarrollador, quiero ver métricas detalladas sobre cómo los jugadores interactúan con mi juego, para mejorar la experiencia del usuario. | **Given** que he publicado un juego, **When** accedo a la sección de estadísticas, **Then** veo datos sobre el tiempo jugado, número de jugadores y porcentaje de finalización. | EPIC04 |
| US11 | Sistema de Revisión de Juegos | Como gamer, quiero ver reseñas de otros jugadores antes de comprar un juego, para tomar una mejor decisión de compra. | **Given** que estoy viendo un juego en la tienda, **When** accedo a la sección de reseñas, **Then** puedo leer opiniones y valoraciones de otros jugadores. | EPIC01 |
| US12 | Subir Actualizaciones de Juegos | Como desarrollador, quiero subir actualizaciones para mi juego publicado, para corregir errores y mejorar la experiencia del usuario. | **Given** que el desarrollador ha publicado un juego, **When** sube un parche o actualización, **Then** el juego se actualiza para todos los usuarios. | EPIC03 |
| US13 | Análisis de Comportamiento de Jugadores | Como desarrollador, quiero analizar el comportamiento de los jugadores para identificar puntos de fricción en mi juego. | **Given** que el desarrollador accede al panel de estadísticas, **When** revisa las métricas de nivel de dificultad o tasa de abandono, **Then** puede identificar puntos de mejora en el diseño del juego. | EPIC04 |
| US14 | Creación de Comunidades de Juego | Como gamer, quiero unirme a comunidades de jugadores de un mismo juego, para compartir estrategias y experiencias. | **Given** que accedo a la página de un juego, **When** selecciono la opción de "Unirme a la comunidad", **Then** puedo interactuar con otros jugadores en foros dedicados. | EPIC02 |
| US15 | Búsqueda de Juegos por Palabra Clave | Como gamer, quiero buscar juegos usando palabras clave, para encontrar juegos específicos rápidamente. | **Given** que estoy en la página de búsqueda, **When** ingreso una palabra clave, **Then** se muestran los juegos relacionados con esa búsqueda. | EPIC01 |
| US16 | Acceso a Demos de Juegos | Como gamer, quiero poder acceder a demos de juegos antes de comprarlos, para probar si me gustan antes de hacer una compra. | **Given** que estoy en la página de un juego, **When** hay una demo disponible, **Then** puedo descargarla y jugarla. | EPIC01 |
| US17 | Personalización de Perfil de Jugador | Como gamer, quiero personalizar mi perfil en la plataforma para reflejar mis gustos y mostrar mi progreso en los juegos. | **Given** que estoy en mi perfil, **When** selecciono la opción de personalización, **Then** puedo cambiar mi avatar, descripción y mostrar mis logros en los juegos. | EPIC02 |
| US18 | Creación de Torneos | Como desarrollador, quiero crear torneos para mi juego, para fomentar la competencia entre los jugadores. | **Given** que el desarrollador ha publicado un juego, **When** crea un torneo en la plataforma, **Then** los jugadores pueden unirse y competir por premios. | EPIC03 |
| US19 | Visualización de Rankings de Jugadores | Como gamer, quiero ver mi posición en el ranking de jugadores de un juego, para comparar mi progreso con el de otros jugadores. | **Given** que estoy jugando un juego, **When** accedo a la sección de rankings, **Then** puedo ver mi posición en relación con otros jugadores. | EPIC02 |
| US20 | Sistema de Logros | Como gamer, quiero desbloquear logros en los juegos que juego, para mejorar mi experiencia y ganar recompensas. | **Given** que estoy jugando un juego, **When** alcanzo ciertos hitos, **Then** se desbloquean logros que se reflejan en mi perfil. | EPIC02 |
| US21 | Notificaciones en Tiempo Real | Como gamer, quiero recibir notificaciones en tiempo real cuando mis amigos comiencen a jugar un nuevo juego, para unirme a ellos de inmediato. | **Given** que estoy conectado a la plataforma, **When** un amigo comienza un juego, **Then** recibo una notificación con la opción de unirme. | EPIC02 |
| US22 | Modo Offline para Juegos Indie | Como gamer, quiero que algunos juegos indie sean jugables en modo offline, para poder jugar incluso sin conexión a internet. | **Given** que estoy jugando un juego indie compatible, **When** pierdo la conexión a internet, **Then** puedo continuar jugando en modo offline. | EPIC01 |


## 3.3. Impact Mapping.

### Gamers

<img src="/assents/Impact-Mapping-G.png" alt="Impact-Mapping-G" />

### Desarrolladoras

<img src="/assents/Impact-Mapping-D.png" alt="Impact-Mapping-D"/>

## 3.4. Product Backlog.


<table border="1">
  <tr>
    <th>Orden</th>
    <th>User Story Id</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Story Points</th>
  </tr>
  <tr>
    <td>1</td>
    <td>US01</td>
    <td>Filtrado de Juegos por Género</td>
    <td>Como gamer, quiero poder filtrar juegos por género para encontrar rápidamente aquellos que me interesan.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>2</td>
    <td>US15</td>
    <td>Búsqueda de Juegos por Palabra Clave</td>
    <td>Como gamer, quiero buscar juegos usando palabras clave, para encontrar juegos específicos rápidamente.</td>
    <td>2</td>
  </tr>
  <tr>
    <td>3</td>
    <td>US11</td>
    <td>Sistema de Revisión de Juegos</td>
    <td>Como gamer, quiero ver reseñas de otros jugadores antes de comprar un juego, para tomar una mejor decisión de compra.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>4</td>
    <td>US16</td>
    <td>Acceso a Demos de Juegos</td>
    <td>Como gamer, quiero poder acceder a demos de juegos antes de comprarlos, para probar si me gustan antes de hacer una compra.</td>
    <td>3</td>
  </tr>
  <tr>
    <td rowspan="3">5</td>
    <td rowspan="3">US02</td>
    <td rowspan="3">Recomendaciones Basadas en Género Favorito</td>
    <td>Como gamer, quiero recibir recomendaciones de juegos en mi género favorito para descubrir más juegos similares.</td>
    <td rowspan="2">3</td>
  </tr>
  <tr>
    <td>Como gamer, quiero que me recomienden juegos similares a aquellos en los que he invertido más tiempo, para seguir disfrutando de ese tipo de juegos.</td>
  </tr>
  <tr>
    <td>Como gamer, quiero ver los juegos más populares entre mis amigos para descubrir qué están jugando.</td>
    <td>5</td>

  <tr>
    <td rowspan="2">6</td>
    <td rowspan="2">US04</td>
    <td rowspan="2">Recomendaciones Basadas en Tiempo Jugado</td>
    <td>Como gamer, quiero que me recomienden juegos similares a aquellos en los que he invertido más tiempo, para seguir disfrutando de ese tipo de juegos.</td>
    <td rowspan="2">5</td>
  </tr>
  <tr>
    <td>Como gamer, quiero ver los juegos más populares entre mis amigos para descubrir qué están jugando.</td>
  </tr>
  <tr>
    <td>7</td>
    <td>US03</td>
    <td>Recomendaciones Basadas en Popularidad entre Amigos</td>
    <td>Como gamer, quiero ver los juegos más populares entre mis amigos para descubrir qué están jugando.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>8</td>
    <td>US22</td>
    <td>Modo Offline para Juegos Indie</td>
    <td>Como gamer, quiero que algunos juegos indie sean jugables en modo offline, para poder jugar incluso sin conexión a internet.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>9</td>
    <td>US05</td>
    <td>Invitación a Amigos para Jugar</td>
    <td>Como gamer, quiero invitar a mis amigos a jugar un juego conmigo, para compartir experiencias de juego.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>10</td>
    <td>US06</td>
    <td>Chat en Tiempo Real</td>
    <td>Como gamer, quiero un sistema de chat en tiempo real, para comunicarme con mis amigos mientras jugamos juntos.</td>
    <td>5</td>
  <tr>
    <td>11</td>
    <td>US14</td>
    <td>Creación de Comunidades de Juego</td>
    <td>Como gamer, quiero unirme a comunidades de jugadores de un mismo juego, para compartir estrategias y experiencias.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>12</td>
    <td>US17</td>
    <td>Personalización de Perfil de Jugador</td>
    <td>Como gamer, quiero personalizar mi perfil en la plataforma para reflejar mis gustos y mostrar mi progreso en los juegos.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>13</td>
    <td>US19</td>
    <td>Visualización de Rankings de Jugadores</td>
    <td>Como gamer, quiero ver mi posición en el ranking de jugadores de un juego, para comparar mi progreso con el de otros jugadores.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>14</td>
    <td>US20</td>
    <td>Sistema de Logros</td>
    <td>Como gamer, quiero desbloquear logros en los juegos que juego, para mejorar mi experiencia y ganar recompensas.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>15</td>
    <td>US21</td>
    <td>Notificaciones en Tiempo Real</td>
    <td>Como gamer, quiero recibir notificaciones en tiempo real cuando mis amigos comiencen a jugar un nuevo juego, para unirme a ellos de inmediato.</td>
    <td>5</td>
  </tr>
    <tr>
    <td>16</td>
    <td>US07</td>
    <td>Compartir Reseñas de Juegos</td>
    <td>Como gamer, quiero compartir reseñas de los juegos que he jugado, para ayudar a otros jugadores a decidir si quieren probarlos.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>17</td>
    <td>US08</td>
    <td>Publicar Juego Indie</td>
    <td>Como desarrollador, quiero poder publicar mi juego indie en la plataforma, para llegar a una audiencia más amplia.</td>
    <td>8</td>
  </tr>
  <tr>
    <td>18</td>
    <td>US12</td>
    <td>Subir Actualizaciones de Juegos</td>
    <td>Como desarrollador, quiero subir actualizaciones para mi juego publicado, para corregir errores y mejorar la experiencia del usuario.</td>
    <td>5</td>
  </tr>
  <tr>
    <td>19</td>
    <td>US09</td>
    <td>Actualización de Juegos Indie</td>
    <td>Como desarrollador, quiero poder actualizar la información de mi juego indie para corregir errores o agregar nuevas características.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>20</td>
    <td>US18</td>
    <td>Creación de Torneos</td>
    <td>Como desarrollador, quiero crear torneos para mi juego, para fomentar la competencia entre los jugadores.</td>
    <td>8</td>
  </tr>
    <tr>
    <td>21</td>
    <td>US10</td>
    <td>Visualización de Métricas de Jugadores</td>
    <td>Como desarrollador, quiero ver métricas detalladas sobre cómo los jugadores interactúan con mi juego, para mejorar la experiencia del usuario.</td>
    <td>8</td>
  </tr>
  <tr>
    <td>22</td>
    <td>US13</td>
    <td>Análisis de Comportamiento de Jugadores</td>
    <td>Como desarrollador, quiero analizar el comportamiento de los jugadores para identificar puntos de fricción en mi juego.</td>
    <td>8</td>
  </tr>
</table>
