# **Capítulo V: Product Implementation, Validation & Deployment.**
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration

- ### Proyect Management:
    * ### Whatsapp: 
        Una plataforma de comunicación instantánea, compatible con sistemas operativos Android e iOS, desarrollada por Meta. También dispone de una versión en línea para su uso a través de navegadores web. <br>
        [Link De Descarga](https://www.whatsapp.com/download//?l=uz&lang=es)
    * ### Discord:
      Una herramienta de mensajería instantánea diseñada para organizar y facilitar reuniones internas semanales. <br>
        [Link De Descarga](https://discord.com/download)
- ### Requirement Management:
    * ### Miro:
      Un sistema que ofrece una amplia gama de plantillas diseñadas para abordar diversos aspectos en la creación y gestión de proyectos. <br>
      [Link De Registro o Inicio De Sesión](https://miro.com/es/login/)
    * ### UXPressia:
      Es una herramienta en línea que simplifica el proceso de mapeo y comprensión de las necesidades del cliente en un proyecto determinado. <br>
      [Link De Registro o Inicio De Sesión](https://uxpressia.com)
    * ### Structurizr:
      Se trata de una suite de herramientas que posibilita la creación colaborativa de modelos C4 para representar de forma gráfica nuestros productos. <br>
      [Link De Registro o Inicio De Sesión](https://structurizr.com)  
- ###  Product UX/UI Design:
    * ### Figma:
      Una herramienta de colaboración que facilita el desarrollo conjunto de wireframes y mockups. <br>
      [Link De Registro,Inicio De Sesión y Descarga](https://www.figma.com/downloads/)
    * ### LucidChart:
      Una herramienta colaborativa que posibilita la creación conjunta de wireframes flow y mockups flow. <br>
      [Link De Registro o Inicio De Sesión ](https://www.lucidchart.com/pages/es)
- ###  Software Development:
    * ### HTML5:
      Es un lenguaje de etiquetado utilizado para crear la estructura a páginas web. Lo utilizamos para incluir componentes como texto, imágenes, enlaces, botones y videos en nuestras páginas web. <br>
      [Informacion Relacionada](https://www.esic.edu/rethink/tecnologia/html5-que-es-caracteristicas-y-como-funciona-c#:~:text=El%20HTML5%20es%20un%20estándar,%2C%20estilo%20de%20letra%2C%20etc.)
    * ### CSS:
      Un lenguaje de diseño gráfico utilizado para dar formato y estilo a la presentación de un documento escrito en HTML. <br>
      [Informacion Relacionada](https://developer.mozilla.org/es/docs/Web/CSS)
    * ### JavaScript:
      Un lenguaje de programación orientado a objetos dinámico que utilizamos para implementar funcionalidades en un documento HTML. <br>
      [Informacion Relacionada]( https://developer.mozilla.org/es/docs/Web/JavaScript )
    * ### WebStorm:
      Un entorno de desarrollo integrado (IDE) que emplearemos para trabajar con JavaScript. <br>
      [Link De Descarga]( https://www.jetbrains.com/es-es/webstorm/)

- ###  Software Testing:
    * ### Lenguaje Gherkin:
      Se trata de un Lenguaje Específico de Dominio (DSL), diseñado específicamente para abordar un problema particular. Es un lenguaje comprensible para los desarrolladores, destinado a resolver necesidades concretas. <br>
- ###  Software Documentation:
    * ### Github:
      Se trata de una plataforma utilizada para el alojamiento de versiones del código fuente de un proyecto. Es una herramienta ampliamente popular en el trabajo colaborativo de programadores. <br>
      [Link De Descarga]( https://desktop.github.com)
      [Link De Registro o Inicio De Sesión](https://github.com/login)
- ###  Software Deployment:
    * ### GitHub Pages: 
      Una plataforma que posibilita la realización de despliegues simples directamente desde un repositorio de GitHub. <br>

### 5.1.2. Source Code Management.
Landing Page Repository: [Landing Page Repository](https://github.com/Teemo-Solutions/Landing-Page_OpenSource)
- #### GitFlow Implementation:
Para implementar el flujo de trabajo Gitflow utilizando Git como nuestra herramienta de control de versiones, nos basamos en la entrada de blog "A successful Git branching model" de Vincent Driessen. Esta referencia nos permitió establecer las convenciones detalladas que serán aplicadas en nuestro proyecto 
![Gitflow Vincent Driessen ](assets/chapter05/Gitflow_graphic.png)

### **Master o Main branch**
La rama principal de desarrollo del proyecto es la Master branch. En esta rama reside el código que actualmente se encuentra en producción.
#### Notación: master o main

### **Develop branch**
La rama "Develop" albergará las más recientes actualizaciones y cambios agregados que serán incluidos en la próxima versión del proyecto. Esta rama sirve como un espacio para la integración y prueba continua de los cambios antes de ser fusionados con la rama principal "Master" para su despliegue en producción.
#### Notación: develop

### **Release branch**
La rama de lanzamiento (Release branch) facilitará la preparación de una nueva versión del producto. Esta rama permitirá la corrección de errores y permitirá que la rama Develop reciba más actualizaciones.
<br>Debe derivarse de la rama Develop.
<br>Debe fusionarse con la rama Develop y Master.
#### Notación: release


### **Feature branch**
Las ramas de características (Feature branches) serán empleadas para desarrollar nuevas funcionalidades o características del producto que se agregarán en la siguiente versión o en versiones futuras. Estas funcionalidades deberán fusionarse eventualmente con la rama Develop.
<br>Debe derivarse de la rama Develop.
<br>Debe fusionarse de vuelta a la rama Develop.
#### Notación: release


### **Hotfix branch**
La rama de corrección rápida (Hotfix branch) se empleará para resolver y actuar de manera inmediata ante posibles errores en la versión en producción del producto. La característica principal de esta rama es que permite preparar una solución rápida mientras el resto del equipo continúa trabajando en otras funcionalidades o mejoras.
<br>Debe derivarse de la rama Master
<br>Debe fusionarse con la rama Develop y Master
#### Notación: hotfix


### **Conventional Commits**
"Conventional Commits" es una convención para estructurar los mensajes de confirmación (commits) en un formato estándar y semántico. Este formato ayuda a comunicar claramente los cambios realizados en el código y facilita la generación de registros de cambios automáticos. Los "Conventional Commits" suelen seguir un formato que incluye un encabezado, un cuerpo opcional y un pie de página opcional, y se utilizan para describir de manera sucinta y clara los cambios realizados en el código, lo que facilita su seguimiento y comprensión por parte de los desarrolladores y otros miembros del equipo.
<br>
La estructura de un commit debe seguir las siguientes pautas:
~~~
git commit -m “<type>[optional scope]: <title>“ -m “<description”
~~~
**Tipos De Conventional Commits**
~~~
1. **feat**: Se usa para describir una nueva característica o funcionalidad añadida al código.
2. **fix**: Indica una corrección de errores o solución a un problema.
3. **docs**: Se emplea para cambios o mejoras en la documentación del código.
4. **style**: Describe cambios relacionados con el formato del código, como espacios en blanco, sangrías, etc., que no afectan su funcionalidad.
5. **refactor**: Se utiliza para modificaciones en el código que no corrigen errores ni añaden nuevas funcionalidades, sino que mejoran su estructura o legibilidad.
6. **test**: Indica la adición o modificación de pruebas unitarias o funcionales.
7. **chore**: Se usa para cambios en el proceso de construcción o tareas de mantenimiento que no están directamente relacionadas con el código en sí.
8. **perf**: Describe mejoras de rendimiento en el código.
~~~


### 5.1.3. Source Code Style Guide & Conventions.
Como norma general, se espera que todo el código desarrollado por los miembros del equipo esté completamente redactado en inglés.
- ### HTML 
    - #### Use Lowercase Element Names:
        Es recomendable utilizar minúsculas o lowercase para los nombres de los elementos HTML.
        ~~~ 
      <body>
            <p>Esto es un párrafo</p>
      <body>
       ~~~
    - #### Close All HTML Elements:
        Es recomendable cerrar todos los elementos HTML correctamente.
        ~~~ 
      <body>
            <p>Esto es un párrafo</p>
            <p>Esto es otro párrafo</p>
      <body>
       ~~~
    - #### Use Lowercase Attribute Names:
        Es recomendable utilizar minúsculas para los nombres de los atributos HTML.
      ~~~ 
      <a href="https://www.w3schools.com/html/">Visit our HTMLtutorial</a>
       ~~~
    - #### Always Specify alt, width, and height for Images:
      Es recomendable seguir estas convenciones en caso de que la imagen no se pueda mostrar, lo que ayuda a mejorar la accesibilidad del contenido.
      ~~~ 
      <img src="html5.gif" alt="HTML5" 
      style="width:128px;height:128px">
      ~~~ 
    - #### Spaces and Equal Signs:
      Se recomienda no utilizar espacios en blanco entre las entidades para mejorar la legibilidad.
      ~~~ 
      <link rel="stylesheet" href="styles.css">
      ~~~ 
- ### CSS
    - #### ID and Class Naming
      Es recomendable utilizar nombres de clases y IDs significativos que expresen claramente el propósito del elemento.
      ~~~ 
      #gallery {}
      #login {}
      .video {}
       ~~~
    - #### ID and Class Name Style
      Se recomienda utilizar nombres cortos para nombrar IDs o clases, pero lo suficientemente descriptivos para entender su propósito.
      ~~~ 
      #nav {}
      .author {}
      ~~~
    - #### Shorthand Properties
      Se recomienda utilizar propiedades CSS de forma abreviada siempre que sea posible para hacer el código más eficiente y comprensible.
       ~~~ 
       border-top: 0;
       font: 100%/1.6 palatino, georgia, serif;
       padding: 0 1em 2em;
       ~~~ 
    - #### 0 and Units
      Es recomendable evitar especificar la unidad después del valor 0 en propiedades que lo permitan, ya que esto ayuda a reducir el tamaño del código y mejora su legibilidad.
       ~~~ 
       margin: 0;
       padding: 0;
       ~~~
     - #### Declaration Order
       Se recomienda ordenar las declaraciones en orden alfabético para facilitar el mantenimiento y la recordación del código.
       ~~~ 
        background: fuchsia;
        border: 1px solid;
        border-radius: 4px;
        color: black;
        text-align: center;
        text-indent: 2em;
       ~~~  
- ### JAVASCRIPT
     - #### Use expanded syntax
       Cada línea de JavaScript debería estar en una nueva línea, con la llave de apertura en la misma línea de su declaración y la llave de cierre en una nueva línea al final.
       ~~~ 
       function myFunc() {
        console.log('Hello!');
       };
       ~~~
     - #### Variable naming
       Para el nombre de las variables, se recomienda utilizar lowerCamelCase. 
       ~~~ 
       let playerScore = 0;
       let speed = distance / time;
       ~~~  
     - #### Declaring variables
       Para la declaración de variables, es recomendable utilizar las palabras reservadas let y const en lugar de var.
       ~~~ 
       const myName = 'Chris';
       console.log(myName);
       let myAge = '40';
       myAge++;
       console.log('Happy birthday!');
       ~~~ 
     - #### Function naming
       Para el nombre de las funciones, se recomienda utilizar lowerCamelCase.
       ~~~ 
       function sayHello() {
       alert('Hello!');
       };
       ~~~ 
- ### C#
    - #### PascalCase
      Mayúscula al principio de cada palabra para nombres de clases y métodos.
      ~~~ 
      public class MiClase {
          public void MetodoEjemplo() {
              // Código del método
          }
      }
      ~~~
    - #### camelCase
      Minúscula al principio con mayúsculas para cada palabra subsiguiente para variables y parámetros.
      ~~~ 
      public class MiClase {
          public void MetodoEjemplo(int numeroEjemplo) {
              string nombreEjemplo = "Ejemplo";
              // Código del método      
          }
      }
      ~~~
    - #### Reasonable line length
      Mantener líneas de código con longitud adecuada para mejorar la legibilidad.
      ~~~ 
      public class MiClase {
          public void MetodoEjemplo() {
              string mensaje = "Este es un mensaje de ejemplo que ocupa varias líneas " +
                               "para demostrar cómo mantener una longitud razonable.";
               Console.WriteLine(mensaje);  
        }
      }
      ~~~ 
    - #### Clear comments:
      Utilizar comentarios para explicar el propósito del código de manera concisa.
      ~~~ 
      public class MiClase {
      // Este método realiza una operación de suma y retorna el resultado.
      public int Sumar(int a, int b) {
      return a + b;
      }
      }
      ~~~
    - #### Single responsibility:
      Cada clase o método debe tener una única función bien definida.
      ~~~ 
      // Clase responsable de manejar operaciones matemáticas básicas
      public class OperacionesMatematicas { 
          // Método para sumar dos números 
          public int Sumar(int a, int b) { 
              return a + b; 
          } 
       
          // Método para restar dos números 
          public int Restar(int a, int b) { 
              return a - b; 
          } 
      }
      ~~~
- ### LENGUAJE GHERKIN
    - #### Descriptive and concise titles for scenarios
      Utilizar títulos descriptivos y concisos para los escenarios.
      ~~~ 
      Feature: Login
        Scenario: Successful login
          Given a user is on the login page     
          When they enter valid credentials     
          Then they should be logged in successfully      
      ~~~
    - #### Follow the Given-When-Then structure consistently.
      Seguir la estructura de Given-When-Then de manera consistente.
      ~~~ 
      Scenario: Adding items to the shopping cart
        Given the user is on the shopping page
        When they add an item to the cart
        Then the item should appear in the cart 
      ~~~
    - #### Focus on business-readable language
      Centrarse en un lenguaje legible para el negocio, evitando detalles técnicos de implementación.
      ~~~ 
      Scenario: Changing user settingst
        Given the user is logged in
        When they navigate to the settings page
        Then they should be able to update their profile
      ~~~
    - ####  Utilize Scenario Outline for scenarios with multiple similar cases.
      Utilizar Scenario Outline para escenarios con múltiples casos similares.
      ~~~ 
      Scenario Outline: Searching for products
        Given the user is on the search page
        When they search for "<product>"
        Then they should see search results for "<product>"
      
      Examples:
        | product  |
        | Laptop   |
        | Smartphone |
      ~~~
    - #### Add comments to provide additional context
      Agregar comentarios para proporcionar contexto adicional o explicaciones cuando sea necesario.
      ~~~ 
      # This scenario checks the functionality of the logout feature
      Scenario: User logout
        Given the user is logged in
        When they click on the logout button
        Then they should be redirected to the login page      
      ~~~
      
### 5.1.4. Software Deployment Configuration.
- Creacion Landing Page:<br>
1. Se crea un repositorio remoto en GitHub
![CreacionRepositorio](assets/chapter05/paso1.png)
2. Agregar a participantes
![CreacionRepositorio](assets/chapter05/paso2.png)
3. Habilitmos Gitgub Pages en branch "master" y ruta "/(root)"
   ![CreacionRepositorio](assets/chapter05/paso3.png)
4. ya se puede visualizar la landing page en la siguiente ruta: [landing page](https://teemo-solutions.github.io/Landing-Page_OpenSource/)
   ![CreacionRepositorio](assets/chapter05/paso4.png)
## 5.2. Landing Page, Services & Applications Implementation.
## 5.2.X. Sprint n
## 5.2.X.1. Sprint Planning n.
## 5.2.X.2. Sprint Backlog n.
## 5.2.X.3. Development Evidence for Sprint Review.
## 5.2.X.4. Testing Suite Evidence for Sprint Review.
## 5.2.X.5. Execution Evidence for Sprint Review.
## 5.2.X.6. Services Documentation Evidence for Sprint Review.
## 5.2.X.7. Software Deployment Evidence for Sprint Review.
## 5.2.X.8. Team Collaboration Insights during Sprint.
## 5.3. Validation Interviews.
## 5.3.1. Diseño de Entrevistas.
## 5.3.2. Registro de Entrevistas.
## 5.3.3. Evaluaciones según heurísticas.
## 5.4. Video About-the-Product.
## 
# Conclusiones
## Conclusiones y recomendaciones.

### Conclusiones

-Validación de Problemas y Necesidades: Se ha confirmado que tanto los gamers como las empresas desarrolladoras enfrentan desafíos significativos en el descubrimiento y promoción de videojuegos. Los gamers buscan recomendaciones personalizadas y una experiencia social enriquecedora, mientras que los desarrolladores necesitan visibilidad en un mercado saturado.

-Efectividad de la Plataforma: La propuesta de una plataforma que integre recomendaciones personalizadas y funciones sociales ha sido validada. Los usuarios valoran la capacidad de descubrir nuevos juegos que se alineen con sus intereses y de interactuar con otros jugadores. Esto respalda la hipótesis de que una solución unificada puede mejorar la experiencia del usuario.

-Importancia de la Interacción Social: La interacción social se ha identificado como un factor crítico para la retención de usuarios. Los gamers desean conectarse con amigos y compartir experiencias, lo que indica que las características sociales deben ser una prioridad en el desarrollo del producto.

-Criterios de Éxito: Los criterios de éxito establecidos, como la tasa de conversión a suscripciones premium y el crecimiento de la comunidad de gamers, son relevantes y deben ser monitoreados de manera continua para asegurar que la plataforma cumpla con las expectativas de los usuarios.

### Recomendaciones

-Desarrollo de Funcionalidades Clave: Se recomienda priorizar el desarrollo de algoritmos de recomendación más precisos y mejorar las características sociales de la plataforma, como chats en tiempo real y grupos de discusión.

-Validación Continua: Implementar un ciclo de retroalimentación constante con los usuarios para ajustar y mejorar la experiencia de la plataforma. Esto incluye pruebas A/B y encuestas para obtener información directa sobre la satisfacción del usuario.

-Estrategias de Marketing: Fortalecer las campañas de marketing dirigidas a gamers y desarrolladores, utilizando influencers y colaboraciones estratégicas para aumentar la visibilidad de Vortex.

-Expansión de la Base de Usuarios: Evaluar la posibilidad de expandir la plataforma a otros segmentos de usuarios, como jugadores casuales, para diversificar la base de usuarios y aumentar el potencial de ingresos.

-Monetización y Alianzas: Refinar el modelo de suscripción premium y explorar alianzas con desarrolladores para ofrecer promociones exclusivas, lo que podría aumentar la retención de usuarios y generar ingresos adicionales.

## Video About-the-Team.
# Bibliografía
# Anexos