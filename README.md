<center>

# Universidad Peruana De Ciencas Aplicadas
## 1ASI0572 Desarrollo de Soluciones IOT
### INGENIERÍA DE SOFTWARE

</center>

<p align = "center"> <img src = "https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img> </p>

<center>

# Informe Trabajo Final
## Docente: Marco Antonio Leon Baca
## Startup: SuiteTechTeam
## Producto: SmartSuit
## Integrantes 

 </center> 

* **Aaron Elias Acuña Alarcon U202211552**
* **Diego Rafael Cisneros Tafur U20221a715**
* **Ely Rivaldo Cortez Flores U202215313**
* **Francis Daniel Mamani Silva U202219315** 
* **Mariana Alexandra Chambi Mendoza U202217389**

<center>

### Abril 2025
### Ciclo: 2025-01
### NRC: 15185

</center>

---

<br>

## Registro de Versiones del Informe

| Versión | Fecha      | Autor                                                                          | Descripción de modificación                                                                                      |
|---------|------------|--------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| 1.0     | 14/04/2025 | Ely Cortez                                                               | Se creo la ramificación del repositorio y se adicionó los documentos en su versión inicial previa a la investigacón |



### Project Report Collaboration Insights

URL del repositorio para el reporte del proyecto: https://github.com/SuiteTechTeam/Project-report

Github Collaboration Insights proporciona un cronograma que muestra las principales ramas y los procesos de fusión que han ocurrido. Todas las ramas se han generado siguiendo los principios de GitFlow, lo que garantiza una organización efectiva al utilizar un sistema de control de versiones.

- Aaron Elias Acuña Alarcon (JenayAaron)
- Diego Rafael Cisneros Tafur (Diego22rct)
- Ely Rivaldo Cortez Flores (rivacortez)
- Francis Daniel Mamani Silva (usuarioGithub)
- Mariana Alexandra Chambi Mendoza (MarianaAlexandra05)

Se divieron las siguientes ramas para la colaboración en el proyecto:

- main
- quality
- develop

* #### Entregable TB1

A continuación se presentan los gráficos de colaboración de los integrantes del equipo en el repositorio de nuestro 
primer sprint. Estos gráficos ofrecen una representación visual de la cantidad de contribuciones realizadas por cada
miembro del equipo, junto con la fecha en que se llevaron a cabo. Además, se presenta información sobre la cantidad de 
líneas de código que se han modificado en cada uno de los commits.


## Contenido 

[Registro de Versiones del Informe](#registro-de-versiones-del-informe)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo](#211-análisis-competitivo)  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)    
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)

