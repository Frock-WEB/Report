# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
### 4.1.2. Web Style Guidelines.
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
### 4.2.2. Labeling Systems.
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems.
### 4.2.5. Navigation Systems.
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
### 4.3.2. Landing Page Mock-up.
## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.
### 4.4.3. Web Applications User Flow Diagrams.
## 4.5. Web Applications Prototyping.

## 4.6. Domain-Driven Software Architecture.
Los esquemas de contenedores ilustran los distintos componentes del sistema, tales como aplicaciones en línea, bases de datos, microservicios y la forma en que interactúan entre ellos. Estos esquemas ofrecen una perspectiva a nivel superior de la arquitectura del sistema, resaltando las obligaciones de cada contenedor y sus interrelaciones.

### 4.6.1. Software Architecture Context Diagram.
El diagrama de contexto del sistema muestra la relación entre el sistema y los actores externos, proporcionando una visión general de la arquitectura del sistema y sus interacciones con el entorno externo.

![Software Architecture Context Diagram](assets/4_6_1.png)

### 4.6.2. Software Architecture Container Diagrams.
Los esquemas de contenedores ilustran las distintas partes que conforman el sistema, tales como aplicaciones en línea, bases de datos, microservicios y la forma en que interactúan entre ellos. Estos esquemas ofrecen una panorámica detallada de la arquitectura del sistema, resaltando las obligaciones de cada contenedor y sus relaciones entre sí.

![Software Architecture Container Diagram](assets/Software-Architecture-Container-Diagrams.png)

### 4.6.3. Software Architecture Components Diagrams.
En esta sección, se presentan los diagramas de componentes de la arquitectura de software. Estos diagramas detallan los diferentes componentes que conforman el sistema, sus responsabilidades y cómo interactúan entre sí.

#### Bounded Context: Analytics

![Analytics](assets/BoundedContext_Analytics.png)

Este bounded context contiene todo lo relacionado al monitoreo y seguimientos de los colectivos, asi como los reportes de estos.

#### Bounded Context: Control

![Control](assets/BoundedContext_Control.png)

Este bounded context separa todo lo relacionado con el control de rutas de los colectivos para los usuarios, por lo que las rutas de los colectivos esta incluido en este bounded context.

#### Bounded Context: Planning

![Planning](assets/BoundedContext_Planning.png)

Este bounded context sirve para alojar el feature de paraderos existente en nuestra plataforma, este feature requiere de muchas entidades tales como ubicación, horarios, capacidad y estado.

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
### 4.7.2. Class Dictionary.
## 4.8. Database Design.
### 4.8.1. Database Diagram.

