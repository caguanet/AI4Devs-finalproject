# Prompts del Proyecto Dike

Este documento detalla los prompts principales utilizados durante la creación del proyecto, justificando el uso de asistentes de código en todas las fases del ciclo de vida del desarrollo.

## Índice

1. [Descripción general del producto](#1-descripción-general-del-producto)
2. [Arquitectura del sistema](#2-arquitectura-del-sistema)
3. [Modelo de datos](#3-modelo-de-datos)
4. [Especificación de la API](#4-especificación-de-la-api)
5. [Historias de usuario](#5-historias-de-usuario)
6. [Tickets de trabajo](#6-tickets-de-trabajo)
7. [Pull requests](#7-pull-requests)

---

## 1. Descripción General del Producto

### 1.1 Definición Estratégica del Producto

#### Prompt Original
```prompt
Actúa como un Product Manager experto y ayúdame a definir el propósito y valor de un sistema de gestión de consultas jurídicas llamado Dike. Necesito:
   - Un propósito principal claro y conciso
   - Los problemas específicos que soluciona
   - El valor que aporta a diferentes tipos de usuarios
   - Identificación del público objetivo
Por favor, estructura la respuesta de manera profesional y detallada.
```

#### Iteración Mejorada
```prompt
Rol: Product Manager Senior especializado en software legal
Objetivo: Definir la visión estratégica y alcance de Dike

Contexto:
Dike busca optimizar la gestión de consultas jurídicas para:
- Mejorar la eficiencia en asignación de casos
- Garantizar seguimiento preciso
- Asegurar cumplimiento normativo
- Proteger información sensible
- Facilitar la colaboración entre equipos legales

Entregables Requeridos:

 Propósito Principal:
   - Objetivo central del sistema
   - Problema específico que resuelve
   - Impacto esperado en la industria legal
   - Métricas de éxito

 Análisis de Necesidades:
   - Problemas actuales del sector
   - Ineficiencias identificadas
   - Costos asociados
   - Riesgos operativos

 Propuesta de Valor:
   - Beneficios por tipo de usuario
   - Ventajas competitivas
   - ROI esperado
   - Diferenciadores clave

 Público Objetivo:
   - Perfiles de usuarios
   - Necesidades específicas
   - Casos de uso principales
   - Puntos de dolor resueltos

Criterios de Validación:
- ¿El propósito está claramente definido?
- ¿Los beneficios son tangibles y medibles?
- ¿Se identifica claramente el mercado objetivo?
- ¿El contenido se alinea con el readme actual?
```

### 1.2 Funcionalidades del MVP

#### Prompt Original
```prompt
Como arquitecto de software, ayúdame a definir las funcionalidades principales para un MVP de un sistema de gestión de consultas jurídicas. Necesito:
   - Lista de 4-5 funcionalidades clave esenciales
   - Descripción detallada de cada funcionalidad
   - Justificación de por qué cada funcionalidad es crucial para el MVP
   - Un diagrama mermaid que muestre el flujo de estas funcionalidades
```

#### Iteración Mejorada
```prompt
Rol: Arquitecto de Soluciones & Product Owner
Objetivo: Definir el conjunto mínimo viable de funcionalidades

Contexto:
MVP enfocado en:
- Registro y gestión de consultas
- Asignación de casos
- Seguimiento de estados
- Dashboard de control
- Evaluaciones y reportes

Requisitos del Entregable:

 Funcionalidades Core:
   - Registro de Consultas
   - Gestión de Consultas
   - Calificación de Consultas
   - Actualización de Consultas
   - Dashboard Personalizado

 Para cada Funcionalidad:
   - Descripción detallada
   - Flujo de usuario
   - Criterios de aceptación
   - Dependencias técnicas
   - Riesgos identificados

 Diagramas de Flujo:
   - Proceso general
   - Interacciones entre módulos
   - Estados y transiciones
   - Puntos de integración

 Consideraciones Técnicas:
   - Stack tecnológico definido
   - Restricciones técnicas
   - Requisitos de seguridad
   - Aspectos de rendimiento

Criterios de Validación:
- ¿Las funcionalidades son esenciales?
- ¿Los flujos son claros y completos?
- ¿Se consideran todos los roles de usuario?
- ¿Mantiene coherencia con el readme actual?
```

### 1.3 Diseño y Experiencia de Usuario

#### Prompt Original
```prompt
Como UX/UI Designer, ayúdame a definir la experiencia de usuario y diseño visual para un sistema de gestión de consultas jurídicas. El sistema debe usar shadcn y V0 como gestor de componentes.
```

#### Iteración Mejorada
```prompt
Rol: UX/UI Designer Senior especializado en sistemas legales
Objetivo: Definir la experiencia de usuario y sistema de diseño completo

Contexto:
Sistema profesional legal que requiere:
- Interfaz intuitiva y eficiente
- Componentes shadcn/V0
- Sistema de diseño escalable
- Implementación progresiva

Requisitos del Entregable:

 Sistema de Diseño:
   - Paleta de colores completa con códigos hexadecimales específicos
   - Tipografía y lineamientos de estilo
   - Componentes base con shadcn/V0
   - Patrones de interacción y estados

 Plan de Implementación:
   - Fase inicial MVP
   - Fases futuras
   - Evolución del diseño

 Documentación Técnica:
   - Guía de implementación
   - Configuración de componentes
   - Estándares de desarrollo

 Consideraciones de Evolución:
   - Plan de iteración
   - Proceso de feedback
   - Gestión de versiones
   - Estrategia de actualización

Criterios de Validación:
- ¿Se especifican todos los elementos visuales?
- ¿Se define claramente el plan de implementación?
- ¿La documentación es suficiente?
- ¿Mantiene coherencia con el readme actual?
```

### 1.4 Instrucciones de Instalación

#### Prompt Original
```prompt
Como DevOps engineer, ayúdame a crear instrucciones detalladas de instalación para un proyecto que usa:
- Frontend: Next.js
- Backend: .NET 9
- Base de datos: Supabase
- Contenedores: Docker
```

#### Iteración Mejorada
```prompt
Rol: DevOps Engineer Senior
Objetivo: Crear guía de instalación y configuración completa

Contexto:
Sistema que utiliza:
- Frontend: Next.js 14
- Backend: .NET 9
- Base de datos: Supabase
- Contenedores: Docker
- CI/CD implementado

Requisitos del Entregable:

28. Prerequisitos:
   - Software requerido
   - Versiones específicas
   - Configuraciones de ambiente
   - Recursos necesarios
   - Accesos y credenciales

29. Proceso de Instalación:
   - Clonación del repositorio
   - Configuración de variables
   - Construcción de contenedores
   - Inicialización de servicios
   - Verificación de funcionamiento

30. Configuración:
   - Variables de entorno
   - Conexiones a servicios
   - Configuraciones de seguridad
   - Optimizaciones
   - Monitoreo

31. Verificación:
   - Tests de instalación
   - Checklist de validación
   - Pruebas de integración
   - Logs y diagnósticos
   - Solución de problemas

Criterios de Validación:
- ¿Las instrucciones son claras y completas?
- ¿El proceso es reproducible?
- ¿Se incluyen verificaciones?
- ¿Mantiene coherencia con el readme actual?
```

## 2. Arquitectura del Sistema

## 2.1 Diagrama de Arquitectura

#### Prompt Original
```prompt
Como arquitecto de soluciones, ayúdame a diseñar la arquitectura de un sistema de gestión de consultas jurídicas que utiliza:
- Frontend: Next.js 14 + TypeScript
- Backend: .NET 9 API
- Base de datos: Supabase/PostgreSQL

Necesito:
 Un diagrama mermaid detallado que muestre:
   - Componentes principales
   - Flujo de datos
   - Integraciones
 Justificación de decisiones arquitectónicas
 Beneficios y sacrificios de la arquitectura elegida
```prompt

#### Primera Iteración
```prompt
Contexto: Estoy desarrollando Dike, un sistema de gestión de consultas jurídicas que necesita manejar información sensible legal, permitir asignación de casos a abogados y seguimiento de consultas en tiempo real. El sistema debe soportar múltiples usuarios concurrentes y garantizar la seguridad de los datos.

Stack tecnológico definido:
- Frontend: Next.js 14 + TypeScript
- Backend: .NET 9 API con patrón vertical slice
- Base de datos: Supabase/PostgreSQL
- Infraestructura: Contenedores Docker

Como arquitecto de soluciones experimentado en sistemas legales, necesito:

 Un diagrama de arquitectura en mermaid que incluya:
   - Capas de la aplicación (presentación, servicios, datos)
   - Componentes específicos de cada capa
   - Flujos de datos y comunicación entre componentes
   - Aspectos de seguridad y autenticación
   - Integración con servicios externos

 Para cada decisión arquitectónica importante:
   - Justificación técnica
   - Alternativas consideradas
   - Ventajas y desventajas
   - Impacto en requisitos no funcionales (seguridad, rendimiento, escalabilidad)

 Detalles de implementación para:
   - Gestión de estado en frontend
   - Comunicación en tiempo real
   - Manejo de documentos legales
   - Caché y optimización de rendimiento

 Consideraciones específicas sobre:
   - Seguridad de datos legales
   - Auditoría de acciones
   - Escalabilidad del sistema
   - Mantenibilidad del código

Por favor, estructura la respuesta siguiendo las secciones del documento actual en el readme.md, manteniendo coherencia con el contenido existente.
```

#### Segunda Iteración
```prompt
Rol: Arquitecto de Soluciones Senior especializado en sistemas legales
Objetivo: Diseñar la arquitectura completa del sistema Dike

Contexto:
Sistema que debe implementar:
- Feature-First Architecture (Frontend)
- Vertical Slice Architecture (Backend)
- Seguridad y auditoría completa
- Optimización de rendimiento
- Escalabilidad horizontal

Requisitos del Entregable:

 Diagrama de Arquitectura (mermaid):
   a. Capa de Presentación:
      - Server/Client Components
      - Gestión de estado
      - Optimizaciones SSR/CSR
      - Componentes Core

   b. Capa de Servicios:
      - Vertical Slices
      - Patrones por módulo
      - Validaciones
      - Event Sourcing

   c. Persistencia:
      - Supabase/PostgreSQL
      - Row Level Security
      - Realtime Updates
      - Auditoría

 Justificación Arquitectónica:
   - Feature-First vs Alternativas
   - Vertical Slices vs N-Layer
   - Decisiones de estado y caché
   - Estrategias de seguridad

 Implementación Técnica:
   - Next.js con Server/Client Components
   - .NET 9 con Vertical Slices
   - Supabase para tiempo real
   - Docker y CI/CD

 Consideraciones:
   - Performance y optimización
   - Seguridad y cumplimiento
   - Escalabilidad y mantenimiento
   - Monitoreo y logging

Formato de Entrega:
   - Diagrama detallado de arquitectura
   - Documento de decisiones arquitectónicas
   - Guías de implementación
   - Matriz de trade-offs

Criterios de Validación:
- ¿La arquitectura soporta todos los requisitos funcionales?
- ¿Se consideran aspectos de seguridad y rendimiento?
- ¿Es escalable y mantenible?
- ¿Mantiene coherencia con el readme actual?
```

## 2.2 Descripción de Componentes

#### Prompt Original
```prompt
Como arquitecto técnico, ayúdame a describir los componentes principales de un sistema de gestión jurídica que incluye:
   - Capa de presentación (Next.js)
   - Capa de servicios (.NET)
   - Capa de persistencia (Supabase)

Para cada componente necesito:
- Tecnologías específicas utilizadas
- Patrones implementados
- Propósito principal
- Interacción con otros componentes
```

#### Iteración Mejorada
```prompt
Rol: Arquitecto de Software Senior
Objetivo: Definir y documentar los componentes principales del sistema

Contexto:
Sistema distribuido con:
- Server/Client Components en Next.js
- Vertical Slices en .NET
- PostgreSQL con Row Level Security
- Integraciones en tiempo real

Requisitos del Entregable:

 Componentes Frontend:
   a. Server Components:
      - Registro de Consultas
      - Dashboard
      - SSR y optimizaciones

   b. Client Components:
      - Gestión de Consultas
      - Interacciones complejas
      - SWR y Context API

   c. Componentes Híbridos:
      - Calificación y Actualización
      - Server Actions
      - Optimistic Updates

 Componentes Backend:
   a. API Gateway:
      - Ruteo y validación
      - Autenticación/Autorización
      - Rate limiting

   b. Vertical Slices:
      - Módulo Registro (Command Pattern)
      - Módulo Gestión (CQRS)
      - Módulo Calificación (State + Event Sourcing)
      - Módulo Dashboard (Repository Pattern)

   c. Servicios Transversales:
      - Logging y monitoreo
      - Caché distribuido
      - Message bus

 Persistencia:
   a. Supabase/PostgreSQL:
      - Modelo de datos
      - Row Level Security
      - Realtime subscriptions
      - Auditoría y tracking

   b. Optimizaciones:
      - Índices y performance
      - Estrategias de caché
      - Manejo de concurrencia

 Integraciones:
   - Autenticación federada
   - Notificaciones
   - Storage de documentos
   - Logging centralizado

Formato de Entrega:
   - Documentación técnica detallada
   - Diagramas de componentes
   - Guías de implementación
   - Ejemplos de código

Criterios de Validación:
- ¿Los componentes cubren todas las funcionalidades?
- ¿Las interacciones están claramente definidas?
- ¿Se optimiza el rendimiento?
- ¿Mantiene coherencia con el readme actual?
```

## 2.3 Estructura de Ficheros

#### Prompt Original
```prompt
Como arquitecto de software, ayúdame a definir la estructura de ficheros del proyecto Dike, considerando:
- Arquitectura modular
- Frontend Next.js
- Backend .NET
- Patrones implementados
```

#### Iteración Mejorada
```prompt
Rol: Arquitecto de Software Senior
Objetivo: Definir la organización y estructura completa del proyecto

Contexto:
Proyecto que implementa:
- Feature-First (Frontend)
- Vertical Slices (Backend)
- Arquitectura modular
- Separación clara de responsabilidades

Requisitos del Entregable:

 Estructura General:
   a. Frontend (Next.js):
      - /app (rutas y páginas)
      - /components (componentes reutilizables)
      - /features (módulos principales)
      - /lib (utilidades y servicios)
      - /styles (estilos globales)

   b. Backend (.NET):
      - /src
        - /Dike.Api
        - /Dike.Application
        - /Dike.Domain
        - /Dike.Infrastructure
      - /tests
        - /Dike.Api.Tests
        - /Dike.Application.Tests
        - /Dike.Domain.Tests

   c. Documentación:
      - /docs
        - /architecture
        - /api
        - /user_manual

 Por Módulo Frontend:
   - Componentes
   - Hooks
   - Servicios
   - Tests
   - Tipos

 Por Slice Backend:
   - Commands/Queries
   - Handlers
   - DTOs
   - Validations
   - Tests

 Configuraciones:
   - Docker
   - CI/CD
   - Environments
   - Logging
   - Monitoring

Formato de Entrega:
62. Árbol de directorios completo
63. README por directorio principal
64. Guías de organización
65. Estándares de nombrado

Criterios de Validación:
- ¿La estructura sigue patrones establecidos?
- ¿Facilita el desarrollo y mantenimiento?
- ¿Está bien documentada?
- ¿Mantiene coherencia con el readme actual?
```

## 2.4 Infraestructura y Despliegue

#### Prompt Original
```prompt
Como DevOps Engineer, define la infraestructura y proceso de despliegue para un sistema de gestión de consultas jurídicas usando Google Cloud Platform, con:
- Frontend en Next.js
- Backend en .NET 9
- Base de datos Supabase
- Contenedores Docker
```

#### Iteración Mejorada
```prompt
Rol: DevOps/Cloud Architect Senior
Objetivo: Diseñar la infraestructura y proceso de despliegue completo

Contexto:
Sistema que requiere:
- Alta disponibilidad (99.9%)
- Escalabilidad horizontal
- Seguridad de datos legales
- Despliegue automatizado
- Monitoreo continuo
- RPO 1 hora, RTO 4 horas

Requisitos del Entregable:

 Infraestructura Cloud (GCP):
   a. Servicios:
      - Cloud Run para Frontend/Backend
      - Cloud SQL para base de datos
      - Cloud Storage para assets
      - Cloud KMS para secretos

   b. Networking:
      - VPC configuración
      - SSL/TLS
      - Firewall rules
      - Load balancing

 CI/CD Pipeline:
   a. Proceso:
      - Build
      - Test
      - Security scan
      - Deploy
      - Smoke tests

   b. Ambientes:
      - Desarrollo
      - Staging
      - Producción

 Monitoreo:
   - Métricas clave
   - Logs centralizados
   - Alertas
   - Dashboard operativo
   - Análisis de performance

 Recuperación:
   - Estrategia de backup
   - Proceso de restore
   - Disaster recovery
   - Failover automático

Formato de Entrega:
   - Diagrama de infraestructura (mermaid)
   - Documentación técnica
   - Scripts de automatización
   - Runbooks operativos

Criterios de Validación:
- ¿La infraestructura cumple SLAs?
- ¿El proceso de CI/CD es robusto?
- ¿Se garantiza la seguridad?
- ¿Mantiene coherencia con el readme actual?
```

## 2.5 Seguridad

#### Prompt Original
```prompt
Como especialista en seguridad, define las prácticas de seguridad para un sistema de gestión de consultas jurídicas, incluyendo:
- Autenticación y autorización
- Protección de datos
- Auditoría
- Compliance
```

#### Iteración Mejorada
```prompt
Rol: Arquitecto de Seguridad Senior
Objetivo: Definir la arquitectura de seguridad completa

Contexto:
Sistema legal que maneja:
- Información confidencial
- Datos personales
- Documentos legales
- Accesos multiusuario
- Requisitos de compliance

Requisitos del Entregable:

 Control de Acceso:
   a. Autenticación:
      - NextAuth.js implementation
      - Tokens JWT
      - SSO
      - MFA

   b. Autorización:
      - RBAC
      - Row Level Security
      - Fine-grained permissions
      - Token validation

 Seguridad de Datos:
   a. En tránsito:
      - TLS/SSL
      - API security
      - Encryption
      - Secure headers

   b. En reposo:
      - Database encryption
      - File encryption
      - Key management
      - Secure backup

 Auditoría:
   - Logging detallado
   - Tracking de cambios
   - Monitoreo de accesos
   - Alertas de seguridad
   - Reportes de compliance

 Implementación:
   - Validación de entradas
   - Sanitización de datos
   - Protección contra ataques
   - Manejo de errores
   - Rate limiting

Formato de Entrega:
   - Arquitectura de seguridad
   - Políticas y procedimientos
   - Guías de implementación
   - Matriz de riesgos

Criterios de Validación:
- ¿Se protegen adecuadamente los datos?
- ¿Se cumple con estándares de seguridad?
- ¿Existe auditoría completa?
- ¿Mantiene coherencia con el readme actual?
```

## 2.6 Tests

#### Prompt Original
```prompt
Como QA Lead, define la estrategia de testing para un sistema de gestión de consultas jurídicas, incluyendo:
- Tests unitarios
- Tests de integración
- Tests E2E
- Performance testing
```

#### Iteración Mejorada
```prompt
Rol: QA Lead & Test Architect
Objetivo: Definir la estrategia y framework de testing completo

Contexto:
Sistema que requiere:
- Alta confiabilidad
- Cobertura completa
- Tests automatizados
- Validación de performance
- Verificación de seguridad

Requisitos del Entregable:

82. Estrategia de Testing:
   a. Tests Unitarios:
      - Frontend (Jest + RTL)
      - Backend (xUnit.net)
      - Mocking
      - Cobertura >80%

   b. Tests de Integración:
      - API testing
      - Database integration
      - External services
      - End-to-end flows

   c. Tests Especializados:
      - Performance
      - Seguridad
      - Accesibilidad
      - Usabilidad

83. Implementación:
   a. Setup:
      - Frameworks
      - Herramientas
      - CI/CD integration
      - Reporting

   b. Datos de Prueba:
      - Test data generation
      - Fixtures
      - Mocks
      - Cleanup

  Automatización:
   - Pipeline integration
   - Scheduled runs
   - Report generation
   - Alert system

  Monitoreo:
   - Coverage tracking
   - Performance metrics
   - Quality gates
   - Trend analysis

Formato de Entrega:
   - Plan de testing
   - Configuración de frameworks
   - Ejemplos de tests
   - Documentación de procesos

Criterios de Validación:
- ¿La cobertura es adecuada?
- ¿Los tests son mantenibles?
- ¿Se automatizan los procesos clave?
- ¿Mantiene coherencia con el readme actual?
```


---

## 3. Modelo de Datos

### 3.1 Diagrama del Modelo de Datos

#### Prompt Original
```prompt
Como diseñador de bases de datos, ayúdame a crear un modelo de datos para un sistema de gestión de consultas jurídicas usando mermaid. El sistema debe manejar:
- Información de personas (abogados y consultantes)
- Datos de clientes
- Consultas jurídicas
- Relaciones entre entidades

Necesito:
 - Diagrama entidad-relación en mermaid
 - Definición de campos principales
 - Relaciones entre tablas
 - Restricciones y claves
```

#### Primera Iteración
```prompt
Rol: Arquitecto de Datos especializado en sistemas legales
Objetivo: Diseñar un modelo de datos completo para el sistema Dike

Contexto: 
Necesitamos diseñar un modelo de datos para un sistema de gestión de consultas jurídicas que debe:
  - Mantener información detallada de personas y sus roles
  - Gestionar relaciones cliente-abogado
  - Tracking completo de consultas jurídicas
  - Soporte para documentos legales
  - Auditoría de cambios
  - Cumplir con regulaciones de protección de datos

Entidades Principales Requeridas:
   - Personas
   - Información de identificación
   - Datos de contacto
   - Roles en el sistema
   
   - Clientes
   - Información comercial
   - Estado de afiliación
   - Historial de servicios

   - Abogados
   - Especialidades
   - Carga de trabajo
   - Métricas de desempeño

   - Consultas
   - Información básica
   - Estados y transiciones
   - Asignaciones
   - Historial de cambios

   - Documentos
   - Metadatos
   - Versionamiento
   - Trazabilidad

Requisitos Específicos:
  - Diagrama ER en mermaid que muestre:
   - Todas las entidades con atributos
   - Relaciones y cardinalidad
   - Claves primarias y foráneas
   - Índices importantes

  - Para cada tabla:
   - Definición completa de campos
   - Tipos de datos
   - Restricciones
   - Justificación de diseño

  - Consideraciones de:
   - Normalización
   - Rendimiento
   - Escalabilidad
   - Seguridad de datos

   - Estrategias para:
   - Auditoría de cambios
   - Soft delete
   - Versionamiento
   - Backup y recuperación

Criterios de Validación:
- ¿Cumple con la tercera forma normal?
- ¿Soporta todos los casos de uso del sistema?
- ¿Permite escalabilidad futura?
- ¿Facilita la auditoría y trazabilidad?
```

#### Segunda Iteración
```prompt
Rol: Arquitecto de Datos Senior especializado en sistemas legales
Objetivo: Diseñar el modelo de datos detallado para Dike

Contexto:
Sistema que requiere modelar:
- Gestión completa de consultas jurídicas
- Múltiples roles de usuario
- Seguimiento de estados
- Auditoría completa
- Documentación legal

Requisitos del Entregable:

 Diagrama ER (mermaid):
   a. Entidades Core:
      PERSONA {
        UUID id PK
        STRING tipo_documento
        STRING numero_documento
        STRING primer_nombre
        STRING segundo_nombre
        STRING primer_apellido
        STRING segundo_apellido
      }
      
      CLIENTE {
        UUID id PK
        STRING tipo_documento
        STRING numero_documento
        STRING razon_social
        STRING estado_afiliacion
        BOOLEAN verificado
      }
      
      CONSULTANTE {
        UUID id PK
        UUID persona_id FK
        UUID cliente_id FK
        STRING correo
        STRING numero_celular
      }
      
      ABOGADO {
        UUID id PK
        UUID persona_id FK
        STRING alias
      }
      
      CONSULTA {
        UUID id PK
        UUID cliente_id FK
        UUID consultante_id FK
        UUID abogado_titular_id FK
        STRING motivo_consulta
        STRING estado
        TIMESTAMP fecha_creacion
      }

   Definición Detallada:
   a. Para cada entidad:
      - Descripción del propósito
      - Campos completos con tipos
      - Restricciones específicas
      - Índices necesarios
      - Justificación de diseño

   b. Relaciones:
      - Cardinalidad exacta
      - Reglas de integridad
      - Cascade rules
      - Índices de relación

  Consideraciones Técnicas:
   a. Normalización:
      - Justificación de nivel
      - Manejo de redundancia
      - Optimizaciones
      
   b. Performance:
      - Estrategia de índices
      - Particionamiento
      - Query optimization
      
   c. Seguridad:
      - Row Level Security
      - Encryption at rest
      - Audit logging

   Implementación:
   - Scripts de creación
   - Migraciones
   - Datos iniciales
   - Pruebas de integridad

Formato de Entrega:
 - Diagrama ER completo
 - Documentación detallada
 - Scripts de implementación
 - Guías de mantenimiento

Criterios de Validación:
- ¿El modelo soporta todos los casos de uso?
- ¿Las relaciones están correctamente definidas?
- ¿Se mantiene la integridad referencial?
- ¿Se facilita el mantenimiento y la escalabilidad?
- ¿Mantiene coherencia con el readme actual?
```

### 3.2 Descripción de Entidades

#### Prompt Original
```prompt
Como arquitecto de datos, proporciona una descripción detallada de las entidades principales del sistema de gestión de consultas jurídicas, incluyendo:
- Propósito de cada entidad
- Atributos y tipos de datos
- Relaciones y cardinalidad
- Restricciones y reglas de negocio
```

#### Iteración Mejorada
```prompt
Rol: Arquitecto de Datos Senior
Objetivo: Documentar en detalle las entidades del sistema

Contexto:
Documentación completa de:
- 5 entidades principales
- Relaciones entre entidades
- Reglas de negocio
- Consideraciones técnicas

Requisitos del Entregable:

 Para cada Entidad (PERSONA, CLIENTE, CONSULTANTE, ABOGADO, CONSULTA):
   a. Descripción General:
      - Propósito en el sistema
      - Rol en el negocio
      - Ciclo de vida
      - Consideraciones especiales

   b. Atributos Detallados:
      - Nombre y tipo de dato
      - Descripción y propósito
      - Restricciones (NOT NULL, UNIQUE, etc.)
      - Valores permitidos
      - Reglas de validación

   c. Relaciones:
      - Entidades relacionadas
      - Tipo de relación
      - Cardinalidad
      - Reglas de integridad
      - Cascade behavior

   d. Consideraciones Técnicas:
      - Índices requeridos
      - Estrategias de particionamiento
      - Optimizaciones
      - Seguridad
      - Auditoría

 Reglas de Negocio:
   - Validaciones cruzadas
   - Reglas de estado
   - Cálculos derivados
   - Restricciones temporales
   - Políticas de acceso

 Aspectos de Implementación:
   - Estrategias de consulta
   - Manejo de cambios
   - Versionamiento
   - Respaldo
   - Mantenimiento

Formato de Entrega:
  - Documentación estructurada
  - Ejemplos de uso
  - Guías de implementación
  - Consideraciones operativas

Criterios de Validación:
- ¿La documentación es completa y clara?
- ¿Se cubren todos los aspectos técnicos?
- ¿Las reglas de negocio están bien definidas?
- ¿Mantiene coherencia con el readme actual?
```


---

## 4. Especificación de la API

#### Prompt Original
```prompt
Como arquitecto de APIs, ayúdame a definir la especificación OpenAPI para un sistema de gestión jurídica. Necesito documentar los endpoints principales para:
 - Gestión de clientes
 - Manejo de consultas
 - Administración de abogados

Incluye para cada endpoint:
- Método HTTP
- Ruta
- Parámetros
- Respuestas
- Ejemplos de petición y respuesta
```

#### Primera Iteración
```prompt
Rol: Arquitecto de APIs Senior
Objetivo: Diseñar la especificación completa de la API de Dike

Contexto:
API RESTful para:
- Gestión de consultas jurídicas
- Manejo de usuarios y roles
- Documentos legales
- Reportes y métricas
- Integraciones

Requisitos del Entregable:

 Especificación OpenAPI:
   - Info y versión
   - Servers y endpoints
   - Schemas de datos
   - Seguridad
   - Responses comunes

 Por Endpoint:
   - Propósito
   - Método HTTP
   - Ruta
   - Request/Response schemas
   - Ejemplos
   - Validaciones
   - Códigos de error

 Seguridad:
   - Autenticación
   - Autorización
   - Rate limiting
   - Validaciones
   - Manejo de errores

 Documentación:
   - Guías de uso
   - Ejemplos completos
   - Postman collections
   - Swagger UI
   - Troubleshooting

Formato de Entrega:
 - Documento OpenAPI (YAML/JSON)
 - Documentación detallada
 - Ejemplos de uso
 - Guías de implementación

Criterios de Validación:
- ¿La API cubre todas las funcionalidades?
- ¿La documentación es clara y completa?
- ¿Los ejemplos son útiles?
- ¿Mantiene coherencia con el readme actual?
```

#### Segunda Iteración
```prompt
Rol: Arquitecto de APIs Senior especializado en sistemas legales
Objetivo: Diseñar una API RESTful completa para Dike

Contexto:
Sistema que requiere endpoints para:
- CRUD de clientes, consultas y abogados
- Gestión de estados y asignaciones
- Manejo de documentos
- Reportes y métricas
- Auditoría y trazabilidad

Requisitos del Entregable:

 Especificación OpenAPI 3.0.1:
   a. Información Base:
      ```yaml
      openapi: 3.0.1
      info:
        title: API de Dike
        version: 1.0.0
      servers:
        - url: https://api.dike.com/v1
      ```

   b. Endpoints Principales:
      - /clientes (GET, POST)
      - /consultas (GET, POST)
      - /abogados (GET, POST)
      Con ejemplos completos de requests y responses

   c. Schemas:
      - Cliente
      - Consulta
      - Abogado
      Incluyendo todas las propiedades y tipos

 Documentación Detallada:
   a. Por Endpoint:
      - Descripción completa
      - Parámetros esperados
      - Validaciones
      - Respuestas posibles
      - Ejemplos reales

 Modelos de Datos:
      - Estructura completa
      - Restricciones
      - Relaciones
      - Validaciones

Seguridad y Control:
   - Autenticación JWT
   - Roles y permisos
   - Rate limiting
   - Validación de datos
   - Manejo de errores

 Ejemplos de Uso:
   a. Requests Completos:
      ```http
      POST /clientes HTTP/1.1
      Host: api.dike.com
      Content-Type: application/json

      {
        "tipo_documento": "NIT",
        "numero_documento": "123456789",
        "razon_social": "Empresa Ejemplo S.A.",
        "estado_afiliacion": "Activo",
        "verificado": true
      }
      ```

   b. Responses:
      ```thttp
      HTTP/1.1 201 Created
      Content-Type: application/json

      {
        "id": "550e8400-e29b-41d4-a716-446655440000",
        "tipo_documento": "NIT",
        "numero_documento": "123456789",
        "razon_social": "Empresa Ejemplo S.A.",
        "estado_afiliacion": "Activo",
        "verificado": true
      }
      ```

Formato de Entrega:
- Archivo OpenAPI (YAML)
- Documentación técnica
- Colección de ejemplos
- Guías de implementación

Criterios de Validación:
- ¿La especificación es completa y precisa?
- ¿Los endpoints cubren todos los casos de uso?
- ¿Los ejemplos son claros y útiles?
- ¿Se mantiene coherencia con el readme actual?
- ¿La documentación facilita la implementación?
```

---

## 5. Historias de Usuario

#### Prompt Original
```prompt
Como Product Owner, ayúdame a crear 3 historias de usuario principales para un sistema de gestión de consultas jurídicas. Necesito para cada historia:
- Título descriptivo
- Narrativa en formato "Como [rol] quiero [acción] para [beneficio]"
- Criterios de aceptación detallados
- Descripción del valor de negocio
```

#### Primera Iteración
```prompt
Rol: Product Owner Senior
Objetivo: Definir las historias de usuario principales para Dike

Contexto:
Sistema que requiere historias para:
- Registro y asignación de consultas
- Gestión de casos por abogados
- Seguimiento de estados
- Evaluación de resultados

Requisitos del Entregable:

 Por Historia:
   - Título descriptivo
   - Narrativa completa
   - Roles involucrados
   - Valor de negocio
   - Impacto esperado

 Criterios de Aceptación:
   - Condiciones específicas
   - Escenarios de prueba
   - Reglas de negocio
   - Validaciones requeridas
   - Estados esperados

 Detalles Técnicos:
   - Dependencias
   - UI/UX considerations
   - Requisitos de seguridad
   - Restricciones técnicas
   - Métricas de éxito

Documentación:
   - Mockups
   - Flujos de trabajo
   - Reglas de negocio
   - Casos de uso
   - Notas adicionales

Formato de Entrega:
 - Historias detalladas
 - Criterios de aceptación
 - Documentación técnica
 - Material de soporte

Criterios de Validación:
- ¿Las historias son claras y completas?
- ¿Los criterios son verificables?
- ¿El valor de negocio es evidente?
- ¿Mantiene coherencia con el readme actual?
```

#### Segunda Iteración
```prompt
Rol: Product Owner Senior especializado en sistemas legales
Objetivo: Definir historias de usuario detalladas para las funcionalidades core de Dike

Contexto:
Necesitamos historias que cubran:
- Registro y asignación de consultas por clientes internos
- Gestión de consultas por abogados asignados
- Actualización del estado de consultas por consultantes

Requisitos del Entregable:

 Historia 1: Registro y Asignación de Consultas
   a. Narrativa:
      Como cliente interno
      Quiero registrar una nueva consulta jurídica y asignarla al abogado más adecuado
      Para garantizar que el caso sea atendido de manera eficiente y especializada

   b. Descripción Detallada:
      - Proceso de registro
      - Criterios de asignación
      - Flujo de trabajo
      - Notificaciones

   c. Criterios de Aceptación:
      - Formulario de registro completo
      - Validaciones específicas
      - Proceso de asignación
      - Confirmaciones requeridas

 Historia 2: Gestión de Consultas
   a. Narrativa:
      Como abogado titular
      Quiero gestionar las consultas jurídicas asignadas desde mi panel
      Para brindar seguimiento adecuado y mantener informados a los consultantes

   b. Descripción Detallada:
      - Panel de gestión
      - Estados y transiciones
      - Comunicación con consultantes
      - Registro de avances

   c. Criterios de Aceptación:
      - Visualización de consultas asignadas
      - Actualización de estados
      - Registro de acciones
      - Notificaciones automáticas

 Historia 3: Actualización de Consultas
   a. Narrativa:
      Como consultante autorizado
      Quiero proporcionar información adicional sobre mi consulta
      Para asegurar que el abogado tenga todos los detalles necesarios

   b. Descripción Detallada:
      - Acceso a consultas
      - Adición de información
      - Comunicación con abogados
      - Seguimiento de estado

   c. Criterios de Aceptación:
      - Interfaz de actualización
      - Validación de permisos
      - Notificaciones a involucrados
      - Registro de cambios

Formato de Entrega:
 Historias completas con:
   - Narrativa
   - Descripción
   - Criterios de aceptación
   - Notas técnicas
   - Consideraciones de implementación

 Documentación Adicional:
   - Flujos de usuario
   - Mockups relevantes
   - Reglas de negocio
   - Dependencias

Criterios de Validación:
- ¿Las historias reflejan necesidades reales de usuarios?
- ¿Los criterios son específicos y medibles?
- ¿Se considera el flujo completo de trabajo?
- ¿Mantiene coherencia con el readme actual?
- ¿Las historias facilitan la implementación?
```


---

### 6. Tickets de Trabajo

#### Prompt Original
```prompt
Como Tech Lead, ayúdame a crear 3 tickets de trabajo detallados (1 backend, 1 frontend, 1 base de datos) para implementar el registro de consultas jurídicas. Para cada ticket necesito:
 Descripción técnica detallada
 Requisitos específicos
 Criterios de aceptación
 Consideraciones técnicas
 Referencias a historias de usuario relacionadas
```

#### Primera Iteración
```prompt
Rol: Tech Lead Senior
Objetivo: Crear tickets técnicos detallados para la implementación del sistema

Contexto:
Implementación de:
- Backend en .NET 9
- Frontend en Next.js 14
- Base de datos en Supabase
- Integración continua

Requisitos por Ticket:

168. Información General:
   - Título descriptivo
   - Tipo (backend/frontend/database)
   - Prioridad y estimación
   - Referencias a historias
   - Dependencias

169. Especificación Técnica:
   - Alcance detallado
   - Arquitectura afectada
   - Cambios requeridos
   - Consideraciones de seguridad
   - Impacto en el sistema

170. Criterios de Aceptación:
   - Requisitos funcionales
   - Requisitos no funcionales
   - Casos de prueba
   - Métricas de calidad
   - Definition of Done

171. Implementación:
   - Guías de código
   - Estándares a seguir
   - Pruebas requeridas
   - Documentación necesaria
   - Monitoreo

Formato de Ticket:
172. Descripción general
173. Especificación técnica
174. Criterios de aceptación
175. Tasks específicos
176. Documentación requerida

Criterios de Validación:
- ¿El alcance está bien definido?
- ¿Los criterios son medibles?
- ¿Se consideran todos los aspectos técnicos?
- ¿Mantiene coherencia con el readme actual?
```

#### Segunda Iteración
```prompt
Rol: Tech Lead Senior especializado en sistemas legales
Objetivo: Definir tickets técnicos detallados para la implementación del registro de consultas

Contexto:
Sistema que requiere:
- Endpoint de registro en .NET 9
- Formulario en Next.js 14
- Modelo de datos en Supabase
- Tests automatizados
- Documentación completa

Requisitos del Entregable:

177. Ticket Backend - Endpoint de Registro:
   a. Descripción:
      Implementar endpoint en .NET 9 que permita al cliente interno registrar una nueva consulta jurídica y asignarla a un abogado específico.

   b. Especificación Técnica:
      - Ruta: POST /api/consultas
      - Validaciones de entrada
      - Manejo de errores
      - Logging y monitoreo
      - Seguridad y autenticación

   c. Criterios de Aceptación:
      - Endpoint funcional y documentado
      - Validaciones implementadas
      - Tests unitarios y de integración
      - Logging configurado
      - Documentación API actualizada

178. Ticket Frontend - Formulario de Registro:
   a. Descripción:
      Desarrollar formulario en Next.js para el registro de consultas jurídicas con validaciones y asignación de abogados.

   b. Especificación Técnica:
      - Componentes React
      - Validaciones cliente
      - Estado y manejo de errores
      - UI/UX según diseño
      - Integración con API

   c. Criterios de Aceptación:
      - Formulario funcional
      - Validaciones implementadas
      - Feedback al usuario
      - Tests de componentes
      - Responsive design

179. Ticket Base de Datos - Modelo de Consultas:
   a. Descripción:
      Implementar estructura de base de datos para el registro y gestión de consultas jurídicas.

   b. Especificación Técnica:
      - Modelo de datos
      - Índices y constraints
      - Procedimientos almacenados
      - Triggers de auditoría
      - Seguridad y permisos

   c. Criterios de Aceptación:
      - Esquema implementado
      - Migraciones creadas
      - Índices optimizados
      - Tests de integración
      - Documentación actualizada

180. Para cada ticket:
   a. Tasks Específicos:
      - Desarrollo
      - Testing
      - Documentación
      - Review
      - Deploy

   b. Consideraciones:
      - Performance
      - Seguridad
      - Mantenibilidad
      - Escalabilidad
      - Monitoreo

Formato de Entrega:
181. Tickets detallados con:
   - Descripción técnica
   - Criterios de aceptación
   - Tasks específicos
   - Documentación requerida
   - Consideraciones adicionales

182. Documentación Adicional:
   - Diagramas técnicos
   - Ejemplos de código
   - Guías de implementación
   - Plan de pruebas

Criterios de Validación:
- ¿Los tickets son implementables?
- ¿Los criterios son verificables?
- ¿Se considera la integración completa?
- ¿Mantiene coherencia con el readme actual?
- ¿Se facilita el desarrollo y testing?
```


---

### 7. Pull Requests

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**
