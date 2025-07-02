---
title: "4. Desarrollar Épicas"
meta_title: ""
description: "meta description"
date: 2025-04-28T04:00:00+00:00
image: "/images/posts/04-4.jpg"
authors: ["Dafne Huertas"]
tags: ["XP", "Épicas"]
draft: false
categories: ["xp"]
---
### Entradas

#### 4.1 Equipo principal XP

De los puntos anteriores hemos obtenido el equipo completo para el desarrollo de este proyecto. Cumpliendo los siguientes roles:

- Jefe de Proyecto: Smith Ramos
- Coach: Dafne Huertas
- Tester: Diego Caballero
- Tracker: Dafne Huertas
- Equipo de Desarrollo:
- Desarrollador Backend: Arian Sevillano
- Desarrollador Móvil 1: Diego Caballero
- Desarrollador Móvil 2: Andre Fernandez

<img src="/images/xp/consolidado_roles.png" 
     alt="Roles XP Identificado" 
     style="display: block; margin: 20px auto; max-width: 35%;" />

#### 4.2. Declaración de la visión del proyecto

##### **Documento adjunto:**
 🗎 [Declaración de la visión del proyecto - Diamond BarberShop App](https://docs.google.com/document/d/10uRcqr6bJ-H-qqzbuojhRv3YDPEu_928QwsCWa_LyCU/edit?usp=sharing)

### Herramientas

#### 4.3. Reuniones de grupo de usuarios

Se realizaron reuniones de grupo de usuarios junto a el equipo XP principal y clientes para clarificar las ideas y que estas puedan apreciarse de manera clara en las épicas a plantear.
<img src="/images/sprint_2/reunion_mas_stakeholder.jpg" 
     alt="Reuniones de grupo de usuarios" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

#### 4.4. Reuniones del grupo de enfoque

Se realizaron reuniones de grupo de enfoque para el apoyo de todos en la priorización de las épicas, además de resolver dudas que alguno de los desarrolladores tenga respecto a la idea del proyecto.
<img src="/images/sprint_2/scrum_team.jpg" 
     alt="Reuniones de grupo de enfoque" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

### Salidas

#### 4.5 Épicas

Posterior a la reunión entre todos los integrantes del equipo XP, se establecieron las siguientes épicas.

**1. Autenticación y maquetas móviles**

Descripción: En esta épica se implementa el flujo de acceso al sistema mediante login, diferenciando los roles de cliente y administrador. Incluye el desarrollo de la API de autenticación en Spring Boot, la conexión con la base de datos de usuarios, y la creación de las pantallas base (mockups) en multiplataforma para cada rol. Al cierre, los usuarios podrán iniciar sesión correctamente y navegar a sus respectivas vistas iniciales.

**2. Gestión de servicios y barberos**

Descripción: Aquí se construyen las funcionalidades que permiten al administrador crear, editar y eliminar tanto los servicios ofrecidos (cortes, barba, tratamientos) como los barberos y sus horarios de atención. Se desarrollan endpoints CRUD en el backend y las interfaces móviles necesarias para listar, registrar y modificar estos datos, garantizando validaciones de disponibilidad y consistencia en el calendario de trabajo.

**3. Funcionalidades de reservas, historial, pagos, notificaciones y landing**

Descripción: Esta épica abarca el “carrito de reserva” para que el cliente seleccione servicios y extras, elija fecha y hora, y genere una cita. Incluye la lógica de back‑office para que el administrador pueda confirmar o cancelar reservas, así como la puesta en marcha de una integración básica para enviar notificaciones automáticas vía WhatsApp al cliente con el estado de su cita con alertas y creación de landing page.

**4. Recompensas y reportes**

Descripción: En la última fase se implementa el historial de citas por cliente y la lógica de recompensas (corte gratis cada 10 citas), además de los reportes de ingresos. El administrador obtiene vistas filtrables por cliente, fecha o servicio, mientras el cliente ve en su perfil cuántas citas lleva acumuladas y cuándo alcanza su siguiente beneficio. Se incluyen ajustes finales de interfaz y optimización de rendimiento.

 📷 Imagenes de [épicas en Jira]
 <img src="/images/xp/epicas_sprint4.png" 
     alt="Epicas en Jira" 
     style="display: block; margin: 20px auto; max-width: 100%;" />
     