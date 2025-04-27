<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="150" alt="UPC Logo">

# Universidad Peruana de Ciencias Aplicadas

### **CURSO:** Desarrollo de Aplicaciones Open Source


### **NRC**: 4334

### **Profesor:** Hugo Allan Mori Paiva


### **Ingeniería de software**

## Informe de Trabajo Final


### **Nombre del startup:** APX-01

### **Nombre del producto:** EduHive


## **Integrantes**


| **Nombre**                             | **Codigo** |
| -------------------------------------- | ---------- |
| **Alejo Cardenas Jose Antonio**        | U202122484 |
| **Luquillas Asto Omar**                | U20211G641 |
| **Real Calderón Sebastián Omar**     | U20221D964 |
| **Flores Apaico Josue Antonio**        | U20201F773 |
| **Mendoza Vergara Franklin Alejandro** | U202312343 |

Abril 2025

## Registro de Versiones del Informe


| Versión | Fecha | Autor | Descripción de modificación |
| -------- | ----- | ----- | ----------------------------- |

## Project Report Collaboration Insights

## Contenido

- [Student Outcome](#student-outcome)
- [Objetivos SMART](#objetivos-smart)
- [Capítulo I](#capítulo-i)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2 Labeling Systems](#422-labeling-systems)
    - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)
    - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)
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

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)

  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## Student Outcome

## Objetivos SMART

## Capitulo I

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

APX-01 es una startup fundada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), dedicada a desarrollar soluciones tecnológicas para revolucionar la educación en Perú. Nuestro primer proyecto, EduHive, es una plataforma integral que conecta a estudiantes y profesores en un ecosistema dinámico, donde la gestión de grupos de estudio, retos académicos y tareas se simplifica y gamifica.

EduHive ofrece una experiencia integral para los estudiantes, permitiéndoles gestionar sus tareas, revisar retos académicos activos y acceder a sus horarios de clases de manera sencilla y organizada. Además, los alumnos pueden explorar los perfiles de sus profesores, conocer sus especializaciones, horarios de atención y métodos de contacto, facilitando una comunicación más fluida y efectiva. De la misma manera, los profesores pueden crear y administrar grupos de estudio en los que podrán establecer retos académicos y monitorear el progreso de sus alumnos. La plataforma también incorpora elementos de gamificación, como sistemas de puntuación y reconocimientos, para motivar el aprendizaje y fomentar la participación activa en grupos de estudio y desafíos educativos, promoviendo un ecosistema educativo dinámico, digital y accesible.

- Misión:
  "Democratizar el acceso a herramientas educativas colaborativas en Perú mediante tecnología open-source, rompiendo las barreras de la educación tradicional con soluciones gamificadas que empoderen a estudiantes y docentes por igual."
- Visión:
  "Convertirnos en el ecosistema educativo digital líder en el Perú, transformando la manera en que se aprende y enseña mediante soluciones tecnológicas orientadas a las necesidades de tanto estudiantes como docentes."

#### 1.1.2. Perfiles de integrantes del equipo

<table>
  <tr>
    <th colspan="2"> Jose Antonio Alejo Cardenas </th>
  </tr>
  <tr>
    <td> <img src="images/chapter-1/jose-pfp.jpg" alt="Jose Alejo" style="width: 500px; height: auto;"> </td>
    <td> Soy José Alejo Cárdenas, estudiante de la carrera de Ingeniería de Software del sexto ciclo. Desde pequeño he sentido facinacion por la tecnologia en general sobretodo por el funcionamiento, desarrollo y proteccion del software en el ambito de ciberseguridad. He estudiado lenguajes de programacion (javascript, python y C++), bases de datos (Microsoft SQL Server y Mongo DB) y Sistemas Operativos (Kali Linux y Windows). Asi mismo, tengo experiencia con hardware a nivel de esamblamiento de equipos y funcionamiento del mismo con sus especificaciones tecnicas. Además, mi constante comunicacion y organizacion durante cualquier trabajo grupal aportara mucho dinamismo al proyecto. Mis principales hobbies son entrenar en el gimnasio, jugar videojuegos con mis amigos y salir a conversar con estos ultimos durante algun almuerzo o cena. Para el proyecto aportare organizacion, comunicacion e inspiracion durante todo el transcurso del mismo. </td>
  </tr>
  <tr>
    <th colspan="2"> Sebastián Omar Real Calderón </th>
  </tr>
  <tr>
    <td> <img src="images/chapter-1/sebastian-pfp.jpeg" alt="b" style="width: 500px; height: auto;"> </td>
    <td> Soy Sebastián Real Calderón, estudainte de Ingeniería de Software. Tengo conocimiento de diferentes lenguajes de programación, como C#, C++ y Java. Mi mayor objetivo al desarrollar software es crear una experiencia de usuario con la que los consumidores puedan sentirse satisfechos al trabajar con nuestras aplicaciones. Asimismo, aspiro a ser un buen participante al mantener una comunicación constante con mis compañeros, resolviendo problemas y apoyándo a quién lo necesite para crear un ambiente cómodo para todos. </td>
  </tr>
  <tr>
    <th colspan="2"> Omar Luquillas Asto </th>
  </tr>
  <tr>
    <td> <img src="images/chapter-1/omar-pfp.jpg" alt="Omar Luquillas" style="width: 500px; height: auto;"> </td>
    <td> Soy Omar Luquillas Asto, estudiante de la carrera de Ingeniería de Software. Elegí esta carrera porque me apasiona la tecnología, el desarrollo de software y la programación. Tengo conocimientos en lenguajes de programación como C++, Python y Java. Me considero una persona investigadora, ya que me gusta aprender cosas nuevas y siempre estoy en busca de soluciones creativas e innovadoras que generen un impacto positivo en la vida de las personas. Además, valoro el trabajo en equipo, soy responsable y me comprometo a cumplir con mis tareas de manera eficiente. </td>
  </tr>
  <tr>
    <th colspan="2">Alejandro Mendoza</th>
  </tr>
  <tr>
    <td> <img src="images/chapter-1/Alejandro-pfp.jpg" alt="Alejandro Mendoza" style="width: 500px; height: auto;"> </td>
    <td> Mi nombre es Alejandro Mendoza y soy estudiante de la carrera de Ingeniería de Software.Actualmente tengo experiencia en C++ y Python. Estoy interesado en seguir aprendiendo sobre diferentes lenguajes de programación y en la creación de distintas aplicaciones web y móviles, por lo que intento dar todo de mí para tener buenos resultados.
    
 </td>
  </tr>
  <tr>
    <th colspan="2">Josue Flores Apaico</th>
  </tr>
  <tr>
    <td> <img src="images/chapter-1/JosueFlores.png" alt="Josue Flores Apaico" style="width: 500px; height: auto;"> </td>
    <td> Soy Josue Flores es una persona creativa, perseverante y empática, con interés en áreas como la Inteligencia Artificial, ciberseguridad y ciencia de datos. Busca aplicar sus conocimientos en C++, Python, C# y Java dentro de una startup tecnológica, impulsando la innovación y la mejora continua. Cuenta con experiencia práctica en proyectos y participación en conferencias de ciberseguridad. </td>
  </tr>
</table>

### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática

## Análisis 5W2H

### **1. WHAT (Qué)**

- Las plataformas educativas existentes no resuelven eficientemente la gestión colaborativa de grupos de estudio en el Perú.

### **2. WHY (Por qué)**

- Herramientas actuales (ej. Google Classroom) están diseñadas para gestión unilateral (profesor a alumno), no para colaboración horizontal.

### **3. WHO (Quién)**

- **Estudiantes universitarios**: Dificultad para organizar grupos de estudio efectivos.
- **Docentes**: Carga administrativa al coordinar actividades colaborativas.
- **Instituciones**: No cuentan con métricas de participación estudiantil.

### **4. WHERE (Dónde)**

- Universidades peruanas (públicas y privadas) con cursos que requieren trabajo en equipo (ej: ingenierías).

### **5. WHEN (Cuándo)**

- Durante periodos de proyectos grupales y exámenes parciales.

### **6. HOW (Cómo)**

- Estudiantes pierden 3-5 horas semanales coordinando logística grupal vía WhatsApp/email.

### **7. HOW MUCH (Cuánto)**

- Instituciones podrían reducir 30% el tiempo de gestión docente con automatización.

#### 1.2.2. Lean UX Process

El Lean UX process es una metodología iterativa de diseño que pone al usuario en el centro del proceso, enfocándose en la colaboración continua del equipo y en ciclos cortos de trabajo. A través de investigaciones, pruebas rápidas y validación constante de ideas, se busca comprobar la validez de las ideas planteadas. A diferencia de los métodos tradicionales, este evita la documentación pesada y prioriza la retroalimentación temprana para validar o descartar hipótesis de manera ágil, siempre orientándose a satisfacer las necesidades reales de los usuarios.

##### 1.2.2.1. Lean UX Problem Statements

Actualmente, los estudiantes y profesores universitarios se enfrentan a varios desafíos cuando intentan organizar sus actividades académicas y comunicarse de forma eficiente. En la mayoría de los casos, dependen de múltiples herramientas que no están conectadas entre sí, como aplicaciones de mensajería, correos electrónicos y agendas separadas, lo que provoca confusiones, olvidos y dificulta llevar un buen control de tareas y responsabilidades.

Para los estudiantes, esto significa tener que recordar plazos de entrega, participar en grupos y mantenerse al día con algunas tareas de manera dispersa. Por otro lado, los profesores tienen dificultades para crear y gestionar grupos de estudio, monitorear el progreso de sus alumnos y mantener una comunicación clara, directa y constante con ellos.

Esta situación no solo genera desorganización, sino que también puede disminuir la motivación y participación de los estudiantes, afectando su rendimiento académico. Por eso, es necesario contar con una plataforma integrada que centralice todas estas funciones, facilitando la organización de tareas, la realización de retos académicos y la interacción directa entre estudiantes y profesores, promoviendo así un entorno educativo más dinámico, ordenado y participativo.

##### 1.2.2.2. Lean UX Assumptions

**User Assumptions (Suposiciones de Usuario)**

- ¿Quién es el usuario?: Los usuarios son estudiantes y profesores universitarios que buscan mejorar la organización de sus actividades académicas, productividad y la comunicación en el entorno educativo.
- ¿Dónde encaja nuestro producto en su trabajo o vida?: Nuestro producto encaja como una herramienta diaria para planificar clases, tareas, retos académicos y la gestión de grupos de estudio, facilitando la interacción constante entre estudiantes y profesores.
- ¿Qué problemas resuelve nuestro producto?: Nuestro producto resuelve problemas de desorganización, falta de comunicación efectiva, dispersión de herramientas y baja motivación por la falta de dinamismo en las actividades académicas.
- ¿Cuándo y cómo se usa nuestro producto?: Nuestro producto se utiliza antes y después de clases, para revisar tareas pendientes, crear o unirse a grupos de estudio, consultar horarios, participar en retos académicos y comunicarse directamente con los profesores o compañeros.
- ¿Qué características son importantes?: Las características importantes son la gestión de tareas, administración de grupos de estudio, perfiles detallados de profesores, sistema de retos académicos, visualización de horarios, interfaz sencilla e intuitiva.
- ¿Cómo debe verse y comportarse nuestro producto?: Nuestro producto debe tener un diseño amigable y moderno, con navegación fluida, colores que generen motivación y claridad visual, y tiempos de respuesta rápidos para no frustrar a los usuarios.

