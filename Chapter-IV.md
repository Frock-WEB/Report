# Capítulo IV: Product Design
## 4.1. Style Guidelines.
  
En 
  esta sección, el equipo establece un repositorio organizado y central de elementos comunes (assets, fonts, colores, iconografía) para mantener una presentación visual consistente y enfocada, alineada con el espíritu de **Chapa tu Ruta**: dinámico, confiable y cercano a la cultura popular peruana.
### 4.1.1. General Style Guidelines.
#### Branding
  - Identidad visual vibrante y accesible, con un estilo animoso que transmita **movimiento**, **eficiencia** y **optimismo urbano**.
    - Iconografía reconocible e intuitiva: íconos simples, grandes, fáciles de asociar a acciones comunes (ej. casa, rutas, búsqueda).

      ![Arrows](resources/chapter-4/Arrow.png)
    
      ![Car - Linear.png](resources%2Fchapter-4%2FCar%20-%20Linear.png)
    
      ![Location.png](resources%2Fchapter-4%2FLocation.png)
    
      ![Notifications.png](resources%2Fchapter-4%2FNotifications.png)
    
      ![Time.png](resources%2Fchapter-4%2FTime.png)
    
      ![Security.png](resources%2Fchapter-4%2FSecurity.png)
    
      ![Settings.png](resources%2Fchapter-4%2FSettings.png)
    
      ![Users.png](resources%2Fchapter-4%2FUsers.png)

#### Typography

  - Tipografías claras y sin serifas, de alta legibilidad para usuarios en movimiento.
    - Priorizar estilos **negrita** o **semi-negrita** para botones y acciones principales.
    - Jerarquías bien marcadas: **Títulos > Subtítulos > Texto general**.



#### Colors

- Paleta de colores fuertes (inspirada en tonos limeños y de transporte urbano):
    - **Primarios**: Violeta energético, verde neón, azul eléctrico.
    - **Secundarios**: Gris claro, blanco para fondos.
    - **Accentos**: Rojo alerta, amarillo vibrante para notificaciones críticas o destacadas.
      - Colores transmiten **agilidad, energía y confianza**.

     ![Color Pallete.png](resources%2Fchapter-4%2FColor%20Pallete.png)

#### Spacing

- Márgenes y paddings estandarizados:
    - Separaciones interiores de **10px**, **20px**, **50px** según jerarquía visual.
    - Áreas interactivas suficientemente amplias para facilidad de click y touch.
  - Espacios que respiran pero mantienen sensación de **compacto y eficiente**.

    ![Spectral.png](resources%2Fchapter-4%2FSpectral.png)

#### Communication Tone

  - Tono de comunicación:
      - **Casual**, cercano pero respetuoso.
      - **Entusiasta y positivo** ("¡Chapa tu ruta!", "¡Listo para salir!").
      - Uso de lenguaje **amigable, directo, breve y familiar** para usuarios peruanos citadinos.

#### Dimension Guidelines

  - Componentes de UI manejan dimensiones estándar para consistencia:
    - **Botones principales**: 100px de ancho mínimo.
    - **Íconos**: 40px a 50px de ancho/alto.
    - **Inputs de texto**: 280px de ancho por 70px de alto.
    - **Tarjetas de información (rutas)**: 300px a 316px de ancho.
    - **Mensajes de éxito/error**: 353px de ancho.

    ![Spectral.png](resources%2Fchapter-4%2FSpectral.png)

    ![Components.png](resources%2Fchapter-4%2FComponents.png)

    ![Inputs and Selectors.png](resources%2Fchapter-4%2FInputs%20and%20Selectors.png)

### 4.1.2. Web Style Guidelines.
#### Design
- Uso de layouts flexibles (Flexbox, Grid) para adaptarse sin perder claridad ni funcionalidad.
- Elementos clave (botones, buscadores, rutas) visibles y accesibles en cualquier tamaño de pantalla.

![design.png](resources%2Fchapter-4%2Fdesign.png)

#### Navigation
- Menús de navegación sencillos y visibles.
- Uso de "sticky headers" para mantener acceso a funciones esenciales (búsqueda de rutas, mapa, perfil).
- Efectos de transición suaves para cambios de página o secciones (fade, slide).
![navigation (1).png](resources%2Fchapter-4%2Fnavigation%20%281%29.png)
- 
#### Interaction States
- Estados de interacción claramente diferenciados:
    - **Hover**: cambios sutiles de color o sombra para indicar interactividad.
    - **Active/Pressed**: ligeras animaciones de hundimiento o cambio de tono.
    - **Focus**: bordes destacados para accesibilidad al navegar con teclado.

#### Visual Consistency
- Mantener coherencia de estilos entre páginas:
    - Botones, íconos y colores respetan el mismo sistema visual.
    - Jerarquías de texto y espacios replican los lineamientos generales.
    - Evitar cambios bruscos de estilo que confundan al usuario.

