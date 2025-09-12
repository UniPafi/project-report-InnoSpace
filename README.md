<h1 align="center">Informe de Trabajo Final</h1>

<p align="center">
  <img src="images/logoupc.png" alt="UPC logo" width="150">
</p>

**Universidad Peruana de Ciencias Aplicadas**

**Ingeniería de Software**

**6to Ciclo**

**Código del curso:** 1ACC0238

**Nombre del curso:** Aplicaciones para Dispositvos Móviles

**NRC:** 1795

**Nombre del profesor:** Jorge Luis Mayta Guillermo

**Nombre del Startup:** UniPafi

**Nombre del Producto:** InnoSpace

### Relación de Integrantes

| **Código** | **Apellidos y Nombres**             |
| ---------- | ----------------------------------- |
| U20211B293 | Cabrera Buitron, Diego Ivan |
| U202313172 | Coca Lavado, Carlos Andres |
| U20231A500 | Palomino Fiestas, Erick Leonardo    |
| U20231D974 | Rivera Ratachi, Renzo Sebastian     |
| U202310988 | Santur Tello, Andrea Elizabeth     |

**Agosto 2025**

---

---

## Contenido

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)

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
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
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
    - [2.3.5. Ubiquitous Language](#235-ubiquitous-language)
  - [2.4. Requirements Specification](#24-requirements-specification)
    - [2.4.1. User Stories](#241-user-stories)
    - [2.4.2. Impact Mapping](#242-impact-mapping)
    - [2.4.3. Product Backlog](#243-product-backlog)
  - [2.5. Strategic-Level Domain-Driven Design](#25-Strategic-level-domain-driven-design)
    - [2.5.1. EventStorming](#251-eventstorming)
      - [2.5.1.1. Candidate Context Discovery](#2511-lean-ux-canvas)
      - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
      - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)
    - [2.5.2. Context Mapping](#252-context-mapping)
    - [2.5.3. Software Architecture](#253-software-architecture)
      - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
      - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
      - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
  - [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
    - [2.6.X. Bounded Context: <Bounded Context Name>](#26x-bounded-context-bounded-context-name)
      - [2.6.X.1. Domain Layer](#26x1-domain-layer)
      - [2.6.X.2. Interface Layer](#26x2-interface-layer)
      - [2.6.X.3. Application Layer](#26x3-application-layer)
      - [2.6.X.4. Infrastructure Layer](#26x4-infrastructure-layer)
      - [2.6.X.5. Bounded Context Software Architecture Component Level Diagrams](#26x5-bounded-context-software-architecture-component-level-diagrams)
      - [2.6.X.6. Bounded Context Software Architecture Code Level Diagrams](#26x6-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.X.6.1. Bounded Context Domain Layer Class Diagrams](#26x61-bounded-context-domain-layer-class-diagrams)
        - [2.6.X.6.2. Bounded Context Database Design Diagram](#26x62-bounded-context-database-design-diagram)


- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---


## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

Unipafi es una startup tecnológica que busca convertirse en un referente en la vinculación entre el talento joven y el ecosistema empresarial. Nacemos con la convicción de que la innovación no surge únicamente en los laboratorios corporativos, sino también en las aulas, los proyectos académicos y las ideas emergentes de estudiantes con visión de futuro. Desde Unipafi impulsamos un modelo de colaboración que une creatividad, impacto social y desarrollo profesional, construyendo un espacio en el que la innovación y el talento se encuentren para transformar realidades.

**Visión:**

En 4 años, consolidarnos como la startup líder en Latinoamérica en la creación de puentes entre universidades y empresas, reconocidos por fomentar el talento emergente, la innovación colaborativa y el crecimiento sostenible.

**Misión:**

Promover el desarrollo profesional de estudiantes universitarios y recién egresados a través de la creación de espacios donde puedan conectar con organizaciones, demostrar sus capacidades y generar soluciones de alto impacto que aporten al progreso económico y social.

#### 1.1.2. Perfiles de integrantes del equipo

<table border="1">
  <thead>
    <tr>
      <th>Fotos del Integrantes</th>
      <th>Nombres y Apellidos</th>
      <th>Código de estudiante</th>
      <th>Conocimiento técnicos y hablidades </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="images/fotointegrante-erick-palomino.jpeg" alt="foto-erick" width="500"></td>
      <td>Palomino Fiestas, Erick Leonardo</td>
      <td>U20231A500</td>
      <td>Hola, Soy Erick Leonardo Palomino Fiestas, un estudiante entusiasta de quinto ciclo en Ingeniería de Software. Mi conjunto de habilidades técnicas incluye C++, HTML, CSS, fundamentos de JavaScript y experiencia con bases de datos SQL y MongoDB. Me considero una persona responsable, con sólidas habilidades de comunicación para trabajar en equipo y una perspectiva optimista. También tengo un nivel básico de inglés. </td>
    </tr>
      <tr>
      <td><img src="images/fotointegrante-renzo.jpg" alt="foto-renzo" width="500"></td>
      <td>Renzo Sebastian Rivera Ratachi</td>
      <td>U20231D974</td>
      <td>Soy Renzo Sebastian Rivera Ratachi y soy estudiante de la carrera de Ingeniería de Software. Actualmente estoy cursando el 6to ciclo de mi carrera y tengo conocimientos intermedios de HTML, CSS, JavaScript y C++. Me considero una persona responsable y puntual. </td>
    </tr>
    <tr>
      <td><img src="images/foto-cr7.jpg" alt="foto-andres" width="500"></td>
      <td>Carlos Andres Coca Lavado</td>
      <td>U202313172</td>
      <td>Mi Nombre es Carlos Andrés Coca, tengo 19 años, actualmente me encuentro cursando el sexto ciclo de la carrera de Ingeniería de Software. Cuento con conocimientos en C++, Python y HTML. y desde muy joven me ha interesado la ciberseguridad y el desarrollo de Software. Teniendo en cuenta el gran impacto que presentan a día de hoy.  </td>
    </tr>
    <tr>
      <td><img src="images/fotointegrante-giovany.jpeg" alt="foto-giovany" width="500"></td>
      <td>Andrea Elizabeth Santur Tello </td>
      <td>U202310988</td>
      <td>Estoy cursando el sexto ciclo de mi carrera Ingeniería de Software, soy una persona responsable que le gusta resolver desafíos a la par con el trabajo responsable y en equipo tengo la capacidad de líder y me gusta aprender nuevas cosas dia a dia.</td>
    </tr>
    <tr>
      <td><img src="images/fotointegrante-giovany.jpeg" alt="foto-giovany" width="500"></td>
      <td>Diego Ivan Cabrera Buitron </td>
      <td>U20211B293</td>
      <td>Estoy cursando el sexto ciclo de mi carrera Ingeniería de Software, soy una persona responsable que le gusta resolver desafíos a la par con el trabajo responsable y en equipo tengo la capacidad de líder y me gusta aprender nuevas cosas dia a dia.</td>
    </tr>
  </tbody>
</table>


### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática
#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements


##### 1.2.2.2. Lean UX Assumptions

##### Business Assumptions<br/><br/>

##### User Assumptions<br/><br/>
##### Feature Assumptions<br/><br/>
##### 1.2.2.3. Lean UX Hypothesis Statements
##### 1.2.2.4. Lean UX Canvas
### 1.3. Segmentos Objetivo


## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

#### 2.1.1. Análisis competitivo


#### 2.1.2. Estrategias y tácticas frente a competidores

## Afrontando las fortalezas de nuestros competidores:

## Comprendemos que nuestras fortalezas son:




## Estrategias:
-



## Tácticas:
-

#### 2.1.2. Estrategias y tácticas frente a competidores



## Afrontando las debilidades de nuestros competidores:
## Comprendemos que nuestras debilidades son:

## Estrategias:
-

## Tácticas:
-

## Afrontando las oportunidades de nuestros competidores:


## Comprendemos que nuestras oportunidades son:

-

## Estrategias:

- 

## Tácticas:

- 

## Afrontando las amenazas de nuestros competidores:

- 

## Comprendemos que nuestras amenazas son:



## Estrategias:
-


## Tácticas:
-


### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

#### 2.2.2. Registro de entrevistas