**Business Assumptions (Suposiciones de Negocio)**

- Necesidades y problemas: Creemos que las universidades necesitan herramientas que mejoren la productividad académica y la colaboración digital entre alumnos y docentes.
- Plataforma: Estas necesidades se pueden resolver mediante una aplicación web para mayor accesibilidad.
- Segmentación: Los usuarios serán estudiantes y profesores universitarios de todas las áreas académicas.
- Comportamientos: El valor principal que un usuario quiere obtener de nuestro servicio es una mayor facilidad, colaboración y disciplina en el área académica.
- Beneficios: Los usuarios obtendrán una mejora de la organización académica, aumento en la participación de los estudiantes, comunicación más fluida y mayor motivación.
- Captación de clientes: Obtendremos nuestros usuarios a través de promociones de alianzas con universidades, redes sociales, y recomendaciones de usuarios dentro de las comunidades universitarias.
- Modelos de ingresos: Al tratarse de una aplicación open source orientada al uso académico y comunitario, no se contempla un modelo de ingresos directo.
- Competencia: Nuestra competencia serán las plataformas similares en el área de educación, gestión académica y organización.
- Ventaja competitiva: Superaremos a la competencia gracias a nuestra plataforma que ofrece varias funciones en un solo lugar y que esta enfocada en la experiencia, motivación y colaboración del estudiante y del profesor universitario.

**Technical Assumptions (Suposiciones Técnicas)**

- Tecnología utilizada: Se utilizarán tecnologías web modernas para el desarrollo de la plataforma.
- Integraciones: La plataforma se integrará con un servicio externo de badges digitales para implementar elementos de gamificación.
- Escalabilidad: La aplicación será diseñada para soportar un número creciente de usuarios y datos.

**Market Assumptions (Suposiciones de Mercado)**

- Tamaño del mercado: El mercado objetivo incluye universidades, abarcando a estudiantes y docentes que buscan soluciones digitales para la organización académica.
- Competencia: Los principales competidores son otras plataformas de organización y gestión educativa.
- Tendencias: Existe un crecimiento en la digitalización de la educación y mayor preferencia por soluciones de productividad.

**Design Assumptions (Suposiciones de Diseño)**

- Interacción del usuario: La plataforma estará diseñada para una navegación sencilla, intuitiva y accesible.
- Experiencia del usuario: El enfoque estará en ofrecer una experiencia fluida y agradable, facilitando la realización de actividades sin complicaciones.
- Colores y tipografía: Los usuarios valoran el uso de una paleta de colores que transmita dinamismo y profesionalismo, junto con tipografías modernas y legibles que mejoren la experiencia visual.
- Preferencias visuales: Los usuarios prefieren un diseño visual atractivo pero limpio, que los permita concentrarse fácilmente en las funciones principales de la plataforma.
- Prototipos y pruebas: Se desarrollarán validaciones de las características principales que serán evaluados mediante pruebas de usabilidad.

##### 1.2.2.3. Lean UX Hypothesis Statements

Hypothesis Statement 01:

- Creemos que los usuarios necesitan una plataforma centralizada para gestionar actividades académicas y mejorar la comunicación.
- Sabremos que estamos en lo correcto cuando veamos una adopción activa de la herramienta dentro de grupos de estudio y recibamos comentarios positivos sobre la facilidad de organización que ofrece.

Hypothesis Statement 02:

- Creemos que la falta de integración entre herramientas actuales genera desorganización y pérdida de información importante para los estudiantes y docentes.
- Sabremos que estamos en lo correcto cuando los usuarios nos indiquen que ya no necesitan usar múltiples aplicaciones por separado y notemos una reducción en quejas relacionadas con la desorganización.

Hypothesis Statement 03:

- Creemos que una plataforma que permita crear y gestionar grupos de estudio facilitará la colaboración entre estudiantes.
- Sabremos que estamos en lo correcto cuando veamos un aumento en la creación de grupos dentro de la plataforma.

Hypothesis Statement 04:

- Creemos que la inclusión de un horario de clases dentro de la plataforma ayudará a los usuarios a organizar mejor su tiempo y visualizar de manera clara sus actividades académicas.
- Sabremos que estamos en lo correcto cuando observemos una mejora en la puntualidad de asistencia a clases y una mayor percepción de organización por parte de los usuarios.

Hypothesis Statement 05:

- Creemos que la implementación de retos académicos incentivará la participación y el compromiso de los estudiantes.
- Sabremos que estamos en lo correcto cuando veamos un aumento en la participación de actividades opcionales y retos dentro de la plataforma.

Hypothesis Statement 06:

- Creemos que una interfaz intuitiva y accesible facilitará la adopción de la plataforma por parte de los usuarios.
- Sabremos que estamos en lo correcto cuando los usuarios utilicen la aplicación con fluidez y la tasa de abandono inicial sea baja.

Hypothesis Statement 07:

- Creemos que permitir a los profesores monitorear el progreso de sus estudiantes mejorará la efectividad del seguimiento académico.
- Sabremos que estamos en lo correcto cuando los profesores utilicen frecuentemente las funciones de seguimiento y den feedback positivo.

Hypothesis Statement 08:

- Creemos que facilitar el acceso a la información de contacto y disponibilidad de los profesores mejorará la comunicación entre estudiantes y docentes.
- Sabremos que estamos en lo correcto cuando los estudiantes reporten mayor facilidad para contactar a sus profesores y se reduzcan las consultas relacionadas con cómo ubicarlos.

Hypothesis Statement 09:

- Creemos que la incorporación de elementos de gamificación, como badges y sistemas de puntuación, aumentará la motivación y participación de los usuarios en los retos académicos y grupos de estudio.
- Sabremos que estamos en lo correcto cuando observemos un incremento en la participación activa en desafíos educativos y una mayor frecuencia de interacción dentro de la plataforma.

Hypothesis Statement 10:

- Creemos que ofrecer una vista clara y centralizada del horario de clases ayudará a los usuarios a planificar mejor su semana académica.
- Sabremos que estamos en lo correcto cuando los usuarios consulten regularmente su horario y reporten una mayor facilidad para organizar otras actividades en función de sus clases.

Hypothesis Statement 11:

- Creemos que mostrar logros y avances individuales motivará a los estudiantes a continuar usando la plataforma.
- Sabremos que estamos en lo correcto cuando observemos una alta interacción con los paneles de progreso y mejoras.

Hypothesis Statement 12:

- Creemos que la privacidad y seguridad de la información son fundamentales para la adopción de la plataforma.
- Sabremos que estamos en lo correcto cuando los usuarios expresen confianza en el manejo de sus datos y no haya incidentes reportados.

Hypothesis Statement 13:

- Creemos que una experiencia de usuario que minimice la curva de aprendizaje aumentará la retención de usuarios nuevos.
- Sabremos que estamos en lo correcto cuando los nuevos usuarios se familiaricen con la plataforma en menos de una semana.

Hypothesis Statement 14:

- Creemos que una paleta de colores atractiva y una tipografía clara mejorarán la experiencia visual y la permanencia en la aplicación.
- Sabremos que estamos en lo correcto cuando los usuarios valoren positivamente el diseño en encuestas de satisfacción.

Hypothesis Statement 15:

- Creemos que ofrecer soporte rápido y accesible motivará a los usuarios a permanecer en la plataforma.
- Sabremos que estamos en lo correcto cuando las consultas de soporte sean resueltas de manera efectiva.

Hypothesis Statement 16:

- Creemos que el crecimiento de la educación híbrida aumentará la demanda de herramientas digitales integradas.
- Sabremos que estamos en lo correcto cuando identifiquemos un incremento sostenido en la adopción de la plataforma durante ciclos académicos híbridos o virtuales.

Hypothesis Statement 17:

- Creemos que permitir a los estudiantes compartir recursos y materiales dentro de sus grupos mejorará el aprendizaje colaborativo.
- Sabremos que estamos en lo correcto cuando observemos una alta frecuencia de archivos y enlaces compartidos en los espacios grupales.

Hypothesis Statement 18:

- Creemos que la disponibilidad de estadísticas y reportes académicos ayudará a los profesores a tomar mejores decisiones pedagógicas.
- Sabremos que estamos en lo correcto cuando los profesores utilicen estas herramientas para ajustar sus clases y estrategias de enseñanza.

Hypothesis Statement 19:

- Creemos que promocionar la plataforma a través de programas académicos y redes sociales, atraerá la mayoría de nuestros usuarios.
- Sabremos que estamos en lo correcto cuando veamos un aumento significativo en los registros de nuevos usuarios.

Hypothesis Statement 20:

- Creemos que incluir una sección de anuncios importantes permitirá mantener informada a la comunidad académica sin depender de medios externos.
- Sabremos que estamos en lo correcto cuando los usuarios accedan frecuentemente a esta sección.

##### 1.2.2.4. Lean UX Canvas

<img src="./images/chapter-1/LeanUXCanvas.png" alt="Lean UX Canvas">

### 1.3. Segmentos Objetivo

### **Segmento Objetivo 1: Estudiantes Universitarios**

Jóvenes que buscan herramientas digitales para optimizar su aprendizaje colaborativo. Necesitan centralizar tareas, horarios y materiales académicos, además de motivación mediante retos gamificados. Benefician de conexión directa con profesores y sistemas de reconocimiento por logros.

**Edad aproximada:** 17-25 años

**Necesidades:**

- Organización eficiente de estudios grupales
- Acceso centralizado a materiales, horarios y tareas
- Motivación mediante gamificación y reconocimiento académico

**Beneficios clave:**

- Plataforma única para gestión de aprendizaje colaborativo
- Sistema de retos que potencia habilidades prácticas
- Conexión directa con profesores y compañeros

### **Segmento Objetivo 2: Profesores Universitarios**

Educadores innovadores que requieren soluciones para dinamizar sus clases y reducir carga administrativa. Buscan crear actividades interactivas, monitorear progreso estudiantil y adaptarse a diferentes metodologías pedagógicas.

**Edad aproximada:** 30-55 años

**Necesidades:**

- Herramientas para dinamizar la enseñanza
- Reducción de carga administrativa
- Monitoreo del progreso estudiantil

**Beneficios clave:**

- Creación de retos académicos personalizables
- Panel de analytics para seguimiento de alumnos
- Integración flexible con metodologías educativas existentes

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