#### Feedback & Notifications
- Mensajes claros y breves en acciones del usuario:
    - Confirmaciones (ej. "¡Ruta guardada exitosamente!").
    - Errores (ej. "No pudimos encontrar esa ruta, intenta de nuevo.").
- Uso de colores de la paleta oficial para comunicar estado (verde éxito, rojo error, amarillo advertencia).

    ![exito.png](resources%2Fchapter-4%2Fexito.png)

## 4.2. Information Architecture.

### 4.2.1. Organization Systems
Para organizar el contenido en las experiencias web y móvil de Frock, se aplicarán los siguientes sistemas de organización:

**Jerárquico (Visual Hierarchy):**  
Se utilizará para destacar información clave como rutas, paraderos y horarios. Por ejemplo, en el Landing Page, la sección "Sé parte de nosotros" tendrá un encabezado principal (#) seguido de subsecciones (##, ###) para registro y detalles de rutas.

**Secuencial (Step-by-Step):**  
Se implementará en procesos como el registro de usuarios o la creación de rutas, donde se guiará al usuario paso a paso (ejemplo: "1. Registro" → "2. Indica tu ruta").

**Por Tópicos:**  
La información se agrupará por temas como "Rutas", "Horarios", "Paraderos" y "Reseñas", facilitando la navegación intuitiva.

**Según Audiencia:**  
Se diferenciará entre conductores (quienes registran rutas y horarios) y pasajeros (quienes buscan información de viaje), adaptando el contenido a cada grupo.

### 4.2.2. Labeling Systems
Las etiquetas se diseñarán para ser claras y concisas, evitando confusión:

**Ejemplos de Etiquetas:**
- "Nombre comercial" (para registro de conductores).
- "Desde / Hasta" (para definir rutas).
- "Horarios: Lun-Vie 8:00 am" (formato uniforme).
- "Editar" / "Agregar Ruta" (acciones destacadas con verbos).

**Asociaciones:**  
Se vincularán términos como "Paradero" con "Ruta" y "Horarios" para reforzar la relación entre componentes.

### 4.2.3. SEO Tags and Meta Tags
Se optimizará el contenido para motores de búsqueda con los siguientes tags:

**Landing Page:**
- **Title:** "Frock - Moderniza tu transporte colectivo"
- **Meta Description:** "Conecta ciudades y distritos con rutas informales organizadas. Encuentra horarios, paraderos y reseñas en un solo lugar."
- **Keywords:** transporte colectivo, rutas informales, paraderos, horarios, movilidad urbana.
- **Author:** Equipo Frock.

**Aplicación Web:**
- **Title (Rutas):** "Mis Rutas | Frock"
- **Meta Description:** "Administra y edita tus rutas registradas. Agrega nuevos trayectos y horarios fácilmente."

### 4.2.4. Navigation Systems
La navegación se basará en:

**Menú Principal:**  
Accesos directos a "Inicio", "Rutas", "Horarios", "Paraderos" y "Reseñas".

**Breadcrumbs:**  
Ruta de navegación como "Inicio > Mis Rutas > Editar Ruta".

**Botones de Acción:**  
Destacados con verbos ("Registrar", "Agregar Ruta", "Editar") y diseño consistente (color/contraste).

**Flujo Secuencial:**  
Para tareas críticas (ejemplo: registro de conductor → agregar ruta → confirmación).

### 4.2.5. Searching Systems
Para ayudar a los usuarios a encontrar información rápidamente:

**Búsqueda por Filtros:**
- Paraderos (dropdown con opciones como "La Torre").
- Horarios (selector de rango horario).
- Precios (slider de "50 a 100").

**Resultados de Búsqueda:**  
Mostrados en tarjetas con detalles clave: "De La Torre a Estación Dos | 7 asientos | 20 min".

**Búsqueda Predictiva:**  
Autocompletado al escribir nombres de paraderos o rutas.

## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.

![wireframe (1).png](resources%2Fchapter-4%2Flanding%2Fwireframe%20%281%29.png)

### 4.3.2. Landing Page Mock-up.

![mockup.png](resources%2Fchapter-4%2Flanding%2Fmockup.png)

## 4.4. Web Applications UX/UI Design.

### 4.4.1. Web Applications Wireframes.

![registro.png](resources%2Fchapter-4%2Fwireframes%2Fregistro.png)

![ruta.png](resources%2Fchapter-4%2Fwireframes%2Fruta.png)

![perfil.png](resources%2Fchapter-4%2Fwireframes%2Fperfil.png)

![home.png](resources%2Fchapter-4%2Fwireframes%2Fhome.png)

![descripcion.png](resources%2Fchapter-4%2Fwireframes%2Fdescripcion.png)

### 4.4.2. Web Applications Wireflow Diagrams.

### 4.4.2. Web Applications Mock-ups.
![registro.png](resources%2Fchapter-4%2Fmockups%2Fregistro.png)

![addRuta.png](resources%2Fchapter-4%2Fmockups%2FaddRuta.png)

![perfil.png](resources%2Fchapter-4%2Fmockups%2Fperfil.png)

![exito.png](resources%2Fchapter-4%2Fmockups%2Fexito.png)

![home.png](resources%2Fchapter-4%2Fmockups%2Fhome.png)

![Informacio-ruta.png](resources%2Fchapter-4%2Fmockups%2FInformacio-ruta.png)

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
### 1. Clase Vehicle
Esta clase representa un vehículo en el sistema, que podría ser un bus o una minivan en el contexto del sistema de transporte colectivo.

**Atributos:**
- `id`: Identificador único del vehículo.
- `ownerId`: Identificador del propietario (conductor o empresa).
- `status`: Estado actual del vehículo.
- `lastMaintenance`: Fecha del último mantenimiento.

**Métodos:**
- `Vehicle(id, ownerId, status, lastMaintenance)`: Constructor para inicializar el vehículo.
- `updateStatus(newStatus)`: Actualiza el estado del vehículo.
- `scheduleMaintenance(date)`: Programa el siguiente mantenimiento.

---

### 2. Clase VehicleFactory
Fábrica para crear vehículos con atributos definidos.

**Métodos:**
- `createItem(id, ownerId, status, lastMaintenance)`: Crea y devuelve una nueva instancia de Vehicle.

---

### 3. Clase VehicleMonitoringService
Servicio central para monitorear los vehículos, siguiendo el patrón singleton.

**Atributos:**
- `instance`: Instancia única del VehicleMonitoringService.

**Métodos:**
- `getAllVehicles()`: Devuelve una lista de todos los vehículos registrados.
- `getVehicleById(id)`: Recupera un vehículo por su ID.
- `addVehicle(vehicle)`: Añade un nuevo vehículo al sistema.
- `logMaintenance(id, date)`: Registra las acciones de mantenimiento de un vehículo.

---

### 4. Clase Observer
Define el contrato para observar cambios en el estado de los vehículos.

**Métodos:**
- `updateStatus(vehicle)`: Actualiza el estado del vehículo cuando ocurre un cambio.

---

### 5. Clase VehicleStatusLogger
Registra los cambios en el estado de los vehículos (implementa la interfaz Observer).

**Métodos:**
- `update(vehicle)`: Registra los cambios que ocurren en el vehículo.

---

### 6. Clase Route
Representa una ruta tomada por los vehículos.

**Atributos:**
- `id`: Identificador único de la ruta.
- `origin`: Punto de inicio de la ruta.
- `destination`: Punto final de la ruta.
- `distance`: Distancia de la ruta.
- `estimatedTime`: Tiempo estimado para completar la ruta.

**Métodos:**
- `addStop(stop)`: Añade una parada a la ruta.
- `getRouteInfo()`: Devuelve toda la información de la ruta.

---

### 7. Clase Stop
Representa una parada a lo largo de una ruta.

**Atributos:**
- `id`: Identificador único de la parada.
- `location`: Ubicación geográfica de la parada.
- `routeId`: Identificador de la ruta a la que pertenece la parada.

**Métodos:**
- `getStopInfo()`: Devuelve información sobre la parada.
- `isAvailable()`: Verifica si la parada está disponible para que el vehículo llegue.

---

### 8. Clase Order
Representa un pedido realizado por un cliente.

**Atributos:**
- `id`: Identificador único del pedido.
- `customerId`: Cliente que hizo el pedido.
- `status`: Estado del pedido.
- `createdDate`: Fecha de creación del pedido.

**Métodos:**
- `createOrder(customerId, status)`: Crea un nuevo pedido para el cliente.

---

### 9. Clase TransportService
Gestiona la creación y recuperación de pedidos dentro del sistema.

**Métodos:**
- `createOrder(customerId, items)`: Crea un nuevo pedido y lo asocia con ítems de servicio (vehículos, paradas).
- `getOrderById(id)`: Recupera un pedido específico por su ID.

### 10. Clase VehicleMonitoringService
Servicio central para monitorear los vehículos, siguiendo el patrón singleton.

**Atributos:**
- `instance`: Instancia única del VehicleMonitoringService (patrón singleton).
- `vehicles`: Lista de todos los vehículos monitoreados.

**Métodos:**
- `getAllVehicles()`: Devuelve una lista de todos los vehículos registrados.
- `getVehicleById(id)`: Recupera un vehículo por su ID.
- `addVehicle(vehicle)`: Añade un nuevo vehículo al sistema de monitoreo.
- `updateVehicleStatus(id, status)`: Actualiza el estado de un vehículo específico.
- `logMaintenance(id, date)`: Registra el mantenimiento realizado en un vehículo.

## 4.8. Database Design.
### 4.8.1. Database Diagram.

