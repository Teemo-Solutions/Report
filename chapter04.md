<style>
  body {
    font-family: 'Times New Roman', sans-serif;
    text-align: justify;
    font-size: 12px;
    margin-left: 2em;
    margin-right: 2em;
    line-height: 2;
  }
  
  p {
    text-indent: 2em; /* Sangría en el primer renglón de cada párrafo */
  }

  h1 {
    margin-left: 0; /* No aplica sangría para el título principal */
  }

  h2 {
    margin-left: 0; /* No aplica sangría para subtítulos de nivel 2 */
  }

  h3 {
    margin-left: 2em; /* Aplica una sangría de 2em para subtítulos de nivel 3 */
  }

  h4 {
    margin-left: 4em; /* Aplica una sangría de 4em para subtítulos de nivel 4 */
  }
</style>

# **CAPÍTULO IV: PRODUCT DESIGN**
## 4.1. Style Guidelines
En esta sección, presentaremos el concepto de diseño para la página web y la aplicación, para proporcionar a nuestros usuarios una interfaz amigable y funcional. Con este propósito en mente, hemos optado por utilizar elementos visuales que sean fáciles de percibir y que resulten atractivos a la vista.

### 4.1.1. General Style Guidelines
La paleta de colores seleccionada para la plataforma se ha diseñado con el objetivo de lograr un equilibrio visual que transmita modernidad, profesionalismo y claridad en la interfaz. Se utiliza una combinación de colores cromáticos y acromáticos para establecer una jerarquía visual coherente, enfocada en mejorar la experiencia del usuario y la legibilidad.

**Chromatic Colors:**

#300D30 (Violeta Oscuro): Este tono profundo y elegante se utiliza para destacar elementos clave, como botones importantes o encabezados, proporcionando un contraste visual que guía la atención del usuario de manera efectiva.   

<p align="center">
  <img src="assets/chapter04/violet.png" style="width:500px; height:auto;">
</p>

**Achromatic Colors:**

#F4F7FA (Gris muy claro): Este color se emplea como fondo principal para áreas extensas, ofreciendo una base neutra y suave que no cansa la vista, manteniendo una atmósfera limpia y ligera.

<p align="center">
  <img src="assets/chapter04/somewhite.png" style="width:500px; height:auto;">
</p>

#FFFFFF (Blanco puro): Se utiliza en secciones que requieren máxima claridad, como el fondo de textos o formularios, asegurando una legibilidad óptima y una presentación pulida.

<p align="center">
  <img src="assets/chapter04/white.png" style="width:500px; height:auto;">
</p>

#000000 (Negro): Aplicado para textos o iconos en áreas donde el contraste es crucial para la lectura, especialmente en textos sobre fondos claros.

<p align="center">
  <img src="assets/chapter04/black.png" style="width:500px; height:auto;">
</p>

### 4.1.2. Web Style Guidelines
**Typography: DM Sans**

La tipografía principal utilizada será DM Sans, seleccionada por su simplicidad, legibilidad y modernidad. Asegura una experiencia de lectura clara tanto en pantallas pequeñas como grandes, lo que la hace ideal para la interfaz de nuestra plataforma de videojuegos.

Este enfoque asegura que se respeten los principios de diseño modernos y que el estilo tipográfico sea consistente en toda la aplicación.

**Icon:**

Nuestro logo está inspirado en el concepto de vortex, en línea con la temática espacial de la plataforma. Representa un remolino dinámico, evocando movimiento y descubrimiento. El color predominante del logo es el violeta, que es nuestro color principal y representativo, simbolizando creatividad y misterio, mientras mantiene una conexión visual con el espacio y la tecnología.

<p align="center">
  <img src="assets/chapter04/vortex_icon.svg" style="width:500px; height:auto;">
<br><br>
  <img src="assets/chapter04/vortex_icon_white.svg" style="width:500px; height:auto;">
</p>

Este enfoque resalta la identidad visual del logo y su conexión con la temática del proyecto.

## 4.2. Information Architecture

La arquitectura de la información de nuestra plataforma establece la estructura y organización de todos los elementos clave, facilitando la navegación eficiente y la experiencia de usuario. Está diseñada para asegurar que los usuarios, tanto desarrolladores como gamers, puedan acceder de manera intuitiva a las funcionalidades principales, como la creación de perfiles, recomendaciones personalizadas, y promoción de videojuegos. La jerarquía de información y los flujos de navegación están optimizados para una interacción fluida, asegurando que cada usuario encuentre lo que busca rápidamente y sin complicaciones.

Como equipo, hemos decidido implementar los patrones de diseño Z y F para optimizar la experiencia del usuario en la plataforma. Estos patrones son conocidos por guiar la vista del usuario de manera eficiente a través del contenido clave. Además, hemos asegurado que la plataforma sea completamente responsive, lo que significa que ofrecerá una experiencia óptima en dispositivos de diferentes tamaños, desde móviles hasta pantallas de escritorio.### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems
**Menú Principal: Home**

