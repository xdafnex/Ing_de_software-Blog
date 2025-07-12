---
title: "2. Pruebas del proyecto"
meta_title: ""
description: "meta description"
date: 2025-05-17T17:00:00+00:00
image: "/images/posts/retro-2.jpg"
draft: false
authors: ["Dafne Huertas"]
tags: ["Retrospectiva"]
categories: ["retro"]
---

### Entradas

#### 1.1. Equipo principal Scrum

De los puntos anteriores hemos obtenido el equipo completo para el desarrollo de este proyecto. Cumpliendo los siguientes roles:

- Product Owner: Smith Ramos
- Scrum Master: Dafne Huertas
- Desarrollador Backend: Arian Sevillano
- Desarrollador Móvil 1: Diego Caballero
- Desarrollador Móvil 2: Andre Fernandez

#### 1.2. Tester identificado

Con las entradas obtenidas anteriormente, se ha tomado la siguiente decisión en la elección de Tester:

<img src="/images/xp/tester.png" 
     alt="Selección de Tester" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

### Herramientas

#### 1.3. Pruebas end to end

Las pruebas End-to-End (E2E) son un tipo de prueba que verifica todo el flujo de una funcionalidad desde el inicio hasta el final, tal como lo haría un usuario real. Evalúan si todos los componentes del sistema (frontend, backend, base de datos, servicios externos) interactúan correctamente entre sí.

<img src="/images/xp/prueba_proyecto.jpg" 
     alt="Pruebas end to end" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

Las pruebas E2E aseguran que el sistema funciona como un todo, desde la entrada del usuario hasta la salida final, a continuación se muestra un video realizado del mismo.

**Flujo completo de la aplicación como administrador**

[Video de app vista de administrador](https://drive.google.com/file/d/17n7YHU9oWQVkVqsqImeawrmQF-jmVhgw/view?usp=sharing)

**Flujo completo de la aplicación como usuario**

[Video de app vista de usuario](https://drive.google.com/file/d/17qtae_JqyUiZ5vSqkdDpBdZ90RQ93oK3/view?usp=drive_link)

### Salidas

#### 1.4. Recomendaciones generales

Estas recomendaciones permiten fortalecer el producto en calidad, seguridad, escalabilidad y usabilidad, garantizando una mejor experiencia para los usuarios y una operación más eficiente para los trabajadores y el administrador de la barbería.

1. Arquitectura y Backend
- Fortalecer la infraestructura con escalabilidad, balanceo de carga y monitoreo.
- Asegurar la gestión segura de sesiones JWT.
- Priorizar pruebas unitarias en funciones críticas como recompensas y reportes.

2. Frontend y UX
- Optimizar la app para móviles de gama baja (rendimiento y compatibilidad).
- Agregar validaciones visuales preventivas para evitar errores del usuario.
- Diseñar pensando en fallos de conexión: feedback visual y tolerancia offline.

3. Pruebas y calidad
- Automatizar pruebas end-to-end y de aceptación para validar flujos reales.
- Usar integración continua (CI) para prevenir errores antes del despliegue.
- Verificar reportes e indicadores con datos reales en entornos de prueba.

4. Seguridad y disponibilidad
- Implementar copias de seguridad automáticas y procedimientos de restauración.
- Proteger los datos sensibles mediante cifrado y control de accesos.
- Aplicar HTTPS y buenas prácticas de seguridad desde el inicio.

5. Gestión y evolución
- Documentar procesos clave para facilitar respuesta ante incidentes.
- Analizar métricas como tiempos de respuesta y errores para mejorar.
- Adoptar una cultura de mejora continua con revisión periódica de soluciones.
