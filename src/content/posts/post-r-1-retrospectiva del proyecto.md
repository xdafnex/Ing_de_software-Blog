---
title: "1. Retrospectiva del proyecto"
meta_title: ""
description: "meta description"
date: 2025-05-17T17:00:00+00:00
image: "/images/posts/retro-1.jpeg"
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

#### 1.3. Pruebas end to end

<img src="/images/xp/e2e.jpg" 
     alt="Pruebas end to end" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

#### 1.4. Pruebas de integración

<img src="/images/xp/integracion.jpg" 
     alt="Pruebas de integración" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

### Herramientas

#### 1.5. Reunión retrospectiva del proyecto
La reunión de retrospectiva del proyecto es una reunión para determinar las formas en las que la colaboración y eficacia del equipo puede mejorarse en futuros proyectos. También se analizan las oportunidades positivas, negativas y potenciales para mejorar.

 🗎 [Link de Retrospectiva en Miro](https://miro.com/app/board/uXjVJerwjMA=/?share_link_id=754926746580)

### Salidas

#### 1.6. Agreed Actionable Improvements

##### **Documento adjunto:**
 🗎 [Agreed Actionable Improvements](https://drive.google.com/file/d/1jf0-C1jj2O-vxFQOLiz9tEewwV4o-Smc/view?usp=sharing)

#### 1.7. Assigned Action Items y fechas límite

##### **Documento adjunto:**
 🗎 [Agreed Actionable Improvements](https://docs.google.com/spreadsheets/d/16f0y_8pM4WOSZxDx-R0NMB7Coa02UQ5Tx6kEWbSnNhQ/edit?usp=sharing )

#### 1.8. Mockup de arquitectura final
En el siguiente mockup se detalla el bosquejo de la arquitectura del proyecto.

<img src="/images/xp/mockup_arqui.jpg" 
     alt="Mockup de arquitectura final" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

#### 1.9. Lecciones aprendidas

1. La experiencia del usuario se ve fuertemente afectada por variables externas (como la conexión a internet)

Aprendizaje: No todos los errores percibidos por el usuario son causados por fallas internas del sistema. Muchos provienen de condiciones fuera de nuestro control, como una mala conexión. Por ello, es clave anticipar estos escenarios e incorporar soluciones offline o tolerantes a fallos desde la etapa de diseño.

2. La validación temprana y la retroalimentación visual previenen errores críticos

Aprendizaje: El simple hecho de validar archivos antes de subirlos y mostrar mensajes claros evita frustraciones, reduce incidencias de soporte y mejora la confianza del usuario en la app. La UX preventiva es una estrategia esencial en productos digitales.

3. La pérdida de datos no es un evento improbable, sino una amenaza constante

Aprendizaje: Confiar solo en que “nunca ha pasado” puede ser riesgoso. Implementar backups automáticos, cifrado, y restauraciones periódicas no debe ser opcional, sino parte del mantenimiento esencial del sistema.

4. La disponibilidad del sistema debe garantizarse con arquitectura resiliente, no solo con buenos desarrolladores

Aprendizaje: Tener un backend bien programado no es suficiente si el servidor no tiene escalabilidad, balanceo de carga o monitoreo. Las caídas pueden prevenirse en gran parte con una infraestructura robusta y autoescalable, especialmente en apps que manejan tiempo real o reservas.

5. La documentación y la automatización permiten responder rápido ante incidencias

Aprendizaje: Tener protocolos definidos para restauración, reinicio o revisión de logs ahorra tiempo crítico cuando ocurre un problema. Cuanto más automatizado esté el proceso de recuperación, menor será el impacto al usuario.

6. La prevención es más económica que la corrección

Aprendizaje: Las medidas preventivas como validaciones, reintentos automáticos o backups representan un costo menor que enfrentar la pérdida de usuarios, datos o reputación. Planificar para los riesgos desde el inicio reduce costos operativos futuros.

7. La mejora continua depende de medir, revisar y adaptar

Aprendizaje: Las soluciones de mitigación no son estáticas. Es necesario revisar su efectividad con métricas (como tiempos de respuesta, logs de error, tasas de éxito) y ajustarlas conforme evolucionan el producto y sus usuarios.

#### 1.10. Recomendaciones generales

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
