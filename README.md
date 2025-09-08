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

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Solution Software Design](#capítulo-iv-product-design)

  - [4.1. Strategic-Level Domain-Driven Design](#41-Strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
      - [4.1.1.1. Candidate Context Discovery](#4111-lean-ux-canvas)
      - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture Context Level Diagrams](#4131-software-architecture-context-level-diagrams)
      - [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
      - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
  
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.X. Bounded Context: <Bounded Context Name>](#42x-bounded-context-bounded-context-name)
      - [4.2.X.1. Domain Layer](#42x1-domain-layer)
      - [4.2.X.2. Interface Layer](#42x2-interface-layer)
      - [4.2.X.3. Application Layer](#42x3-application-layer)
      - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
      - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](#42x5-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](#42x6-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams](#42x61-bounded-context-domain-layer-class-diagrams)
        - [4.2.X.6.2. Bounded Context Database Design Diagram](#42x62-bounded-context-database-design-diagram)




 
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

El propóstivo de InnoBridge es ser el puente entre el mundo académico y el empresarial en el Perú.

En el cual, por un lado, los estudiantes y profesores universitarios, quienes podrán subir proyectos, investigaciones, tesis o ideas innovadoras. Además, podrán explorar retos reales publicados por empresas y organizaciones, con la posibilidad de trabajar y mostrar su talento en un entorno competitivo y profesional.

Por otro lado, las empresas, ingenieros, administradores, técnicos y médicos, quienes podrán publicar problemas o necesidades que enfrenta su sector. De esta manera podrán tener acceso a un ecosistema de propuestas frescas e innovadoras de estudiantes y docentes, con lo que podrán evaluar un financiamiento o contratar soluciones concretas.

Y ante esta problemática nos surge la siguiente pregunta: ¿Cómo podríamos hacer que las personas universitarias puedan tener un ámbito laboral y estable, sin importar en el sector en el que estén?

- Domain: Personas con una visión laboral en base a la Universidad en la que se encuentran.
- Customer Segments: Estudiantes y profesores de una Universidad, que quieren dar el salto del estudio al centro laboral.
- Pain Points: Falta de personal joven que quieran tener un futuro en el ámbito laboral, falta de atención en el mundo laboral y bajos recursos para contratar profesionales de buen desempeño individual.
- Gap: No existe una solución en el mercado que se dedique al conocimiento y a la conexión entre personas universitarias y el ámbito laboral. Así como también, las empresas requieren de personal joven para mantener una estabilidad económica aceptable.
- Vision/Strategy: Crear una plataforma accesible cuyos estudiantes y profesores de una Universidad, puedan darse a conocer mediante sus trabajos, tesis, asignaciones y que tengan oportunidad en el mundo laboral, obteniendo múltiples propuestas.
- Initial Segment: Estudiantes y profesores universitarios que buscan dar el paso entre la Universidad y el centro laboral, también, contar con empresas de peso, para la contratación de nuevo personal.

##### 1.2.2.2. Lean UX Assumptions

##### Business Assumptions<br/><br/>
1. **Creo en que nuestros usuarios, ya sean estudiantes o profesores universitarios, puedan dar el gran paso desde la Universidad a un centro laboral.

2. **Estas necesidades se pueden satisfacer una plataforma web que conecte a estudiantes y profesores lanzando sus materiales importantes a personas que quieran sobresalir.

3. **Nuestros clientes iniciales serán estudiantes y profesores universitarios, de carreras al azar, que buscan un trabajo en cualquier empresa.

4. **El valor más importante que un cliente quiere de nuestros servicios es poder conseguir trabajos y publicar sus logros y materiales anteriores para poder tener un historial llamativo.

5. **El cliente también va a obtener flexibilidad de horarios, ingresos adicionales, desarrollo de habilidades blandas y validación en su perfil.

6. **Se va a obtener a la gran mayoría de clientes mediante las redes sociales (Facebook, X, Instagram, TikTok), alianzas con empresas peruanas e internacionales y campañas digitales en varios foros universitarios.

7. **Se van a obtener ingresos mediante comisiones por publicación de materiales u obtener una suscripción permium para empresas de mayor jerarquía.

8. **Nuestra competencia en el mercado serán plataformas como Indeed, LinkedIn Jobs, Glassdoor, etc.

9. **Vamos a tener ventaja frente a nuestra competencia debido a que estamos centrados en el mercado nacional e internacional, sin barreras como un título o años de experiencia.

10. **El mayor riesgo del servicio es la baja participación de estudiantes y profesores o la desconfianza de las empresas en contratar a personal sin tener preparación seria.

11. **Lo resolveremos realizando incentivos por primeras contrataciones, sistema de reputación de candidatos, alianzas con universidades y empresas y casos de éxito visible.

12. **Otro riesgo que debemos considerar es que los estudiantes y los profesores no tengan el tiempo, ni la motivación para postularse para otros centros laborales durante su carrera.


##### User Assumptions<br/><br/>
1. <b>¿Quién es el usuario?</b>

Estudiantes y profesores universitarios, con habilidades en los centros laborales, que apuntan a un futuro mejor y además, de contar con un trabajo en una empresa mostrando sus trabajos, tesis y demás.

2. <b>¿Dónde encaja nuestro producto en su vida?</b>

Durante la última etapa universitaria. Permitiendo aplicar conocimientos en proyectos reales, ganar reputación y generar ingresos.

3. <b>¿Qué problemas resuelve nuestro producto?</b>

InnoBridge se centra en resolver problemas como: Validación de trabajos y tesis, obtener oportunidades laborales a nivel nacional e internacional, poca preocupación en los nuevos empleados a las empresas, falta de contratación de plantel por bajos recursos.

4. <b>¿Cuándo y cómo se usa nuestro producto?</b>

En el tiempo libre de los estudiantes y profesores, acceden a la aplicación, crean su perfil, suben sus trabajos, tesis y más, buscan oportunidades mediante esos archivos y se visualizan las empresas de quienes están interesados por contar con dicha persona.

5. <b>¿Qué características son importantes?</b>

- Interfaz sencilla y fácil de aprender.
- Filtro de búsqueda de habilidades.
- Sistema de reputación.
- Mensajes internos.
- Perfil con insignias.

6. <b>¿Cómo debería lucir y comportarse el producto?</b>

Debe ser moderno, amigable, accesible, con diseño responsivo, colores neutros y una experiencia clara e intuitiva que no distraiga ni complique al usuario.

##### Feature Assumptions<br/><br/>
- **Creemos que** la aplicación debe contar una interfaz de usuario clara, responsiva y fácil de navegar que permitirá a estudiantes y empleadores a utilizar la plataforma sin necesidad de capacitación previa ni conocimientos técnicos avanzados.

- **Creemos que** la plataforma debe proporcionar notificaciones automáticas y personalizables que mantendrán informados a los usuarios sobre contrataciones recibidas, nuevas oportunidades, mensajes o estados de contratación.

- **Creemos que** la aplicación debe contar con un sistema de reputación y validación de desempeño, que permitirá a los clientes calificar los trabajos, las tesis tanto de otros estudiantes y profesores, para así, construir un historial profesional verificable.

- **Creemos que** la aplicación debe ofrecer una sección de perfil personal con un historial digital, donde los estudiantes puedan mostrar trabajos y tesis previas, habilidades destacadas y contar con una base preparada dentro y fuera de la plataforma.

- Creemos que la aplicación debe permitir la publicación rápida y sencilla de proyectos por parte de las empresas o clientes, incluendo la posibilidad de establecer plazos, presupuestos y requerimientos específicos.
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







