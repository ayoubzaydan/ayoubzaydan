# 🚗 Aplicación Móvil para la Gestión de Reservas en un Lavadero de Coches (CarWash)

![CarWash App](https://apptechllc.com/wp-content/uploads/car-wash.jpg)


[![Android Studio](https://img.shields.io/badge/Android%20Studio-Kotlin-blue.svg)](https://developer.android.com/studio)

---

## 📌 Descripción del Proyecto
Este proyecto consiste en el desarrollo de una aplicación móvil intuitiva para la gestión de reservas en un lavadero de coches. La aplicación permitirá a los clientes:
- Programar citas para el lavado de sus vehículos.
- Seleccionar entre distintos tipos de lavado.
- Consultar su historial de servicios.
- Recibir notificaciones sobre recordatorios y promociones.

🎯 **Objetivos:**
- Desarrollar una aplicación móvil intuitiva.
- Brindar opciones para seleccionar diferentes tipos de lavado disponibles.
- Permitir a los usuarios visualizar su historial de servicios.
- Enviar notificaciones para recordar citas y promociones.

---

## 🏢 Vinculación a Empresa
- No se encuentra vinculada a ninguna empresa.

---

## 📋 Actividades a Realizar

### 🔍 1. Análisis y Planificación
- Definir requisitos funcionales y no funcionales.
- Diseñar la arquitectura de la aplicación.

### 🎨 2. Diseño de la Interfaz
- Crear un prototipo de la aplicación utilizando herramientas de diseño.
- Definir un diseño UX/UI enfocado en mejorar la experiencia del usuario.

### 💻 3. Desarrollo
- Implementación del frontend utilizando Kotlin en Android Studio.
- Desarrollo de la base de datos local en SQL Server.
- Implementación de la lógica de reservas y gestión de usuarios.

### ✅ 4. Pruebas y Optimización
- Realizar pruebas de funcionalidad y usabilidad.
- Optimizar el rendimiento de la aplicación.

---

## 🛠️ Recursos Necesarios

### 🖥️ Hardware
| Recurso | Descripción |
|---------|-------------|
| Equipo Informático | Sistema operativo Windows |
| Conexión a Internet | Necesaria para desarrollo y pruebas |

### 🖥️ Software y Tecnologías
| Software | Uso |
|----------|-----|
| Android Studio | Desarrollo de la aplicación móvil |
| Kotlin | Lenguaje de programación principal |
| SQL Server | Almacenamiento de datos |
| Figma | Diseño de interfaz |

---

## 🌐 Otras Consideraciones
- 🔗 Posible integración con una plataforma web para la gestión administrativa.
- 💳 Evaluación de futuras mejoras como pago en línea y geolocalización de lavaderos cercanos.

---

## 📺 Video Demostrativo
[![Texto alternativo](https://apptechllc.com/wp-content/uploads/car-wash.jpg)](https://www.youtube.com/watch?v=vJapzH_46a8&list=PL8ie04dqq7_OcBYDpvHrcSFVoggLi3cm_)
---

## 📊 Gráfica Circular de Tipos de Lavado
```mermaid
graph TD;
    A[Tipos de Lavado] -->|Económico| B(Económico - 30%)
    A -->|Estándar| C(Estándar - 50%)
    A -->|Premium| D(Premium - 20%)
```

---

## 📜 Diagrama de Flujo de Reserva
```mermaid
flowchart TD;
    A[Inicio] --> B[Seleccionar Tipo de Lavado]
    B --> C[Seleccionar Fecha y Hora]
    C --> D[Confirmar Reserva]
    D --> E[Notificación Enviada]
    E --> F[Reserva Exitosa]
```

---

## 🔄 Diagrama de Secuencia de una Reserva
```mermaid
sequenceDiagram
    participant Usuario
    participant App
    participant Servidor
    Usuario->>App: Selecciona tipo de lavado
    App->>Servidor: Envía solicitud de reserva
    Servidor->>App: Confirma disponibilidad
    App->>Usuario: Muestra confirmación
    App->>Servidor: Guarda reserva
    Servidor->>Usuario: Envía notificación
```

---

## 🗂️ Diagrama Entidad-Relación
```mermaid
erDiagram
    Usuario ||--o{ Reserva : hace
    Reserva ||--|{ Servicio : incluye
    Usuario {
        int id
        string nombre
        string correo
    }
    Reserva {
        int id
        date fecha
        int usuario_id
    }
    Servicio {
        int id
        string tipo
        float precio
    }
```

---

## 📅 Diagrama Gantt de Desarrollo
```mermaid
gantt
title Cronograma de Desarrollo
    section Planificación
    Análisis de requisitos :done, a1, 2025-03-20, 2025-03-30
    Diseño de arquitectura :done, a2, 2025-03-31, 2025-04-10
    section Desarrollo
    Implementación frontend :active, a3, 2025-04-11, 2025-05-05
    Desarrollo base de datos :a4, 2025-05-06, 2025-05-20
    section Pruebas
    Pruebas de funcionalidad :a5, 2025-05-21, 2025-05-30
    Optimización y entrega :a6, 2025-06-01, 2025-06-10
```

---

## 🌳 Diagrama Git Workflow
```mermaid
gitGraph
    commit
    branch feature/reservas
    checkout feature/reservas
    commit
    checkout main
    merge feature/reservas
    commit
```

---

## 📅 Diagrama Gantt de Desarrollo
```mermaid
gantt
title Cronograma de Desarrollo
    section Planificación
    Análisis de requisitos :done, a1, 2024-02-01, 2024-02-10
    Diseño de arquitectura :done, a2, 2024-02-11, 2024-02-20
    section Desarrollo
    Implementación frontend :active, a3, 2024-02-21, 2024-03-15
    Desarrollo base de datos :a4, 2024-03-16, 2024-03-30
    section Pruebas
    Pruebas de funcionalidad :a5, 2024-04-01, 2024-04-10
    Optimización y entrega :a6, 2024-04-11, 2024-04-20
```

---

## 📌 Diagrama de Requerimientos
```mermaid
mindmap
  root((Requerimientos))
    Funcionales
      Reservas en línea
      Historial de servicios
    No Funcionales
      Seguridad
      Usabilidad
```

---

## 📞 Contacto
📧 Para más información sobre el proyecto, puedes contactar al equipo de desarrollo.

[Volver al inicio](#🚗-Aplicación-Móvil-para-la-Gestión-de-Reservas-en-un-Lavadero-de-Coches-CarWash)
