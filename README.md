# report

<div align="center">

<h3>Universidad Peruana de Ciencias Aplicadas</h3>

<img alt="upc-logo" src="assets/upc_logo.png" width="200"/><br>

<strong>Ingeniería de Software - 2026-1</strong><br>
<strong>1ACC0238 - Aplicaciones para Dispositivos Móviles</strong><br>
<strong>NRC: 3248</strong><br>
<strong>Profesor: David Gerardo Quevedo Velasco</strong><br>

<br><strong>Informe del Trabajo Final</strong><br><br>

<strong>Startup: HuariqueHub</strong><br>
<strong>Producto: PuntoSabor</strong><br>



### Team Members:

|             Member              |   Code    |
|:-------------------------------:|:---------:|
|  Delgado Carrasco, Schneider  | u202321843 |
|  Lopez Goitia, Carlos Alberto  | u202312700 |
|  Tumi Oliden Manuel Ignacio  | u20241c134 |
|  Becerra Llempen, Fabiola Dayane |u20171a518|
|  Vasquez Goicochea Erick Alessander | u202019871 |

<strong> Abril 2026</strong><br>
</div>

# Registro de Versiones del Informe

<table>
  <tr>
    <th>Version</th>
    <th>Fecha</th>
    <th>Autor</th>
    <th>Descripción de modificación </th>
  </tr>
  <tr>
    <td>AV1</td>
    <td>2026-04-20</td>
    <td>
      <ul> 
        <li>Delgado Carrasco, Schneider</li> 
        <li>Lopez Goitia, Carlos Alberto</li> 
        <li>Tumi Oliden Manuel Ignacio</li>
        <li>Becerra Llempen Fabiola Dayane </li>
        <li>Vasquez Goicochea, Erick Alessander</li>
        <li> </li>
      </ul>
    </td>
    <td> Se han incluído los siguientes capítulos:
        <ul>
          <li>Carátula</li>
          <li>Registro de Versiones del informe</li>
          <li>Project Report Collaboration Insights</li>
          <li>Contenido</li>
          <li>Student Outcome</li>
          <li>Capítulo I: Presentación</li>
        <li>Capítulo II: Requirements Development and Sotware Solution Design</li>
        <li>Conclusiones</li>
        <li>Bibliografía</li>
        <li>Anexos</li>
        </ul></td>
  </tr>