En esta sección, se presenta un análisis de los principales competidores de nuestra startup, centrado en aquellos que operan con modelos de negocio digitales similares o que, aunque no sean idénticos, ofrecen productos o servicios que se superponen parcialmente con los de EduHive. Evaluamos tanto competidores directos, que se encuentran en el mismo segmento de mercado, como competidores indirectos, que abordan áreas relacionadas como el uso de grupos de estudio, horarios, calendarios, etc.

**1. Chamilo**

<img src="./images/chapter-2/chamilo.png" alt="Chamilo" width="400"/>

**Descripción:**

Chamilo es una plataforma de aprendizaje libre y de código abierto orientada a facilitar la educación en línea. Es ligera, fácil de usar y tiene una fuerte presencia en instituciones educativas de habla hispana, especialmente en Latinoamérica.

**Principales características:**

* Gestión de cursos, tareas, exámenes y contenidos multimedia.
* Interfaz intuitiva, ideal para entornos con poca experiencia técnica.
* Herramientas colaborativas: foros, chats, wikis, encuestas.
* Seguimiento del progreso del estudiante.
* Certificaciones automáticas y calificaciones.
* Soporte multilingüe.
* Se instala fácilmente en servidores modestos.

**2. Canvas LMS**

<img src="./images/chapter-2/canvas.png" alt="Canvas" width="400"/>

**Descripción:**

Canvas LMS es una plataforma moderna y flexible, ampliamente utilizada en universidades de EE.UU. Tiene un enfoque centrado en la experiencia de usuario y permite integraciones con otras herramientas educativas.

**Principales características:**

* Gestión de cursos, tareas, evaluaciones y rúbricas.
* Integración con videollamadas, Google Docs, etc.
* Sistema de calendario y notificaciones.
* Interfaz moderna y personalizable.
* Alta escalabilidad, aunque la versión completa es de pago (Open Source cubre lo esencial).

**3. Moodle**

<img src="./images/chapter-2/moodle.png" alt="Moodle" width="400"/>

**Descripción:**

Moodle es una de las plataformas LMS más populares del mundo. Se destaca por su extensibilidad a través de plugins y su amplia comunidad de desarrolladores. Utilizada por universidades, escuelas y empresas.

**Principales características:**

* Creación de cursos, cuestionarios, tareas, foros, wikis y más.
* Sistema de roles y permisos muy detallado.
* Seguimiento avanzado del progreso del alumno.
* Interfaz personalizable con miles de plugins.
* Integración con herramientas externas y videoconferencias (BigBlueButton, Zoom).
* Soporte para gamificación (medallas, rankings, niveles).
* Multiplataforma y multilingüe.

**4. Open edX**

<img src="./images/chapter-2/openedx.png" alt="Open edX" width="400"/>

**Descripción:**

Desarrollado por Harvard y el MIT, Open edX es una plataforma robusta para cursos en línea tipo MOOC. Aunque más compleja de implementar, es ideal para proyectos educativos a gran escala.

**Principales características:**

* Creación de cursos interactivos con vídeos, exámenes, y tareas.
* Soporte para cursos auto-dirigidos o con fechas definidas.
* Análisis avanzados del aprendizaje.
* Herramientas de colaboración como foros y wikis.
* Compatible con gamificación y credenciales digitales.
* Escalable para miles de usuarios concurrentes.

#### 2.1.1. Análisis competitivo

<table> 
  <tr>
    <th colspan="6"> Competitive Analysis Landscape </th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2"> ¿Por qué llevar acabo este análisis? </td>
    <td colspan="4"> Pregunta </td>
  </tr>
  <tr>
    <td colspan="4"> Deberíamos llevar a cabo este análisis para conocer el entorno, la competencia, tomar decisiones de desarrollo y construir nuestra propuesta de valor. </td>
  </tr>
  <tr>
    <td colspan="2"> Productos </td>
    <td style="text-align: center;"> <div>EduHive</div> <img src="./images/chapter-2/eduhive.png" alt="EduHive" width="200"/> </td>
    <td style="text-align: center;"> <div>Chamilo</div> <img src="./images/chapter-2/chamilo.png" alt="Chamilo" width="200"/> </td>
    <td style="text-align: center;"> <div>Canvas</div> <img src="./images/chapter-2/canvas.png" alt="Canvas" width="200"/> </td>
    <td style="text-align: center;"> <div>Moodle</div> <img src="./images/chapter-2/moodle.png" alt="Moodle" width="200"/> </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>Plataforma gamificada para conectar a estudiantes y profesores mediante gestión de retos, tareas y grupos de estudio colaborativos.</td>
    <td>Plataforma educativa open source ligera y sencilla para crear y gestionar cursos virtuales con enfoque en colaboración.</td>
    <td>LMS moderno y escalable, enfocado en la experiencia de usuario y la integración con herramientas de terceros.</td>
    <td>LMS ampliamente utilizado, muy configurable, con comunidad activa y enfoque en educación formal y continua.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes? </td>
    <td>Gamificación integrada, conexión directa estudiante-docente, interfaz moderna, enfoque colaborativo y motivacional.</td>
    <td>Facilidad de uso, bajo consumo de recursos, ideal para instituciones pequeñas/medianas.</td>
    <td>Interfaz intuitiva, integración robusta (API, LTI), apps móviles, experiencia moderna.</td>
    <td>Extensibilidad, miles de plugins, comunidad global, adaptabilidad a distintos niveles educativos.</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td> Mercado Objetivo </td>
    <td>Estudiantes y profesores universitarios en Perú; instituciones que buscan digitalizar su enseñanza con una experiencia atractiva.</td>
    <td>Centros educativos de habla hispana, especialmente de educación básica y media.</td>
    <td>Universidades y centros educativos grandes en países desarrollados; instituciones con foco en experiencia digital.</td>
    <td>Universidades, colegios, gobiernos y empresas de todo el mundo; adaptable a distintas necesidades educativas.</td>
  </tr>
  <tr>
    <td> Estrategias de Marketing </td>
    <td>Generar alianzas con universidades y redes estudiantiles</td>
    <td>Promoción por su facilidad de implementación y uso; comunidad y eventos educativos.</td>
    <td>Campañas institucionales, participación en conferencias, marketing directo a universidades.</td>
    <td>Distribución vía comunidad, asociaciones educativas, y marketing institucional.</td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td> Productos & Servicios </td>
    <td>Gestión de grupos, retos, tareas, horarios; perfiles docentes; gamificación; métricas de progreso.</td>
    <td>Cursos virtuales, tareas, exámenes, seguimiento, colaboración básica.</td>
    <td>Gestión de cursos, tareas, integración de apps externas, mobile apps, calendario académico.</td>
    <td>Cursos, exámenes, plugins avanzados, aprendizaje adaptativo, integraciones multimedia.</td>
  </tr>
  <tr>
    <td> Precios & Costos</td>
    <td>Modelo gratuito para estudiantes, versión premium de 7 dolares para brindar soporte o funcionalidades personalizadas.</td>
    <td>Completamente gratuito (open source); costos asociados a servidores/soporte.</td>
    <td>Open source con versión gratuita; versión cloud/enterprise con costo.</td>
    <td>Gratuito (open source); servicios premium disponibles con MoodleCloud o partners.</td>
  </tr>
  <tr>
    <td> Canales de distribución </td>
    <td>Web oficial, convenios con universidades</td>
    <td>Descarga directa desde web.</td>
    <td>GitHub, partners educativos, sitio oficial (Canvas Free for Teachers).</td>
    <td>Web oficial y empresas proveedoras autorizadas.</td>
  </tr>
  <tr>
    <td rowspan="5">Análisis SWOT</td>
    <td> Fortalezas </td>
    <td>Innovación, gamificación nativa, enfoque en experiencia estudiantil, motivación académica.</td>
    <td>Ligero, fácil de usar y buen rendimiento en servidores básicos.</td>
    <td>Moderno, escalable, apps móviles, excelente UI/UX, alta compatibilidad.</td>
    <td>Altamente configurable, comunidad enorme, muy probado a nivel global.</td>
  </tr>
  <tr>
    <td> Debilidades</td>
    <td>Poca presencia en el mercado, requiere validación institucional.</td>
    <td>Menos funciones avanzadas comparado con otros LMS, interfaz menos moderna.</td>
    <td>Complejo de instalar, depende de servicios cloud si se desea escalar rápido.</td>
    <td>Puede ser complejo para usuarios nuevos, requiere personal técnico para mantener.</td>
  </tr>
  <tr>
    <td> Oportunidades</td>
    <td>Expansión en universidades peruanas, integración con apps educativas, escalamiento regional.</td>
    <td>Mejorar diseño, expandir funciones modernas para captar nuevos usuarios.</td>
    <td>Mayor adopción en América Latina, alianzas con plataformas edtech.</td>
    <td>Integración con IA y nuevas tecnologías educativas, adaptación a educación híbrida.</td>
  </tr>
  <tr>
    <td> Amenazas</td>
    <td>Resistencia al cambio por parte de instituciones tradicionales.</td>
    <td>Limitado crecimiento frente a plataformas más modernas.</td>
    <td>Dependencia de actualizaciones constantes, competencia con Moodle y Blackboard.</td>
    <td>Riesgo de sobrecarga por su complejidad; posible saturación de mercado LMS.</td>
  </tr>
</table>

#### 2.1.2. Estrategias y tácticas frente a competidores

**Frente a Chamilo**

<img src="./images/chapter-2/chamilo.png" alt="Chamilo" width="400"/>

Estrategias:

* **Diferenciación por experiencia de usuario (UX/UI)**: Mientras Chamilo tiene una interfaz funcional pero básica, apostaremos por una plataforma más intuitiva y visualmente atractiva.
* **Estrategia de comunidad activa**: Aprovechar la baja visibilidad de la comunidad de Chamilo para formar una comunidad más activa y comprometida en nuestra plataforma (eventos).

Tácticas:

* Realizar pruebas de usabilidad frecuentes para optimizar la interfaz.
* Ofrecer documentación amigable y soporte proactivo, donde Chamilo es más limitado.

---

**Frente a Canvas**

<img src="./images/chapter-2/canvas.png" alt="Canvas" width="400"/>

Estrategias:

* **Penetración en mercados con menos recursos**: Canvas es fuerte en instituciones grandes, pero tu startup puede enfocarse en medianas y pequeñas instituciones educativas.
* **Agilidad e innovación en funciones**: Aprovecha que Canvas, al ser robusto, puede ser más lento en adoptar cambios o innovaciones.

Tácticas:

* Ofrecer una versión gratuita limitada pero útil para captar usuarios en etapa inicial.
* Incluir funcionalidades nuevas o innovadoras como gamificación.
* Utilizar canales alternativos (influencers edtech, redes locales) para captar usuarios donde Canvas no llega fácilmente.

---

**Frente a Moodle**

<img src="./images/chapter-2/moodle.png" alt="Moodle" width="400"/>

Estrategias:

