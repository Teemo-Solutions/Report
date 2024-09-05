# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS 

![icon-upc](assets/UPC_logo_transparente.png)

## DESARROLLO DE APLICACIONES OPEN SOURCE (SV54)
### PROFESOR: Hugo Allan Mori Paiva
### Informe TB1
### START UP: Teemo Solutions
### PRODUCTO: Vortex

#### INTEGRANTES:
- Andrés Alberto Torres García (U202220528)
- Fernando Jesus Lizano Coll Cardenas (u202214522)
- Yasser Renteria Palacios (u202214130)
- Vicente Quijandria Araneda (u201822697)
- Jose Miguel Riega Salas (u202211254)

---
# Registro de Versiones del Informe
|       Versión       |   Fecha    | Autor | Descripción de modificación| 
|:-------------------:|:----------:|:-----:|:---------------------------| 
| Primera Entrega TB1 | 28/03/2024 |Todos los integrantes del equipo| El equipo completo colaboró en la definición de la solución propuesta, llevando a cabo un análisis Lean UX y definiendo el segmento objetivo. Además, se recopilaron todos los requisitos necesarios para desarrollar las herramientas requeridas, incluyendo User Persons, User stories, Product Backlog, e Impact Mapping, entre otros elementos. Posteriormente, se procedió al diseño de los mockups y prototipos de la página de inicio basándose en la información recabada. Finalmente, se completó la creación de la página de inicio con la ayuda del sprint backlog, asegurando así un control efectivo de los progresos realizados.|

---
# Project Report Collaboration Insights
Para este proyecto hemos utilizado las herramientas GitHub  para gestionar el progreso grupal.

Se puede acceder al contenido de la organización en GitHub mediante el siguiente enlace:
[Teemo.com](https://github.com/Teemo-Solutions/Report-OpenSource.git)
---

| Criterio Específico | Acciones Realizadas | Conclusiones |
|---------------------|----------------------|--------------|
| ABET – EAC - Student Outcome 3: Capacidad de comunicarse efectivamente con un rango de audiencias | <br><br>Fernando Lizano:<br>Lideró el proyecto y ayudó en todos los puntos del informe de incio hasta el final de la entrega. Además, hizo gran parte de la Landing Page..<br><br>Yasser Rentería:<br>Ayudó en la mayoría de puntos del informe de inicio a fin, comunicandose con sus compañeros constantemente y apoyando en la Landing.<br><br>Andres Torres:<br>Diseñó los diagramas necesario de base de datos y clase. Además que se reunió cuando el equipo lo necesitaba y ayudó en la Landing.<br><br>José Riega:<br>Realizó el Imapct Mapping.<br><br>Vicente Quijandria<br>Hizó el problem statemnt y una entrevista de segmento objetivo empresa desarrolladora de videojuegos | Los estudiantes demostraron una sólida capacidad para comunicarse efectivamente con diversas audiencias. Utilizaron una variedad de medios y técnicas, incluyendo presentaciones orales, informes escritos, sesiones de retroalimentación, contenido multimedia y comunicación interpersonal. Adaptaron su lenguaje y enfoque según el público objetivo, desde expertos técnicos hasta el público general. Esta diversidad de habilidades comunicativas les permitió transmitir información compleja de manera clara y accesible, facilitando la colaboración en equipo y la difusión efectiva del proyecto a diferentes grupos de interés. |
# Contenido
## Tabla de Contenidos
### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome-1)
### [Capítulo I: Introducción](#capc3adtulo-i-introduccic3b3n-1)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capc3adtulo-ii-requirements-elicitation--analysis-1)
- [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)

### [Capítulo III: Requirements Specification](#capc3adtulo-iii-requirements-specification-1)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capc3adtulo-iv-product-design-1)
- [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)

### [Capítulo V: Product Implementation, Validation & Deployment](#capc3adtulo-v-product-implementation-validation--deployment-1)
- [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
        - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
        - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
        - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
        - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
        - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
        - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
        - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
        - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

### [Conclusiones](#conclusiones-1)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

### [Bibliografía](#bibliografc3ada-1)
### [Anexos](#anexos-1)

Conclusiones y Recomendaciones

Bibliografía
