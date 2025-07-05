---
title: "13. Crear entregables"
meta_title: ""
description: "meta description"
date: 2025-05-02T13:20:00+00:00
image: "/images/posts/13-4.png"
categories: ["xp"]
authors: ["Dafne Huertas"]
tags: ["Tareas", "Entregables"]
draft: false
---
### Entradas

#### 13.1. Equipo principal XP

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

#### 13.2. Sprint Backlog
El Sprint Backlog incluye:
- Historias de usuario comprometidas.
- Tareas identificadas y asignadas a los miembros del equipo.
- Estimaciones de esfuerzo para cada tarea.

##### **Documento adjunto:**
 🗎 [Sprint Backlog](https://docs.google.com/spreadsheets/d/1nYnzbE_RGJRdWk0OzwQJm9pGUs4zZNcP/edit?usp=sharing&ouid=105357714069578698229&rtpof=true&sd=true)

Este documento se actualizará a medida que avanzamos en la iteración, permitiendo al equipo mantener una visión clara de las tareas completadas y las que están en progreso.

#### 13.3. Scrumboard 
El Scrumboard desempeña un papel fundamental al permitir visualizar el avance del trabajo, fortalecer la colaboración y comunicación del equipo, detectar posibles obstáculos y garantizar que las actividades se mantengan alineadas con los objetivos de la iteración. Asímismo, contribuye a una mejor planificación y fomenta la transparencia, la capacidad de adaptación y la eficiencia en el desempeño del equipo.

 📷 Imagenes de [Reunión de scrumboard]
<img src="/images/xp/scrumboard1.jpg" 
     alt="Reunion de scrumboard1" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

<img src="/images/xp/scrumboard2.jpg" 
     alt="Reunion de scrumboard2" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

<img src="/images/xp/scrumboard3.jpg" 
     alt="Reunion de scrumboard3" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

#### 13.4. Impediment Log
En este caso, el Impediment Log permitió identificar y documentar los problemas específicos surgidos en el proyecto de digitalización de la biblioteca, asegurando un seguimiento claro de los desafíos técnicos, humanos y operativos que impactan el progreso del equipo. Gracias a ello, se facilita la planificación e implementación de acciones correctivas para abordar estos impedimentos de forma oportuna.

##### **Documento adjunto:**
 🗎 [Impediment Log](https://docs.google.com/document/d/1BffCpf1HhRq9Woq6ISu1Drljpy4naYFnpLrb9-TX1Pw/edit?usp=sharing)

### Herramientas

#### 13.5. Experiencia del equipo
En el proyecto de Sistema de gestion para barbería, la experiencia del equipo evidencia el conocimiento compartido y las competencias de los integrantes del Equipo XP para llevar a cabo el trabajo previsto y alcanzar los resultados esperados. Cada integrante aporta su experiencia técnica y criterio profesional en la ejecución de las tareas del Sprint Backlog, tomando decisiones clave para transformar las historias de usuario en productos funcionales.

 📷 Imagenes de [Experiencia del equipo]
<img src="/images/xp/sprint_backlog.jpg" 
     alt="Experiencia del equipo" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

#### 13.6. Entregables de la iteración

##### **Documento adjunto:**
 🗎 [Entregables de la iteración](https://drive.google.com/file/d/152H0MFRMDqHqEDzfZ-LjWIo1OlXo9cHp/view?usp=sharing)

### Salidas

#### 13.7. Scrumboard actualizado
El Scrum Board Actualizado refleja el progreso en tiempo real del equipo, mostrando tareas pendientes, en progreso y completadas. Facilita la colaboración, la identificación de bloqueos y el seguimiento continuo del Sprint.

<img src="/images/xp/scrumboard_fin.png" 
     alt="Scrumboard actualizado" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

#### 13.8. Prototipos
Un prototipo es una versión preliminar del software creada rápidamente para visualizar y validar los requisitos del usuario. Sirve como herramienta para obtener retroalimentación temprana, asegurando que el producto final cumpla con las expectativas antes de invertir más tiempo en el desarrollo completo. Los prototipos en XP suelen ser simples y enfocados en funcionalidades clave.

 📷 Imágenes de [Prototipos]

Pantalla de login para los dos tipos de usuario:

<img src="/images/xp/prototipo_login.jpg" 
     alt="Prototipo1" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

Página de inicio para administrador:

<img src="/images/xp/prototipo_inicio_admin.jpg" 
     alt="Prototipo2" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

Página de inicio para cliente:

<img src="/images/xp/prototipo_inicio_usuario.jpg" 
     alt="Prototipo2" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

#### 13.9. Incremento de software
Se entrega un software funcional e incrementalmente mejorado al cliente, cada vez que se completa una nueva iteración.

**Nuevas funcionalidades**

Se agregaron los filtros por fechas de inicio y fin para la busqueda de reservas.

<img src="/images/xp/reporte_reserva.jpg" 
     alt="Nuevas funcionalidades" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

**Mejoras**

En el servicio, se crearon 3 métodos que generan la lógica de recompensas, además de modificar el método de crear reserva añadiéndole un flag para que dependa desde donde se llama al método.

<img src="/images/xp/logica_recompensas.jpg" 
     alt="Mejoras" 
     style="display: block; margin: 20px auto; max-width: 80%;" />

**Correción de errores**

Se modificó el método listarReservas para que la lógica maneje el envío del usuario para el administrador.

<img src="/images/xp/reporte_cliente.jpg" 
     alt="Correción de errores" 
     style="display: block; margin: 20px auto; max-width: 100%;" />