* **Simplificación y experiencia out-of-the-box**: Moodle es muy personalizable, pero eso también lo hace complejo para usuarios no técnicos. Tu producto puede destacarse ofreciendo soluciones listas para usar.
* **Integraciones modernas y nativas**: Moodle requiere plugins adicionales para muchas funciones; puedes destacar al tener todo integrado desde el inicio.

Tácticas:

* Crear plantillas prediseñadas para diferentes tipos de cursos (educación básica, profesional, corporativa).
* Incluir soporte técnico especializado para evitar que los usuarios dependan de técnicos propios como en Moodle.

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

**Segmento Objetivo 1: Estudiantes Universitarios**

**Preguntas principales:**

1. ¿Podrías contarme un poco sobre ti? (edad, carrera, lugar de residencia y ocupacion)
2. ¿Cómo organizas actualmente tus tareas, horarios y trabajos en grupo?
3. ¿Qué herramientas digitales utilizas con más frecuencia para estudiar o coordinar con tu equipo?
4. ¿Qué tan fácil o difícil es para ti mantenerte motivado/a durante el ciclo académico?
5. ¿Qué valoras más en una plataforma educativa o de gestión del aprendizaje?
6. ¿Qué te parecería si se añadieran retos o elementos gamificados a tus cursos?

**Preguntas complementarias:**

7. ¿Utilizas más el celular, la laptop o una tablet para estudiar?
8. ¿Has usado plataformas como Moodle, Canvas u otras? ¿Qué te gustó o no te gustó?
9. ¿Qué tan importante es para ti recibir reconocimientos o insignias por tus logros?
10. ¿Qué redes sociales o canales digitales usas más para temas académicos?

**Segmento Objetivo 2: Profesores Universitarios**

**Preguntas principales:**

1. ¿Podría contarme un poco sobre usted? (edad, distrito de residencia y ocupacion)
2. ¿Qué herramientas digitales utiliza actualmente para gestionar sus clases?
3. ¿Qué aspectos de su trabajo le consumen más tiempo fuera del aula?
4. ¿Cómo monitorea actualmente el avance de sus estudiantes?
5. ¿Qué valoraría más en una plataforma educativa para apoyar su enseñanza?
6. ¿Qué tipo de actividades interactivas suele aplicar o le gustaría aplicar en clase?
7. ¿Qué tan dispuesto estaría a incorporar retos o elementos gamificados para motivar a sus alumnos?

**Preguntas complementarias:**

8. ¿Prefiere trabajar desde laptop, PC o tablet?
9. ¿Qué tan importante es para usted tener estadísticas o datos visuales sobre el desempeño del grupo?
10. ¿Qué otros canales (correo, redes, WhatsApp, campus virtual) usa para comunicarse con sus alumnos?

#### 2.2.2. Registro de entrevistas

*Segmento Estudiantes Universitarios:*

- *Entrevista 1*
  - Nombre: Sebastián
  - Apellidos: Pacheco Astiguetta
  - Edad: 22 Años
  - Distrito: San Miguel

![Imagen de la entrevista 1 del Segmento Objetivo 1](/images/chapter-2/entrevistaS11.png)

- Inicio: 0:23
- Duración: 4:46