[2.4. Ubiquitous Language](#24-ubiquitous-language)

[Capítulo III: Requirements Specificatio](#capítulo-iii-requirements-specification)

[3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)

[3.2. User Stories](#32-user-stories)

[3.3. Impact Mapping](#33-impact-mapping)

[3.4. Product Backlog](#34-product-backlog)

[Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)

[4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)  

[4.1.1. EventStorming](#411-eventstorming)  
[4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)  
[4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)  
[4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)  
[4.1.2. Context Mapping](#412-context-mapping)  
[4.1.3. Software Architecture](#413-software-architecture)  
[4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)  
[4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)  
[4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)  
[4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)

[4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)

[4.2.1. Bounded Context: <Bounded Context Name>](#421-bounded-context-bounded-context-name)  
[4.2.1.1. Domain Layer](#4211-domain-layer)  
[4.2.1.2. Interface Layer](#4212-interface-layer)  
[4.2.1.3. Application Layer](#4213-application-layer)  
[4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)  
[4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)  
[4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)  
[4.2.1.7. Bounded Context Domain Layer Class Diagrams](#4217-bounded-context-domain-layer-class-diagrams)  
[4.2.1.8. Bounded Context Database Design Diagram](#4218-bounded-context-database-design-diagram)

[4.2.2. Bounded Context: <Bounded Context Name>](#422-bounded-context-bounded-context-name)  
[4.2.2.1. Domain Layer](#4221-domain-layer)  
[4.2.2.2. Interface Layer](#4222-interface-layer)  
[4.2.2.3. Application Layer](#4223-application-layer)  
[4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)  
[4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)  
[4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)  
[4.2.2.7. Bounded Context Domain Layer Class Diagrams](#4227-bounded-context-domain-layer-class-diagrams)  
[4.2.2.8. Bounded Context Database Design Diagram](#4228-bounded-context-database-design-diagram)

[4.2.3. Bounded Context: <Bounded Context Name>](#423-bounded-context-bounded-context-name)  
[4.2.3.1. Domain Layer](#4231-domain-layer)  
[4.2.3.2. Interface Layer](#4232-interface-layer)  
[4.2.3.3. Application Layer](#4233-application-layer)  
[4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)  
[4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)  
[4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)  
[4.2.3.7. Bounded Context Domain Layer Class Diagrams](#4237-bounded-context-domain-layer-class-diagrams)  
[4.2.3.8. Bounded Context Database Design Diagram](#4238-bounded-context-database-design-diagram)

[4.2.4. Bounded Context: <Bounded Context Name>](#424-bounded-context-bounded-context-name)  
[4.2.4.1. Domain Layer](#4241-domain-layer)  
[4.2.4.2. Interface Layer](#4242-interface-layer)  
[4.2.4.3. Application Layer](#4243-application-layer)  
[4.2.4.4. Infrastructure Layer](#4244-infrastructure-layer)  
[4.2.4.5. Bounded Context Software Architecture Component Level Diagrams](#4245-bounded-context-software-architecture-component-level-diagrams)  
[4.2.4.6. Bounded Context Software Architecture Code Level Diagrams](#4246-bounded-context-software-architecture-code-level-diagrams)  
[4.2.4.7. Bounded Context Domain Layer Class Diagrams](#4247-bounded-context-domain-layer-class-diagrams)  
[4.2.4.8. Bounded Context Database Design Diagram](#4248-bounded-context-database-design-diagram)

[4.2.5. Bounded Context: <Bounded Context Name>](#425-bounded-context-bounded-context-name)  
[4.2.5.1. Domain Layer](#4251-domain-layer)  
[4.2.5.2. Interface Layer](#4252-interface-layer)  
[4.2.5.3. Application Layer](#4253-application-layer)  
[4.2.5.4. Infrastructure Layer](#4254-infrastructure-layer)  
[4.2.5.5. Bounded Context Software Architecture Component Level Diagrams](#4255-bounded-context-software-architecture-component-level-diagrams)  
[4.2.5.6. Bounded Context Software Architecture Code Level Diagrams](#4256-bounded-context-software-architecture-code-level-diagrams)  
[4.2.5.7. Bounded Context Domain Layer Class Diagrams](#4257-bounded-context-domain-layer-class-diagrams)  
[4.2.5.8. Bounded Context Database Design Diagram](#4258-bounded-context-database-design-diagram)

[Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)

[5.1. Style Guidelines](#51-style-guidelines)  
[5.1.1. General Style Guidelines](#511-general-style-guidelines)  
[5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)

[5.2. Information Architecture](#52-information-architecture)  
[5.2.1. Organization Systems](#521-organization-systems)  
[5.2.2. Labeling Systems](#522-labeling-systems)  
[5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)  
[5.2.4. Searching Systems](#524-searching-systems)  
[5.2.5. Navigation Systems](#525-navigation-systems)

[5.3. Landing Page UI Design](#53-landing-page-ui-design)  
[5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)  
[5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)

[5.4. Applications UX/UI Design](#54-applications-uxui-design)  
[5.4.1. Applications Wireframes](#541-applications-wireframes)  
[5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)  
[5.4.3. Applications Mock-ups](#543-applications-mock-ups)  
[5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)

[5.5. Applications Prototyping](#55-applications-prototyping)

[Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation-deployment)

[6.1. Software Configuration Management](#61-software-configuration-management)  
[6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)  
[6.1.2. Source Code Management](#612-source-code-management)  
[6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide-conventions)  
[6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)

[6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services-applications-implementation)  
[6.2.X. Sprint 1](#62x-sprint-1)  
[6.2.X.1. Sprint Planning 1](#62x1-sprint-planning-1)  
[6.2.X.2. Aspect Leaders and Collaborators](#62x2-aspect-leaders-and-collaborators)  
[6.2.X.3. Sprint Backlog 1](#62x3-sprint-backlog-n)  
[6.2.X.4. Development Evidence for Sprint Review](#62x4-development-evidence-for-sprint-review)  
[6.2.X.5. Testing Suite Evidence for Sprint Review](#62x5-testing-suite-evidence-for-sprint-review)  
[6.2.X.6. Execution Evidence for Sprint Review](#62x6-execution-evidence-for-sprint-review)  
[6.2.X.7. Services Documentation Evidence for Sprint Review](#62x7-services-documentation-evidence-for-sprint-review)  
[6.2.X.8. Software Deployment Evidence for Sprint Review](#62x8-software-deployment-evidence-for-sprint-review)  
[6.2.X.9. Team Collaboration Insights during Sprint](#62x9-team-collaboration-insights-during-sprint)

[6.3. Validation Interviews](#63-validation-interviews)  
[6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)  
[6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)  
[6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)

[6.4. Video About-the-Product](#64-video-about-the-product)

[Conclusiones](#conclusiones)

[Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

[Video About-the-Team](#video-about-the-team)

[Bibliografía](#bibliografía)

[Anexos](#anexos)




## Student Outcome

<table>
  <thead>
    <tr>
      <th>Criterio especifico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
     <!--PRIMER CRITERIO DE STUDENT OUTCOME-->
      <td rowspan="17">
        Trabaja en equipo para
        proporcionar liderazgo en
        forma conjunta
      </td>
       <!--ENTREGA TB1-->
      <!-- Estudiante 1 TB1 -->    
      <td>
        <b>Acuña Alarcon, Aaron Elias TB1:</b> 
        Texto
        </td>
        <td rowspan="5"> 
         <b>CONCLUSIÓN DEL ENTREGABLE TB1</b><br>
        Texto
      </td>   
    </tr>
    <!-- Estudiante 2 TB1 --> 
    <tr> 
      <td>
      <b>Cisneros Tafur, Diego Rafael TB1:</b> <br> 
      Texto  
    </td>   
    </tr>
    <!-- Estudiante 3 TB1-->
     <tr>   
      <td>
        <b>Cortez Flores, Ely Rivaldo TB1:</b><br>
        Texto
      </td>    
    </tr>
    <!-- Estudiante 4 TB1-->
     <tr>   
      <td>
      <b>Chambi Mendoza, Mariana Alexandra TB1:</b><br>
       Texto</td>   
    </tr>
    <!-- Estudiante 5 TB1-->
    <tr>   
      <td>
        <b>Mamani Silva, Francis Daniel TB1:</b><br>
        Texto
      </td>   
    </tr>
    <tbody>
    <tr>
     <!--SEGUNDO CRITERIO DE STUDENT OUTCOME-->
      <td rowspan="17">
        Crea un entorno colaborativo e
        inclusivo, establece metas,
        planifica tareas y cumple
        objetivos.  
      </td>
       <!--ENTREGA TB1-->
      <!-- Estudiante 1 TB1 -->    
      <td>
        <b>Acuña Alarcon, Aaron Elias TB1:</b> 
        Texto
        </td>
        <td rowspan="5"> 
         <b>CONCLUSIÓN DEL ENTREGABLE TB1</b><br>
        Texto
      </td>   
    </tr>
    <!-- Estudiante 2 TB1 --> 
    <tr> 
      <td>
      <b>Cisneros Tafur, Diego Rafael TB1:</b> <br> 
      Texto  
    </td>   
    </tr>
    <!-- Estudiante 3 TB1-->
     <tr>   
      <td>
        <b>Cortez Flores, Ely Rivaldo TB1:</b><br>
        Texto
      </td>    
    </tr>
    <!-- Estudiante 4 TB1-->
     <tr>   
      <td>
      <b>Chambi Mendoza, Mariana Alexandra TB1:</b><br>
       Texto</td>   
    </tr>
    <!-- Estudiante 5 TB1-->
    <tr>   
      <td>
        <b>Mamani Silva, Francis Daniel TB1:</b><br>
        Texto
      </td>   
    </tr>
</table>

# Capítulo I: Introducción

## 1.1. Startup Profile

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

#### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements.

#### 1.2.2.2. Lean UX Assumptions.

#### 1.2.2.3. Lean UX Hypothesis Statements.

#### 1.2.2.4. Lean UX Canvas.

## 1.3. Segmentos objetivo.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores.

### 2.1.1. Análisis competitivo.

### 2.1.2. Estrategias y tácticas frente a competidores.

## 2.2. Entrevistas.

### 2.2.1. Diseño de entrevistas.

### 2.2.2. Registro de entrevistas.

### 2.2.3. Análisis de entrevistas.

## 2.3. Needfinding.
Para tener una mejor idea de cómo será la experiencia del usuario con nuestro producto, utilizaremos las herramientas de User Persona, User Task Matrix, User Journey Mapping, Empathy Mapping y As-is Scenario Mapping.

### 2.3.1. User Personas.

**Segmento de gerentes:**  
![Imagen User Persona 1](https://i.imgur.com/68GDcWN.png)

**Segmento de trabajadores:**  
![Imagen User Persona 1](https://i.imgur.com/R5GiS1R.png)
### 2.3.2. User Task Matrix.

| Tarea                                  | Gerente (Frecuencia / Importancia) | Empleado (Frecuencia / Importancia) |
|----------------------------------------|------------------------------------|-------------------------------------|
| Crear una cuenta                      | Alta - Alta                        | Alta - Alta                         |
| Seguimiento de ingresos y gastos      | Media - Alta                       | Baja - Media                        |
| Gestión de inventarios                | Media - Alta                       | Alta - Alta                         |
| Coordinación con proveedores          | Alta - Alta                        | Baja - Baja                         |
| Capacitación del personal             | Alta - Alta                        | Media - Alta                        |
| Evaluación de desempeño del personal | Alta - Alta                        | Alta - Alta                         |
| Preparación de informes y análisis de datos | Media - Alta              | Alta - Alta                         |
| Recibir notificaciones de baja en el inventario | Alta - Alta             | Baja - Media                        |
| Asignar tareas a empleados            | Alta - Alta                        | Alta - Alta                         |
| Visualizar la ocupación de habitaciones en tiempo real | Alta - Alta          | Media - Media                       |
| Administrar permisos de los empleados | Alta - Alta                        | Baja - Alta                         |
| Programar turnos de trabajo           | Alta - Alta                        | Alta - Alta                         |
| Notificaciones de cambio de agenda    | Media - Alta                       | Baja - Baja                         |
| Reportar problemas a la gerencia      | Alta - Alta                        | Media - Alta                        |
| Registrar el check-in y check-out del huésped | Alta - Alta                  | Alta - Alta                         |
| Notificaciones de comentarios         | Media - Alta                       | Baja - Alta                         |

Tareas con mayor frecuencia e importancia:<br><br>
Crear una cuenta: Esta tarea es crucial tanto para el gerente como para el empleado, ya que implica establecer una identidad en el sistema y acceso a las herramientas.<br><br>
Seguimiento de ingresos y gastos: Esta tarea es de alta importancia para el gerente, ya que implica la supervisión de la salud financiera del hotel y la toma de decisiones informadas. Para el empleado, aunque puede no estar directamente involucrado en esta tarea a diario, entender los ingresos y gastos del hotel puede ayudar en la planificación y ejecución de sus responsabilidades.<br><br>
Gestión de inventarios: Tanto el gerente como el empleado realizan esta tarea con alta frecuencia e importancia, ya que asegura que el hotel tenga los suministros necesarios para operar sin problemas. La falta de inventario puede afectar negativamente la experiencia del cliente y la eficiencia del hotel.<br><br>
Coordinación con proveedores: Esta tarea es de alta importancia para el gerente, ya que garantiza la disponibilidad oportuna de suministros esenciales. Aunque para el empleado puede tener una frecuencia menor, sigue siendo crucial para mantener la continuidad operativa.<br><br>
Asignar tareas a empleados: Esta tarea es fundamental para ambos usuarios, ya que garantiza que el trabajo se distribuya de manera eficiente y que todas las actividades necesarias para el funcionamiento del hotel se completen a tiempo.<br><br>
Programar turnos de trabajo: La programación de turnos es esencial para garantizar una cobertura adecuada en todas las áreas del hotel, lo que contribuye a la satisfacción del cliente y al funcionamiento fluido del negocio.<br><br>
Registrar el check-in y el check-out del huésped: Estas tareas son cruciales para ambos usuarios, ya que afectan directamente la experiencia del cliente y la gestión de la ocupación de las habitaciones del hotel.<br><br>
Principales diferencias y coincidencias entre lo realizado por los User Personas:<br><br>
Diferencias:<br>
La coordinación con proveedores es una tarea de alta importancia para el gerente pero de baja importancia para el empleado. Esto refleja el nivel de responsabilidad y la naturaleza estratégica de las decisiones que el gerente toma en comparación con las tareas más operativas del empleado.<br><br>
La capacitación del personal es una tarea de alta importancia para el gerente, ya que influye en la calidad del servicio y la satisfacción del cliente, pero es de media importancia para el empleado, que puede recibir la capacitación pero no necesariamente esté involucrado en su planificación y ejecución.<br><br>
Coincidencias:<br>
Tanto el gerente como el empleado participan en la evaluación del desempeño del personal, lo que destaca la importancia compartida de garantizar un equipo bien capacitado y motivado para brindar un servicio de calidad.<br><br>
La preparación de informes y análisis de datos es una tarea de alta importancia para ambos roles, lo que resalta la necesidad de tomar decisiones basadas en datos para mejorar la eficiencia operativa y la experiencia del cliente.

### 2.3.3. User Journey Mapping.

User Journey Map - Carlos Rebagliati - Gerente (As-Is):<br><br>
Inicio del día: El gerente comienza el día revisando los informes financieros y preparando la agenda para el día. Se siente estresado por la cantidad de tareas pendientes y la presión para garantizar que todo funcione sin problemas.<br><br>
Gestión de inventarios: El gerente se enfrenta a la tarea de revisar el inventario y hacer pedidos a los proveedores según sea necesario. Se siente frustrado por la falta de un sistema integrado que facilite esta tarea, y aburrido por la tarea en sí.<br><br>
Coordinación del personal: El gerente asigna tareas al personal y revisa los horarios. Se siente abrumado por la cantidad de comunicación necesaria para coordinar a todos los empleados.<br><br>
Comunicación con proveedores: El gerente se comunica con los proveedores para hacer seguimiento de los pedidos y resolver cualquier problema de entrega. Se siente frustrado por la falta de eficiencia en la comunicación.<br><br>
Análisis de datos y toma de decisiones: El gerente revisa los informes y datos disponibles para tomar decisiones informadas para el hotel. Se siente satisfecho cuando encuentra información útil, pero también preocupado por la falta de herramientas para un análisis más profundo, terminando con una sensación de aceptación por ser la última tarea del día.

![Journey Map Gerente](https://i.imgur.com/CDlhVY7.jpeg)

User Journey Map - Juan Guarnizo - Empleado (As-Is):<br><br>
Inicio del turno: El empleado comienza su turno revisando los horarios y recibiendo instrucciones del gerente. Se siente preparado para comenzar su jornada laboral.<br><br>
Atención al Cliente: El empleado atiende a los clientes, toma pedidos y proporciona asistencia según sea necesario. Se esfuerza por brindar un servicio amable y eficiente, pero termina sintiéndose aburrido o frustrado.<br><br>
Realización de tareas asignadas: El empleado completa las tareas asignadas, como limpieza de habitaciones, reposición de suministros o preparación de alimentos. Termina furioso cuando no obtiene una idea clara de los suministros y recursos faltantes.<br><br>
Comunicación con el Equipo: El empleado se comunica con otros miembros del equipo para coordinar actividades o resolver problemas. Se esfuerza por mantener una comunicación clara y efectiva con sus colegas, pero se frustra cuando ocurren malentendidos.<br><br>
Final del día: El empleado finaliza su turno, informa al gerente sobre cualquier problema o tarea pendiente, y se prepara para partir. Se siente resignado al terminar, especialmente cuando faltan tareas por completar y es a causa de la mala organización de recursos o suministros.

![Journey Map Empleado](https://i.imgur.com/CDlhVY7.jpeg)

### 2.3.4. Empathy Mapping.

**Segmento gerente:**
![Empathy Map Segmento1](https://i.imgur.com/572jtIM.png)

**Segmento trabajador:**
![Empathy Map Segmento1](https://i.imgur.com/ega3pUi.png)

### 2.3.5. As-is Scenario Mapping.
En esta sección se presentan los Scenario Mapping para los segmentos de gerentes y trabajadores, que describen cómo son las experiencias actuales de los usuarios en sus tareas diarias.

El link para ambos Scenario Mapping es: [Link de enlace](https://lucid.app/lucidspark/6d541f3f-440a-40fc-b3a7-1461742dc65e/edit?viewport_loc=2162%2C964%2C2846%2C1413%2C0_0&invitationId=inv_0e4e4622-20f9-43c4-ac8a-c034737fb585)

**Segmento gerente:**
![Segmento1](assets/chapter-2/seg-gerente.png)

**Segmento trabajador:**
![Segmento2](assets/chapter-2/seg-trabaj.png)

## 2.4. Ubiquitous Language.
En esta sección, nos centraremos en definir el significado de ciertos términos utilizados en el ambiente de nuestra solución en la gestión hotelera.

- **Check-In**  
  **Definition:** Process by which a guest registers their arrival at the hotel, provides the necessary information and receives the key to their room.

- **Check-Out**  
  **Definition:** Process by which a guest completes their stay at the hotel, makes final payment, and returns the room key.

- **Role**  
  **Definition:** Worker role to a specific area.

- **Staff**  
  **Definition:** They represent all hotel workers. They perform various tasks and responsibilities needed for the organization to operate.

- **Reservation**  
  **Definition:** Booking of a room by a guest.

- **Occupancy**  
  **Definition:** The percentage of rooms occupied in the hotel over a specified period of time.

- **Rate**  
  **Definition:** The price per night for a room.

- **House Rules**  
  **Definition:** Policies and regulations of the hotel that guests are required to follow.

- **Housekeeping**  
  **Definition:** The department responsible for cleaning and maintaining the rooms.

- **Inventory Management**  
  **Definition:** The process of overseeing and controlling the hotel's supply of goods and materials, ensuring that adequate stock levels are maintained while minimizing costs and waste.

- **Asset Tracking**  
  **Definition:** The practice of monitoring and managing the hotel's physical assets, such as furniture, equipment, and fixtures, to ensure they are utilized efficiently and maintained properly.

- **Task Management**  
  **Definition:** The organization and tracking of tasks and responsibilities within the hotel, ensuring that deadlines are met and workflows are optimized.

- **Type of Reservation**  
  **Definition:** List of types of reservations.

- **Staff Scheduling**  
  **Definition:** The process of creating and managing work schedules for hotel employees, taking into account factors such as shift rotations, staffing levels, and employee availability.

- **Resource Allocation**  
  **Definition:** The allocation and distribution of resources, such as staff, equipment, and funds, to different areas of the hotel based on operational needs and priorities.

- **Vendor Management**  
  **Definition:** The coordination and oversight of relationships with external suppliers and vendors, including negotiating contracts, monitoring performance, and ensuring timely delivery of goods and services.

- **Quality Control**  
  **Definition:** The process of monitoring and evaluating the quality of products and services offered by the hotel, identifying areas for improvement, and implementing measures to maintain or enhance quality standards.

- **Cost Management**  
  **Definition:** The control and optimization of expenses within the hotel, including labor costs, operating expenses, and capital expenditures, to maximize profitability and efficiency.

- **Data Analytics**  
  **Definition:** The use of data analysis techniques to extract insights and patterns from hotel operations data, enabling informed decision-making and strategic planning.

- **Risk Management**  
  **Definition:** The identification, assessment, and mitigation of risks when resources are limited at any moment.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

## 3.2. User Stories.

## 3.3. Impact Mapping.
## 3.4. Product Backlog.

## Capítulo IV: Solution Software Design

### 4.1. Strategic-Level Domain-Driven Design

#### 4.1.1. EventStorming

##### 4.1.1.1. Candidate Context Discovery

##### 4.1.1.2. Domain Message Flows Modeling

##### 4.1.1.3. Bounded Context Canvases

#### 4.1.2. Context Mapping

#### 4.1.3. Software Architecture

##### 4.1.3.1. Software Architecture System Landscape Diagram

##### 4.1.3.2. Software Architecture Context Level Diagrams

##### 4.1.3.3. Software Architecture Container Level Diagrams

##### 4.1.3.4. Software Architecture Deployment Diagrams

### 4.2. Tactical-Level Domain-Driven Design

#### 4.2.1. Bounded Context: <Bounded Context Name>

##### 4.2.1.1. Domain Layer

##### 4.2.1.2. Interface Layer

##### 4.2.1.3. Application Layer

##### 4.2.1.4. Infrastructure Layer

##### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.1.7. Bounded Context Domain Layer Class Diagrams

##### 4.2.1.8. Bounded Context Database Design Diagram

#### 4.2.2. Bounded Context: <Bounded Context Name>

##### 4.2.2.1. Domain Layer

##### 4.2.2.2. Interface Layer

##### 4.2.2.3. Application Layer

##### 4.2.2.4. Infrastructure Layer

##### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.2.7. Bounded Context Domain Layer Class Diagrams

##### 4.2.2.8. Bounded Context Database Design Diagram

#### 4.2.3. Bounded Context: <Bounded Context Name>

##### 4.2.3.1. Domain Layer

##### 4.2.3.2. Interface Layer

##### 4.2.3.3. Application Layer

##### 4.2.3.4. Infrastructure Layer

##### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.3.7. Bounded Context Domain Layer Class Diagrams

##### 4.2.3.8. Bounded Context Database Design Diagram

#### 4.2.4. Bounded Context: <Bounded Context Name>

##### 4.2.4.1. Domain Layer

##### 4.2.4.2. Interface Layer

##### 4.2.4.3. Application Layer

##### 4.2.4.4. Infrastructure Layer

##### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.4.7. Bounded Context Domain Layer Class Diagrams

##### 4.2.4.8. Bounded Context Database Design Diagram

#### 4.2.5. Bounded Context: <Bounded Context Name>

##### 4.2.5.1. Domain Layer

##### 4.2.5.2. Interface Layer

##### 4.2.5.3. Application Layer

##### 4.2.5.4. Infrastructure Layer

##### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams

##### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.5.7. Bounded Context Domain Layer Class Diagrams

##### 4.2.5.8. Bounded Context Database Design Diagram