1. Home: Punto de inicio para los usuarios, donde podrán acceder a recomendaciones personalizadas y noticias relevantes de la industria de videojuegos.
2. About us: Información sobre la misión y visión de Vortex, los servicios que ofrecemos, y la historia detrás del proyecto.
3. Subscriptions: Sección dedicada a las diferentes opciones de suscripción, ofreciendo a los usuarios acceso a características premium.
4. Comunidad: Espacio donde los usuarios pueden interactuar, compartir experiencias y recomendaciones de videojuegos.
5. Testimonios: Opiniones y reseñas de usuarios y empresas desarrolladoras sobre el impacto de Vortex en su experiencia.
6. Contact: Información de contacto para asistencia, soporte técnico y consultas generales.
7. Login: Para acceder al perfil del usuario y sus funciones personalizadas.

Las secciones Comunidad y About Us contarán con menús desplegables, lo que permitirá a los usuarios acceder a subcategorías y explorar contenido adicional de manera más organizada y eficiente. Esto contribuirá a mejorar la navegación dentro de la plataforma, facilitando una experiencia más intuitiva.

1. **Home:**
   La página principal será el punto de partida de los usuarios, brindando acceso directo a las secciones más importantes de la plataforma, con un diseño enfocado en la accesibilidad y claridad de la información. Aquí se destacarán los juegos recomendados, las novedades, y cualquier anuncio relevante para los gamers y desarrolladores.
   <br><br>
2. **About Us:**
   Esta sección contará con un menú desplegable que incluirá diferentes subsecciones, tales como la historia de Vortex, la misión y visión de la plataforma, así como el equipo detrás del proyecto. La intención es que los usuarios puedan conocer en detalle el propósito de la plataforma y a las personas que la han hecho posible.
   <br><br>
3. **Subscriptions:**
   En esta sección se ofrecerán diferentes planes de suscripción para acceder a funcionalidades avanzadas, como recomendaciones más precisas, conexión ilimitada con otros gamers, y acceso a juegos exclusivos. Se presentarán de forma clara las diferencias entre los tipos de suscripciones disponibles y sus beneficios.
   <br><br>
4. **Comunidad:**
   La sección de Comunidad incluirá un menú desplegable que permitirá a los usuarios acceder a distintas subcategorías como foros, grupos de discusión, eventos organizados por la comunidad, y noticias sobre la industria de los videojuegos. Este espacio será clave para fomentar la interacción y la colaboración entre gamers y desarrolladores.
   <br><br>
5. **Testimonios:**
   Aquí los usuarios podrán ver reseñas y testimonios de otros gamers y desarrolladores que han utilizado la plataforma. Será una herramienta útil para crear confianza en los nuevos usuarios y destacar la experiencia positiva de la comunidad.
   <br><br>
6. **Contact:**
   La sección de Contact permitirá a los usuarios ponerse en contacto con el equipo de soporte de la plataforma, ya sea para resolver dudas, sugerir mejoras o reportar problemas. Incluirá un formulario de contacto y posiblemente un chatbot para asistencia rápida.
<br><br>
7. **Login:**
   El Login será el acceso a los perfiles de usuario, permitiendo a los gamers y desarrolladores iniciar sesión, crear cuentas nuevas, o recuperar credenciales. Una vez logueados, los usuarios tendrán acceso a sus recomendaciones personalizadas, listas de amigos y gestión de su suscripción.

**Consideraciones a Implementar:**
1. **Novedades:** Es esencial incluir una sección dedicada a Novedades, donde los usuarios puedan descubrir los juegos más recientes que han sido lanzados en la plataforma. Esta sección destacará juegos populares, nuevos lanzamientos y actualizaciones de títulos ya disponibles.
2. **Tienda:** La implementación de una Tienda será clave para permitir la compra de juegos directamente desde la plataforma. Los desarrolladores podrán ofrecer sus títulos a los gamers, quienes podrán adquirirlos utilizando diferentes métodos de pago. Esto no solo proporcionará una nueva fuente de ingresos para los desarrolladores, sino que también facilitará a los usuarios el acceso a nuevos juegos sin salir de la plataforma. Además, se podrían ofrecer ofertas exclusivas y descuentos para aquellos que tengan suscripciones avanzadas.
3. **Sistema de Puntos**: Para incentivar la participación y fidelización de los usuarios, se debería considerar la implementación de un Sistema de Puntos propio de la plataforma. Los gamers podrían acumular puntos al completar ciertas acciones como recomendar juegos, escribir reseñas, o participar en eventos de la comunidad. Estos puntos podrían ser canjeables por descuentos en la tienda, acceso anticipado a ciertos juegos o contenidos exclusivos, mejorando la experiencia del usuario y fomentando la permanencia en la plataforma.


**Otras Funcionalidades (Posible Expansión):**

Cambio de Perfil: Los usuarios podrán actualizar su información personal, foto de perfil y preferencias desde un panel de configuración fácil de usar.

Manejo de Configuraciones: La plataforma permitirá ajustar configuraciones como el idioma de la interfaz y el fondo del perfil para personalizar la experiencia del usuario de acuerdo con sus preferencias.

Además, se contará con una barra de navegación en todo momento en la parte superior de la página. Además de tener un Botón en el lado derecho. Con la finalidad de ayudar al usuario a ir de manera más rápida a la parte superior de la página.

### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary
## 4.8. Database Design
### 4.8.1. Database Diagram