URL: [Link de la Entrevista](https://drive.google.com/file/d/1O7KD7yPBEEN0ZW6fmfPgLXTRWlm64wF5/view?usp=sharing)

- Resumen de la entrevista:

  - La entrevista con Sebastián Pacheco nos indica principalmente la dificultad que tienen varios estudiantes universitarios para mantenerse motivados a través del ciclo escolar. Nos comenta como la falta de participación o interacción por parte de sus compañeros puede llevar a una desmotivación. También nos comenta que aprecia que una aplicación dedicada al estudio tenga una funcionalidad de notificaciones, que le permitan recordarse a si mismo las tareas pendientes. Por último, Sebastián expresa una opinión positiva hacia la idea de un sistema gamificado que involucre medallas o premios para mantener la motivación en los proyectos.
- *Entrevista 2*

  - Nombre: Luis
  - Apellidos: Alejo Cárdenas
  - Edad: 22 Años
  - Distrito: San Martin de Porres
  - Inicio de la entrevista: 0:30
  - Duracion: 03:54

<img src="./images/chapter-2/entrevistaS12.png" alt="Moodle" width="800"/>

URL: [Entrevista Luis](https://drive.google.com/file/d/1BhuX4fWP7TAfVWXeDaHPoxkAYatOYrYv/view?usp=sharing)

- Resumen de la entrevista:

  - La entrevista con Luis nos indica principalmente tiene la dificultad de organizar su tiempo con sus horarios siendo estudiante y practicante.Asi mismo, usa herramientas como Google calendar, Trello y Notion para agendar clases, definir reuniones, seguir el profeso de sus tareas,etc. Nos comenta que usa googlemet y discord para reuniones, Notion para apuntes y GitHub para el codigo. También nos comenta que su motivacion se ve mermada conforme avanza el ciclo,ya que es mas dificil tener una buena organizacion con mas tareas. Ademas, busca un app organizada y centralizada priorizando la comunicacion. Por otro lado, considera que la gamificacion haria mucho mas interesante los cursos o temas. Por ultimo, usa bastante Whatsapp y Discord para temas academicos, pues le permiten una mayor libertad, comodidad y simplicidad mediante sus interfaces.
- *Entrevista 3*

  - Nombre: Jhon Alexander
  - Apellidos: Chuchon
  - Edad: 19 años
  - Distrito: San Martin de Porres
  - Inicio de la entrevista: 0:10
  - Duración: 07:30

<img src="./images/chapter-2/entrevistaS13.png" alt="Moodle" width="800"/>

URL: [Link de la Entrevista](https://drive.google.com/file/d/13wdEr0jYvA2IRAnuAReC42t7sB5QRqY7/view?usp=drive_link)

- Resumen de la entrevista:
  - La entrevista con Jhon resalta la importancia de que los estudiantes universitarios se mantengan comunicados, organizados y motivados. Él menciona que valora las plataformas que están bien estructuradas y que ofrecen diversas herramientas integradas en un solo lugar. Además, considera que un sistema gamificado sería útil, ya que fomentaría la competitividad, la motivación por superarse y una mayor participación entre los estudiantes. Finalmente, destaca la utilidad de poder visualizar fácilmente las fechas límite de tareas o pendientes, ya que es común que los estudiantes las olviden.

*Segmento Profesores Universitarios:*

- Entrevista 1

  - Nombre: Jose Alejandro
  - Apellidos: Marchena Chauca
  - Edad: 23 Años
  - Distrito: -
  - Inicio de la entrevista: -
  - Duración: -


![Imagen de la entrevista 1 del Segmento Objetivo 2](/images/chapter-2/Entrevista-Jose.png)

URL: [Link de la Entrevista](https://drive.google.com/file/d/1YY7Z6qGQi_AiX7WK-ms3v26tmmknqYqK/view?usp=drive_link)

- Resumen de la entrevista:

  - Durante la entrevista, el docente compartió su experiencia como profesor en un instituto, destacando las limitaciones que enfrentaba en su labor diaria. A pesar de que recibía material por parte de la institución, este resultaba insuficiente y carecía de elementos interactivos que facilitaran el aprendizaje de sus alumnos. Además, comentó que los canales de comunicación eran poco eficientes, ya que solían limitarse a mensajes por WhatsApp o correos electrónicos, lo que dificultaba un acompañamiento más cercano y organizado.
  - Al presentarle la plataforma educativa, su interés fue inmediato. Señaló que le ofrecía precisamente las herramientas que le hubiera gustado tener en su etapa docente. Le llamó la atención la posibilidad de interactuar con sus estudiantes de manera más dinámica, ya sea enviando horarios, proponiendo retos personalizados o haciendo seguimiento al progreso individual de cada alumno. Valoró especialmente la función de análisis del rendimiento, ya que permite identificar en qué temas destaca cada estudiante, lo que facilitaría una enseñanza más personalizada y efectiva.
- Entrevista 2

  - Nombre: Melina Micaela
  - Apellidos: Orderique Castro
  - Edad: 22 Años
  - Distrito: -
  - Inicio de la entrevista: -
  - Duración: -


![Imagen de la entrevista 1 del Segmento Objetivo 2](/images/chapter-2/Interviews-Melina.png)

URL: [Link de la Entrevista](https://drive.google.com/file/d/1ImXhOUmLZpevvlPW1oYm_Y7A9z5AXstp/view?usp=drive_link)

- Resumen de la entrevista:

  - Durante la entrevista, la docente compartió su experiencia previa en el ámbito educativo, destacando que había utilizado diversos recursos para apoyar el aprendizaje de sus alumnos, como una pizarra interactiva y juegos didácticos, entre ellos el popular "pupiletras", con el objetivo de captar su atención de manera lúdica.
  - Sin embargo, mencionó que enfrentaba ciertas limitaciones, especialmente en lo que respecta a la participación activa de los estudiantes. Aunque deseaba que ellos pudieran interactuar directamente en la pizarra durante sus explicaciones, las herramientas disponibles no lo permitían. Además, señaló que la comunicación y organización fuera del aula resultaban poco prácticas, ya que debía enviar horarios o comunicados a través de WhatsApp o correos electrónicos. También comentó que no contaba con una plataforma donde pudiera centralizar actividades, tareas o avisos, lo que la obligaba a anunciar todo exclusivamente durante las clases presenciales.

**Entrevista 3**

- Nombre: Ariana
- Apellidos: Castilla
- Edad: 24 Años
- Distrito: La Victoria
- Inicio de la entrevista: 0:03
- Duracion: 06:14

![Imagen de la entrevista 3 del Segmento Objetivo 2](/images/chapter-2/Entrevista_3.png)

URL: https://youtu.be/QTE_TH3pnVc

- Resumen de la entrevista:

  - La entrevista con Ariana nos cuenta que, como profesora de idiomas, actualmente usa aplicaciones como Canva, materiales de libros en la red y videos de Youtube, además del uso de la IA para preparar fichas para resolver. Lo que más busca en una aplicación educativa es que se realice un seguimiento al progreso de los alumnos, para saber que partes se le complica. Además, como actividades interactivas destaca el uso de exposiciones y ve como una buena idea el uso de herramientas gamificadas y un sistema de contactos directos con el alumno para mejorar el aprendizaje.

#### 2.2.3. Análisis de entrevistas

**Análisis Segmento 1**: Estudiantes Universitarios

La entrevista con estudiantes universitarios destacó muchos puntos en común. En primer lugar, una diversa cantidad de problemas con los que lidian en su vida académica, tales como la falta de organización, la desmotivación y la falta de comunicación. En segundo lugar, concordaron en que la implementación de un sistema gamificado con medallas y premios sería una gran idea para mantener la motivación de los proyectos y hacer las clases más interesantes. La mayoría de ellos resalta que una buena aplicación educativa debería contar con un sistema de notificaciones y una correcta organización para ayudar a los estudiantes menos hábiles. 
Los estudiantes están enfocados en mejorar su situación académica con herramientas útiles e innovadores que busquen sacar la mayor productividad de cada uno de ellos. Algunos de ellos resaltaron el uso de diversas herramientas para agendar tarea o realizar proyectos en grupo como Google calendar o Trello, además del uso de redes sociales para coordinarse rápidamente y el uso de laptops que da mayor versatilidad en el avance de sus proyectos. 


**Análisis Segmento 2**: Profesores Universitarios

La entrevista con profesores revela los distintos desafíos con los que luchan para llevar a cabo sus clases, como una comunicación limitada, falta de materiales y dificultad en el seguimiento del progreso del alumno. Muchos de ellos concordaron en el uso de correo electrónico y Whatsapp para comunicarse con sus alumnos, además de implementar sus propias herramientas para captar la atención del alumno, entre ellas “pupiletras”, exposiciones y concursos online con quizzes. Lo que más se les complica fuera de clases era la búsqueda de materiales y una comunicación activa con sus alumnos.
Los docentes destacaron el uso de una plataforma capaz de contar con diversas funciones que solucionarían sus problemas, tales como un sistema de notificaciones, un seguimiento del alumno y herramientas gamificadas para captar la atención de este. Concordaron que todas estas funciones mejorarían y facilitaría considerablemente sus trabajos, además de que brindaría un gran apoyo a todo tipo de estudiantes que tuviesen problemas en este ámbito.



### 2.3. Needfinding

#### 2.3.1. User Personas

A continuación, presentamos los User Persona correspondientes a cada segmento objetivo, basados en las características de sus usuarios ideales.

**Segmento 1: Estudiantes Universitarios**

<img src="./images/chapter-2/UserPerson_Student.png" alt="Canvas" width="400"/>

**Segmento 2: Profesores Universitarios**

<img src="./images/chapter-2/UserPerson_Teacher.png" alt="Canvas" width="400"/>

#### 2.3.2. User Task Matrix

**Segmento 1: Estudiantes Universitarios**

<table  cellspacing="0" border="1">
  <thead>
    <tr>
      <th>Tarea (Task)</th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Revisar los miembros y objetivo del grupo de estudio al que pertenece</td>
      <td>Baja</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Revisar el horario y organización del grupo</td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Acceder y consultar materiales académicos subidos por el profesor</td>
      <td>Media</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Resolver retos académicos planteados por el profesor</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Revisar el progreso personal dentro del grupo</td>
      <td>Baja</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Recibir y analizar feedback de actividades realizadas</td>
      <td>Media</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Ajustar su ritmo o estrategia de estudio según feedback y resultados</td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
  </tbody>
</table>

**Segmento 2: Profesores Universitarios**

<table  cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>Tarea (Task)</th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Gestionar los miembros y definir el objetivo del grupo de estudio</td>
      <td>Baja</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Crear el grupo de estudio y establecer su horario</td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Subir y actualizar materiales académicos (lecturas, videos, recursos)</td>
      <td>Media</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Crear y configurar retos académicos para el grupo</td>
      <td>Alta</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Monitorear el progreso y participación de los estudiantes</td>
      <td>Alta</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Ajustar la dificultad o el enfoque de los retos según el avance del grupo</td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Revisar y dar feedback sobre actividades realizadas</td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
  </tbody>
</table>

#### 2.3.3. User Journey Mapping

* **Estudiantes Universitarios**

<img src="./images/chapter-2/User-Journey-Student.png" alt="As-Is Estudiantes Universitarios" width="800"/>

* **Profesores Universitarios**

<img src="./images/chapter-2/User-Journey-Teacher.png" alt="As-Is Estudiantes Universitarios" width="800"/>

#### 2.3.4. Empathy Mapping

**Segmento 1: Estudiantes Universitarios**

<img src="./images/chapter-2/Empathy_map_Student.png" alt="As-Is Estudiantes Universitarios" width="800"/>

**Segmento 2: Profesores Universitarios**

<img src="./images/chapter-2/Empathy_map_Teacher.png" alt="As-Is Estudiantes Universitarios" width="800"/>

#### 2.3.5. As-is Scenario Mapping

**Segmento 1: Estudiantes Universitarios**

<img src="./images/chapter-2/asisestudiantes.png" alt="As-Is Estudiantes Universitarios" width="800"/>

**Segmento 2: Profesores Universitarios**

<img src="./images/chapter-2/asisprofesores.png" alt="Profesores Universitarios" width="800"/>

### 2.4. Ubiquitous Language

<table cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th colspan="3"><strong>Ubiquitous Language</strong></th>
    </tr>
    <tr>
      <th><strong>Término en inglés</strong></th>
      <th><strong>Término en español</strong></th>
      <th><strong>Descripción</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Study Group</td>
      <td>Grupo de Estudio</td>
      <td>Un grupo conformado por estudiantes que colaboran para estudiar y resolver retos académicos. Se define un objetivo común y una estructura de trabajo para su éxito.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td>Tarea</td>
      <td>Actividad específica asignada a un estudiante o grupo, generalmente con plazos o metas claras.</td>
    </tr>
    <tr>
      <td>Academic Challenge</td>
      <td>Reto Académico</td>
      <td>Actividad educativa diseñada por el profesor para evaluar y motivar el aprendizaje de los estudiantes. Incluye tareas prácticas o de resolución de problemas.</td>
    </tr>
    <tr>
      <td>Group Objective</td>
      <td>Objetivo del Grupo</td>
      <td>Meta clara definida para el grupo de estudio, relacionada con el tema de estudio o el resultado esperado de su trabajo colaborativo.</td>
    </tr>
    <tr>
      <td>Schedule</td>
      <td>Horario</td>
      <td>La planificación temporal de actividades del grupo, como las sesiones de estudio o la entrega de tareas.</td>
    </tr>
    <tr>
      <td>Feedback</td>
      <td>Retroalimentación</td>
      <td>Comentarios y observaciones proporcionados por el profesor o compañeros, con el fin de mejorar el rendimiento de los estudiantes.</td>
    </tr>
    <tr>
      <td>Progress Tracking</td>
      <td>Seguimiento del Progreso</td>
      <td>Método de monitoreo del avance individual o grupal, utilizado por los profesores para evaluar la participación y el desempeño académico.</td>
    </tr>
    <tr>
      <td>Motivation</td>
      <td>Motivación</td>
      <td>Factor que impulsa a los estudiantes a participar activamente, basado en incentivos como los sistemas de puntuación o logros.</td>
    </tr>
    <tr>
      <td>Learning Materials</td>
      <td>Materiales de Aprendizaje</td>
      <td>Recursos académicos proporcionados por el profesor, como lecturas, videos y ejercicios, para apoyar el proceso de aprendizaje.</td>
    </tr>
    <tr>
      <td>Study Session</td>
      <td>Sesión de Estudio</td>
      <td>Encuentro o periodo de tiempo dedicado a trabajar en conjunto sobre materiales de estudio o tareas académicas.</td>
    </tr>
    <tr>
      <td>Student Profile</td>
      <td>Perfil del Estudiante</td>
      <td>Información personal y académica de un estudiante, como sus logros, metas, y desempeño dentro de un grupo.</td>
    </tr>
    <tr>
      <td>Instructor Profile</td>
      <td>Perfil del Profesor</td>
      <td>Información relacionada con el profesor, sus especializaciones, horarios de atención y métodos de contacto.</td>
    </tr>
    <tr>
      <td>Analytics</td>
      <td>Análisis</td>
      <td>Herramienta utilizada para interpretar y visualizar el rendimiento de los estudiantes a través de datos recopilados de sus actividades.</td>
    </tr>
    <tr>
      <td>Group Collaboration</td>
      <td>Colaboración en Grupo</td>
      <td>Trabajo conjunto de los miembros del grupo para alcanzar un objetivo común. Incluye la comunicación y cooperación entre los estudiantes.</td>
    </tr>
    <tr>
      <td>Achievement System</td>
      <td>Sistema de Logros</td>
      <td>Sistema diseñado para reconocer el rendimiento y éxito de los estudiantes mediante puntos, medallas o certificados, fomentando la competitividad sana.</td>
    </tr>
  </tbody>
</table>

## Capítulo III: Requirements specification

### 3.1. To-Be Scenario Mapping

**1. Segmento 1: Estudiantes Universitarios**

<img src="./images/chapter-3/tobeestudiantes.png" alt="To-Be Estudiantes Universitarios" width="800"/>

**2. Segmento 2: Profesores Universitarios**

<img src="./images/chapter-3/tobeprofesores.png" alt="To-Be Profesores Universitarios" width="800"/>

### 3.2. User Stories

**Epics:**

<table >
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Título</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP-001</td>
      <td>Gestión de Equipos</td>
      <td>Esta épica se centra en la creación y gestión eficiente de equipos de estudiantes dentro de la plataforma EduHive. Los equipos pueden organizarse según diferentes criterios, y los miembros podrán ver y coordinar sus horarios, facilitando la colaboración efectiva y la programación de reuniones. La gestión de equipos es esencial para promover el trabajo conjunto y la dinámica de aprendizaje dentro de los retos y actividades.</td>
    </tr>
    <tr>
      <td>EP-002</td>
      <td>Seguimiento de Progreso</td>
      <td>Esta épica se enfoca en la visualización y el seguimiento del progreso de los equipos y los estudiantes dentro de EduHive. Los profesores podrán monitorear el rendimiento de los estudiantes a lo largo de los retos y actividades, proporcionando retroalimentación constructiva y ajustando el nivel de dificultad según sea necesario. Además, los estudiantes podrán seguir su propio progreso y entender cómo van en el curso.</td>
    </tr>
    <tr>
      <td>EP-003</td>
      <td>Sistema de Retos</td>
      <td>Esta épica tiene como objetivo desarrollar un sistema que permita la creación, distribución y seguimiento de retos gamificados semanales. Los profesores podrán diseñar retos personalizados con niveles de dificultad adaptados al ritmo del curso, mientras que los estudiantes recibirán estos retos de manera continua para mantener su motivación y mejorar sus habilidades. Este sistema es clave para la experiencia de aprendizaje dentro de EduHive, ya que fomenta el desarrollo continuo y la competencia sana.</td>
    </tr>
    <tr>
      <td>EP-004</td>
      <td>Sistema de Evaluación</td>
      <td>Esta épica se centra en el desarrollo de un sistema de evaluación dentro de EduHive que proporcione retroalimentación automática y permita tanto a estudiantes como a profesores evaluar el rendimiento y progreso en los retos. Los estudiantes recibirán retroalimentación inmediata al finalizar los retos, lo que les permitirá identificar sus áreas de mejora, mientras que los profesores tendrán acceso a herramientas para monitorear el rendimiento y ajustar la dificultad según sea necesario.</td>
    </tr>
    <tr>
      <td>EP-005</td>
      <td>Interacción y Navegación en la Landing page</td>
      <td>Esta épica engloba el diseño y funcionalidad de las secciones clave del landing page (Hero, Main Features, Explore Courses, Knowledge, Contact, Testimonials, Latest Updates y Subscribe), con el objetivo de presentar de manera atractiva e interactiva la propuesta de valor de EduHive. Cada sección está optimizada para guiar al usuario a través de un recorrido visual intuitivo, destacando beneficios, oferta académica y testimonios, mientras facilita la conversión mediante formularios validados (contacto y suscripción) y contenido multimedia actualizado, todo integrado en una experiencia cohesiva y orientada.</td>
    </tr>
  </tbody>
</table>

**User Stories:**

<table >
  <thead>
    <tr>
      <th>User Storie ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>US-001</td>
<td>Asignación de grupos</td>
<td>Como estudiante, quiero ser asignado o unirme a un grupo de trabajo, para empezar a colaborar desde el inicio del curso.</td>
<td>Escenario 1:Dado que el estudiante se ha registrado en el curso,
Cuando accede por primera vez a la plataforma,
Entonces el sistema le asigna automáticamente a un grupo disponible.
Escenario 2:Dado que el estudiante no ha sido asignado aún,
Cuando elige un grupo desde el listado de equipos abiertos,
Entonces el sistema confirma su integración al grupo.</td>
<td>EP-001</td>
</tr>
    <tr><td>US-002</td>
<td>Visualización del equipo</td>
<td>Como estudiante, quiero visualizar los distintos perfiles de integrantes de mi grupo, para conocer sus habilidades y roles asignados.</td>
<td>Escenario 1:Dado que el estudiante pertenece a un grupo,
Cuando accede a la sección "Mi equipo",
Entonces puede ver los perfiles con habilidades y roles asignados de sus compañeros.
Escenario 2:Dado que un nuevo integrante ha sido añadido,
Cuando se actualiza la composición del grupo,
Entonces la vista del equipo se actualiza automáticamente para todos los miembros.</td>
<td>EP-001</td>
</tr>
    <tr><td>US-003</td>
<td>Creación de grupos</td>
<td>Como profesor, quiero crear grupos de estudiantes, para optimizar tiempo al inicio del curso.</td>
<td>Escenario 1:Dado que el curso ha iniciado,
Cuando el profesor accede a la herramienta de gestión de grupos,
Entonces puede crear nuevos grupos y asignar estudiantes manualmente o de forma aleatoria.
Escenario 2:Dado que los grupos han sido creados,
Cuando el profesor confirma la creación,
Entonces los estudiantes reciben una notificación con la asignación correspondiente.</td>
<td>EP-001</td>
</tr>
    <tr><td>US-004</td>
<td>Comparación de rendimiento</td>
<td>Como estudiante, quiero comparar mi progreso con el de mis compañeros, para saber cómo estoy avanzando respecto al grupo.</td>
<td>Escenario 1:Dado que el estudiante ha completado al menos un reto,
Cuando accede a la sección de progreso del grupo,
Entonces puede visualizar cómo se compara su rendimiento con el promedio de su equipo.
Escenario 2:Dado que se han actualizado las notas,
Cuando el estudiante revisa su panel de comparación,
Entonces los datos reflejan la información más reciente.</td>
<td>EP-002</td>
</tr>
    <tr><td>US-005</td>
<td>Acceder al panel de progreso del curso</td>
<td>Como profesor, quiero acceder a un panel de progreso general del curso, para hacer seguimiento del avance sin necesidad de herramientas externas.</td>
<td>Escenario 1:Dado que hay múltiples grupos en el curso,
Cuando el profesor entra al panel de progreso,
Entonces ve un resumen visual con el avance por equipo y por reto.
Escenario 2:Dado que el sistema recopila datos de entrega,
Cuando el profesor filtra por fecha o reto,
Entonces obtiene métricas detalladas del desempeño de los estudiantes.</td>
<td>EP-002</td>
</tr>
    <tr><td>US-006</td>
<td>Recepcion de retos semanales gamificados</td>
<td>Como estudiante, quiero recibir retos gamificados semanales, para desarrollar mis habilidades mientras me mantengo motivado.</td>
<td>Escenario 1: Dado que soy un estudiante registrado en la plataforma,
Cuando inicio sesión en mi cuenta,
Entonces recibiré un reto gamificado semanalmente para desarrollar mis habilidades.
Escenario 2: Dado que soy un estudiante que ha completado el reto anterior,
Cuando llegue una nueva semana,
Entonces recibiré un nuevo reto gamificado semanalmente para mantenerme motivado.</td>
<td>EP-003</td>
</tr>
    <tr><td>US-007</td>
<td>Diseñar de retos personalizados</td>
<td>Como profesor, quiero diseñar retos personalizados con niveles de dificultad, para adaptarlos al ritmo del curso.</td>
<td>Escenario 1: Dado que soy un profesor con acceso a la plataforma,
Cuando entro a la sección de diseño de retos,
Entonces podré crear un reto personalizado con niveles de dificultad que se adapten al ritmo de mi curso.
Escenario 2: Dado que soy un profesor,
Cuando configuro los niveles de dificultad de un reto,
Entonces los estudiantes verán el reto con la dificultad adecuada a su nivel de conocimiento.</td>
<td>EP-003</td>
</tr>
    <tr><td>US-008</td>
<td>Obtencion de feedback automático</td>
<td>Como estudiante, quiero obtener retroalimentación automática tras resolver un reto, para identificar en qué puedo mejorar.</td>
<td>Escenario 1: Dado que soy un estudiante que ha completado un reto,
Cuando finalizo la resolución de un reto,
Entonces recibiré retroalimentación automática que me ayudará a identificar mis áreas de mejora.
Escenario 2: Dado que soy un estudiante,
Cuando resuelvo un reto correctamente,
Entonces recibiré un feedback positivo y constructivo que me motive a seguir aprendiendo.</td>
<td>EP-004</td>
</tr>
    <tr><td>US-009</td>
<td>Definición de fechas límite de retos</td>
<td>Como profesor, quiero establecer fechas límite para cada reto, para asegurar que los estudiantes cumplan con los entregables en el tiempo establecido.</td>
<td>Escenario 1: Dado que soy un profesor,
Cuando creo un reto en la plataforma,
Entonces puedo establecer una fecha límite para asegurarme de que los estudiantes cumplan con los entregables a tiempo.
Escenario 2: Dado que soy un profesor,
Cuando un estudiante ve un reto asignado,
Entonces podrá ver claramente la fecha límite para entregarlo.</td>
<td>EP-003</td>
</tr>
    <tr><td>US-010</td>
<td>Visualizacion de horarios</td>
<td>Como estudiante, quiero poder ingresar y visualizar los horarios disponibles de los miembros de mi equipo, para coordinar reuniones y sesiones de trabajo efectivas.</td>
<td>Escenario 1: Dado que soy un estudiante que pertenece a un equipo,
Cuando accedo a la sección de horarios,
Entonces puedo ver los horarios disponibles de los miembros de mi equipo para coordinar reuniones y sesiones de trabajo.
Escenario 2: Dado que soy un estudiante,
Cuando visualizo los horarios de mi equipo,
Entonces puedo seleccionar y proponer un horario que se ajuste a la disponibilidad de todos.</td>
<td>EP-001</td>
</tr>
    <tr><td>US-011</td>
<td>Seguir el rendimiento de los equipos</td>
<td>Como profesor, quiero visualizar el progreso de los distintos grupos, para modificar el nivel de dificultad</td>
<td>Escenario 1: Dado que soy un profesor,
Cuando accedo a la sección de seguimiento de rendimiento,
Entonces puedo visualizar el progreso de cada equipo para tomar decisiones sobre los niveles de dificultad de los retos.
Escenario 2: Dado que soy un profesor,
Cuando visualizo el progreso de los equipos,
Entonces puedo ajustar el nivel de dificultad de los retos para cada equipo de acuerdo a su rendimiento.</td>
<td>EP-002</td>
</tr>
    <tr><td>US-012</td>
<td>Revisar general de rendimiento</td>
<td>Como estudiante, quiero ver una vista gráfica de mis notas acumuladas, para entender fácilmente cómo voy en el curso.</td>
<td>Escenario 1: Dado que soy un estudiante,
Cuando accedo a la sección de rendimiento,
Entonces puedo ver una vista gráfica de mis notas acumuladas para comprender fácilmente mi desempeño en el curso.
Escenario 2: Dado que soy un estudiante,
Cuando veo la vista gráfica de mi rendimiento,
Entonces puedo identificar mis puntos fuertes y áreas de mejora a través de los diferentes colores o indicadores de las gráficas.</td>
<td>EP-004</td>
</tr>
    <tr><td>US-013</td><td>Asignación de feeback</td><td>Como profesor, quiero poder asignar una calificación, junto con un comentario o feedback a los envíos de los estudiantes.</td><td>Escenario 1: Dado un envío de estudiante. Cuando el profesor ingresa una calificación (ej: 80/100) y un comentario (ej: "Buen trabajo"). Entonces el sistema guarda el feedback y muestra: "Feedback registrado"<br>Escenario 2: Dado un envío de estudiante. Cuando el profesor ingresa una calificación mayor a 100 (ej: 110/100). Entonces el sistema muestra: "Error: La calificación debe ser entre 0 y 100"</td><td>EP-004</td></tr>
    <tr><td>US-014</td><td>Enviar respuesta a reto</td><td>Como estudiante, quiero poder realizar envíos a los retos, añadiendo imágenes o documentos adjuntos de acorde a la necesidad.</td><td>Escenario 1: Envío exitoso<br>Dado que el estudiante está en un reto activo<br>Cuando selecciona "Nuevo envío", adjunta un documento PDF y escribe un comentario<br>Y hace clic en "Enviar"<br>Entonces el sistema guarda el envío<br>Y muestra el mensaje "Envío realizado correctamente"<br><br>Escenario 2: Envío sin archivos<br>Dado que el estudiante está en un reto activo<br>Cuando intenta enviar sin adjuntar archivos ni texto<br>Entonces el sistema muestra "Debe agregar al menos un archivo o texto"<br>Y no permite completar el envío</td><td>EP-003</tr>
    <tr><td>US-015</td><td>Gestionar integrantes del grupo</td><td>Como profesor, quiero poder ver la lista de estudiantes de cada grupo que manejo, y opciones tanto para ver sus perfiles como para eliminarlos</td><td>Escenario 1: Ver lista de estudiantes<br>Dado que el profesor accede a un grupo<br>Cuando selecciona la opción "Integrantes"<br>Entonces el sistema muestra la lista completa de estudiantes matriculados<br><br>Escenario 2: Eliminar estudiante<br>Dado que el profesor está viendo la lista de integrantes<br>Cuando selecciona "Eliminar" junto a un estudiante<br>Y confirma la acción<br>Entonces el sistema remueve al estudiante del grupo<br>Y actualiza la lista mostrada</td><td>EP-001</td></tr>
    <tr><td>US-016</td><td>Distribución programada de retos</td><td>Como profesor, quiero programar la publicación automática de retos en fechas específicas, para garantizar que se liberen según el cronograma académico.</td><td>Escenario 1: Programación exitosa<br>Dado que el profesor ha creado un reto<br>Cuando selecciona "Programar publicación" y fija fecha/hora<br>Entonces el sistema guarda la configuración<br>Y muestra "El reto se publicará el [fecha] a las [hora]"<br><br>Escenario 2: Intento de fecha pasada<br>Dado que el profesor ingresa una fecha anterior al día actual<br>Cuando intenta programar<br>Entonces el sistema muestra "La fecha debe ser futura"<br>Y bloquea la confirmación</td><td>EP-003</td></tr>
    <tr><td>US-017</td><td>Generación de Código de Invitación</td><td>Como profesor, quiero poder generar un código de invitación que pueda compartir con mis alumnos de forma sencilla para que se unan al grupo creado</td><td>Escenario 1: Generación de código exitosa<br>Dado que el profesor accede a un grupo creado<br>Cuando selecciona la opción "Generar código de invitación"<br>Entonces el sistema crea un código alfanumérico único<br>Y muestra las opciones para copiarlo/compartirlo<br><br>Escenario 2: Código ya generado<br>Dado que el grupo ya tiene un código activo<br>Cuando el profesor intenta generar otro código<br>Entonces el sistema muestra el código existente<br>Y ofrece renovarlo (invalidando el anterior)</td><td>EP-001</td></tr>
    <tr><td>US-018</td><td>Visualización de logros gamificados</td><td>Como estudiante, quiero ver mis insignias y puntos acumulados en un tablero personal, para mantenerme motivado con mi progreso académico.</td><td>Escenario 1: Visualización de logros<br>Dado que el estudiante ha completado retos<br>Cuando accede a su perfil<br>Entonces ve un tablero con insignias obtenidas y puntaje total<br><br>Escenario 2: Nuevo logro desbloqueado<br>Dado que el estudiante cumple condiciones para una nueva insignia<br>Cuando completa un reto especial<br>Entonces recibe notificación automática con el nuevo logro</td><td>EP-003</td></tr><tr><td>US-019</td><td>Configuración de notificaciones</td><td>Como usuario, quiero personalizar qué notificaciones recibo (recordatorios de retos, mensajes grupales, etc.), para optimizar mi experiencia en la plataforma.</td><td>Escenario 1: Personalización exitosa<br>Dado que el usuario accede a configuración<br>Cuando selecciona/deselecciona tipos de notificación<br>Y guarda los cambios<br>Entonces el sistema aplica las preferencias<br><br>Escenario 2: Notificación no deseada<br>Dado que el usuario desactivó notificaciones de logros<br>Cuando desbloquea una insignia<br>Entonces no recibe alerta en su bandeja</td><td>EP-001</td></tr><tr>
    <tr><td>US-020</td><td>Validación de códigos de grupo</td><td>Como estudiante, quiero poder validar códigos de invitación a grupos, para unirme rápidamente a las actividades académicas correctas.</td><td>Escenario 1: Unión exitosa a grupo<br>Dado que el estudiante ingresa un código válido<br>Cuando el sistema verifica que coincide con un grupo activo<br>Entonces se une automáticamente al grupo<br>Y recibe confirmación visual<br><br>Escenario 2: Código inválido<br>Dado que el estudiante ingresa un código expirado/erróneo<br>Cuando el sistema intenta validarlo<br>Entonces muestra mensaje claro "Código inválido o expirado"<br>Y sugiere solicitar uno nuevo al profesor</td><td>EP-001</td></tr>
    <tr><td>US-021</td>
<td>Hero Section</td>
<td>Como usuario, quiero ver una introducción atractiva de la página con una imagen representativa.</td>
<td>Escenario 1: Visualización de la sección Hero<br>
Dado que el usuario ingresa al sitio web<br>
Cuando la página carga completamente<br>
Entonces puede ver una imagen destacada con texto introductorio</td>
<td>EP-005</td>
</tr>
    <tr><td>US-022</td>
<td>Main Features Section</td>
<td>Como usuario, quiero conocer las razones para elegir EduHive a través de sus características principales.</td>
<td>Escenario 1: Visualización de características<br>
Dado que el usuario navega hasta Main Features<br>
Cuando scrollea la sección<br>
Entonces ve 4 iconos y descripciones de beneficios clave<br><br>
Escenario 2: Interacción con características<br>
Dado que el usuario está en Main Features<br>
Cuando pasa el cursor sobre una tarjeta<br>
Entonces esta muestra un efecto visual destacado</td>
<td>EP-005</td>
</tr>
    <tr><td>US-023</td>
<td>Explore Course Section</td>
<td>Como usuario, quiero explorar los cursos disponibles para encontrar opciones que se ajusten a mis necesidades.</td>
<td>Escenario 1: Visualización de cursos<br>
Dado que el usuario llega a la sección<br>
Cuando navega por la página<br>
Entonces ve tarjetas de cursos con imágenes y título<br><br>
Escenario 2: Interacción con cursos<br>
Dado que el usuario está en Explore Course<br>
Cuando pasa el cursor sobre una tarjeta<br>
Entonces esta muestra un efecto visual destacado</td>
<td>EP-005</td>
</tr>
    <tr><td>US-024</td>
<td>Knowledge Section</td>
<td>Como usuario, quiero obtener información adicional sobre la plataforma y su enfoque educativo.</td>
<td>Escenario 1: Acceso a información<br>
Dado que el usuario navega a Knowledge<br>
Cuando lee el contenido<br>
Entonces encuentra datos relevantes sobre la metodología educativa</td>
<td>EP-005</td>
</tr>
    <tr><td>US-025</td>
<td>Contact Section</td>
<td>Como usuario, quiero contactar al equipo.</td>
<td>Escenario 1: Visualización del formulario<br>
Dado que el usuario scrollea en la landing page<br>
Cuando llega a la sección Contact<br>
Entonces ve campos para nombre, email, número de teléfono, compañia y mensaje<br><br>
Escenario 2: Validación de campos<br>
Dado que el usuario no completa un campo requerido<br>
Cuando intenta enviar<br>
Entonces el sistema muestra un mensaje de error específico<br><br>
Escenario 3: Envío exitoso<br>
Dado que completa todos los campos correctamente<br>
Cuando envía el formulario<br>
Entonces recibe un mensaje de confirmación</td>
<td>EP-005</td>
</tr>
    <tr><td>US-026</td>
<td>Testimonials Section</td>
<td>Como usuario, quiero ver testimonios de otros estudiantes para evaluar la calidad del servicio.</td>
<td>Escenario 1: Visualización de testimonios<br>
Dado que el usuario llega a la sección<br>
Cuando la página carga<br>
Entonces ve al menos un testimonio con comentario, nombre y carrera<br><br>
Escenario 2: Navegación entre testimonios<br>
Dado que hay múltiples testimonios<br>
Cuando hace clic en las flechas de navegación<br>
Entonces el sistema muestra el testimonio siguiente o anterior</td>
<td>EP-005</td>
</tr>
    <tr><td>US-027</td>
<td>Latest Updates Section</td>
<td>Como usuario, quiero conocer las últimas actualizaciones de cursos con fechas y material informativo.</td>
<td>Escenario 1: Visualización de actualizaciones<br>
Dado que el usuario scrollea en la landing page<br>
Cuando llega a la sección de Lastest Updates<br>
Entonces ve una lista de cursos con fechas de actualización<br><br>
Escenario 2: Reproducción de video<br>
Dado que hay un video informativo<br>
Cuando hace clic en el botón de reproducción<br>
Entonces el video se inicia en un reproductor</td>
<td>EP-005</td>
</tr>
    <tr><td>US-028</td>
<td>Subscribe Section</td>
<td>Como usuario, quiero suscribirme al newsletter para recibir actualizaciones por correo.</td>
<td>Escenario 1: Visualización del formulario<br>
Dado que el usuario scrollea en la landing page<br>
Cuando llega a la sección Subscribe<br>
Entonces ve un campo de email y botón "Subscribe"<br><br>
Escenario 2: Suscripción exitosa<br>
Dado que ingresa un email válido<br>
Cuando hace clic en Subscribe<br>
Entonces recibe un mensaje de confirmación<br><br>
Escenario 3: Validación de email<br>
Dado que ingresa un email inválido<br>
Cuando intenta suscribirse<br>
Entonces el sistema muestra un error</td>
<td>EP-005</td>
</tr>
    <tr><td>US-029</td><td>Edición de perfil</td><td>Como usuario, quiero editar mi perfil personal, para mantener actualizada mi información de contacto y habilidades.</td><td>Escenario 1: Dado que el usuario accede a su perfil, Cuando selecciona "Editar perfil", Entonces puede modificar su nombre, foto, bio y habilidades.<br><br>
	  Escenario 2: Dado que el usuario guarda cambios, Cuando completa la edición, Entonces el sistema actualiza su información en todos los módulos donde aparece.
</td><td>EP-005</td></tr>
    <tr><td>US-030</td><td>Recordatorios de Fechas Límite</td><td>Como estudiante, quiero recibir recordatorios automáticos de las fechas límite de retos, para no olvidar entregar a tiempo.</td><td>Escenario 1: Dado que hay un reto próximo a vencer, Cuando faltan 48 horas, Entonces el sistema envía una notificación automática.<br><br>
    Escenario 2: Dado que el reto vence hoy, Cuando quedan 6 horas, Entonces se envía un último recordatorio.
</td><td>EP-003</td></tr>
    <tr><td>US-031</td><td>Historial de retos completados</td><td>Como estudiante, quiero ver un historial de los retos que he completado, para hacer seguimiento de mi progreso a lo largo del curso.</td><td>Escenario 1: Dado que el estudiante accede a su perfil, Cuando ingresa a la sección "Historial de retos", Entonces puede ver una lista con fecha, nombre del reto y su resultado.<br><br>
    Escenario 2: Dado que el estudiante revisa un reto específico, Cuando hace clic en el reto, Entonces puede ver detalles como su calificación y feedback recibido.
</td><td>EP-004</td></tr>
    <tr><td>US-032</td><td>Foro de equipos</td><td>Como estudiante, quiero participar en un foro de discusión de mi grupo, para colaborar y resolver dudas de los retos en equipo.</td><td>Escenario 1: Dado que el estudiante pertenece a un grupo, Cuando accede al foro, Entonces puede publicar mensajes y responder a sus compañeros.<br><br>
    Escenario 2: Dado que un estudiante responde en el foro, Cuando se publica un comentario, Entonces todos los integrantes reciben una notificación.
</td><td>EP-001</td></tr>
    <tr><td>US-033</td><td>Métricas de participación</td><td>Como profesor, quiero visualizar métricas de participación de los estudiantes en sus grupos, para evaluar su colaboración.</td><td>Escenario 1: Dado que el profesor accede a un grupo, Cuando visualiza las métricas, Entonces puede ver estadísticas de publicaciones en foros, entregas de retos y reuniones realizadas.<br><br>
    Escenario 2: Dado que un estudiante no participa, Cuando su participación es baja, Entonces el sistema lo marca con un indicador de alerta.
</td><td>EP-002</td></tr>
    <tr><td>US-034</td><td>Clasificación de equipos</td><td>Como estudiante, quiero ver un ranking de equipos basado en los puntos de retos completados, para motivarme a mejorar junto a mi grupo.</td><td>Escenario 1: Dado que los equipos completan retos, Cuando acceden a la sección de rankings, Entonces ven la posición de su equipo respecto a otros.<br><br>
    Escenario 2: Dado que se actualizan los puntajes, Cuando un equipo sube de posición, Entonces el sistema muestra una notificación de felicitación.
</td><td>EP-003</td></tr>
    <tr><td>US-035</td><td>Reporte semanal</td><td>Como estudiante, quiero recibir un resumen semanal de mis actividades y avances, para reflexionar sobre mi progreso.</td><td>Escenario 1: Dado que es fin de semana, Cuando el sistema genera reportes, Entonces el estudiante recibe por correo un resumen de retos completados, puntos acumulados y nuevas habilidades.<br><br>
    Escenario 2: Dado que el estudiante abrió el correo, Cuando revisa el reporte, Entonces puede ver sugerencias de próximas actividades a realizar.
</td><td>EP-004</td></tr>
    <tr><td>US-036</td><td>Reporte de errores</td><td>Como usuario, quiero reportar fácilmente fallos técnicos en la plataforma, para ayudar a mejorar el sistema.</td><td>Escenario 1: Dado que el usuario detecta un error, Cuando hace clic en "Reportar un problema", Entonces puede enviar una descripción y captura de pantalla.<br><br>
    Escenario 2: Dado que el reporte es enviado, Cuando se registra exitosamente, Entonces el usuario recibe confirmación y un número de seguimiento.
</td><td>EP-005</td></tr>
    <tr><td>US-037</td><td>Seguridad de la cuenta con correo</td><td>Como usuario quiero que haya una fuerte seguridad de mi cuenta por correo electrónico para evitar vulneraciones</td><td>Escenario 1: Dado que creó una cuenta en la página Cuando escribo mi correo Entonces se me notifica que se ha enviado un mensaje de verificación.<br><br>
    Escenario 2: Dado que recibo un mensaje de verificación Cuando escribo el mensaje Entonces mi cuenta es más difícil de vulnerar
</td><td>EP-005</td></tr>
    <tr><td>US-038</td><td>Olvido de contraseñas</td><td>Como usuario quiero poder cambiar contraseñas si me olvido de ella para tener buen registro de mi cuenta</td><td>Escenario 1: Dado que olvidé mi contraseña Cuando presióno el botón de “Olvidé mi contraseña” Entoncesme sale un menú para cambiarla<br><br>Escenario 2: Dado que lleno los datos que se me piden Cuando verificó que somos el mismo usuario Entonces cambió mi contraseña
</td><td>EP-005</td></tr>
    <tr><td>US-039</td><td>Estadísticas de insignias del estudiante</td><td>Como estudiante quiero tener estadísticas sobre mis insignias para tener una data de mis logros</td><td>Escenario 1: Dado que deseo tener la estadísticas de mis insignias Cuando ingresó a mi perfil Entonces me voy al apartado de estadísticas<br><br>Escenario 2: Dado que  entró al menú de estadísticas Cuando seleccione la información que deseo Entonces podré visualizar mis insignias
</td><td>EP-003</td></tr>
    <tr><td>US-040</td><td>Eliminar estudiantes de los grupos</td><td>Como profesor quiero poder eliminar estudiantes de los grupos para que haya una mejor gestión de estos</td><td>Escenario 1: Dado que el profesor hace click en “Kick ” Cuando la gestión de grupos se le pregunta si desea echar al estudiante, Entonces el profesor ve las opciones<br><br>Escenario 2: Dado que eligió la opción “Si ”, Cuando se envía el formulario, Entonces se procede a eliminar al estudiante del grupo
</td><td>EP-001</td></tr>
  </tbody>
</table>

### 3.3. Impact Mapping

<img src="./images/chapter-3/impactmapping.png" alt="Impact Mapping" width="1000"/>

### 3.4. Product Backlog

<table>
  <thead>
    <tr>
      <th>Orden</th>
      <th>Código US</th>
      <th>Título</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>US-005</td><td>Acceder al panel de progreso del curso</td><td>13</td></tr>
    <tr><td>2</td><td>US-011</td><td>Seguir el rendimiento de los equipos</td><td>13</td></tr>
    <tr><td>3</td><td>US-033</td><td>Métricas de participación</td><td>13</td></tr>
    <tr><td>4</td><td>US-003</td><td>Creación de grupos</td><td>8</td></tr>
    <tr><td>5</td><td>US-007</td><td>Diseñar de retos personalizados</td><td>8</td></tr>
    <tr><td>6</td><td>US-009</td><td>Definición de fechas límite de retos</td><td>8</td></tr>
    <tr><td>7</td><td>US-016</td><td>Distribución programada de retos</td><td>8</td></tr>
    <tr><td>8</td><td>US-001</td><td>Asignación de grupos</td><td>5</td></tr>
    <tr><td>9</td><td>US-002</td><td>Visualización del equipo</td><td>5</td></tr>
    <tr><td>10</td><td>US-004</td><td>Comparación de rendimiento</td><td>5</td></tr>
    <tr><td>11</td><td>US-006</td><td>Recepcion de retos semanales gamificados</td><td>5</td></tr>
    <tr><td>12</td><td>US-008</td><td>Obtencion de feedback automático</td><td>5</td></tr>
    <tr><td>13</td><td>US-010</td><td>Visualizacion de horarios</td><td>5</td></tr>
    <tr><td>14</td><td>US-012</td><td>Revisar general de rendimiento</td><td>5</td></tr>
    <tr><td>15</td><td>US-013</td><td>Asignación de feeback</td><td>5</td></tr>
    <tr><td>16</td><td>US-014</td><td>Enviar respuesta a reto</td><td>5</td></tr>
    <tr><td>17</td><td>US-015</td><td>Gestionar integrantes del grupo</td><td>5</td></tr>
    <tr><td>18</td><td>US-017</td><td>Generación de Código de Invitación</td><td>5</td></tr>
    <tr><td>19</td><td>US-018</td><td>Visualización de logros gamificados</td><td>5</td></tr>
    <tr><td>20</td><td>US-019</td><td>Configuración de notificaciones</td><td>5</td></tr>
    <tr><td>21</td><td>US-020</td><td>Validación de códigos de grupo</td><td>5</td></tr>
    <tr><td>22</td><td>US-021</td><td>Hero Section</td><td>5</td></tr>
    <tr><td>23</td><td>US-022</td><td>Main Features Section</td><td>5</td></tr>
    <tr><td>24</td><td>US-023</td><td>Explore Course Section</td><td>5</td></tr>
    <tr><td>25</td><td>US-024</td><td>Knowledge Section</td><td>5</td></tr>
    <tr><td>26</td><td>US-025</td><td>Contact Section</td><td>5</td></tr>
    <tr><td>27</td><td>US-026</td><td>Testimonials Section</td><td>5</td></tr>
    <tr><td>28</td><td>US-027</td><td>Latest Updates Section</td><td>5</td></tr>
    <tr><td>29</td><td>US-028</td><td>Subscribe Section</td><td>5</td></tr>
    <tr><td>30</td><td>US-029</td><td>Edición de perfil</td><td>5</td></tr>
    <tr><td>31</td><td>US-030</td><td>Recordatorios de Fechas Límite</td><td>5</td></tr>
    <tr><td>32</td><td>US-031</td><td>Historial de retos completados</td><td>5</td></tr>
    <tr><td>33</td><td>US-032</td><td>Foro de equipos</td><td>5</td></tr>
    <tr><td>34</td><td>US-034</td><td>Clasificación de equipos</td><td>5</td></tr>
    <tr><td>35</td><td>US-035</td><td>Reporte semanal</td><td>5</td></tr>
    <tr><td>36</td><td>US-036</td><td>Reporte de errores</td><td>5</td></tr>
    <tr><td>37</td><td>US-037</td><td>Seguridad de la cuenta con correo</td><td>3</td></tr>
    <tr><td>38</td><td>US-038</td><td>Olvido de contraseñas</td><td>3</td></tr>
    <tr><td>39</td><td>US-039</td><td>Estadísticas de insignias del estudiante</td><td>3</td></tr>
    <tr><td>40</td><td>US-040</td><td>Eliminar estudiantes de los grupos</td><td>3</td></tr>
  </tbody>
</table>

## Capítulo IV: Product Design

### 4.1. Style Guidelines

#### 4.1.1. General Style Guidelines

#### 4.1.2. Web Style Guidelines

### 4.2. Information Architecture

#### 4.2.1. Organization Systems

#### 4.2.2 Labeling Systems

#### 4.2.3 SEO Tags and Meta Tags

#### 4.2.4. Searching Systems

#### 4.2.5. Navigation Systems

### 4.3.  Landing Page UI Design.

#### 4.3.1. Landing Page Wireframe.

#### 4.3.2. Landing Page Mock-up.

### 4.4.  Web Applications UX/UI Design.

#### 4.4.1. Web Applications Wireframes

#### 4.4.2. Web Applications Wireflow Diagrams

#### 4.4.2. Web Applications Mock-ups

#### 4.4.3. Web Applications User Flow Diagrams

### 4.5.  Web Applications Prototyping

### 4.6.  Domain-Driven Software Architecture

#### 4.6.1. Software Architecture Context Diagram

#### 4.6.2. Software Architecture Container Diagrams

#### 4.6.3. Software Architecture Components Diagrams

### 4.7.  Software Object-Oriented Design

#### 4.7.1. Class Diagrams

#### 4.7.2. Class Dictionary

### 4.8.  Database Design

#### 4.8.1. Database Diagram

## Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management

#### 5.1.1. Software Development Environment Configuration

#### 5.1.2. Source Code Management

#### 5.1.3. Source Code Style Guide & Conventions

#### 5.1.4. Software Deployment Configuration

### 5.2. Landing Page, Services & Applications Implementation.

#### 5.2.1. Sprint 1

##### 5.2.1.1. Sprint Planning 1

##### 5.2.1.2. Aspect Leaders and Collaborators

##### 5.2.1.3. Sprint Backlog 1

##### 5.2.1.4. Development Evidence for Sprint Review

##### 5.2.1.5. Execution Evidence for Sprint Review

##### 5.2.1.6. Services Documentation Evidence for Sprint Review

##### 5.2.1.7. Software Deployment Evidence for Sprint Review

##### 5.2.1.8. Team Collaboration Insights during Sprint

### 5.3. Validation Interviews

#### 5.3.1. Diseño de entrevistas

#### 5.3.2. Registro de entrevistas

#### 5.3.3. Evaluaciones según heurísticas

### 5.4. Video About-the-Product

## Conclusiones

## Bibliografía

## Anexos
