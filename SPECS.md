# AgentHub

## Descripción
AgentHub es una startup que está desarrollando una plataforma SaaS que permite a empresas alquilar agentes de inteligencia artificial preconfigurados. Estos agentes pueden equiparse con distintas habilidades —como navegación web, lectura de documentos o gestión de calendarios— y desplegarse para automatizar tareas específicas de negocio.

El equipo ya cuenta con un backend funcional, pero necesita definir y diseñar su panel de administración interno. Para ello, el objetivo inicial es crear un prototipo HTML completamente diseñado que sirva como referencia visual y funcional. Antes de construirlo, se requiere una especificación detallada (Vision to spec) que describa qué se va a desarrollar y bajo qué reglas, de modo que cualquier desarrollador o agente de código pueda implementarlo sin ambigüedades.

## Requisitos
- Rol: Desarrollador junior con conocimiento básico
- Stack: HTML, Tailwind (CDN), JS vanilla
- Datos ficticios hardcodeados, sin backend real (moqueta)
- Inventario de componentes reutilizables (Pensar en componentes siempre que sea posible):
    - Sidebar
    - Tarjeta Métrica
    - Dropdown acciones
    - Modal
    - Badges
    - etc.


## Panel: Secciones
### 1. Dashboard:
- Tarjetas de métricas:
    - Ingresos totales (mes)
    - pérdidas por descuentos/cupones
    - Nº de agentes activos & fallando
- Debajo:
    - Placeholder para gráfico de actividad semanal

### 2. Dashboard:
- Tabla con columnas:
    - Nombre
    - Email
    - Plan
    - Estado
- Cada fila:
    - Dropdown de acciones:
        - Ver detalle -> abre modal con  info completa
        - Eliminar
- Modal:
    - Overlay
    - Cierre con botón + click en backdrop

### 3. Gestión de agentes:
- Listado con:
    - Nombre agente
    - Propietario
    - Estado (activo, inactivo o fallando)
    - Skills
- Interacción:
    - Expandir skills con transición suave
- Acciones por agente:
    - Dropdown:
        - Configurar -> modal con prompt del sistema
        - Eliminar

### 4. Skills
- Cátalogo de skills:
    - Nombre
    - Descripción breve
    - Nº de agentes que la usan
- Incluir explicación:
    - Qué es una "skill" en AgentHub
- Acciones:
    - Dropdown:
        - Ver detalle
        - Eliminar

### 5. Contrataciones de agentes
- Tabla con:
    - Cliente
    - Agente
    - Skills contratadas
    - Fechas
    - importa total
- Acciones:
    - Dropdown:
        - Ver detalle -> modal
- Modal incluye:
    - Desglose completo del contrato
    - Lista de skills + precios individuales

### 6. Log de errores
- Table con:
    - Timestamp
    - Nombre agente
    - tipo error
    - descripción breve
- UI:
    - Badges por tipo/gravedad (color-coded)
- Acciones:
    - Dropdown:
        - Ver detalle -> Modal con traza completa
        - Marcar como resuelto