</table>

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
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
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
        - [5.2.2. Sprint 2](#522-sprint-2)
            - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
            - [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
            - [5.2.2.3. Sprint Backlog 2](#5223-sprint-backlog-2)
            - [5.2.2.4. Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
            - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
            - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
            - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
            - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
        - [5.2.3. Sprint 3](#523-sprint-3)
            - [5.2.3.1. Sprint Planning 3](#5231-sprint-planning-3)
            - [5.2.3.2. Aspect Leaders and Collaborators](#5232-aspect-leaders-and-collaborators)
            - [5.2.3.3. Sprint Backlog 3](#5233-sprint-backlog-3)
            - [5.2.3.4. Development Evidence for Sprint Review](#5234-development-evidence-for-sprint-review)
            - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
            - [5.2.3.6. Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
            - [5.2.3.7. Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
            - [5.2.3.8. Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
        - [5.2.4. Sprint 4](#524-sprint-4)
            - [5.2.4.1. Sprint Planning 4](#5241-sprint-planning-4)
            - [5.2.4.2. Aspect Leaders and Collaborators](#5242-aspect-leaders-and-collaborators)
            - [5.2.4.3. Sprint Backlog 4](#5243-sprint-backlog-4)
            - [5.2.4.4. Development Evidence for Sprint Review](#5244-development-evidence-for-sprint-review)
            - [5.2.4.5. Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)
            - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)
            - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
            - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)


    - [5.3. Validation Interviews](#53-validation-interviews)
        - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
        - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
        - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)

    - [5.4. Video About-the-Product](#54-video-about-the-product)


---

## Student Outcome

ABET – EAC - Student Outcome 5 Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.
<div>
<table>
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Nombre</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <!-- Criterio 1 -->
    <tr>
      <td rowspan="5">Trabaja en equipo para proporcionar liderazgo en forma conjunta</td>
      <td>Delgado Carrasco, Schneider</td>
      <td>
        <strong> AV1:</strong><br>
        Identifiqué con claridad la problemática central de nuestra startup, definí los segmentos a los que está dirigida y realicé la investigación necesaria para establecer los requisitos de la aplicación web. Además, llevé a cabo una entrevista con un usuario representativo del público objetivo.
        <br>
      </td>
      <td rowspan="5">El equipo se comunicó de forma clara y estructurada, aportando conjuntamente al análisis técnico y estratégico del proyecto.</td>
    </tr>
    <tr>
      <td>Lopez Goitia, Carlos Alberto</td>
      <td>
        <strong> AV1:</strong><br>
        Realicé entrevistas para la extracción de requisitos críticos y definí la arquitectura del sistema bajo el enfoque de Domain-Driven Design (DDD), documentando la estructura mediante diagramas de contexto, contenedores y componentes.<br>
      </td>
    </tr>
    <tr>
      <td>Tumi Oliden, Manuel Ignacio</td>
      <td>
        <strong> AV1:</strong><br>
        Durante esta etapa redacté el análisis de antecedentes y problemática mediante las 5W's y 2H's, identificando los principales grupos afectados: propietarios de huariques y usuarios que buscan gastronomía local auténtica. Asimismo,  desarrollé los Lean UX Problem Statements, las Business y User Assumptions, y los Lean UX Hypothesis Statements con sus respectivos criterios de validación, estableciendo así las bases para la dirección estratégica del producto.<br>
        <br>
      </td>
    </tr>
    <tr>
      <td>Becerra Llempen, Fabiola Dayane</td>
      <td>
        <strong> AV1:</strong><br>
        Durante este trabajo realice los análisis competitivos de mercado para obtener las ventajas y encontrar oportunidades de mejora para nuestro proyecto. Asimismo, desarrolle los perfiles del user persona , user task matrix y el journey mapping con sus respectivas conclusiones. <br>
        <br>
      </td>
    </tr>
    <tr>
  <td>Vasquez Goicochea Erick Alessander</td>
  <td>
    <strong> AV1:</strong><br>
    Apoyé en la revisión del contenido del capítulo 2, mejorando la redacción para que sea más clara y entendible. Además, reforcé el análisis en las secciones de competidores y entrevistas para que reflejen mejor las necesidades de los usuarios.<br>
  </td>
</tr>
    <tr>
    </tr>
    <!-- Criterio 2 -->
    <tr>
      <td rowspan="6">Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos</td>
      <td>Delgado Carrasco, Schneider</td>
      <td>
        <strong> AV1:</strong><br>
        Como parte de las user stories, apoye en el desarrollo, su contexto y antecedentes; tambien realice algunos puntos del lean UX; realicé un análisis competitivo y definí los segmentos del público objetivo respaldados con datos estadísticos.<br>
      </td>
      <td rowspan="6">La comunicación escrita se realizó con claridad, ajustando el contenido según las necesidades tanto de públicos técnicos como de lectores no especializados.</td>
    </tr>
    <tr>
      <td>Lopez Goitia, Carlos Alberto</td>
      <td>
        <strong> AV1:</strong><br>
        Diseñé instrumentos de entrevista estructurados para validar las decisiones arquitectónicas y propuse soluciones técnicas fundamentadas en una investigación previa, asegurando que el proyecto mantuviera un enfoque sólido y justificado.<br>
        <br>
      </td>
    </tr>
    <tr>
      <td>Tumi Oliden Manuel Ignacio</td>
      <td>
        <strong> AV1:</strong><br>
        Me encargué de redactar las secciones de antecedentes, problemática y supuestos del proyecto, adaptando el lenguaje según el destinatario: un enfoque analítico para la documentación técnica del equipo y un enfoque estratégico para los Lean UX Statements e Hypothesis, asegurando que el contenido fuera claro y coherente para todos los involucrados.<br>
        <br>
      </td>
    </tr>
    <tr>
      <td> Becerra Llempen, Fabiola Dayane </td>
      <td>
        <strong> AV1:</strong><br>
        Realice entrevistas y análisis de entrevistas para poder obtener fundamentos en la investigación. Tambien, realice un enfoque estratégico con el empathy Mapping y As-is Scenario Mapping de los segmentos obtenidos junto con el Big Picture Event Storming y Ubiquitous Language.<br>
      </td>
    </tr>
  <tr>
    <td>Vasquez Goicochea Erick Alessander</td>
    <td>
      <strong> AV1:</strong><br>
      Colaboré con el equipo revisando y mejorando la claridad del documento, asegurando que el contenido sea comprensible tanto para lectores técnicos como no técnicos. También apoyé en la organización de la información del capítulo 2 para mantener coherencia en el análisis.<br>
    </td>
  </tr>
    <tr>

  </tbody>
</table>
</div>             


# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

HuariqueHub es una startup dedicada a la creación de soluciones tecnológicas diseñadas para impulsar la competitividad y el crecimiento de pequeños comercios locales, con un énfasis particular en el rubro gastronómico. Su propuesta central, PuntoSabor, consiste en una plataforma web que vincula a los comensales con "huariques", establecimientos de cocina tradicional que destacan por su autenticidad y calidad, pero que suelen carecer de exposición en el entorno digital.

El proyecto surge para resolver la brecha de visibilidad que enfrentan estos negocios frente a las grandes cadenas en las aplicaciones convencionales. 

Mediante una interfaz intuitiva, la herramienta permite a la comunidad descubrir y recomendar estos locales, validando un modelo de negocio sostenible basado en planes de visibilidad y membresías que fortalecen el ecosistema emprendedor local.
    
### 1.1.2. Perfiles de integrantes del equipo

|                             Miembro                             |                                                                                                                                                                                   .
|:---------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| ![alt text](<assets/Perfil_Manuel.jpg>) || 
|![alt text](<assets/Perfil_Delgado.jpg>)                                                                 || 
| ![alt text](<assets/Perfil_Lopez.jpg>)                                                                || 
| ![alt text](<assets/Perfil_Becerra.jpg>)                                                                || 
| ![alt text](<assets/Perfil_Erick.jpg>)                                                                 ||

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

#### Las 5W's y 2H's

#### What? (¿Qué?)
El problema central radica en que los huariques, negocios gastronómicos pequeños y poco conocidos que ofrecen comida tradicional, tienen una presencia casi nula en el entorno digital, lo que impide que los consumidores puedan acceder fácilmente a alternativas de comida auténtica y a precios razonables más allá de los restaurantes con mayor popularidad.

#### Why? (¿Por qué?)
Los grandes establecimientos y cadenas dominan las plataformas de comida digitales gracias a su mayor capacidad de inversión y volumen de operaciones, desplazando a los huariques que no disponen de los recursos para competir en ese terreno. Esto crea un vacío importante: los usuarios no logran encontrar estos lugares con facilidad, y los huariques pierden potenciales oportunidades de crecimiento.

#### Where? (¿Dónde?)
El fenómeno ocurre principalmente en zonas urbanas y comunidades donde los huariques tienen presencia física, pero carecen de representación digital. Se hace especialmente evidente en mercados hispanohablantes, donde la gastronomía local es culturalmente rica, pero aún escasamente digitalizada.

#### When? (Cuándo?)
Se trata de una problemática persistente, cuya gravedad ha aumentado con la acelerada transformación digital del mercado gastronómico en los últimos años.

#### Who? (¿Quién?)
Existen dos grupos directamente perjudicados:

1. Los propietarios de huariques, quienes enfrentan dificultades para captar clientes y sostenerse frente a la competencia de restaurantes y cadenas con mayor presencia en medios digitales.

2. Los usuarios que buscan experiencias gastronómicas locales, económicas y genuinas, pero no cuentan con herramientas digitales adecuadas para encontrarlas.

#### How? (¿Cómo?)
El problema se expresa en la escasa o inexistente promoción digital de estos negocios, su ausencia en aplicaciones y mapas de referencia, la poca interacción con posibles clientes y la carencia de una comunidad que los recomiende y divulgue.

#### How much? (¿Cuánto?)
Esta brecha representa no solo una oportunidad económica sin aprovechar para los dueños de huariques, sino también una pérdida del patrimonio gastronómico cultural. A escala de mercado, miles de negocios pequeños y millones de usuarios permanecen al margen del ecosistema digital gastronómico.

##### 1.2.2.1. Lean UX Problem Statements

- Los huariques no cuentan con una plataforma digital especializada y de fácil acceso donde puedan promover su negocio, lo que restringe su capacidad para crecer y captar nuevos clientes.

- Quienes desean descubrir gastronomía local, auténtica y accesible económicamente tienen pocas opciones digitales orientadas a ese fin, ya que los huariques casi no aparecen en las aplicaciones convencionales.

- La inexistencia de un sistema de reseñas y valoraciones enfocado en huariques dificulta generar confianza y construir una comunidad sólida entre usuarios y propietarios de estos negocios.

- Las aplicaciones gastronómicas más populares favorecen a los grandes restaurantes y cadenas, dejando a los huariques sin visibilidad ni alcance en el mercado digital.

- Los propietarios de huariques, que habitualmente trabajan con recursos escasos, necesitan una herramienta práctica que les permita gestionar su presencia en línea sin complicaciones técnicas ni inversiones elevadas.

##### 1.2.2.2. Lean UX Assumptions
#### Business Assumptions
- Se estima que PuntoSabor logrará convocar a un número considerable de dueños de huariques que buscan mayor visibilidad digital a través de membresías o planes publicitarios.

- Se prevé que la implementación de planes de membresía o publicidad genere ingresos recurrentes y estables para la startup.

- Se considera que el mercado gastronómico local está preparado para adoptar soluciones digitales accesibles que impulsen a los pequeños negocios y mejoren la experiencia de descubrimiento para los usuarios.

- Se parte del supuesto de que una comunidad activa de usuarios y propietarios de huariques favorecerá el crecimiento orgánico y la fidelización dentro de la plataforma.

#### User Assumptions
- Se estima que los usuarios priorizan hallar opciones de comida local genuina, económica y diferente a las que ofrecen las grandes aplicaciones.

- Se espera que los usuarios no solo exploren huariques a través de la app, sino que también contribuyan con calificaciones y reseñas que orienten a otros.

- Se considera que una interfaz sencilla, combinada con acceso a fotografías, especialidades del lugar, rangos de precios y mapas integrados, motivará un uso frecuente de la plataforma.

- Se supone que funciones como guardar favoritos y consultar rankings impulsarán a los usuarios a volver y recomendar PuntoSabor en su entorno cercano.

- Se asume que los propietarios o administradores de huariques valorarán y encontrarán sencillo el proceso de registrar y gestionar su negocio dentro de la app, con miras a aumentar su visibilidad.

- Se espera que estos usuarios proporcionen información completa y actualizada —fotos, especialidades, precios— para enriquecer la experiencia de quienes los visiten.

- Se estima que beneficios como la membresía y la dinámica comunitaria fomentarán que los propietarios mantengan su perfil activo y atractivo.

##### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que ofrecer una plataforma fácil e intuitiva para descubrir huariques auténticos y económicos aumentará la cantidad de usuarios que visitan estos negocios. Sabremos que esto es cierto cuando al menos el 60% de los usuarios activos reporten haber visitado un huarique recomendado en la plataforma durante el primer mes de uso.

- Creemos que permitir a los dueños de huariques registrar y gestionar su negocio con fotos, especialidades y precios incentivará su participación activa y mejorará la calidad del contenido disponible. Sabremos que esto es cierto cuando al menos el 50% de los huariques registrados actualicen su información o respondan a reseñas dentro de los primeros tres meses tras su registro.

- Creemos que la integración de mapas y funciones de geolocalización facilitará a los usuarios encontrar huariques cercanos, aumentando la interacción y el uso recurrente de la app. Sabremos que esto es cierto cuando al menos el 70% de las búsquedas y accesos diarios incluyan el uso del mapa durante el primer mes de lanzamiento.

- Creemos que un sistema confiable de reseñas y calificaciones incentivará la confianza en los usuarios y motivará a más personas a utilizar PuntoSabor como su app de referencia para descubrir huariques. Sabremos que esto es cierto cuando el 80% de los huariques tengan al menos cinco reseñas activas y una valoración promedio superior a 4 estrellas en los primeros tres meses.

- Creemos que la oferta de planes de membresía y publicidad atraerá a suficientes dueños de huariques para generar ingresos recurrentes sostenibles. Sabremos que esto es cierto cuando el 30% de los huariques registrados contraten al menos un plan pago durante los primeros seis meses.

##### 1.2.2.4. Lean UX Canvas
![alt text](<assets/Lean UX Canvas - PuntoSabor.png>)

## 1.3. Segmentos objetivo
##Exploradores Gastronómicos

- Edad: 18 a 40 años.

- Estilo de vida: Activos, curiosos, buscan descubrir comida auténtica y económica.

- Uso de tecnología: Frecuente, usuarios habituales de apps móviles y web para buscar lugares para comer.

- Necesidad principal: Encontrar huariques poco conocidos con buena sazón y precios accesibles.

- Beneficios buscados: Acceso a recomendaciones confiables, mapas con ubicación cercana, y sistema de reseñas para tomar decisiones informadas.

##Dueños y Administradores de Huariques

- Perfil: Emprendedores y pequeños negocios de comida tradicional o casera.

- Necesidad principal: Promocionar su negocio, aumentar la visibilidad y atraer nuevos clientes de manera sencilla, accesible y rentable.

- Beneficios buscados: Herramienta accesible para gestionar su información en la plataforma, recibir retroalimentación valiosa y utilizar planes de membresía o publicidad para crecer.


# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo

En el mercado contemporáneo, hay numerosas plataformas y aplicaciones alimentarias que posibilitan a los usuarios buscar sitios y restaurantes para comer, como Google Maps, Uber Eats, Yelp o Rappi. Estas aplicaciones, no obstante, dan preferencia a
restaurantes establecidos y cadenas, lo que da escaso lugar a huariques o negocios locales de gastronomía menos conocidos.

![alt text](assets/AnalisisCompetitivo_PuntoSabor.png)
![alt text](assets/FODA_PuntoSabor.png)

PuntoSabor se distingue por su enfoque exclusivo en huariques, brindando un lugar especializado para pequeños establecimientos de comida tradicional que normalmente no son resaltados en otras plataformas. Asimismo, incluye funciones concretas como la administración directa de huariques por sus propietarios, un sistema de reseñas y evaluaciones enfocado en estos establecimientos y un modelo de membresía para aumentar la visibilidad.

### 2.1.2. Estrategias y tácticas frente a competidores.  

Con el objetivo de distinguir a PuntoSabor de las plataformas generales más grandes y establecerse con éxito en el sector de los huariques, se proponen las siguientes tácticas y estrategias:

Estrategias:
- Dirigir la plataforma únicamente hacia pequeñas empresas de comida local que sean poco reconocidas, lo que posibilitará brindar una experiencia genuina y única que los competidores masivos no logran satisfacer de manera adecuada.

- Promover la implicación activa de los propietarios y usuarios, a través de reseñas, sugerencias y la producción de contenido genuino que genere un sentimiento de confianza y pertenencia.

- Crear un modelo de ingresos que se base en membresías y publicidad y que esté al alcance de los propietarios de huariques, logrando un balance entre la monetización y el crecimiento orgánico de la plataforma.

Tácticas: 

- Con el fin de atraer a los usuarios y propietarios que estén interesados, emplear publicidad en buscadores y redes sociales dirigida a áreas urbanas concretas donde se encuentran huariques..

- Trabajar en conjunto con ferias, eventos y organizaciones gastronómicas con el fin de impulsar la aplicación y añadir huariques significativos a la plataforma.

- Asegurar que la aplicación web sea accesible, rápida y fácil de usar, incorporando un sistema simple para añadir y actualizar huariques, una interfaz amigable para el usuario y funcionalidades intuitivas de mapas.

- Fomentar el uso y la lealtad a través de incentivos como reconocimientos, descuentos o beneficios para quienes participen activamente (reseñas, renovación del perfil, membresía).

- Para mejorar de manera continua la plataforma, se debe establecer un sistema que analice y responda rápidamente a las sugerencias y problemas que los usuarios reporten.

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

Segmento 1: Exploradores Gastronómicos (Usuarios de la app web)

Objetivo: Entender sus motivaciones, comportamientos y expectativas al usar una app web para descubrir comida local auténtica.

Preguntas Segmento 1:
- ¿Con qué frecuencia usas aplicaciones web para buscar lugares para comer fuera de lo común?
- ¿Cómo sueles descubrir huariques o lugares de comida poco conocidos en la web?
- ¿Qué aspectos valoras más al elegir un lugar para comer usando una app web (precio, ubicación, reseñas, fotos, etc.)?
- ¿Qué dificultades has tenido al usar apps web para buscar lugares de comida local?
- ¿Qué te motivaría a usar una app web dedicada exclusivamente a huariques?
- ¿Qué funcionalidades en la app web considerarías imprescindibles para usarla con regularidad?
- ¿Qué preocupaciones o barreras tendrías al usar una app web para descubrir huariques?

Segmento 2: Dueños y Administradores de Huariques (Usuarios que usan la app web para gestionar su huarique).

Objetivo: Entender lo que necesita y espera al utilizar la aplicación web para gestionar y publicitar sus huariques.

Preguntas Segmento 2:
- ¿Actualmente usas alguna plataforma web o digital para promocionar tu huarique? ¿Cuál?
- ¿Qué retos has enfrentado al tratar de gestionar tu negocio a través de plataformas digitales?
- ¿Qué tan cómodo te sientes usando aplicaciones web para actualizar la información de tu negocio?
- ¿Qué características te harían decidirte a usar una app web especializada para huariques?
- ¿Qué tipo de soporte o facilidades esperarías al usar esta app web para gestionar tu perfil o negocio?
- ¿Qué modelo de tarifas o membresías considerarías justo para usar esta plataforma?
- ¿Qué resultados te gustaría ver después de usar esta aplicación web para promocionar tu huarique?

### 2.2.2. Registro de entrevistas
### Segmento #1: Exploradores Gastronómicos (Usuarios de la app web)
| Número de entrevista | Datos del entrevistado                                                                 | Evidencia de entrevista |
|-----------------------|-----------------------------------------------------------------------------------------|--------------------------|
| 1                     | **Nombre:**  Vitaly Baca  <br> **Edad:** 20  <br> **Distrito:** Lurin <br><br> **Resumen:** Vitaly Baca, un estudiante de 20 años que está estudiando Ingeniería de Software en la UPC, emplea estas aplicaciones durante casi todos los fines de semana, ya que le gusta salir a conocer lugares nuevos con su pareja o amigos. Encuentra la mayoría de los huariques en Instagram y TikTok siguiendo a foodies, además de buscar en Google Maps. Lo que primero aprecia es el precio, puesto que como estudiante posee un presupuesto limitado, y después las fotos y los comentarios de confianza para no terminar en un lugar inapropiado. Señala entre los obstáculos que ha tenido que afrontar que, a veces, llega a lugares que parecen abiertos pero están cerrados, y también que muchas huariques pequeñas no aparecen en las aplicaciones. Siempre que contenga críticas honestas de usuarios semejantes a él, se sentiría motivado para utilizar una aplicación exclusiva de huariques. Considera esenciales recomendaciones personalizadas, filtros según tipo de comida y precio, así como un mapa rápido e intuitivo. Sus inquietudes más importantes serían que la aplicación esté saturada de anuncios, contenga información poco confiable o incluya escasos sitios en su ciudad, lo que haría que pierda su valor. | ![Evidencia](assets/Entrevista1_Segmento1.jpeg) <br> [📂 Ver entrevista](https://drive.google.com/file/d/1NSQkOkLNAq3A-IIhc4_lm2q3UwWDaylk/view?usp=sharing) 00:00 - 05:37|


| Número de entrevista | Datos del entrevistado                                                                 | Evidencia de entrevista |
|-----------------------|-----------------------------------------------------------------------------------------|--------------------------|
| 2                     | **Nombre:** Sebastian del Rio  <br> **Edad:** 20  <br> **Distrito:** Chorrillos <br><br> **Resumen:** Sebastián del Río, un estudiante de 20 años que estudia Ingeniería de Software en la UTP, no tiene el hábito de emplear con regularidad aplicaciones web para encontrar huariques; lo hace solamente una o dos veces al mes cuando desea salir con sus amigos o experimentar algo diferente. Con frecuencia, encuentra la mayoría de los lugares a través de Google Maps, pero principalmente por sugerencias en Instagram y TikTok. Para él, lo fundamental al seleccionar un lugar es la proximidad, el precio y las imágenes y comentarios auténticos de otros clientes. Indica como mayor obstáculo el hecho de que los huariques no suelen aparecer en las aplicaciones, y que son más frecuentes los restaurantes conocidos. También menciona que la información está frecuentemente incompleta o carece de buenas imágenes. Lo incentivaría a utilizar una aplicación que sea simple y que muestre sitios verdaderos y seguros. Ten en cuenta elementos indispensables como fotografías auténticas, reseñas sinceras, un mapa con la ubicación, filtros de precio y la posibilidad de guardar favoritos. Lo que más le inquietaría es que la información no fuera confiable, que la aplicación lo dirija a lugares cerrados o de baja calidad, o que sea lenta y compleja. | ![Evidencia](assets/Entrevista2_Segmento1.jpeg) <br> [📂 Ver entrevista](https://drive.google.com/file/d/1NSQkOkLNAq3A-IIhc4_lm2q3UwWDaylk/view?usp=sharing) 05:37 - 09:56|


| Número de entrevista | Datos del entrevistado                                                                 | Evidencia de entrevista |
|-----------------------|-----------------------------------------------------------------------------------------|--------------------------|
| 3                     | **Nombre:** Luis Fernandez  <br> **Edad:** 20  <br> **Distrito:** Pueblo Libre <br><br> **Resumen:** Luis Fernández, un estudiante de 20 años que se encuentra cursando la carrera de Ingeniería de Sistemas en la UTP, explora sitios nuevos cada semana, especialmente los fines de semana cuando está con su pareja. Se orienta por cuentas de amantes de la comida en Instagram y TikTok, guarda videos para ver más tarde y revisa críticas en Google Maps o grupos de Facebook. Para él, el precio es crucial, pero también le da importancia a la experiencia total: comentarios sobre la calidad de los alimentos y el servicio, así como imágenes de los platos. Ha enfrentado dificultades con horarios obsoletos en aplicaciones, al llegar a sitios que estaban cerrados y con la escasa visibilidad de huariques menos famosos. Lo motivaría una aplicación fiable que se centre en huariques y tenga opiniones de personas del lugar. Un mapa interactivo, sugerencias personalizadas y filtros por tipo de comida, ubicación y costo son elementos que consideras esenciales. Sus inquietudes son que la aplicación tenga demasiada publicidad, información falsa o que no ofrezca suficientes alternativas locales. | ![Evidencia](assets/Entrevista3_Segmento1.jpeg) <br> [📂 Ver entrevista](https://drive.google.com/file/d/1P5WpXLAtHH9lsgnF7tXXyMJiK7xsN05h/view?usp=sharing) 09:56 - 13:01|

### Segmento #2: Dueños y Administradores de Huariques (Usuarios que usan la app web para gestionar su huarique)
| Número de entrevista | Datos del entrevistado                                                                 | Evidencia de entrevista |
|-----------------------|-----------------------------------------------------------------------------------------|--------------------------|
| 1                     | **Nombre:** Wildor Villalobos  <br> **Edad:** 28  <br> **Distrito:** Santiago de Surco <br><br> **Resumen:** Dueño de un establecimiento que vende pan con chicharrón. Utiliza Instagram y TikTok (principalmente IG Reels); las publicaciones son útiles para promociones, pero los reels generan más movimiento. Obstáculos: competencia y algoritmo, es necesario pagar para llegar a más personas. Desea que la aplicación le deje destacar su negocio y observar métricas claras (cuántas personas lo encuentran, qué tan eficaz es para atraer clientes), a través de gráficos directos y un panel sencillo. Estaría dispuesto a pagar S/ 20–50/mes si rinde igual o mejor que IG/TikTok. Objetivo: aumentar ventas. | ![Evidencia](assets/Entrevista_Wildor.jpg) <br> [📂 Ver entrevista](https://drive.google.com/file/d/1P5WpXLAtHH9lsgnF7tXXyMJiK7xsN05h/view?usp=sharing) 00:00 - 03:15|


| Número de entrevista | Datos del entrevistado                                                                 | Evidencia de entrevista |
|-----------------------|-----------------------------------------------------------------------------------------|--------------------------|
| 2                     | **Nombre:** Piero Tapia  <br> **Edad:** 26  <br> **Distrito:** Jesús María <br><br> **Resumen:** Dueño de un establecimiento de venta de sándwiches. Hoy en día, la falta de presupuesto y experiencia limitada en redes y pagos en línea hacen que dependa de la afluencia local; no le parece intuitiva la afiliación a aplicaciones. Es importante que la aplicación sea sencilla de aprender y utilizar, así como que tenga comisiones bajas (que no encarezcan sus productos). Solicita orientación y soporte para aprender a utilizar la herramienta y optimizar el negocio, además de visibilidad. Sugiere planes de forma escalonada (principiante, intermedio y avanzado). Éxito esperado: un mayor número de personas que consuman en el local (no solo lo visiten). | ![Evidencia](assets/Entrevista_Piero.jpg) <br> [📂 Ver entrevista](https://drive.google.com/file/d/1P5WpXLAtHH9lsgnF7tXXyMJiK7xsN05h/view?usp=sharing) 03:15 - 08:14|


| Número de entrevista | Datos del entrevistado                                                                 | Evidencia de entrevista |
|-----------------------|-----------------------------------------------------------------------------------------|--------------------------|
| 3                     | **Nombre:** Gabriela Vasquez  <br> **Edad:** 23  <br> **Distrito:** Pueblo libre <br><br> **Resumen:** Dueña de un establecimiento de jugos artesanales. Hasta el momento, está principalmente condicionado por los clientes que pasan por la zona, debido a que su presupuesto es reducido y no tiene mucha experiencia con las plataformas digitales de venta o las redes sociales. Se queja de que le parece un poco confuso afiliarse a aplicaciones de pago o de entrega. Encuentra una aplicación que sea fácil de usar, que tenga comisiones bajas y que le permita hacer publicidad de sus productos sin dificultades. Asimismo, le gustaría tener a su disposición tutoriales o asesoramiento que la asistan en el aprendizaje del empleo de la herramienta y en el fomento de su negocio. Sugiere tener niveles de uso progresivos para avanzar gradualmente. Su objetivo es aumentar la cantidad de clientes que visitan su juguería, no solo establecer una presencia en línea. | ![Evidencia](assets/Entrevista_Gabriela.jpg) <br> [📂 Ver entrevista](https://drive.google.com/file/d/15Qma_86tWBnnfWBWlx28-MLKOQJRCrI2/view?usp=drive_link) |


### 2.2.3. Análisis de entrevistas
### Segmento #1: Exploradores Gastronómicos (Usuarios de la app web)
---
### Hallazgos :
## 👨 Vitaly Baca

Le gusta salir con su pareja o sus amigos para conocer sitios nuevos, por lo que usa aplicaciones web casi todos los fines de semana. Utiliza Google Maps y sigue a foodies en Instagram y TikTok para descubrir la mayoría de huariques. Aprecia el precio por ser estudiante, pero también la fiabilidad de las fotos y los comentarios. Además de que numerosas tiendas pequeñas no aparecen en las aplicaciones, ha habido inconvenientes con locales que se muestran abiertos pero estaban cerrados.Si cuenta con críticas honestas de usuarios parecidos, se incentivaría el uso de una aplicación enfocada únicamente en huariques. Piensa que son imprescindibles los filtros de tipo de comida y precio, un mapa rápido e intuitivo y sugerencias personalizadas. Sus inquietudes son que la aplicación contenga escasa información en su ciudad, que esté llena de publicidad o que tenga datos poco fiables.
**Puntos clave:**
- Usa apps de búsqueda gastronómica con frecuencia (fines de semana).  
- Descubre lugares principalmente en **TikTok, Instagram y Google Maps**.  
- Valora sobre todo el **precio**, seguido de **fotos y reseñas confiables**.  
- Ha tenido problemas con **información desactualizada** y huariques que no aparecen.  
- Se motiva por una app exclusiva con reseñas sinceras.  
- Considera imprescindibles **filtros, mapa interactivo y recomendaciones personalizadas**.  
- Le preocupa la **publicidad excesiva** y la **poca cobertura local**.  


## 👨 Sebastián del Río

No utiliza con mucha regularidad aplicaciones para buscar huariques, solamente una o dos veces al mes cuando tiene ganas de salir con amigos o hacer algo diferente. Conoce los lugares, sobre todo en Instagram y TikTok, y de vez en cuando en Google Maps. Cuando se trata de escoger un lugar, considera principalmente las reseñas y fotos verdaderas, además del precio y la proximidad. Ha presentado como problema el que los huariques escasean en las aplicaciones, ya que se imponen los restaurantes conocidos y la información es frecuentemente incompleta o carece de fotos de calidad. Siempre que sea fácil de usar, se sentiría motivado a emplear una aplicación que realmente exhiba lugares auténticos y fiables. Para él, son indispensables fotografías auténticas, calificaciones sinceras, un mapa interactivo con la localización y filtros de precio, así como la oportunidad de guardar elementos favoritos. Su inquietud es que la información no sea fiable, que lo envíen a sitios de mala calidad o cerrados y que la aplicación sea lenta o complicada.

**Puntos clave:**
- Usa apps **esporádicamente** (1–2 veces al mes).  
- Descubre huariques en **redes sociales** y a veces en Google Maps.  
- Valora **fotos, reseñas reales, precio y cercanía**.  
- Problemas: **huariques invisibles, info incompleta y fotos deficientes**.  
- Se motiva por una app **auténtica y confiable**.  
- Imprescindibles: **fotos reales, reseñas honestas, mapa interactivo, filtros y favoritos**.  
- Preocupaciones: **información falsa, lugares cerrados, app lenta o complicada**.  

## 👨 Luis Fernández

Cada semana busca sitios nuevos, especialmente los fines de semana con su pareja. Se orienta por las cuentas de amantes de la comida en TikTok e Instagram, guarda videos para consultarlos después y examina opiniones en Facebook y Google Maps. Valora mucho el precio, aunque también le da relevancia a la experiencia total: comentarios sobre la atención, calidad de los alimentos y fotografías de los platos. Entre los obstáculos que menciona, se encuentran los horarios de las aplicaciones desactualizados, que lo conducen a locales cerrados, y la escasa visibilidad de huariques menos populares. Se incentivaría el uso de una aplicación fiable que dé prioridad a los huariques que tengan reseñas escritas por personas del lugar. Un mapa interactivo, sugerencias personalizadas y filtros por tipo de comida, ubicación y costo son elementos que consideras esenciales. Sus inquietudes son las siguientes: que la aplicación contenga demasiada publicidad, información engañosa o no ofrezca suficientes alternativas locales.

**Puntos clave:**
- Usa apps **frecuentemente**, casi cada semana.  
- Descubre lugares en **TikTok, Instagram, Google Maps y Facebook**.  
- Valora **precio, experiencia completa, fotos y reseñas sobre atención/comida**.  
- Problemas: **horarios desactualizados, falta de visibilidad de huariques pequeños**.  
- Se motiva por una app **confiable y enfocada en huariques**.  
- Imprescindibles: **filtros por comida, precios y ubicación, mapa interactivo, recomendaciones**.  
- Preocupaciones: **publicidad excesiva, información falsa, pocas opciones locales**.
---
### Segmento #2: Dueños y Administradores de Huariques
## 👨 Wildor Villalobos (28 años)

Para difundir su negocio de pan con chicharrón, emplea sobre todo **Instagram y TikTok**, aunque los **reels** son más eficaces que las publicaciones habituales. El principal desafío que afronta es la **competencia**, el obstáculo de **comprender el algoritmo** y la exigencia de destinar dinero a publicidad para obtener más visibilidad.

Se siente **a gusto** al utilizar aplicaciones web, siempre que sean **útiles y sencillas de manejar**. Aprecia bastante las **métricas claras** acerca de cuántos clientes lo descubren y cómo llegan a su restaurante. Le agradan las interfaces sencillas, con gráficos directos y comunicación lineal.

En cuanto al **modelo de pago**, ya invierte mensualmente entre **S/ 20 y S/ 50 en Instagram**. Por lo tanto, estaría dispuesto a invertir la misma cantidad en una aplicación especializada, siempre que esta le proporcione un rendimiento igual o superior en términos de atracción de clientes. La principal expectativa que tiene es que la aplicación **eleve sus ventas** de un modo significativo.

**Puntos clave:**  
- Usa **Instagram y TikTok** (prefiere reels).  
- Problemas: **competencia alta, algoritmos complicados, inversión en publicidad**.  
- Cómodo con apps web si son **efectivas y simples**.  
- Valora **métricas claras y directas** (clientes alcanzados, interacciones, impacto real).  
- Prefiere **interfaz simple con gráficos directos y comunicación lineal**.  
- Dispuesto a pagar **20–50 soles/mes** si rinde igual o mejor que Instagram/TikTok.  
- Expectativa central: que la app **genere más clientes y ventas**.  
## 👨 Piero Tapia (26 años)

Propietario de un local de sándwiches. Su clientela llega sobre todo por la localización física de su negocio; hoy en día no usa plataformas web para promocionarse. Señala que tiene escaso conocimiento en redes sociales y que no dispone de un presupuesto adecuado para campañas de marketing digital, lo cual le dificulta proyectar una buena imagen online.

La **falta de conocimientos sobre el manejo digital**, la complejidad para atraer al público adecuado y las dificultades para entender procedimientos como **las afiliaciones a aplicaciones de entrega o los pagos online** son algunos de sus principales desafíos. Como cliente ha utilizado aplicaciones de pedidos, pero como empresa no siente que pueda afiliarse porque no le parecen intuitivas. 

Si una aplicación especializada es **fácil de entender y utilizar**, con **comisiones bajas** que no encarecen sus productos, se incentivaría su uso porque eso tiene un impacto negativo en la demanda. Además, espera que la aplicación le proporcione **guía y soporte** para adquirir habilidades en su uso y optimizar su gestión a lo largo del tiempo. Sugiere que el modelo de tarifas/membresías sea **escalonado** (para principiantes, negocios intermedios y avanzados) a fin de no dejar fuera a las empresas que están en sus inicios.

Su principal expectativa es que la aplicación le produzca **un incremento en el número de clientes reales y las ventas**, no solamente visibilidad sin conversión.

**Puntos clave:**  
-En la actualidad, no emplea plataformas en línea; su negocio depende del **tráfico físico** en el local.  
- Problemas: **Dificultades con los pagos online y las afiliaciones, falta de presupuesto, escaso conocimiento digital.**  
- Como cliente, emplea aplicaciones de comida, pero no las utiliza como negocio (no son intuitivas).  
- Evalúa: **la sencillez de uso, las comisiones bajas y la guía o soporte práctico para aprender**.  
- Propone un **sistema de tarifas escalonado** (para principiantes, intermedios y avanzados).  
- Expectativa: **Incrementar las ventas y atraer a más clientes reales**, además de la visibilidad.

## 👩‍🦰 Gabriela Vasquez (23 años)

Propietaria de una **juguería artesanal** situada en un barrio con mucho tráfico. En la actualidad, su negocio se basa en el **boca a boca y el tránsito local**, puesto que no emplea plataformas digitales o redes sociales para hacer publicidad. Dice que no tiene mucha familiaridad con las herramientas en línea y que le parecen **poco intuitivas** las alternativas de suscribirse a aplicaciones de delivery o de pagos online.

Su mayor desafío es **obtener visibilidad sin sacrificar la simplicidad** que distingue a su juguería. Intenta captar nuevos clientes sin la necesidad de invertir sumas elevadas en publicidad o de enredarse con procesos tecnológicos. Ten en cuenta que la aplicación sea **fácil de usar, clara y atractiva**, incluso para aquellos que no tienen un conocimiento previo del marketing digital.

Además, le gustaría que la aplicación proporcionara **soporte y consejos prácticos** para aprender a utilizar la herramienta de manera óptima, lo que incluye sugerencias para sobresalir su empresa frente a otras competidoras. Piensa que es beneficioso un **sistema de planes por niveles** (básico, intermedio, avanzado) que se ajuste al crecimiento de la empresa sin requerir grandes desembolsos iniciales.

Su objetivo fundamental es que la aplicación lo asista para **incrementar el número de clientes en su negocio de jugos**, sobre todo aquellos que buscan alternativas naturales o saludables en las cercanías.

**Puntos clave:**  
- No utiliza aplicaciones ni redes sociales para hacer publicidad; se basa en el **tráfico local y el boca a boca**.  
- Problemas: **poca experiencia en el ámbito digital, dificultades con las suscripciones y los pagos online**.  
- Valora: **Diseño atractivo, facilidad de uso y guía por pasos**.  
- Busca **visibilidad verdadera sin altos costos de publicidad**.  
- Se inclina por un **modelo de membresía escalonado** (básico, intermedio y avanzado).  
- Expectativa: **Consolidar la identidad de su negocio y hacer crecer la clientela que va en persona**.


## 2.3. Needfinding
### 2.3.1. User Personas
Se han creado dos perfiles de usuario o personas representativas para entender con mayor precisión las motivaciones, necesidades y conductas de los usuarios principales de PuntoSabor. Estos perfiles resumen los rasgos, metas y desafíos comunes de los segmentos principales, lo que simplifica el desarrollo de la plataforma al diseñarla con enfoque en el usuario y tomar decisiones estratégicas.

- Persona  1: Carla, la Exploradora Gastronómica

   Carla simboliza a los usuarios jóvenes y activos, quienes buscan alternativas culinarias auténticas y asequibles que se aparten de las propuestas tradicionales. Este perfil aprecia que se pueda hallar huariques confiables de manera sencilla por medio de plataformas digitales, las cuales ofrezcan información clara y reseñas auténticas.
![alt text](assets/UserPersonaSeg1.jpg)

- Persona 2: Don Luis, dueño de huarique tradicional
Don Luis representa a los dueños de huariques y a los emprendedores pequeños que requieren instrumentos asequibles y eficaces para hacer publicidad de su negocio y ampliar su clientela. Con una experiencia reducida en tecnología digital, busca soluciones sencillas de utilizar que le faciliten manejar su presencia en línea sin excesivas dificultades ni gastos altos.
![alt text](assets/UserPersonaSeg2.jpg)

### 2.3.2. User Task Matrix

![alt text](assets/UserTaskMatrix-PuntoSabor.jpg)

Los perfiles de usuario en PuntoSabor presentan diferencias notables en sus tareas habituales, dependiendo de las necesidades y el rol de cada uno. Como exploradora gastronómica, Carla Dípes emplea la aplicación web de manera continua y activa para buscar huariques, leer reseñas y utilizar la función de mapas con geolocalización. Para ella, estas actividades son fundamentales para su experiencia. Por otro lado, Don Luis Pérez, propietario de huarique, no suele emplear la aplicación para buscar o ver mapas; su interés principal es actualizar la información de su huarique, tarea que lleva a cabo con frecuencia y considera esencial. Los dos individuos se comunican de vez en cuando utilizando la función de responder reseñas y compartir fotografías u opiniones, aunque Don Luis lo hace con menos frecuencia, pero sigue siendo significativo en términos de importancia.

Coincidencias:
- Ambos, de manera ocasional, interactúan con la función de responder reseñas, a la que le asignan una importancia media.

- Carla tiene una frecuencia más alta que los demás en lo que respecta a compartir fotos y opiniones, aunque todos comparten una actitud media hacia la importancia de hacerlo.

- Para los dos perfiles, las funciones que tienen que ver con la interacción social y la comunidad son de importancia media.
  
Diferencias:
- Carla utiliza con frecuencia la búsqueda y consulta de huariques y mapas; en cambio, Don Luis tiene menos frecuencia en estas actividades debido a que su rol es más administrativo.

- La actualización de la información de su huarique es una tarea que Carla no lleva a cabo, pero Don Luis invierte más tiempo y la considera importante.

- Como resultado de sus roles y objetivos distintos en la plataforma, Carla tiene un alto grado de interacción con mapas y geolocalización, mientras que Don Luis lo tiene bajo.
  
### 2.3.3. User Journey Mapping
Segmento 1

Con el uso de este artefacto se analizará y entenderá cómo los usuarios del segmento 1 (Exploradores Gastronómicos) llevan a cabo sus tareas con el fin de lograr sus metas desde su punto de vista. Este segmento está constituido por individuos que persiguen vivencias gastronómicas auténticas y asequibles, indagando en huariques menos conocidos y apreciando los datos fidedignos suministrados por medio de imágenes, mapas de localización y reseñas.

![alt text](assets/Carla_Dipes.png)

Segmento 2

Este artefacto permitirá explicar y entender la manera en que los usuarios del segmento 2 (dueños y administradores de huariques) llevan a cabo sus actividades para lograr sus metas desde su punto de vista. Este segmento está conformado por pequeños empresarios que buscan promover su empresa, incrementar su visibilidad y captar nuevos clientes a través de una plataforma fácil de administrar y accesible, sin requerir conocimientos técnicos sofisticados.

![alt text](assets/Don_Luis.jpg)

### 2.3.4. Empathy Mapping
Los siguientes mapas de empatía corresponden a los dos perfiles principales de usuarios de PuntoSabor: Carla Dípes, la exploradora de la gastronomía, y Don Luis Pérez, propietario de un huarique tradicional. Estos mapas posibilitan entender a fondo sus sentimientos, pensamientos, necesidades y conductas, lo que contribuye a que el diseño esté orientado hacia el usuario.

- Segmento 1:

La carta de empatía de Carla revela que es una clienta que desea experiencias culinarias locales únicas y autenticidad. Considera que es fácil hallar información fiable y se siente frustrada por la abundancia de opciones genéricas en otras plataformas.
![alt text](assets/EmphatyMap_CarlaDipes.png)

- Segmento 2:

El mapa de empatía de Don Luis muestra a un empresario con restricciones tecnológicas, que requiere una herramienta simple para administrar su huarique y expandir su clientela. Busque apoyo y soluciones asequibles que le permitan tener presencia en línea sin altos costos.
![alt text](assets/EmphatyMap_DonLuisPerez.png)


### 2.3.5. As-is Scenario Mapping
Segmento 1

Con este artefacto, se ha desarrollado el As-is Scenario Mapping para la primera franja (Exploradores Gastronómicos). Este panorama muestra la manera en que los usuarios que desean descubrir huariques llevan a cabo sus actividades hoy en día, los obstáculos a los que se enfrentan al buscar alternativas económicas y auténticas, además de las sensaciones y percepciones que sienten en cada fase de su recorrido.

![alt text](assets/Segmento1_AsIs.png)

Segmento 2

Con este instrumento se ha realizado el As-is Scenario Mapping para el segundo grupo (los propietarios y administradores de huariques). Esta situación muestra la manera en que los emprendedores de pequeña escala administran hoy en día la promoción y organización de sus negocios, destacando las limitaciones tecnológicas, los procesos manuales y las emociones relacionadas con su necesidad de atraer nuevos clientes y obtener más visibilidad.

![alt text](assets/Segmento2_AsIs.png)

## 2.4. Big Picture Event Storming

Pasos para el event storming:

Step 1: Unstructured Exploration


![alt text](<assets/Step 1.png>)

Step 2: Timelines

![alt text](<assets/Step 2.png>)

Step 3: Paint Points

![alt text](<assets/Step 3.1.png>)

![alt text](<assets/Step 3.1.png>)

![alt text](<assets/Step 3.2.png>)

Step 4: Pivotal Points

![alt text](<assets/Step 4.png>)

Step 5: commands

![alt text](<assets/Step 5.png>)

Step 6: Policies

![alt text](<assets/event 6.png>)

Step 7: Read Models

![alt text](<assets/event 7.png>)

Step 8: External system

![alt text](<assets/event 8.png>)

Step 9: Aggregates

![alt text](<assets/event 9.png>)

Step 10: Bounded Contexts

![alt text](<assets/event 10.png>)

Link del miro: 

https://miro.com/welcomeonboard/N1ZUMVF3dkJEMXY1VTIvR0hhWisyQlFnU1VFYU1UVVFGOFNVKzdGS3FVOFJ1ZWRaNUI3L3NyMGcxNTRqSkN4bUZTZGo1N2VVbVNITTIvc3p2c1V6emNGUEprWThGdVg0SGsvRmtwSWJzTzR3dTVQVG5Hb1ZzWlRuK0tUM2hZSU9nbHpza3F6REdEcmNpNEFOMmJXWXBBPT0hdjE=?share_link_id=673091896888

## 2.5. Ubiquitous Language

En esta parte se muestra el glosario de términos fundamentales del ámbito de PuntoSabor, que están escritos en inglés y acompañados de su traducción al español entre paréntesis. Cada definición tiene como objetivo que la comunicación entre todos los miembros del equipo y los interesados sea coherente y clara, así como eliminar ambigüedades y alinear el lenguaje de la empresa.

Glosario:

- Huarique (Huarique): Restaurante peruano tradicional, que normalmente es familiar o local, famoso por su cocina auténtica, accesible y casera. Es el núcleo de la propuesta de PuntoSabor.

- Gastronomic Explorer (Explorador culinario): Persona que tiene como motivación la experiencia cultural y gastronómica y que se interesa por encontrar huariques auténticos, asequibles y poco conocidos.

- Huarique Owner (Propietario de Huarique): Persona encargada de administrar un huarique, que incluye la elaboración de los platos, la atención al cliente y la gestión general del negocio.

- Review (reseña): Opinión o valoración escrita por un consumidor acerca de su vivencia en un huarique, que contiene observaciones sobre la calidad de los platos, el servicio y el ambiente.

- Recommendation (Recomendación): Recomendación hecha por un cliente para que otros visitantes tengan la oportunidad de conocer o probar un huarique específico.

- Favorite (Favorito): Huarique es un cliente que recuerda o enfatiza como favorito debido a la calidad de su experiencia, y al que desea volver a visitar o sugerir.

- Culinary Tradition (Tradición Culinaria): Conjunto de hábitos, recetas y prácticas culinarias típicas de los huariques, que enriquecen culturalmente la vivencia gastronómica.

- Community Interaction (Interacción Comunitaria): Interacción entre los clientes y los propietarios de huariques a través del intercambio de experiencias, reseñas, sugerencias y conversaciones que aumentan la confianza y el reconocimiento de sus empresas.
  
- Membership (Membresía): Acuerdo financiero por el que un propietario de huarique obtiene ventajas extra de visibilidad y promoción dentro del ecosistema de PuntoSabor.

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
### Segmento 1 
![alt text](assets/To_be_seg1.jpeg)
### Segmento 2
![alt text](assets/To_be_seg2.jpeg)
## 3.2. User Stories
En esta sección se presentan los requisitos definidos para PuntoSabor, expresados mediante User Stories y Epics. Cada User Story incluye criterios de aceptación claros y comprobables, redactados en tiempo presente y tercera persona, siguiendo la estructura Gherkin (Given-When-Then). Se considera tanto la experiencia del usuario en la app web como aspectos técnicos del desarrollo, incluyendo historias técnicas para el RESTful API.

A continuación, se muestra un cuadro resumen con los Epics y User Stories definidos, sus descripciones, criterios de aceptación y relaciones entre ellos.
 
| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------|--------|-------------|-------------------------|---------------------------|
| EP01 | Descubrimiento de Huariques | Como explorador gastronómico, quiero buscar y descubrir huariques locales para elegir dónde comer. |  |  |
| EP02 | Gestión de Huariques | Como dueño, quiero registrar y actualizar la información de mi huarique para mantenerlo visible. |             |                           |
| EP03 | Interacción Comunitaria | Como usuario, quiero dejar reseñas y calificaciones para compartir mi opinión. |        |                           |
| EP04 | Información del Sitio Web Estático | Como visitante, quiero acceder a una landing page con información clara sobre PuntoSabor y sus servicios. |     |                           |
| EP05 | Notificaciones y Alertas | Como usuario, quiero recibir notificaciones sobre novedades, promociones o actualizaciones. |                |                           |
| EP06 | Servicios Técnicos y API | Como developer, necesito APIs RESTful para gestionar huariques, usuarios y búsquedas. |           |                           |
| EP07 | Seguridad y Autenticación | Como usuario, quiero que mis datos estén protegidos y acceder con autenticación segura. |              |                           |
| EP08 | Personalización y Recomendador | Como usuario, quiero recibir sugerencias ajustadas a mis preferencias y búsquedas previas, para descubrir huariques relevantes a mis gustos y presupuesto. |
| EP09 | Calidad de Datos y Verificación | Como usuario, quiero que la plataforma valide horarios, estado abierto/cerrado y datos clave de los huariques para no perder tiempo en información desactualizada. |
| EP10 | Monetización y Facturación | Como dueño de huarique, quiero acceder a planes de membresía claros y a facturación transparente para mejorar la visibilidad de mi negocio. |
| US01 | Búsqueda avanzada | Como usuario, puedo filtrar huariques por ubicación, tipo de comida y precio para una búsqueda eficiente. | Escenario 1: Filtrado con resultados. Dado que el usuario aplica filtros válidos, Cuando realiza la búsqueda, Entonces la app muestra huariques que cumplen esos filtros. Escenario 2: Filtrado sin resultados Dado que el usuario aplica filtros estrictos sin coincidencias, Cuando realiza la búsqueda, Entonces aparece un mensaje de "No se encontraron huariques con esos filtros". Escenario 3: Búsqueda sin filtros Dado que el usuario no aplica filtros, Cuando realiza la búsqueda, Entonces la app muestra todos los huariques disponibles. | EP01 |
| US02 | Visualización en mapa | Como usuario, quiero ver la ubicación de los huariques en un mapa para facilitar la visita. | Escenario 1: Mostrar mapa con marcadores Dado que el usuario accede a la vista de mapa, Cuando se carga la página, Entonces el mapa muestra marcadores para cada huarique visible según la búsqueda. Escenario 2: Selección de marcador Dado que el usuario selecciona un marcador en el mapa, Cuando hace clic en el marcador, Entonces se muestra un resumen con el nombre, dirección y calificación del huarique. | EP01 |
| US03 | Guardar favoritos | Como usuario, puedo guardar huariques para acceder fácilmente después. | Escenario 1: Guardar huarique como favorito Dado que el usuario marca un huarique como favorito, Cuando confirma la acción, Entonces se guarda en su lista personal. Escenario 2: Acceder lista de favoritos Dado que el usuario accede a su lista de favoritos, Cuando la abre, Entonces puede ver y seleccionar huariques guardados. | EP01|
| US04 | Registro de nuevo huarique | Como dueño, puedo registrar un nuevo huarique con información básica para aparecer en la plataforma. | Escenario 1: Registro exitoso Dado que el dueño completa los campos requeridos, Cuando envía el formulario, Entonces el huarique se registra y aparece en la app. Escenario 2: Campos obligatorios faltantes Dado que el dueño no completa todos los campos obligatorios, Cuando intenta registrar, Entonces la app muestra errores indicando campos faltantes. | EP02 |
| US05 | Actualización de información | Como dueño, puedo modificar los datos de mi huarique para mantenerlos actualizados. | Escenario 1: Actualización exitosa Dado que el dueño edita la información, Cuando hace clic en guardar, Entonces los datos se actualizan correctamente. Escenario 2: Error en datos incompletos Dado que el dueño deja un campo obligatorio vacío, Cuando intenta guardar, Entonces la app muestra un error indicando llenar el campo. | EP02 |
| US06 | Gestión multimedia | Como dueño, puedo subir fotos y videos para mostrar mi huarique. | Escenario 1: Subida exitosa Dado que el dueño selecciona archivo válido, Cuando lo sube, Entonces se añade multimedia al perfil del huarique. Escenario 2: Archivo inválido Dado que el archivo no es compatible, Cuando intenta subirlo, Entonces la app muestra un error indicando tipos permitidos. | EP02 |
| US07 | Envío de reseñas | Como usuario, puedo dejar una reseña y calificación en un huarique. | Escenario 1: Envío exitoso Dado que el usuario completa la reseña y la calificación, Cuando confirma el envío, Entonces la reseña aparece visible para todos los usuarios. Escenario 2: Restricción de una reseña por huarique Dado que el usuario ya dejó una reseña en el huarique, Cuando intenta dejar otra, Entonces la app impide la acción con mensaje informativo. | EP03 |
| US08 | Moderación automática | Como sistema, debo detectar reseñas inapropiadas y bloquearlas. | Escenario 1: Detección de contenido inapropiado Dado que la reseña contiene lenguaje ofensivo, Cuando se intenta publicar, Entonces el sistema bloquea o marca la reseña para revisión. | EP03 |
| US09 | Presentación de beneficios | Como visitante, puedo ver las ventajas de PuntoSabor en la landing page. | Escenario 1: Carga de landing page Dado que el visitante entra al sitio, Cuando se carga la página, Entonces se muestran claramente los beneficios para usuarios y dueños. | EP04 |
| US10 | Formulario de contacto | Como visitante, puedo enviar consultas a través de un formulario. | Escenario 1: Envío exitoso Dado que el visitante completa el formulario correctamente, Cuando lo envía, Entonces el equipo recibe la consulta y confirma recepción. Escenario 2: Campos obligatorios Dado que el visitante no completa datos requeridos, Cuando intenta enviar, Entonces la app muestra errores indicando los campos faltantes. | EP04 |
| US11 | Configuración de notificaciones | Como usuario, puedo activar o desactivar notificaciones a mi preferencia. | Escenario 1: Guardar preferencias Dado que el usuario cambia su configuración, Cuando guarda, Entonces las preferencias se aplican correctamente. | EP05 |
| US12 | Notificación de nuevas reseñas | Como dueño, recibo alertas cuando hay reseñas nuevas en mi huarique. | Escenario 1: Alerta por nueva reseña Dado que un usuario publica una reseña, Cuando ésta es aprobada, Entonces el dueño recibe una notificación inmediata. | EP05 |
| US13 | API de búsqueda | Como developer, puedo consultar huariques filtrando por parámetros vía API. | Escenario 1: Consulta con filtros Dado que la petición API incluye criterios, Cuando se procesa, Entonces devuelve resultados acordes a los filtros. Escenario 2: Consulta sin horarios válidos Dado que la petición API tiene parámetros inválidos, Cuando se procesa, Entonces devuelve error o mensaje claro. | EP06 |
| US14 | API de registro y actualización | Como developer, puedo crear y actualizar huariques a través de la API. | Escenario 1: Creación exitosa Dado que la petición contiene datos válidos, Cuando se procesa, Entonces se crea un nuevo huarique y responde con éxito. Escenario 2: Actualización exitosa Dado que se envían datos para modificar un huarique existente, Cuando se procesa, Entonces se actualizan los datos y responde con éxito. | EP06 |
| US15 | Registro y login seguro | Como usuario, puedo crear cuenta y acceder con credenciales seguras. | Escenario 1: Registro exitoso Dado que el usuario completa datos válidos, Cuando envía el formulario, Entonces la cuenta se crea y puede iniciar sesión. Escenario 2: Login con credenciales incorrectas Dado que el usuario ingresa datos erróneos, Cuando intenta iniciar sesión, Entonces recibe mensaje de error y no accede. | EP07 |
| US16 | Recuperación de contraseña | Como usuario, puedo recuperar mi contraseña en caso de olvido. | Escenario 1: Solicitud de recuperación Dado que usuario solicita recuperación, Cuando facilita su correo válido, Entonces recibe instrucciones para restablecer contraseña. | EP07 |
| US17 | Configuración de preferencias | Como usuario, puedo guardar mis preferencias de tipo de cocina, presupuesto y ubicación para recibir recomendaciones personalizadas. | Escenario 1: Guardar preferencias. Dado que ingreso mis preferencias, Cuando confirmo, Entonces se almacenan en mi perfil. Escenario 2: Recomendaciones aplicadas. Dado que tengo preferencias guardadas, Cuando entro a “Recomendados”, Entonces aparecen huariques que cumplen esos criterios. | EP08 |
| US18 | Recomendador automático | Como usuario, quiero que la app me sugiera huariques basados en mi historial de búsquedas y favoritos. | Escenario 1: Con historial. Dado que ya busqué huariques, Cuando accedo a “Recomendados”, Entonces aparecen opciones similares. Escenario 2: Sin historial. Dado que no tengo historial, Cuando accedo a “Recomendados”, Entonces aparecen sugerencias populares de la zona. | EP08 |
| US19 | Sugerencias por ubicación | Como usuario, quiero recibir recomendaciones de huariques cercanos a mi ubicación actual. | Escenario 1: Geolocalización activada. Dado que otorgo permiso de ubicación, Cuando accedo a “Cerca de mí”, Entonces se muestran huariques dentro del radio definido. Escenario 2: Sin permisos. Dado que no otorgo acceso a ubicación, Cuando accedo a “Cerca de mí”, Entonces la app solicita permisos o permite búsqueda manual. | EP08 |
| US20 | Verificación de horarios | Como usuario, quiero que la app me muestre si el horario de un huarique ha sido confirmado recientemente. | Escenario 1: Confirmado. Dado que un dueño actualiza su horario, Cuando entro al perfil, Entonces aparece la etiqueta “Horario verificado”. Escenario 2: Sin confirmar. Dado que no hay actualizaciones recientes, Cuando entro al perfil, Entonces aparece la etiqueta “Horario no verificado”. | EP09 |
| US21 | Reporte de información incorrecta | Como usuario, puedo reportar si un huarique tiene datos erróneos (dirección, horario, estado). | Escenario 1: Reporte enviado. Dado que detecto un error, Cuando envío el reporte, Entonces queda registrado en el sistema. Escenario 2: Corrección aplicada. Dado que la información fue revisada, Cuando el administrador actualiza, Entonces el huarique refleja el cambio. | EP09 |
| US22 | Validación automática de estado | Como sistema, quiero mostrar si un huarique está abierto o cerrado en tiempo real mediante verificación cruzada con reseñas recientes o interacción del dueño. | Escenario 1: Estado confirmado. Dado que el sistema valida apertura con datos recientes, Cuando el usuario accede al perfil, Entonces se muestra “Abierto ahora” o “Cerrado”. Escenario 2: Datos inciertos. Dado que no hay datos suficientes, Cuando accede al perfil, Entonces aparece la alerta “Estado no confirmado”. | EP09 |
| US23 | Planes de membresía | Como dueño, quiero poder elegir entre planes de membresía con distintos beneficios (básico, pro) para dar mayor visibilidad a mi huarique. | Escenario 1: Selección de plan. Dado que elijo un plan, Cuando confirmo, Entonces la suscripción queda activa. Escenario 2: Cambio de plan. Dado que deseo cambiar de plan, Cuando lo solicito, Entonces la app actualiza la suscripción al finalizar el periodo vigente. | EP10 |
| US24 | Pago de suscripción | Como dueño, quiero pagar mi membresía mediante tarjeta o billetera digital de forma segura. | Escenario 1: Pago válido. Dado que ingreso datos de tarjeta válidos, Cuando confirmo, Entonces la suscripción se activa y recibo comprobante. Escenario 2: Pago inválido. Dado que ingreso datos erróneos, Cuando confirmo, Entonces la app muestra un mensaje de error. | EP10 |
| US25 | Facturación y comprobantes | Como dueño, quiero descargar facturas mensuales de mis pagos para llevar un control contable. | Escenario 1: Descarga exitosa. Dado que accedo a facturación, Cuando selecciono un mes, Entonces puedo descargar el PDF. Escenario 2: Pago fallido. Dado que hubo un problema de cobro, Cuando reviso facturación, Entonces aparece un aviso de “Pago pendiente”. | EP10 |
| US26 | Promociones destacadas | Como dueño Pro, quiero publicar promociones que aparezcan destacadas en los listados de huariques. | Escenario 1: Crear promoción. Dado que configuro fechas y cupos, Cuando publico, Entonces la promoción aparece destacada. Escenario 2: Fin de promoción. Dado que expira la fecha límite, Cuando reviso el listado, Entonces la promoción deja de mostrarse. | EP10 |
|     |  |  |  |  |

## 3.3. Impact Mapping
## 3.4. Product Backlog
| # Orden | User Story ID | Título                          | Descripción                                                                 | Story Points (1 / 2 / 3 / 5 / 8) |
|---------|---------------|----------------------------------|-----------------------------------------------------------------------------|----------------------------------|
| 1       | US01          | Búsqueda avanzada               | Como usuario, puedo filtrar huariques por ubicación, tipo de comida y precio para una búsqueda eficiente. | 5 |
| 2       | US02          | Visualización en mapa           | Como usuario, quiero ver la ubicación de los huariques en un mapa para facilitar la visita. | 3 |
| 3       | US03          | Guardar favoritos               | Como usuario, puedo guardar huariques para acceder fácilmente después. | 3 |
| 4       | US04          | Registro de nuevo huarique      | Como dueño, puedo registrar un nuevo huarique con información básica para aparecer en la plataforma. | 5 |
| 5       | US05          | Actualización de información    | Como dueño, puedo modificar los datos de mi huarique para mantenerlos actualizados. | 3 |
| 6       | US06          | Gestión multimedia              | Como dueño, puedo subir fotos y videos para mostrar mi huarique. | 3 |
| 7       | US07          | Envío de reseñas                | Como usuario, puedo dejar una reseña y calificación en un huarique. | 3 |
| 8       | US08          | Moderación automática           | Como sistema, debo detectar reseñas inapropiadas y bloquearlas. | 5 |
| 9       | US09          | Presentación de beneficios      | Como visitante, puedo ver las ventajas de PuntoSabor en la landing page. | 2 |
| 10      | US10          | Formulario de contacto          | Como visitante, puedo enviar consultas a través de un formulario. | 2 |
| 11      | US11          | Configuración de notificaciones | Como usuario, puedo activar o desactivar notificaciones a mi preferencia. | 2 |
| 12      | US12          | Notificación de nuevas reseñas  | Como dueño, recibo alertas cuando hay reseñas nuevas en mi huarique. | 2 |
| 13      | US13          | API de búsqueda                 | Como developer, puedo consultar huariques filtrando por parámetros vía API. | 5 |
| 14      | US14          | API de registro y actualización | Como developer, puedo crear y actualizar huariques a través de la API. | 5 |
| 15      | US15          | Registro y login seguro         | Como usuario, puedo crear cuenta y acceder con credenciales seguras. | 5 |
| 16      | US16          | Recuperación de contraseña      | Como usuario, puedo recuperar mi contraseña en caso de olvido. | 2 |
| 17      | US17          | Configuración de preferencias   | Como usuario, puedo guardar mis preferencias de tipo de cocina, presupuesto y ubicación para recibir recomendaciones personalizadas. | 3 |
| 18      | US18          | Recomendador automático         | Como usuario, quiero que la app me sugiera huariques basados en mi historial de búsquedas y favoritos. | 5 |
| 19      | US19          | Sugerencias por ubicación       | Como usuario, quiero recibir recomendaciones de huariques cercanos a mi ubicación actual. | 3 |
| 20      | US20          | Verificación de horarios        | Como usuario, quiero que la app muestre si el horario de un huarique ha sido confirmado recientemente. | 3 |
| 21      | US21          | Reporte de información incorrecta | Como usuario, puedo reportar si un huarique tiene datos erróneos (dirección, horario, estado). | 2 |
| 22      | US22          | Validación automática de estado | Como sistema, quiero mostrar si un huarique está abierto o cerrado en tiempo real mediante verificación cruzada. | 5 |
| 23      | US23          | Planes de membresía             | Como dueño, quiero poder elegir entre planes de membresía con distintos beneficios (básico, pro). | 3 |
| 24      | US24          | Pago de suscripción             | Como dueño, quiero pagar mi membresía mediante tarjeta o billetera digital de forma segura. | 5 |
| 25      | US25          | Facturación y comprobantes      | Como dueño, quiero descargar facturas mensuales de mis pagos para control contable. | 3 |
| 26      | US26          | Promociones destacadas          | Como dueño Pro, quiero publicar promociones que aparezcan destacadas en listados. | 3 |
# Capítulo IV: Product Design
## 4.1. Style Guidelines
Un “Style Guideline” es un conjunto de directrices y normas que establecen los estándares y criterios a seguir en la redacción, diseño y presentación de documentos, contenido web, software y otros productos creativos. A continuación, se presentan las especificaciones detalladas de los parámetros implementados en la estructura del proyecto.
### 4.1.1. General Style Guidelines
Branding

Para el desarrollo de la identidad de PuntoSabor, se ha diseñado un estilo que encapsula la esencia de la aplicación y su propuesta de valor. La marca busca transmitir cercanía, autenticidad y confianza, resaltando la importancia de los huariques en la cultura gastronómica local.

El logotipo de PuntoSabor está compuesto por un ícono que evoca un marcador de ubicación gastronómica (pin), fusionado con elementos culinarios, reforzando la idea de descubrimiento y autenticidad. La elección cromática, con tonos cálidos y frescos, proyecta energía, sabor y dinamismo, generando una conexión emocional con el usuario. La integración de estos elementos comunica visualmente el compromiso de PuntoSabor con la promoción de pequeños negocios, la innovación tecnológica y la experiencia de usuario accesible.
![alt text](assets/LogoSabot.png)

Typography:

Para la tipografía de PuntoSabor, se ha seleccionado una combinación que equilibra modernidad, legibilidad y calidez. La tipografía principal Poppins se utiliza en los encabezados, aportando un estilo fresco y amigable, ideal para captar la atención del usuario en títulos y mensajes clave. Para los textos de párrafo y componentes de interfaz, se emplea Inter, reconocida por su alta legibilidad en entornos digitales, favoreciendo una experiencia clara y ordenada.

Esta combinación tipográfica refuerza el carácter accesible y confiable de la marca, al mismo tiempo que permite destacar información importante y mantener un diseño coherente en toda la aplicación web.

A continuación, se detallan las tipografías adoptadas para PuntoSabor siguiendo los parámetros de color, peso, tamaño, interlineado y alineación:
![alt text](assets/Typography_PuntoSabor.jpg)

Colors:

La paleta de colores de PuntoSabor fue seleccionada para reflejar los valores de autenticidad, cercanía y dinamismo que definen a nuestra plataforma. Los tonos predominantes, rojo, verde y amarillo, evocan energía, sabor y frescura, transmitiendo la esencia de los huariques y la cultura gastronómica local.

La combinación de colores busca generar confianza en los usuarios, a la vez que mantiene un carácter amigable y moderno, reforzando la identidad visual del producto como una solución innovadora para descubrir pequeños negocios de comida.
![alt text](assets/Colores_PuntoSabor.jpg)

Spacing:

El espaciado en PuntoSabor está cuidadosamente definido para garantizar una interfaz limpia, legible y organizada. Se emplea una separación uniforme entre elementos, lo que mejora la jerarquía visual, facilita la navegación y aporta equilibrio al diseño.

El sistema de espaciado se basa en una escala modular de 8px, adaptada para mantener consistencia en todas las vistas de la aplicación.
![alt text](assets/Spacing_PuntoSabor.jpg)
### 4.1.2. Web Style Guidelines
PuntoSabor cuenta con un diseño web adaptable y responsivo, que garantiza una experiencia fluida y accesible en cualquier dispositivo, desde computadoras de escritorio hasta teléfonos móviles.

El patrón de diseño principal sigue la forma de “F” y “Z”, ya que son los más efectivos para dirigir la atención del usuario en interfaces web modernas. Este enfoque permite destacar funciones clave como la barra de búsqueda, los listados de huariques y las promociones destacadas, asegurando que el contenido más relevante esté siempre visible en los primeros segundos de navegación.

En la estructura visual:

El logo de PuntoSabor se ubica en la esquina superior izquierda como ancla de marca.

La barra de navegación con secciones principales (Explorar, Mejor valorados, Promos, Contacto) se encuentra en la parte superior derecha, permitiendo un acceso rápido e intuitivo.

El llamado a la acción (CTA) principal —Buscar huariques o Registrarse— está resaltado con el color primario rojo , lo que atrae la mirada del usuario de inmediato.

El hero section incluye un buscador interactivo con filtros de comida y ubicación, optimizando la experiencia de exploración.

Secciones como “Cerca de ti” y “Mejor valorados” utilizan un sistema de tarjetas modulares que mantienen consistencia y escalabilidad.

Se incluyen chips y badges de colores para resaltar promociones, precios y distancias, mejorando la jerarquía visual.

El footer minimalista refuerza la identidad de marca y proporciona enlaces clave sin sobrecargar la interfaz.

La interfaz en su conjunto transmite autenticidad, simplicidad y dinamismo, reflejando los valores de la marca y favoreciendo la interacción constante entre exploradores gastronómicos y dueños de huariques.
## 4.2. Information Architecture
La arquitectura de la información en PuntoSabor se ha diseñado para garantizar que tanto visitantes como usuarios puedan encontrar con facilidad el contenido y las funciones más relevantes, minimizando la carga cognitiva y generando una experiencia intuitiva. Las decisiones adoptadas buscan reflejar autenticidad, cercanía y dinamismo, alineándose con la identidad de la marca y con los valores de los huariques como espacios gastronómicos locales.
### 4.2.1. Organization Systems
En PuntoSabor se aplican distintos sistemas de organización según el tipo de contenido y la plataforma:

- **Organización jerárquica (Visual Hierarchy):** en la landing page se estructura la información en niveles: primero se presenta la propuesta de valor y el buscador principal, seguido de secciones de beneficios, exploración de huariques mejor valorados, promociones y finalmente el contacto.  

- **Organización secuencial (Step-by-step):** en la aplicación web, procesos como el registro de huariques o la actualización de información siguen un flujo paso a paso que guía al usuario de manera clara.  

- **Organización por tópicos:** el catálogo de huariques se categoriza según criterios como tipo de comida (criolla, marina, postres, etc.), ubicación, y estado de promociones (activas, destacadas).  

- **Organización según audiencia:** la landing page presenta bloques diferenciados: exploradores gastronómicos (jóvenes y adultos que buscan comida auténtica) y dueños de huariques (emprendedores locales). Cada segmento recibe mensajes y beneficios específicos.  
### 4.2.2. Labeling Systems
El etiquetado en PuntoSabor prioriza la claridad y simplicidad, usando palabras cortas, directas y consistentes en todas las interfaces:

- **Landing Page:** Inicio, Explorar, Beneficios, Promos, Contacto.  
- **Aplicación Web:** Huariques, Favoritos, Reseñas, Promociones, Perfil.  

Además, los CTAs refuerzan la acción con verbos imperativos como “Buscar Huariques”, “Registra tu negocio”, “Explora promociones” o “Deja tu reseña”, que facilitan la interacción y mantienen coherencia con los objetivos de la plataforma.
### 4.2.3. SEO Tags and Meta Tags
Se han definido meta elementos para mejorar el posicionamiento SEO tanto en la landing page como en la aplicación web:

- **Title (Landing Page):** PuntoSabor | Descubre huariques auténticos cerca de ti.  
- **Meta Description:** PuntoSabor conecta a exploradores gastronómicos con huariques auténticos y económicos, ofreciendo reseñas confiables, mapas interactivos y promociones exclusivas.  
- **Meta Keywords:** huariques, comida peruana, gastronomía local, reseñas, recomendaciones, restaurantes pequeños, comida auténtica.  
- **Author:** Equipo FijasDev – Startup PuntoSabor.  

Estos elementos aseguran coherencia en motores de búsqueda y fortalecen la estrategia de atracción de usuarios.
### 4.2.4. Searching Systems
La aplicación web de PuntoSabor ofrece sistemas de búsqueda diseñados para que el usuario encuentre lo que necesita sin esfuerzo:

- **Búsqueda en catálogo:** localización de huariques por nombre, tipo de comida o distrito.  
- **Filtros avanzados:** por rango de precios, valoración de usuarios, ubicación geográfica y promociones activas.  
- **Mapa interactivo:** permite aplicar filtros visuales y seleccionar huariques desde su ubicación exacta.  
- **Búsqueda en reseñas:** posibilidad de filtrar comentarios por calificación (positivas/negativas) o por temas (precio, atención, sabor).  

De esta manera se evita que el usuario se sienta perdido entre la cantidad de opciones disponibles y se mejora la eficiencia en la exploración.
### 4.2.5. Navigation Systems
La navegación de PuntoSabor combina claridad, consistencia y adaptabilidad:

- **Landing Page (Desktop):** menú superior con navegación horizontal que permite acceder rápidamente a Inicio, Explorar, Beneficios, Promos y Contacto.  
- **Landing Page (Móvil):** menú tipo hamburguesa con navegación vertical, optimizado para pantallas pequeñas.  
- **Aplicación Web:** navegación lateral (sidebar) con accesos directos a Huariques, Favoritos, Promociones, Perfil y Configuración.  
- **CTAs estratégicos:** botones visibles en rojo primario (#E63946) para guiar al usuario a acciones críticas como buscar huariques, registrar un negocio o activar una promoción.  

En conjunto, estos sistemas garantizan que los usuarios puedan recorrer
la plataforma de forma intuitiva, cumpliendo sus metas sin obstáculos.
## 4.3. Landing Page UI Design
La interfaz de la landing page es clave para el proyecto, pues constituye la primera impresión del producto. Debe ofrecer una experiencia estética y funcional que atraiga de inmediato a los visitantes y los impulse a seguir explorando.

### 4.3.1. Landing Page Wireframe
**Landing Page para Desktop Web Browser**

![alt text](<assets/landing page wireframe desktop 1.png>)

![alt text](<assets/landing page wireframe desktop 2.png>)

**Landing Page para Mobile Web Browse**

![alt text](<assets/landing page wireframe mobile 1.png>)

![alt text](<assets/landing page wireframe mobile 2.png>)

### 4.3.2. Landing Page Mock-up
Esta sección presenta y explica los Mock-ups del Landing Page, tanto en su versión para Desktop Web Browser como Mobile Web Browser. En la propuesta y la 
explicación debe evidenciarse la aplicación de los principios, elementos de diseño, diseño inclusivo y arquitectura de información, así como el Design System establecido para los productos digitales.

![alt text](<assets/Landing Page Mock-up.1.png>)

## 4.4. Web Applications UX/UI Design
El diseño de experiencia de usuario (UX) y de interfaz de usuario (UI) en aplicaciones web consiste en construir una experiencia digital que resulte clara, práctica y agradable para las personas que la utilizan. La UX se enfoca en identificar las necesidades y expectativas de los usuarios, diseñando flujos de navegación y estructuras de información que hagan más sencilla la interacción. En cambio, la UI aborda la parte visual de la aplicación, como el estilo de los botones, menús y la organización del contenido en pantalla. Cuando ambos enfoques se integran de forma adecuada, se logra un equilibrio entre estética y usabilidad, generando así una experiencia atractiva, funcional y memorable para los usuarios.

### 4.4.1. Web Applications Wireframes
**Web applications wireframes desktop**

![alt text](<assets/web applications wireframe desktop 1.png>)

![alt text](<assets/web applications wireframe desktop 2.png>)

**Web applications wireframes mobile**

![alt text](<assets/web applications wireframe mobile 1.png>)

![alt text](<assets/web applications wireframe mobile 2.png>)

### 4.4.2. Web Applications Wireflow Diagrams
Los diagramas de wireflow para aplicaciones web son representaciones visuales que muestran tanto la navegación como la estructura de una aplicación. Estos combinan características de los wireframes y de los diagramas de flujo, ofreciendo una visión clara de cómo los usuarios se desplazan por la plataforma y de qué manera interactúan con sus diferentes funciones. Su utilidad radica en detectar posibles dificultades de usabilidad y en asegurar que la experiencia del usuario sea consistente y eficiente.
En el caso de PuntoSabor, el diagrama de wireflow ilustra los recorridos principales de sus dos tipos de usuarios: el descubridor gastronómico y el dueño de restaurante. Incluye procesos clave como la autenticación, la exploración de categorías de comida, la búsqueda de huariques cercanos, el acceso a promociones, la gestión de planes de membresía, así como funciones para editar el perfil y acceder al soporte.

![alt text](<assets/Wireflow Diagrams.png>)

### 4.4.2. Web Applications Mock-ups
**Web applications Mock-ups desktop**

![alt text](<assets/Web applications Mock-ups desktop.1.png>)

![alt text](<assets/Web applications Mock-ups desktop.2.png>)

**Web applications Mock-ups mobile**

![alt text](<assets/Web applications Mock-ups mobile.1.png>)

![alt text](<assets/Web applications Mock-ups mobile.2.png>)

### 4.4.3. Web Applications User Flow Diagrams
El User Flow Diagram es una representación gráfica del recorrido que sigue un usuario al interactuar con una aplicación o sitio web. En él se detalla la secuencia de acciones necesarias para cumplir una tarea concreta, lo que permite detectar posibles dificultades en el proceso y mejorar la experiencia del usuario.

Leyenda:

![alt text](<assets/Leyenda - Web Applications User Flow Diagrams.png>)

Flujo de usuario:
Empieza con el usuario ingresando la página de inicio de PuntoSabor. Aqui determina  si es "Explorador Gastronómico" o "Dueño de Restaurante"

![alt text](<assets/Web Applications User Flow Diagrams.1.png>)

Flujo de Explorador Gastronómico:El usuario con rol de Explorador Gastronómico puede acceder a un buscador para obtener información sobre huariques. En caso de no realizar una búsqueda, podrá visualizar sugerencias. 

![alt text](<assets/Flujo de explorador.png>)

Flujo de Dueño de Restaurante: El usuario con rol de Dueño de Restaurante puede acceder a su perfil, consultar y modificar su plan, así como gestionar la lista de huariques, productos y promociones. Además, tiene la opción de actualizar su perfil añadiendo o editando un huarique: cambiar el nombre, actualizar la foto, modificar la ubicación y gestionar los productos y promociones. También podrá programar una sesión de retroalimentación en una fecha determinada.

![alt text](<assets/Flujo de Dueño.png>)

![alt text](<assets/Flujo de Dueño.2.png>)

Vista general del flujo de usuario:

![alt text](<assets/Flujo de Usuario General.png>)

## 4.5. Web Applications Prototyping
Prototipo de la aplicación web PuntoSabor en figma:
**https://www.figma.com/design/lT88eEZFP7G86QwYXq59Lc/PuntoSabor?node-id=0-1&p=f&t=NTWZ6fdPzB6mKTpe-0**

## 4.6. Domain-Driven Software Architecture
La arquitectura de software orientada al dominio es una metodología de diseño que organiza la estructura del sistema a partir de los conceptos y procesos esenciales de un área específica. Este enfoque permite construir aplicaciones alineadas con las necesidades reales y la lógica del negocio, facilitando tanto la incorporación de funcionalidades concretas como la adaptación ante cambios en el entorno. En PuntoSabor, aplicamos esta arquitectura para estructurar la plataforma de manera clara y escalable, lo que garantiza el desarrollo de una aplicación robusta, flexible y sencilla de mantener.


 ### 4.6.1. Design-Level EventStorming.

# Design Level Event Storming — PuntoSabor  

En este apartado se detalla los elementos clave del dominio de *PuntoSabor* a partir del big event storming, definiendo Aggregates, Commands, Domain Events, Policies, Invariantes y Read Models.  


## 1. Explorer Discovery  

### Aggregate  
- `SearchSession`  

### Commands  
- `StartSearchSession(userId, zoneId?, q?, filters)`  
- `ApplySearchFilter(sessionId, filters)`  
- `OpenMap(sessionId, viewport)`  
- `SelectHuarique(sessionId, huariqueId)`  
- `ViewHuariqueDetail(userId, huariqueId)`  

### Domain Events  
- `SearchSessionStarted`  
- `SearchPerformed`  
- `MapDisplayed`  
- `HuariqueSelected`  
- `HuariqueDetailViewed`  

### Policies  
- `AutoSearch`  
- `RankingPolicy`  

### Invariantes  
- Solo se listan huariques con estado `PUBLISHED` y `ACTIVE`.  

### Read Models  
- `SearchResultsView`  
- `HuariqueMiniCard`  


## 2. User Preferences  

### Aggregate  
- `UserPreferences`  

### Commands  
- `SetPreferredLanguage(userId, lang)`  
- `SetDiscoveryPreferences(userId, priceRange?, foodTypes?, zone?)`  
- `SavePrivacyConsent(userId?, anonymousId, scopes)`  

### Domain Events  
- `PreferredLanguageChanged`  
- `DiscoveryPreferencesSaved`  
- `PrivacyConsentRecorded`  

### Read Models  
- `UserPrefView`  


## 3. Business Listing  

### Aggregate  
- `BusinessListing`  

### Commands  
- `CreateListing(ownerId, basicInfo)`  
- `UploadListingImage(huariqueId, imageMeta)`  
- `UpdateListingFields(huariqueId, fields)`  
- `GeocodeAddress(huariqueId, address)`  
- `PublishListing(huariqueId)`  

### Domain Events  
- `ListingCreated`  
- `ListingImageUploaded`  
- `ListingFieldsUpdated`  
- `AddressGeocoded`  
- `ListingPublished`  

### Policies  
- `RunListingValidations`  

### Invariantes  
- No se publica un huarique sin nombre, dirección, geolocalización y dueño asignado.  

### Read Models  
- `OwnerListingDashboard`  
- `PublicListingView`  


## 4. Subscription & Billing  

### Aggregate  
- `BusinessSubscription`  

### Commands  
- `SelectPlan(huariqueId, planId)`  
- `AcceptPlanTerms(huariqueId, termsVersion)`  
- `ValidateBusinessEligibility(huariqueId)`  
- `ActivatePlan(huariqueId, paymentId)`  
- `ChangePlan(huariqueId, newPlanId)`  

### Domain Events  
- `PlanSelected`  
- `PlanTermsAccepted`  
- `BusinessEligibilityValidated`  
- `PlanActivated`  
- `PlanChanged`  

### Policies  
- `EnablePromotionCapabilities`  
- `DisablePromotionCapabilities`  

### Invariantes  
- Solo un `PlanActivated` habilita la creación de promociones.  

### Read Models  
- `BillingHistory`  
- `PlanStatusView`  

## 5. Promotion  

### Aggregate  
- `Promotion`  

### Commands  
- `CreatePromotion(huariqueId, content)`  
- `SetPromotionTargeting(promoId, zones?, tags?, audience?)`  
- `SetPromotionSchedule(promoId, startAt, endAt)`  
- `PublishPromotion(promoId)`  
- `UnpublishPromotion(promoId, reason)`  

### Domain Events  
- `PromotionCreated`  
- `PromotionTargetingSet`  
- `PromotionScheduleSet`  
- `PromotionPublished`  
- `PromotionUnpublished`  

### Policies  
- `IndexPromotionForDiscovery`  
- `SchedulePublish/Unpublish`  

### Invariantes  
- Solo se publican promociones si el huarique tiene `ListingPublished` y `PlanActivated`.  

### Read Models  
- `ZonePromotionsView`  
- `OwnerPromotionsDashboard`  


## 6. Contact & Support  

### Aggregate  
- `SupportRequest`  

### Commands  
- `SubmitContactForm(userId?, payload)`  
- `OpenDirections(userId?, huariqueId)`  
- `AcceptPrivacyConsent(subjectId, scopes)`  

### Domain Events  
- `ContactFormSubmitted`  
- `DirectionsOpened`  
- `PrivacyConsentRecorded`  

### Read Models  
- `SupportInboxView`  
- `ConsentLedger`  


## 7. Flujos clave  

### Publicar un Huarique  
1. `CreateListing` → `ListingCreated`  
2. `UpdateListingFields` → `ListingFieldsUpdated`  
3. `GeocodeAddress` → `AddressGeocoded` → (policy) `RunListingValidations` → `ListingValidationsPassed`  
4. `PublishListing` → `ListingPublished` → actualiza `PublicListingView`  

### Crear y Publicar una Promoción  
1. `CreatePromotion` → `PromotionCreated`  
2. `SetPromotionTargeting` → `PromotionTargetingSet`  
3. `SetPromotionSchedule` → `PromotionScheduleSet` → (policy) `SchedulePublish/Unpublish`  
4. `PublishPromotion` → `PromotionPublished` → (policy) `IndexPromotionForDiscovery` → actualiza `ZonePromotionsView`  

## 8. Invariantes transversales  

- Un huarique solo puede publicarse si cumple validaciones y tiene geolocalización.  
- Una promoción solo puede publicarse si existe un plan activo y el huarique está publicado.  
- Los resultados de búsqueda nunca incluyen huariques inactivos o no publicados.  
- Los comandos deben ser idempotentes para evitar duplicación de eventos.  


### 4.6.2. Software Architecture Context Diagram
**Elementos:**
- PuntoSabor: Principal para los usuarios
- Usurio - Descubridor gastronómico: Encuentra huariques poco conocidos 
- Usuario - Dueño de restaurante: Publica su huarique y más cosas según su plan de membresía 

![alt text](assets/structurizr-punto_context.png)

### 4.6.3. Software Architecture Container Diagrams
**Elementos:**
- Aplicación web: Frontend donde los usuarios interactúan con la aplicación 
Se usará tecnología: Vue.js
- Servidor de aplicaciones: Backend que maneja los planes de membresía de los usuarios.
Se usará tecnología: C#
- Base de datos: Almacena los datos de los usuarios, sus planes y cosas que realizan en la aplicación.
Se usara tecnología: SQL  server 

![alt text](assets/structurizr-c2_puntosabor.png)

### 4.6.4. Software Architecture Components Diagrams

API Service — Components

![alt text](<assets/structurizr-c3_api (1).png>)

Categories Service — Components

![alt text](assets/structurizr-c3_categories.png)

Zones Service — Components

![alt text](assets/structurizr-c3_zones.png)

Promotions Service — Components

![alt text](assets/structurizr-c3_promotions.png)

Plans Service — Components

![alt text](assets/structurizr-c3_plans.png)

Profile Service — Components

![alt text](assets/structurizr-c3_profile.png)

Auth Service — Components

![alt text](assets/structurizr-c3_auth.png)

Contact Service — Components

![alt text](assets/structurizr-c3_contact.png)

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

```mermaid
classDiagram
direction TB

%% =================== TOP (APPLICATION) ===================
class HuariquesApplicationService {
  +getHuarique(id: UUID) HuariqueDTO
  +createReview(review: ReviewDTO) void
}
HuariquesApplicationService --> ReviewService
HuariquesApplicationService --> IHuariqueRepository
HuariquesApplicationService --> HuariqueDTO
HuariquesApplicationService --> ReviewDTO

%% =================== DTOs (SIDES) ===================
class HuariqueDTO {
  +UUID id
  +string name
  +string description
  +string category
  +float averageRating
  +string status
  +string address
  +string location
}
class ReviewDTO {
  +UUID userId
  +UUID huariqueId
  +int rating /*1..5*/
  +string comment
  +datetime date
}

%% =================== DOMAIN SERVICE (LEFT) ===================
class ReviewService {
  +publish(huariqueId: UUID, rating: int, comment: string) void
}
ReviewService --> IReviewRepository
ReviewService --> Huarique

%% =================== REPOSITORIES (RIGHT) ===================
class IHuariqueRepository {
  +getById(id: UUID) Huarique
  +save(h: Huarique) void
}
class IReviewRepository {
  +forHuarique(id: UUID) List_Review
  +save(r: Review) void
}
class HuariqueRepositorySQL {
  +getById(id: UUID) Huarique
  +save(h: Huarique) void
}
HuariqueRepositorySQL ..|> IHuariqueRepository

%% =================== AGGREGATE (CENTER) ===================
class Huarique {
  +UUID id
  +string name
  +Description description
  +Address address
  +Coordinates location
  +float averageRating
  +OpeningStatus status
  +addReview(r: Review) void
}
Huarique "1" --> "0..*" Review
Huarique --> Category
Huarique --> Description
Huarique --> Address
Huarique --> Coordinates
Huarique --> OpeningStatus

%% =================== ENTITIES / VALUE OBJECTS (BOTTOM) ===================
class Review {
  +UUID id
  +Rating rating
  +string comment
  +datetime date
}
Review --> Rating

class Category { +UUID id; +string name }
class Description { -string value }
class Address { -string line1; -string district; -string city }
class Coordinates { -float lat; -float lng }
class Rating { -int value /*1..5*/ }

class OpeningStatus {
  <<enumeration>>
  +OPEN
  +CLOSED
  +UNKNOWN
  +TEMPORARILY_CLOSED
}

```

### 4.7.2. Class Dictionary
| Class                         | Definition                                                                                                                |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| `User`                        | Entity representing the platform user (name, email) who creates reviews and manages favorites.                            |
| `Huarique`                    | Aggregate root: a food venue with name, `Description`, `Address`, `Coordinates`, average rating, and `OpeningStatus`. |
| `Category`                    | Lightweight entity that classifies huariques by type/style.                                                               |
| `Review`                      | Entity that models a review on a huarique, with a `Rating` (1..5), comment, and date.                                     |
| `Favorite`                    | User–huarique relationship to bookmark huariques.                                                                         |
| `MembershipPlan`              | Commercial plan available to a huarique (name, benefits, monthly price).                                                  |
| `Subscription`                | Link between huarique and plan; stores dates and `SubscriptionStatus`.                                                    |
| `Description`                 | Value Object encapsulating the huarique’s validated description.                                                      |
| `Address`                     | Value Object with line, district, and city; prevents invalid addresses.                                               |
| `Coordinates`                 | Value Object with valid latitude/longitude for geolocation.                                                           |
| `Rating`                      | Value Object (integer 1..5) ensuring valid ratings.                                                                   |
| `OpeningStatus`               | VO / Enumeration representing the venue’s operating status (`OPEN`, `CLOSED`, `UNKNOWN`, `TEMPORARILY_CLOSED`).       |
| `SubscriptionStatus`          | VO / Enumeration for subscription lifecycle (`ACTIVE`, `CANCELED`, `EXPIRED`).                                        |
| `IHuariqueRepository`         | Port for `Huarique` persistence (get by id, search by filters, save).                                                 |
| `IReviewRepository`           | Port for `Review` persistence (list by huarique, save).                                                               |
| `ISubscriptionRepository`     | Port for `Subscription` persistence (get, save).                                                                      |
| `HuariqueRepositorySQL`       | Adapter implementing `IHuariqueRepository` using SQL storage.                                                         |
| `SearchService`               | Domain service to find huariques by filters.                                                                          |
| `ReviewService`               | Domain service to publish/moderate reviews applying business rules.                                                   |
| `MembershipService`           | Domain service that manages subscription lifecycle.                                                                   |
| `HuariquesApplicationService` | Application service that orchestrates use cases (get huarique, create review) and coordinates repositories/services.  |

## 4.8. Database Design
### 4.8.1. Database Diagram

```mermaid
erDiagram
  %% ================= RELATIONSHIPS =================
  Users            ||--o{ Reviews           : "writes"
  Users            ||--o{ Favorites         : "bookmarks"
  Huariques        ||--o{ Reviews           : "reviewed in"
  Huariques        ||--o{ Favorites         : "bookmarked"
  Categories       ||--o{ Huariques         : "classifies"
  Huariques        ||--o{ Huarique_Photos   : "has"
  Membership_Plans ||--o{ Subscriptions     : "offered to"
  Huariques        ||--o{ Subscriptions     : "subscribes"
  Users            ||--o{ Subscriptions     : "created by"
  Users            ||--o{ Audit_Logs        : "logs"

  %% ================= TABLES =================

  Users {
      uuid user_id PK
      string name
      string email UK
      enum role "admin, user"
      timestamp created_at
      timestamp updated_at
  }

  Huariques {
      uuid huarique_id PK
      string name
      text description
      string address_line
      string district
      string city
      float lat
      float lng
      enum opening_status "OPEN, CLOSED, UNKNOWN, TEMPORARILY_CLOSED"
      decimal average_rating
      int category_id FK
      timestamp created_at
      timestamp updated_at
  }

  Categories {
      int category_id PK
      string name
      string description
      timestamp created_at
  }

  Reviews {
      uuid review_id PK
      uuid huarique_id FK
      uuid user_id FK
      int rating "1..5"
      string comment
      datetime review_date
      timestamp created_at
  }

  Favorites {
      uuid user_id PK,FK
      uuid huarique_id PK,FK
      timestamp created_at
  }

  Membership_Plans {
      uuid plan_id PK
      string name
      text description
      decimal monthly_price
      timestamp created_at
  }

  Subscriptions {
      uuid subscription_id PK
      uuid huarique_id FK
      uuid plan_id FK
      uuid user_id FK        "creator/owner"
      date start_date
      date end_date
      enum status "ACTIVE, CANCELED, EXPIRED"
      timestamp created_at
      timestamp updated_at
  }

  Huarique_Photos {
      uuid photo_id PK
      uuid huarique_id FK
      string url
      timestamp created_at
  }

  Audit_Logs {
      int audit_id PK
      uuid user_id FK
      string entity_type
      uuid entity_id
      string action
      json details
      timestamp audit_date
  }

```
# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

En esta sección se detalla cómo se implementa, organiza y publica PuntoSabor en su estado actual (sitio estático con HTML, CSS y JavaScript). No se utiliza aún backend ni base de datos; la publicación se realiza con GitHub Pages. El objetivo es mantener la consistencia del desarrollo y dejar preparado el terreno para futuras iteraciones.

---

### 5.1.1. Software Development Environment Configuration

**Implementado (estado actual)**
- Frontend (Landing + Páginas): HTML5, CSS3, JavaScript (vanilla).
- Responsive Web Design: únicamente con CSS (Flexbox/Grid + media queries).
- Editor: Visual Studio Code (o editor de preferencia).
- Control de versiones y colaboración: Git + GitHub.

**Estructura de páginas (referencial)**
- `index.html` (inicio / home)
- `inicio.html`
- `planes.html`
- `contacto.html`
- `perfil.html`
- `promos.html`
- `zonas.html`
- `css/` (hojas de estilo)
- `img/` u otra carpeta de recursos

> Nota: En esta entrega no se ha implementado servidor, API ni base de datos.

---

### 5.1.2. Source Code Management

**Repositorio GitHub (actual)**
- `puntosabor-landing` (código estático de la web).

**Flujo de trabajo (GitFlow ligero)**
- **Ramas principales**
  - `main`: versión estable publicada.
  - `develop`: integración previa a publicación.
- **Ramas de apoyo**
  - `feature/*`: nuevas secciones o mejoras (p. ej., `feature/US01-landing-planes`).
  - `hotfix/*`: correcciones urgentes sobre `main`.

**Versionado Semántico**
- **X (major)**: cambios incompatibles (reestructura global de navegación/archivos).
- **Y (minor)**: nuevas secciones o funcionalidades compatibles.
- **Z (patch)**: correcciones menores (estilos, textos, enlaces).
- Ejemplos: `v1.0`, `v1.1`.

**Conventional Commits**

Formato general:
```
<type>[scope]: <descripción>
```
Ejemplos:
- `feat: agregar sección planes con cards responsivas`
- `fix(css): corregir overflow en navbar móvil`
- `docs: actualizar pasos de despliegue en README`

---

### 5.1.3. Source Code Style Guide & Conventions

**HTML**
- Estructura semántica: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.
- Imágenes siempre con `alt`.
- Enlaces relativos y consistentes entre páginas.
- Scripts JS al final del `body` cuando corresponda.

**CSS**
- Uso de variables CSS (`:root { --color... }`) para colores y espaciados.
- Convención de clases en kebab-case (ej.: `.hero-title`, `.card-grid`).
- Layout con Flexbox y/o Grid.
- Media queries para puntos de quiebre (ej.: 960px, 760px, 560px).
- Estados y accesibilidad: `:hover`, `:focus-visible`, contraste adecuado.

**JavaScript**
- `const` / `let` (evitar `var`), funciones pequeñas y claras.
- Separar lógica de interacción del DOM cuando sea posible.
- Uso moderado de `localStorage` solo para preferencias/estado del cliente (si aplica).

---

### 5.1.4. Software Deployment Configuration

**Despliegue actual — GitHub Pages (Landing + Páginas estáticas)**

**Pasos:**
1. Subir el código al repositorio (por ejemplo `puntosabor-landing`) en la rama `main`.
2. En GitHub: ir a Settings → Pages.
3. En Build and deployment, seleccionar Deploy from a branch.
4. Elegir Branch: `main` y Folder: `/ (root)`. Guardar.
5. Esperar a que GitHub procese el sitio y obtener la URL pública, por ejemplo:
```
https://<usuario-o-organizacion>.github.io/puntosabor-landing/
```

Landing Page de PuntoSabor:

https://1asi0730-2520-7432-g3-fijasdev.github.io/PuntoSabor-LandingPage/ 

**Validación post-despliegue**
- Probar navegación entre páginas: `index.html`, `planes.html`, `contacto.html`, `perfil.html`, `promos.html`, `zonas.html`.
- Verificar rutas relativas a hojas de estilo, imágenes y scripts.
- Comprobar responsive en móvil/escritorio (inspector del navegador).
- Revisar enlaces externos y formularios (si existieran) que no dependan de backend.

**(Futuro, cuando se añada backend/BD)**
- Mantener frontend estático (o migrar a SPA) y publicar API por separado.
- Añadir CI/CD con GitHub Actions y variables/secretos necesarios.
- Documentar endpoints con Swagger/OpenAPI y pruebas con Postman.


---
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
| #                                    | Sprint 1                                                                                                                                                          |
| ------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Sprint Planning Background**       |                                                                                                                                                                   |
| **Date**                             | 2025-04-18                                                                                                                                                        |
| **Time**                             | 10:00PM – 11:00PM                                                                                                                                                 |
| **Location**                         | Meet                                                                                                                                                              |
| **Prepared by**                      | Delgado Carrasco, Schneider; Lopez Goitia, Carlos Alberto                                                                                                         |
| **Attendees**                        | Delgado Carrasco, Schneider; Lopez Goitia, Carlos Alberto; Tumi Oliden, Manuel Ignacio; Vega Coronado, Fabricio Samir; Villanueva Andrade, Ysaac Ligorio          |
| **Sprint n-1 Review Summary**        | No hubo sprint anterior                                                                                                                                           |
| **Sprint n-1 Retrospective Summary** | No hubo sprint anterior                                                                                                                                           |
| **Sprint Goal & User Stories**       | **Goal**: Create a clear, functional **landing page** (benefits, CTA, testimonials, and contact form), laying the groundwork for future integrations. |
| **Sprint 1 velocity**                | 10 horas                                                                                                                                                          |
| **Sum of Story Points**              | 10                                                                                                                                                                |

#### 5.2.1.2. Aspect Leaders and Collaborators
| Team member                       | GitHub username | Beneficios | Planes | Testimonios | Responsive | Soporte |
| --------------------------------- | --------------: | :--------: | :----: | :---------: | :--------: | :-----: |
| Delgado Carrasco, Schneider       |     schneiderdc |    **C**   |    L   |      C      |      C     |    L    |
| Lopez Goitia, Carlos Alberto      |    CarlosAlb101 |      L     |  **C** |      C      |      C     |    C    |
| Tumi Oliden, Manuel Ignacio       |  ManuelTumi2224 |      C     |    C   |    **L**    |      C     |    C    |
| Vega Coronado, Fabricio Samir     |      Fabricio1v |      C     |    L   |      C      |    **C**   |    C    |
| Villanueva Andrade, Ysaac Ligorio | YsaacVillanueva |      L     |    C   |      C      |      C     |  **C**  |

#### 5.2.1.3. Sprint Backlog 1
| Sprint # | Sprint 1 |
| -------- | -------- |

| #  | ID   | Title                  | User Story                                                                                                     | Story Points | Sprint 1 Status |
|----|------|------------------------|---------------------------------------------------------------------------------------------------------------|-------------:|-----------------|
| 1  | US01 | Advanced search        | As a user, I can filter huariques by location, cuisine type, and price for an efficient search.              | 5 | Partial |
| 2  | US02 | Map view               | As a user, I want to see the huariques’ locations on a map to make visiting easier.                          | 3 | Done |
| 4  | US04 | Register new huarique  | As an owner, I can register a new huarique with basic information to appear on the platform.                 | 5 | Done |
| 6  | US06 | Media management       | As an owner, I can upload photos and videos to showcase my huarique.                                         | 3 | Done |
| 9  | US09 | Landing benefits       | As a visitor, I can see PuntoSabor’s advantages on the landing page.                                         | 2 | Done |
| 10 | US10 | Contact form           | As a visitor, I can send inquiries through a form.                                                            | 2 | Done |
| 26 | US26 | Featured promotions    | As a Pro owner, I want to publish promotions that appear highlighted in the listings.                         | 3 | Partial |

#### 5.2.1.4. Development Evidence for Sprint Review
Se versionó todo el trabajo (copy, diseño de secciones, CTA, testimonios y formulario con validaciones) en Git y se crearon ramas por feature con sus pull requests. Se adjuntaron capturas de antes/después en los issues correspondientes y se documentó cada componente en el repositorio.
#### 5.2.1.5. Execution Evidence for Sprint Review
Durante el Sprint se completaron las tareas del backlog de la landing page. Se redactó contenido, se diseñaron las secciones visuales, se añadió un CTA persistente y se implementó el formulario con validaciones. Se mostró una demo navegable en la review para validar experiencia y copy.
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
Se generó documentación en Markdown describiendo estructura, componentes UI, flujos de interacción del formulario (y validaciones), y criterios de accesibilidad/responsividad. Esto alinea al equipo para los próximos sprints donde se integrarán servicios backend.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
Se desplegó la landing page en GitHub Pages (o hosting equivalente) con el contenido del Sprint: beneficios, testimonios, CTA y formulario. Se compartió el enlace para revisión, se registraron observaciones en issues y se planificaron ajustes menores visuales para el siguiente sprint.
#### 5.2.1.8. Team Collaboration Insights during Sprint  
El equipo trabajó de forma colaborativa con comunicación fluida (Meet/Discord). Se usaron tableros Kanban para seguimiento y ramas por feature para aislar cambios. Todos asumieron responsabilidades claras y se apoyaron mutuamente en revisiones, lo que permitió cumplir el objetivo del sprint sin bloqueos.

### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2
Mostramos en este apartado el cuadro correspondiente al Sprint Planning 2, donde rescatamos los aspectos más importantes del Sprint Planning Meeting.

<div>
   <table>
     <thead>
       <tr>
         <th># Número</th>
         <th>Sprint 2</th>
       </tr>
       <tr>
         <th colspan=2>Sprint Planning Background</th>
       </tr>
     </thead>
     <tr align='center'>
       <td> Date </td>
       <td> 2025-10-01 </td>
     </tr>
     <tr>
       <td>Time</td>
       <td> 11:45PAM </td>
     </tr>
     <tr>
       <td>Location</td>
       <td> Remote mode through the GitHub platform </td>
     </tr>
     <tr>
       <td>Prepared by</td>
       <td> Vega Coronado, Fabricio Samir </td>
     </tr>
     <tr>
       <td>Attendees</td>
       <td> Delgado Carrasco, Schneider <br> Lopez Goitia, Carlos Alberto <br> Tumi Oliden, Manuel Ignacio <br> Vega Coronado, Fabricio Samir	<br> Villanueva Andrade, Ysaac Ligorio </td>
     </tr>
     <tr>
       <td>Sprint n-1 Review Summary</td>
       <td> In Sprint 1, the static landing page was created and deployed on Github Pages</td>
     </tr>
     <tr>
       <td>Sprint n-1 Retrospective Summary</td>
       <td>Our team did a great job overall, but there are several aspects that could be improved. We should have been more organized from the beginning to avoid some issues later on. It would also have helped to maintain better communication throughout the development of the project to prevent misunderstandings among team members.</td>
     </tr>
      <tr>
        <td colspan="2"><b>Sprint Goal & User Stories</b></td>
      </tr>
      <tr>
        <td>Sprint 2 Goal</td>
        <td> Implement the initial functionalities of the PuntoSabor web system, focusing on advanced search, displaying huariques on a map, and registering new huariques by owners, integrating the first simulated backend services. </td>
      </tr>
      <tr>
        <td>Sprint 2 velocity</td>
        <td> 12 </td>
      </tr>
      <tr>
        <td>Sum of Story Points</td>
        <td> 21 Story Points</td>
      </tr>

   </table>
</div>

#### 5.2.2.2. Aspect Leaders and Collaborators


Below are the members of the FijasDev team with their respective leadership (L) and collaboration (C) roles assigned for the Sprint 2 tasks.

| **Team Member (Last Name, First Name)** | **GitHub Username** | **Advanced Search** | **Map View** | **Register Huarique** | **Update Information** | **API Services** |
|----------------------------------------|----------------------|----------------------|---------------|------------------------|-------------------------|------------------|
| **Delgado Carrasco, Schneider** | schneiderdc |  |  | **C** | **L** |  |
| **Lopez Goitia, Carlos Alberto** | CarlosAlb101 | **L** |  | **C** | **C** |  |
| **Tumi Oliden, Manuel Ignacio** | ManuelTumi2224 |  | **C** | **L** | **C** |  |
| **Vega Coronado, Fabricio Samir** | Fabricio1v | **C** | **C** |  |  | **L** |
| **Villanueva Andrade, Ysaac Ligorio** | YsaacVillanueva |  |  |  | **C** | **C** |

#### 5.2.2.3. Sprint Backlog 2

Nuestro objetivo principal sprint 2 es realizar la primera version de la aplicacion web, como tambien una segunda versión mejorada del Landing Page, implementando las vistas de las user stories de nuestro proyecto.

![alt text](assets/SprintBacklog2.jpg)

link: https://trello.com/invite/b/68e71048a816b1be49c8f045/ATTIdc7cb6e3dc20feb0c795a893e2ed2e5c21DF59CA/puntosabor-app

#### 5.2.2.4. Development Evidence for Sprint Review

Commits:
![alt text](assets/Commits.jpg)

**Commits (convencionales, ejemplos):**
- `feat(search): add combined filters and empty state`
- `feat(map): show markers + popups from API`
- `feat(huariques): create/edit forms with validation`
- `docs(api): mock endpoints for search and crud`
- `fix(ui): card grid wrap and responsive spacing`

Repository	Branch	Commit Id	Commit Messaage	Commit Message Body	Commited on

#### 5.2.2.5. Execution Evidence for Sprint Review

Lo que se logró para este Sprint 2 es el peliegue de la primera versión de la aplicación web. En esta logramos desarrollar el toolbar, footer, la vista principal, categorias, reseñas, mapa, promociones y planes. Esto fue realizado mediante la aplicacion webStorm y su complemento de git, con esto cada integrante pudo realizar cambios y versiones en sus ramas para luego mandarlas a la rama principal y no tener ningun inconveniente. A continuación se mostrarán las evidencias de ejecución.

Home:
![alt text](assets/homeFRONT.jpg)

Iniciar Sesion:
![alt text](assets/LOGINFRONTjpg.jpg)

Registrar:
![alt text](assets/signFRONT.jpg)

Registrar Huarique:
![alt text](assets/registrarHuariqueFRONT.jpg)

Categorias:
![alt text](assets/categoriasFRONT.jpg)

Promociones:
![alt text](assets/promosFRONT.jpg)

Plans:
![alt text](assets/plansFRONT.jpg)

Mapa:
![alt text](assets/mapaFRONT.jpg)

#### 5.2.2.6. Services Documentation Evidence for Sprint Review
En esta sección se presenta la lista de los endpoints documentados. A continuación se presenta el proyecto que muestra el despliegue de la web.

db.json:
![alt text](assets/service-db.json.jpg)

Deployment:
![alt text](assets/evidenciaDeploy.jpg)

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

Link hacia el deployment:
https://puntosabor.netlify.app/

Home:
![alt text](assets/homeDeploy.jpg)

Categoria:
![alt text](assets/categoriasDeploy.jpg)

Promos:
![alt text](assets/promosDeploy.jpg)

Plans:
![alt text](assets/plansDeploy.jpg)

Contactos:
![alt text](assets/contactosDeploy.jpg)

Map:
![alt text](assets/mapaDeploy.jpg)

Rol:
![alt text](assets/rolDeploy.jpg)

Login:
![alt text](assets/loginDeploy.jpg)

Registrar:
![alt text](assets/registerDeploy.jpg)

Resgistrar Huarique:
![alt text](assets/registrarHuariqueDeploy.jpg)



#### 5.2.2.8. Team Collaboration Insights during Sprint
El equipo mantuvo una colaboración constante y una comunicación efectiva a través de plataformas como Meet y Discord. Se implementaron tableros Kanban para el control del progreso y ramas por funcionalidad para gestionar los cambios de forma ordenada. Cada integrante asumió responsabilidades definidas y brindó apoyo en las revisiones, lo que facilitó alcanzar las metas del sprint sin contratiempos.

![alt text](assets/UsersActivar.jpg)

![alt text](assets/ActividadUsers.jpg)


# 5.2.3. Sprint 3

## 5.2.3.1. Sprint Planning 3

Mostramos en este apartado el cuadro correspondiente al Sprint Planning 3 para nuestro startup PuntoSabor, donde se registran los aspectos más importantes acordados durante la reunión de planificación del equipo FijasDev.

<div>
 <table> 
 <thead> 
 <tr> 
 <th># Número</th> <th>Sprint 3</th> 
 </tr> 
 <tr> <th colspan=2>Sprint Planning Background</th> 
 </tr> 
 </thead>
 <tr align='center'>
   <td>Date</td>
   <td>09-11-2025</td>
 </tr>

 <tr>
   <td>Time</td>
   <td>12:25 PM</td>
 </tr>

 <tr>
   <td>Location</td>
   <td>Remote mode through GitHub, Discord & Trello</td>
 </tr>

 <tr>
   <td>Prepared by</td>
   <td> Vega Coronado, Fabricio Samir </td>
 </tr>

 <tr>
   <td>Attendees</td>
   <td>
     Delgado Carrasco, Schneider <br>
     Lopez Goitia, Carlos Alberto <br>
     Tumi Oliden, Manuel Ignacio <br>
     Vega Coronado, Fabricio Samir <br>
     Villanueva Andrade, Ysaac Ligorio
   </td>
 </tr>

 <tr>
   <td>Sprint n-2 Review Summary</td>
   <td>
   Durante la revisión del Sprint 2 se validó la primera versión funcional de la Web Application de PuntoSabor.  
   Se implementaron las bases del enrutamiento, los primeros módulos visuales, el prototipo final de la landing page,  
   y se integraron servicios simulados mediante JSON Server.  
   Se corrigieron problemas de estilos y se reforzó la documentación de arquitectura solicitada por el profesor.
   </td>
 </tr>

 <tr>
   <td>Sprint n-1 Retrospective Summary</td>
   <td>
   El equipo acordó mejorar la consistencia en la división de tareas, mantener una comunicación más frecuente dentro del repositorio y centralizar los avances en el tablero de Trello.  
   También se decidió estandarizar los commits y reforzar la revisión cruzada de PRs.
   </td>
 </tr>

 <tr>
    <td colspan="2"><b>Sprint Goal & User Stories</b></td>
 </tr>

 <tr>
    <td>Sprint 3 Goal</td>
    <td>
        Implementar las funcionalidades clave para consolidar la segunda versión funcional de PuntoSabor,  
        incluyendo reseñas, favoritos, membresías, gestión multimedia, notificaciones y módulos asociados  
        a la interacción con huariques. Además se dará a cabo la implementacion inicial del backend. 
    </td>
 </tr>

 <tr>
    <td>Sprint 3 velocity</td>
    <td>12</td>
 </tr>

 <tr>
    <td>Sum of Story Points</td>
    <td>44 Story Points</td>
 </tr>

</table> 
</div>

## 5.2.3.2. Aspect Leaders and Collaborators

A continuación se presenta la matriz Leadership-and-Collaboration (LACX) correspondiente al Sprint 3.
En ella se define quién lidera cada aspecto del desarrollo y quiénes participan como colaboradores, considerando los módulos del producto PuntoSabor.

| Team Member (Last Name, First Name) | GitHub Username | Notifications              | MONITORING              | PREFERENCES         | ANALYTICS                 | SUBSCRIPTIONS               |
|------------------------------------|------------------|----------------------------|-------------------------|---------------------|---------------------------|-----------------------------|
| Delgado Carrasco, Schneider        | schneiderdc      | C                          | L                       | C                   | C                         | C                           |
| Lopez Goitia, Carlos Alberto       | CarlosAlb101     | C                          | C                       | C                   | L                         | C                           |
| Tumi Oliden, Manuel Ignacio        | ManuelTumi2224   | C                          | C                       | C                   | C                         | L                           |
| Vega Coronado, Fabricio Samir      | Fabricio1v       | L                          | C                       | C                   | C                         | C                           |
| Villanueva Andrade, Ysaac Ligorio  | YsaacVillanueva  | C                          | C                       | L                   | C                         | C                           |


## 5.2.3.3. Sprint Backlog 3

En este apartado se presenta el Sprint Backlog correspondiente al Sprint 3 del proyecto PuntoSabor.  
Para esta iteración, se seleccionaron únicamente las historias que aún requieren desarrollo, excluyendo aquellas que ya fueron completadas en sprints anteriores o que se encuentran marcadas como “Done”.

El objetivo del Sprint Backlog 3 es organizar y visualizar de manera clara el conjunto de funcionalidades que serán implementadas, así como su responsable asignado, nivel de complejidad y estado actual de avance. La tabla siguiente resume las User Stories pendientes de finalización durante esta iteración.

Link al tablero de Sprint 3:
https://trello.com/invite/b/68e71048a816b1be49c8f045/ATTIaa410bab4b959b3258cc6f372a477673875CBC7E/puntosabor-app 

Tareas que se realizarán en este sprint por el lado del frontend.

| User Story ID | Title | Description | Story Points | Assigned To | Status |
|---------------|--------|-------------|--------------|-------------|--------|
| **US03** | Guardar favoritos | Como usuario, puedo guardar huariques para acceder fácilmente después. | 3 | ManuelTumi2224 | To-Do |
| **US05** | Actualización de información | Como dueño, puedo modificar los datos de mi huarique para mantenerlos actualizados. | 3 | ManuelTumi2224 | In-Progress |
| **US07** | Envío de reseñas | Como usuario, puedo dejar una reseña y calificación en un huarique. | 3 | Fabricio1v | To-Do |
| **US08** | Moderación automática | Como sistema, debo detectar reseñas inapropiadas y bloquearlas. | 5 | schneiderdc | To-Do |
| **US11** | Configuración de notificaciones | Como usuario, puedo activar o desactivar notificaciones a mi preferencia. | 2 | ManuelTumi2224 | To-Do |
| **US12** | Notificación de nuevas reseñas | Como dueño, recibo alertas cuando hay reseñas nuevas en mi huarique. | 2 | Fabricio1v | To-Do |
| **US16** | Recuperación de contraseña | Como usuario, puedo recuperar mi contraseña en caso de olvido. | 2 | schneiderdc | To-Do |
| **US17** | Configuración de preferencias | Como usuario, puedo guardar mis preferencias de cocina, presupuesto y ubicación. | 3 | YsaacVillanueva | To-Do |
| **US19** | Sugerencias por ubicación | Como usuario, quiero recibir recomendaciones de huariques cercanos a mi ubicación actual. | 3 | CarlosAlb101 | To-Do |
| **US21** | Reporte de información incorrecta | Como usuario, puedo reportar si un huarique tiene datos erróneos. | 2 | CarlosAlb101 | To-Do |
| **US22** | Validación automática de estado | Como sistema, quiero mostrar si un huarique está abierto o cerrado en tiempo real. | 5 | CarlosAlb101 | To-Do |
| **US24** | Pago de suscripción | Como dueño, quiero pagar mi membresía mediante tarjeta o billetera digital de forma segura. | 5 | schneiderdc | To-Do |
| **US25** | Facturación y comprobantes | Como dueño, quiero descargar facturas mensuales de mis pagos. | 3 | YsaacVillanueva | To-Do |
| **US26** | Promociones destacadas | Como dueño Pro, quiero publicar promociones destacadas en listados. | 3 | schneiderdc | In-Progress |

## 5.2.3.4. Development Evidence for Sprint Review
A continuación se presentan los commits registrados en el repositorio de nuestro Backend, realizados durante el desarrollo del sprint 3, en el cual se implementaron las funcionalidades correspondientes.

![alt text](assets/reporte.png)

![alt text](<assets/report 2.png>)

![alt text](assets/report3.png)

## 5.2.3.5. Execution Evidence for Sprint Review
Lo que se logró en este Sprint 3 fue el despliegue de una nueva versión funcional de la aplicación web, con el flujo de registro e inicio de sesión de usuarios, y la actualización de la landing page con contenido mejorado. Además, se avanzó en la primera versión del backend, definiendo endpoints para gestionar la información principal del sistema. Todo se trabajó siguiendo la metodología GitFlow, usando ramas de feature y develop para mantener estable la rama principal.

Evidencia de la landing page

![alt text](assets/landing1.png)

![alt text](assets/landing2.png)

![alt text](assets/landing3.png)

![alt text](assets/landing4.png)

Evidencias de la aplicación web
![alt text](assets/Inicio.png)

![alt text](<assets/Sing in.png>)

![alt text](assets/Sing_up.png)

![alt text](assets/Menu_principal.png)

![alt text](assets/Membrensia.png)

## 5.2.3.6. Services Documentation Evidence for Sprint Review
En esta sección se presenta el listado de endpoints del sistema, junto con su respectiva documentación técnica y descripción de uso.

![alt text](assets/backend1.png)

## 5.2.3.7. Software Deployment Evidence for Sprint Review
Link de la landing page: https://1asi0730-2520-7432-g3-fijasdev.github.io/PuntoSabor-LandingPage

Link de la aplicación web: https://frontend-punto-sabor-git-develop-manuels-projects-cd9f9665.vercel.app/

En esta sección se presentan de forma resumida las actividades de Deployment realizadas durante este Sprint. El backend fue desplegado en la plataforma Render.

![alt text](assets/Vercel.jpeg)

![alt text](assets/backend1.png)

## 5.2.3.8. Team Collaboration Insights during Sprint
En esta sección se muestra cómo el equipo ha trabajado de forma colaborativa para completar la entrega de este sprint. Asimismo, se presentan las métricas relacionadas con el desarrollo del Backend.

![alt text](assets/report3.png)


# 5.2.4. Sprint 4

# 5.2.4.1. Sprint Planning 4

En este apartado presentamos el cuadro correspondiente al Sprint Planning 4 de nuestro startup PuntoSabor, donde se registran los puntos más relevantes acordados durante la reunión de planificación del equipo FijasDev.

<div>
 <table> 
 <thead> 
 <tr> 
 <th># Número</th> <th>Sprint 4</th> 
 </tr> 
 <tr> <th colspan=2>Sprint Planning Background</th> 
 </tr> 
 </thead>
 <tr align='center'>
   <td>Date</td>
   <td>30-11-2025</td>
 </tr>

 <tr>
   <td>Time</td>
   <td>20:00 PM</td>
 </tr>

 <tr>
   <td>Location</td>
   <td>Remote mode through GitHub, Discord & Trello</td>
 </tr>

 <tr>
   <td>Prepared by</td>
   <td> Vega Coronado, Fabricio Samir </td>
 </tr>

 <tr>
   <td>Attendees</td>
   <td>
     Delgado Carrasco, Schneider <br>
     Lopez Goitia, Carlos Alberto <br>
     Tumi Oliden, Manuel Ignacio <br>
     Vega Coronado, Fabricio Samir <br>
     Villanueva Andrade, Ysaac Ligorio
   </td>
 </tr>

 <tr>
  <td>Sprint n-3 Review Summary</td>
  <td>
    Como conclusión del Sprint 3, el equipo acordó mejorar la distribución y seguimiento de tareas, mantener una
    comunicación más constante dentro del repositorio y registrar el avance de forma centralizada en Trello.
    Asimismo, se estableció estandarizar los commits y reforzar la revisión cruzada de pull requests para asegurar calidad.
  </td>
</tr>

 <tr>
  <td>Sprint n-2 Review Summary</td>
  <td>
    En el cierre del Sprint 2 se confirmó una primera versión operativa de la aplicación web de PuntoSabor.
    Se avanzó con el enrutamiento base, los primeros módulos visuales y la versión final de la landing page,
    además de integrar servicios simulados mediante JSON Server. También se ajustaron detalles de estilos y
    se fortaleció la documentación de arquitectura solicitada por el profesor.
  </td>
</tr>

<tr>
  <td>Sprint n-1 Retrospective Summary</td>
  <td>
    En la revisión del Sprint 1 se dejaron sentadas las bases del proyecto PuntoSabor: organización del repositorio,
    lineamientos de trabajo y una primera estructura funcional para iniciar el desarrollo. Esto permitió arrancar con
    un flujo de trabajo más ordenado para los siguientes sprints.
  </td>
</tr>

 <tr>
    <td colspan="2"><b>Sprint Goal & User Stories</b></td>
 </tr>

 <tr>
  <td>Sprint 4 Goal</td>
  <td>
    Desarrollar y entregar una versión mejorada y corregida de PuntoSabor, consolidando los ajustes de frontend y backend:
    corrección de errores, mejoras de interfaz y experiencia, integración estable de APIs/endpoints y una base de funcionamiento
    más consistente para las funcionalidades principales.
  </td>
</tr>

 <tr>
    <td>Sprint 4 velocity</td>
    <td>15</td>
 </tr>

 <tr>
    <td>Sum of Story Points</td>
    <td>50 Story Points</td>
 </tr>

</table> 
</div>

# 5.2.4.2. Aspect Leaders and Collaborators

En este punto se presenta la matriz Leadership-and-Collaboration (LACX) asignada al Sprint 4. Este documento detalla la distribución de responsabilidades, identificando a los líderes y colaboradores encargados de cada módulo del proyecto PuntoSabor.

| Team Member (Last Name, First Name) | GitHub Username | Notifications              | MONITORING              | PREFERENCES         | ANALYTICS                 | SUBSCRIPTIONS               |
|------------------------------------|------------------|----------------------------|-------------------------|---------------------|---------------------------|-----------------------------|
| Delgado Carrasco, Schneider        | schneiderdc      | C                          | C                       | L                   | C                         | C                           |
| Lopez Goitia, Carlos Alberto       | CarlosAlb101     | L                          | C                       | C                   | C                         | C                           |
| Tumi Oliden, Manuel Ignacio        | ManuelTumi2224   | C                          | C                       | C                   | L                         | C                           |
| Vega Coronado, Fabricio Samir      | Fabricio1v       | C                          | L                       | C                   | C                         | C                           |
| Villanueva Andrade, Ysaac Ligorio  | YsaacVillanueva  | C                          | C                       | C                   | C                         | L                           |


# 5.2.4.3. Sprint Backlog 4

En este apartado se presenta el Sprint Backlog correspondiente al Sprint 4 del proyecto PuntoSabor. Para esta iteración, se seleccionaron únicamente las historias que aún requieren desarrollo o ajustes, dejando fuera aquellas que ya fueron completadas en sprints anteriores o que figuran con estado “Done”.

El objetivo del Sprint Backlog 4 es ordenar y mostrar de forma clara las funcionalidades que se implementarán en este sprint, junto con su responsable asignado, nivel de complejidad y estado actual de avance. En la siguiente tabla se resumen las User Stories pendientes de cierre durante esta iteración.

Tareas que se realizarán en este sprint por el lado del frontend.

| User Story ID | Title | Description | Story Points | Assigned To | Status |
|---------------|--------|-------------|--------------|-------------|--------|
| **US03** | Guardar favoritos | Como usuario, puedo guardar huariques para acceder fácilmente después. | 3 | ManuelTumi2224 | Done |
| **US05** | Actualización de información | Como dueño, puedo modificar los datos de mi huarique para mantenerlos actualizados. | 3 | ManuelTumi2224 | In-Progress |
| **US07** | Envío de reseñas | Como usuario, puedo dejar una reseña y calificación en un huarique. | 3 | Fabricio1v | Done |
| **US08** | Moderación automática | Como sistema, debo detectar reseñas inapropiadas y bloquearlas. | 5 | schneiderdc | In-Progress |
| **US11** | Configuración de notificaciones | Como usuario, puedo activar o desactivar notificaciones a mi preferencia. | 2 | ManuelTumi2224 | In-Progress |
| **US12** | Notificación de nuevas reseñas | Como dueño, recibo alertas cuando hay reseñas nuevas en mi huarique. | 2 | Fabricio1v | In-Progress |
| **US16** | Recuperación de contraseña | Como usuario, puedo recuperar mi contraseña en caso de olvido. | 2 | schneiderdc | In-Progress |
| **US17** | Configuración de preferencias | Como usuario, puedo guardar mis preferencias de cocina, presupuesto y ubicación. | 3 | YsaacVillanueva | In-Progress |
| **US19** | Sugerencias por ubicación | Como usuario, quiero recibir recomendaciones de huariques cercanos a mi ubicación actual. | 3 | CarlosAlb101 | In-Progress |
| **US21** | Reporte de información incorrecta | Como usuario, puedo reportar si un huarique tiene datos erróneos. | 2 | CarlosAlb101 | In-Progress|
| **US22** | Validación automática de estado | Como sistema, quiero mostrar si un huarique está abierto o cerrado en tiempo real. | 5 | CarlosAlb101 | In-Progress |
| **US24** | Pago de suscripción | Como dueño, quiero pagar mi membresía mediante tarjeta o billetera digital de forma segura. | 5 | schneiderdc | Done |
| **US25** | Facturación y comprobantes | Como dueño, quiero descargar facturas mensuales de mis pagos. | 3 | YsaacVillanueva | Done |
| **US26** | Promociones destacadas | Como dueño Pro, quiero publicar promociones destacadas en listados. | 3 | schneiderdc | Done |

# 5.2.4.4. Development Evidence for Sprint Review
A continuación se presentan los avances del desarrollo de la aplicación web, incluyendo las mejoras realizadas en el frontend y la evidencia de los commits registrados en GitHub.

- Repositorio Landing: https://github.com/1ASI0730-2520-7432-G3-FijasDev/PuntoSabor-LandingPage          
- Repositorio Frontend: https://github.com/1ASI0730-2520-7432-G3-FijasDev/Frontend---PuntoSabor           
- Repositorio Backend:https://github.com/1ASI0730-2520-7432-G3-FijasDev/PuntoSabor-Backend

| Repo                     | Commit   | Branch   | Mensaje                                                                 |
|--------------------------|----------|----------|--------------------------------------------------------------------------|
| Frontend---PuntoSabor    | 11391a1  | develop  | Merge pull request #26 from 1ASI0730-2520-7432-G3-FijasDev/Manuel        |
| Frontend---PuntoSabor    | b3f4cb0  | develop  | feat: link reviews with logged user and fix i18n                         |
| Frontend---PuntoSabor    | 91e1fca  | develop  | feat: upload base-endpoint and env.development                           |
| Frontend---PuntoSabor    | ea25ede  | develop  | fix: locales                                                             |
| Frontend---PuntoSabor    | 5e2680d  | develop  | Merge pull request #25 from 1ASI0730-2520-7432-G3-FijasDev/Carlos        |
| Frontend---PuntoSabor    | 82620b1  | develop  | Merge branch 'Develop' into Carlos                                       |
| Frontend---PuntoSabor    | 854f2fb  | develop  | feat: open/closed status badge by hours                                  |
| Frontend---PuntoSabor    | c0a1dc3  | develop  | feat: add incorrect information report                                   |
| Frontend---PuntoSabor    | 06b7693  | develop  | Merge pull request #24 from 1ASI0730-2520-7432-G3-FijasDev/Ysaac         |
| Frontend---PuntoSabor    | 20ee11e  | develop  | feat: es.json and en.json in preferences                                 |
| Frontend---PuntoSabor    | 4afaf3e  | develop  | Merge pull request #23 from 1ASI0730-2520-7432-G3-FijasDev/Ysaac         |
| PuntoSabor-LandingPage   | c96d7d9  | main     | Merge pull request #9 from 1ASI0730-2520-7432-G3-FijasDev/feature/carlos |
| PuntoSabor-LandingPage   | e11c687  | main     | fix: html and style                                                      |
| PuntoSabor-LandingPage   | b3e367b  | main     | Merge branch 'develop' into feature/carlos                               |
| PuntoSabor-LandingPage   | 261fe00  | main     | LandingPage                                                              |
| PuntoSabor-LandingPage   | 73331b0  | main     | Merge pull request #7 from 1ASI0730-2520-7432-G3-FijasDev/feature/ysaac  |
| PuntoSabor-LandingPage   | c390d01  | main     | feat: fix css                                                            |
| PuntoSabor-LandingPage   | c0d72f0  | main     | Merge pull request #6 from 1ASI0730-2520-7432-G3-FijasDev/feature/carlos |
| PuntoSabor-LandingPage   | 425aa5a  | main     | LandingPage: Contactos                                                   |
| PuntoSabor-LandingPage   | 9399289  | main     | feat: fix phrase                                                         |
| PuntoSabor-LandingPage   | 7d9630a  | main     | Merge pull request #5 from 1ASI0730-2520-7432-G3-FijasDev/feature/ysaac  |
| PuntoSabor-LandingPage   | 59378c1  | main     | Merge pull request #4 from 1ASI0730-2520-7432-G3-FijasDev/feature/carlos |
| PuntoSabor-LandingPage   | 849a19c  | main     | LandingPage Contactanos                                                  |
| PuntoSabor-LandingPage   | d6616b9  | main     | LandingPage: Contactanos                                                 |
| PuntoSabor-Backend       | 10acd95  | develop  | Merge pull request #7 from 1ASI0730-2520-7432-G3-FijasDev/feature/sprint4-schneider |
| PuntoSabor-Backend       | 524c390  | develop  | fix: summary                                                             |
| PuntoSabor-Backend       | c126572  | develop  | Merge pull request #6 from 1ASI0730-2520-7432-G3-FijasDev/feature/sprint4-carlos |
| PuntoSabor-Backend       | 67ff3f6  | develop  | Merge branch 'develop' into feature/sprint4-carlos                      |
| PuntoSabor-Backend       | 0e6b353  | develop  | fix: obj                                                                 |
| PuntoSabor-Backend       | 22b2fb1  | develop  | Merge pull request #5 from 1ASI0730-2520-7432-G3-FijasDev/feature/sprint4-schneider |
| PuntoSabor-Backend       | ed2b4e3  | develop  | feat: summary                                                            |
| PuntoSabor-Backend       | 352156b  | develop  | Merge pull request #4 from 1ASI0730-2520-7432-G3-FijasDev/feature/sprint4-schneider |
| PuntoSabor-Backend       | 18a2f37  | develop  | fix: code order                                                          |
| PuntoSabor-Backend       | 16be063  | develop  | fix: code order                                                          |
| PuntoSabor-Backend       | 20aeb63  | develop  | feat: responsive                                                         |
| PuntoSabor-Backend       | eef2e11  | develop  | Merge pull request #3 from 1ASI0730-2520-7432-G3-FijasDev/feature/sprint4-ysaac |
| PuntoSabor-Backend       | 45ff675  | develop  | feat: upload program.cs                                                  |
| PuntoSabor-Backend       | e81704f  | develop  | Merge pull request #2 from 1ASI0730-2520-7432-G3-FijasDev/feature/sprint4-manuel |
| PuntoSabor-Backend       | 840c47f  | develop  | feat: Create API and connection with FrontEnd                            |
| PuntoSabor-Backend       | ee32070  | develop  | Merge pull request #1 from 1ASI0730-2520-7432-G3-FijasDev/feature/sprint4-fabricio |
| PuntoSabor-Backend       | 817b21b  | develop  | feat: Initial Database                                                   |
| PuntoSabor-Backend       | af44ff6  | develop  | feat: backend ready with EF Core, migrations and Users API integration  |
| PuntoSabor-Backend       | e453db4  | develop  | first commit                                                             |

# 5.2.4.5. Execution Evidence for Sprint Review

Se presentarán los avances logrados en el desarrollo de la aplicación web, incluyendo su despliegue en Swagger y los endpoints implementados para garantizar su correcto funcionamiento. A continuación, se detallan los endpoints creados junto con su respectivo comportamiento, tal como se visualizan en Swagger:

![alt text](assets/swagger1.png)

![alt text](assets/swagger2.png)

![alt text](assets/swagger3.png)

Finalmente, se presentan los Schemas y Resources correspondientes a los endpoints implementados:

![alt text](assets/swagger4.png)

Se mejoró la vista de Mapa en el frontend de PuntoSabor, mostrando en la ficha del restaurante si está abierto o cerrado para que el usuario lo identifique al instante.

![alt text](assets/mapamejorado.png)

Se mejoró el landing page adaptándolo a formato móvil, ajustando la distribución de elementos, tipografías y botones para lograr una navegación responsive y más cómoda.

![alt text](assets/landingmejorado.png)


Se mejoró la experiencia de personalización del usuario incorporando la vista de preferencias, donde se configuran tipos de cocina, presupuesto por persona y distrito.

![alt text](assets/preferencias.png)

Se mejoró el frontend habilitando la sección Mis huariques favoritos, donde el usuario puede guardar los locales marcados como favoritos para acceder a ellos rápidamente.

![alt text](assets/preferenciasmejoradas.png)

Se mejoró el frontend incorporando la vista Registrar huarique, permitiendo que el dueño cree su propio huarique ingresando datos, dirección, horarios, servicios y menú.

![alt text](assets/registrohuarique.png)

Se mejoró el frontend incorporando la opción de reportar información incorrecta de un huarique, permitiendo corregir datos como horarios y enviar un reporte con el valor correcto.

![alt text](assets/report.png)

# 5.2.4.6. Services Documentation Evidence for Sprint Review
Se implementaron endpoints adicionales relacionados con la lógica de negocio. En este sprint se agregó el endpoint de actualización parcial de huariques para editar información específica a partir de su identificador.

| Método | Endpoint           | Descripción                                                     |
|--------|---------------------|-----------------------------------------------------------------|
| GET    | /huariques          | Obtiene la lista de huariques registrados.                     |
| POST   | /huariques          | Crea un nuevo huarique.                                        |
| GET    | /huariques/{id}     | Devuelve la información de un huarique según su id.            |
| PATCH  | /huariques/{id}     | Actualiza parcialmente un huarique según su id.                |
| GET    | /users             | Lista los usuarios registrados.                                |
| POST   | /users             | Crea un nuevo usuario.                                          |
| GET    | /categories        | Obtiene la lista de categorías disponibles.                     |
| GET    | /plans             | Devuelve los planes registrados.                                |
| GET    | /promos            | Obtiene las promociones disponibles.                            |
| GET    | /reviews           | Lista todas las reseñas registradas.                            |
| POST   | /reviews           | Crea una nueva reseña.                                          |

# 5.2.4.7. Software Deployment Evidence for Sprint Review
La API se desplegó en Railway luego de probarse localmente en Rider. Se habilitó Swagger, se configuró CORS para permitir el consumo desde el frontend en Vite y la base de datos MySQL se inicializó con datos semilla para validar los flujos del sistema.

![alt text](assets/api.png)

![alt text](assets/ray.png)

La API está disponible en: https://puntosabor-backend-production.up.railway.app/swagger/index.html

![alt text](assets/swaggerv2.png)

# 5.2.4.8. Team Collaboration Insights during Sprint
En esta sección se evidencia cómo el equipo ha colaborado para sacar adelante la entrega correspondiente al Sprint 4. Además, se incluyen las métricas que reflejan el avance y el desempeño del backend, frontend y la landing page durante esta iteración.

Backend:

![alt text](assets/backend4.png)

Frontend

![alt text](assets/frontend4.png)
 
LandingPage:

![alt text](assets/landingpage4.png)


# 5.3 Validation Interviews

## 5.3.1 Diseño de Entrevistas
Para validar la usabilidad, claridad visual y facilidad de uso de la plataforma web PuntoSabor, se diseñó un conjunto de entrevistas dirigidas a dos segmentos de usuarios:

Segmento 1: Usuarios comensales que navegan por la plataforma para descubrir huariques.

Segmento 2: Dueños/administradores de huariques que usan el panel de gestión.

El objetivo de estas entrevistas es evaluar la experiencia del usuario al interactuar con las funcionalidades principales, así como identificar áreas de mejora para futuras iteraciones del proyecto.

### Preguntas del Segmento 1 – Usuarios Comensales

- ¿Qué tan fácil te resultó navegar desde la landing page hasta la búsqueda de huariques?

- ¿La presentación visual de las tarjetas (foto, nombre, descripción, estrellas) fue clara y suficiente para decidir revisar un huarique?

- ¿Los filtros (tipo de comida, precio, ubicación) te ayudaron a encontrar lo que buscabas?

- ¿El mapa interactivo te resultó útil para ubicar huariques cercanos o de interés?

- ¿Fue sencillo dejar una reseña y entender el sistema de calificación por estrellas?

- ¿Qué tan intuitivo te pareció marcar un huarique como favorito o revisar las recomendaciones?

### Preguntas del Segmento 2 – Administradores de Huariques

- ¿Qué tan claro fue el proceso de registrar tu huarique en la plataforma?

- ¿Te resultó fácil revisar y responder las reseñas de los usuarios?

- ¿La manera en que tu huarique aparece en el buscador y en el mapa refleja adecuadamente tu negocio?

- ¿Consideras que PuntoSabor mejora la visibilidad de tu huarique frente a potenciales clientes?

- ¿Qué tan útil te parece la plataforma para administrar y promocionar tu huarique de forma digital?

## 5.3.2 Registro de Entrevistas
### Entrevista M1 – Segmento 1 (Usuario Comensal)

Entrevistador: Ysaac Villanueva
Entrevistado: Vitaly Baca
Fecha: 2025-11-13
Link de la entrevista: [Entrevista 1 Segmento 1](https://drive.google.com/file/d/1u_jtYq7m1XSMKOQxpQ-8db2F7O0-XYeC/view?usp=sharing)
![Entrevista1_TB2_Seg1.jpg](assets/Entrevista1_TB2_Seg1.jpg)

### Resumen
Vitaly indicó que la navegación general de la plataforma fue fluida y que desde la landing pudo ubicar rápidamente la sección de huariques sin dificultad. Consideró que las tarjetas presentan de manera clara la información necesaria para decidir si ingresar al detalle de un huarique, destacando especialmente la utilidad de la foto y la calificación.

En cuanto a los filtros, comentó que le parecieron útiles, sobre todo los de tipo de comida y ubicación. Sin embargo, sugirió que el filtro de distancia debería ser más visible, ya que en zonas como Lurín es importante identificar huariques realmente cercanos. También señaló que el mapa fue práctico y preciso, pues los pines mostraban huariques ubicados en lugares reconocidos como la Panamericana Antigua.

Por último, mencionó que dejar reseñas y marcar favoritos fue sencillo e intuitivo, y que las recomendaciones mostradas coincidían con los huariques que había estado buscando, aportando valor a su experiencia como usuario.

### Entrevista M2 – Segmento 1 (Usuario Comensal)

Entrevistador: Ysaac Villanueva
Entrevistado: Sebastian del Rio
Fecha: 2025-11-13
Link de la entrevista: [Entrevista 2 Segmento 1](https://drive.google.com/file/d/1SPHOZAo3V3sFyVSMT4Wib91-wXRuOldF/view?usp=sharing)
![Entrevista2_TB2_Seg1.jpg](assets/Entrevista2_TB2_Seg1.jpg)

### Resumen
En la entrevista, Sebastián comentó que la navegación desde la landing page hacia la sección de huariques le resultó clara y directa, sin pasos innecesarios. Señaló que las tarjetas le parecieron completas y fáciles de entender, ya que la combinación de foto, nombre y calificación permite evaluar rápidamente un huarique, aunque mencionó que una imagen un poco más grande podría mejorar la visualización.

Respecto a los filtros, indicó que funcionaron correctamente al buscar opciones de mariscos, comunes en su zona, aunque consideró que el filtro de precio podría ser más visible para acceder a él con mayor facilidad. También destacó que el mapa fue una herramienta útil, ya que los pines coincidían con huariques reales de Chorrillos, lo cual le generó confianza al explorar opciones cercanas.

Finalmente, mencionó que el proceso de dejar reseñas fue simple e intuitivo, y que la función de favoritos y recomendaciones le pareció coherente con sus búsquedas, permitiéndole descubrir alternativas relacionadas a sus preferencias.

### Entrevista N1 – Segmento 2 (Administrador de Huarique)
Entrevistador: Manuel Tumi
Entrevistado: Piero Tapia
Fecha: 2025-11-13
Link de la entrevista: [Entrevista 1 Segmento 2](https://drive.google.com/file/d/1qXveDIikLAa3Lm5JW85rZf6rT8Ym_qf9/view?usp=drive_link)
![Entrevista1](assets/Entrevista1Review.png)

### Resumen
En esta entrevista, el participante indicó que el proceso de registrar un huarique en PuntoSabor le resultó claro, intuitivo y fácil de completar, destacando que cualquier usuario podría manejarlo sin complicaciones. Valoró la interfaz amigable y la forma en que la información del negocio se refleja posteriormente en el mapa y en el buscador.

Propuso mejoras específicas, como incluir un sistema de promociones y descuentos que permita activar días específicos y aumentar la visibilidad del negocio. También sugirió añadir opciones predeterminadas para reseñas (por ejemplo, “Excelente”, “Recomendado”), para facilitar la participación de los usuarios.

Respecto al mapa, recomendó que al aplicar filtros se muestren todas las opciones correspondientes sin necesidad de hacer clic individual en cada huarique, lo cual ayudaría a una navegación más fluida.

En general, su percepción fue positiva y consideró que la plataforma puede mejorar significativamente la visibilidad y gestión digital de un huarique.

### Entrevista N2 – Segmento 2 (Administrador de Huarique)

Entrevistador: Manuel Tumi
Entrevistado: Wildor Villalobos
Fecha: 2025-11-13
Link de la entrevista: [Entrevista 2 Segmento 2](https://drive.google.com/file/d/1NIV0eMvDfTuqKxPW2k5sOicxA9n9dmuR/view?usp=sharing)
![Entrevista1](assets/Entrevista2Review.png)

### Resumen
En esta entrevista, el participante señaló que el proceso de registrar su huarique en PuntoSabor le pareció muy intuitivo, directo y fácil de completar. Consideró que la interfaz es amigable incluso para personas con poca experiencia tecnológica. También destacó la claridad del mapa interactivo y la forma en la que el huarique aparece ubicado visualmente, lo que ayuda a los usuarios a encontrarlo con facilidad.

Propuso añadir una sección más completa para promociones y descuentos, donde los dueños puedan activar ofertas por días y que estas se desactiven automáticamente, ya que muchos clientes buscan primero promociones antes que el restaurante. Además, sugirió mejorar la distribución del menú y permitir organizar mejor los productos.

Respecto al sistema de reseñas, indicó que sería valioso incluir opciones predeterminadas (como “Excelente”, “Muy bueno”, “Lo recomiendo”) para facilitar la participación de usuarios que no siempre quieren redactar comentarios completos. También recomendó que en el mapa, al aplicar un filtro (por ejemplo, “Pollos”), se muestren todos los huariques filtrados al mismo tiempo, sin necesidad de hacer clic uno por uno.

Finalmente, mencionó que PuntoSabor sí puede mejorar significativamente la visibilidad de un huarique y atraer nuevos clientes, aunque considera importante ajustar los precios de los planes o incrementar el valor que ofrecen para justificar la inversión.

## 5.3.3 Evaluaciones según heurísticas
Sitio o App a evaluar:

PuntoSabor – Plataforma Web de Descubrimiento y Gestión de Huariques

Tareas a evaluar:

El alcance de esta evaluación incluye revisar la usabilidad, claridad y consistencia de las principales funcionalidades disponibles en la plataforma para ambos segmentos de usuarios (comensales y administradores).

## Tareas del Segmento 1 – Usuarios Comensales

- Navegación desde la landing page hacia la búsqueda de huariques

- Uso de los filtros (tipo de comida, precio, ubicación)

- Interacción con las tarjetas de huariques

- Consulta de detalles de un huarique

- Visualización del promedio de estrellas y reseñas

- Uso del mapa interactivo

- Marcar un huarique como favorito

- Revisión de la sección de favoritos

- Publicación de una reseña

- Calificación mediante el sistema de estrellas

- Revisión del apartado “Recomendados para ti”

- Flujo general de navegación entre resultados, mapa y detalles

## Tareas del Segmento 2 – Administradores de Huariques
- Registro de huarique en la plataforma

- Inicio de sesión en el panel de administración

- Actualización de información del huarique (fotos, descripción, precios, horarios)

- Gestión de menú o especialidades

- Revisión de reseñas recibidas

- Respuesta a reseñas de usuarios

- Gestión de visibilidad del huarique

- Actualización de ubicación en el mapa

- Carga y actualización de imágenes

- Supervisión del rendimiento del huarique dentro de la plataforma (visitas, interacciones, favoritos)

## Tareas no incluidas en esta versión de la evaluación

- Las siguientes tareas no se incluyeron por encontrarse fuera del alcance de la iteración actual:

- Integración con métodos de pago

- Publicación de promociones internas del huarique

- Gestión avanzada de estadísticas (métricas comerciales)

- Flujo de registro de administradores mediante documentación legal

- Revisión de métricas de plataforma en tiempo real

# 5.4. Video About-the-Product

https://drive.google.com/file/d/1IFWF2grAcX5bDUyp4jeoviRTwzra_2JY/view

# Conclusiones

A lo largo de los cuatro sprints, el equipo pudo establecer no solo una base técnica para el proyecto, sino también un procedimiento de trabajo más cooperativo y estructurado. Establecimos las bases del proyecto en el Sprint 1: definimos el flujo de trabajo con GitHub, organizamos roles, estructuramos el repositorio y creamos la primera versión de la página de aterrizaje. También se diseñaron los componentes iniciales en Figma y se preparó el entorno para seguir avanzando en el producto.

Durante el Sprint 2, logramos un avance significativo al crear la primera versión funcional de la aplicación web. Además de lanzar la primera versión en producción, también pusimos en marcha la búsqueda avanzada, la vista de mapa, las categorías y el registro de huariques. Se incorporó una API falsa a través de Render y JSON Server, lo que posibilitó la prueba de los flujos reales entre el frontend y el backend. Además, se llevó a cabo una mejora en el empleo de GitFlow, ramas por funcionalidad y despliegues en Netlify y Vercel.

Se implementaron características más completas y enfocadas en la conducta real del usuario, como iniciar sesión y registrarse, dejar reseñas, marcar favoritos, tener membresías y recibir notificaciones iniciales durante el Sprint 3. Además, se puso en marcha la versión inicial del backend, que incluye controladores, una base de datos inicial, endpoints reales y documentación en Swagger. Esto facilitó la mejora de la calidad de la plataforma y el progreso hacia una integración entre los módulos del sistema.

En última instancia, en el Sprint 4, nos concentramos en perfeccionar la experiencia del usuario y optimizar elementos visuales, flujos internos y estabilidad general. Se incorporaron actualizaciones en el mapa, opciones personalizadas, huariques preferidos, informes de datos erróneos y una versión adaptable del landing page. Asimismo, se logró una integración con el backend más sólida al resolver errores, organizar los endpoints y garantizar la compatibilidad con el frontend.

Durante los sprints, el equipo perfeccionó su organización interna de manera significativa, reforzó la comunicación, utilizó en Git prácticas adecuadas y aprendió a coordinarse mejor entre diseño, backend y frontend. Esto posibilitó que cada entrega tuviera más solidez que la anterior.

# Bibliografía

- Brown, A., & Evans, E. (2004). Domain-Driven Design: Tackling Complexity in the Heart of Software. Addison-Wesley.

- Brandolini, A. (2019). Introducing EventStorming: An Act of Deliberate Collective Learning. Leanpub.

- Gothelf, J., & Seiden, J. (2013). Lean UX: Applying Lean Principles to Improve User Experience. O’Reilly Media.

- Cohn, M. (2004). User Stories Applied: For Agile Software Development. Addison-Wesley.

- Sommerville, I. (2011). Ingeniería de Software (9ª ed.). Pearson Educación.

- DDD By Examples. (s.f.). Design Level Event Storming Guide. Recuperado de: https://github.com/ddd-by-examples/library

- Pressman, R. (2014). Ingeniería del Software: Un Enfoque Práctico. McGraw-Hill.

- Fowler, M. (2003). Patterns of Enterprise Application Architecture. Addison-Wesley.
# Anexos

VIDEOS DEL EQUIPO:

https://drive.google.com/drive/folders/1O24Act8yiSku-69flphDrmjVyVIwWxQs?usp=sharing
