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

#### 1.2. Mockup de arquitectura final
En el siguiente mockup se detalla el bosquejo de la arquitectura del proyecto.

<img src="/images/xp/mockup_arqui.jpg" 
     alt="Mockup de arquitectura final" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

### Herramientas

#### 1.3. Reunión retrospectiva del proyecto
La reunión de retrospectiva del proyecto es una reunión para determinar las formas en las que la colaboración y eficacia del equipo puede mejorarse en futuros proyectos. También se analizan las oportunidades positivas, negativas y potenciales para mejorar.

 🗎 [Link de Retrospectiva en Miro](https://miro.com/app/board/uXjVJerwjMA=/?share_link_id=754926746580)

<img src="/images/sprint_2/reunion_team.png" 
     alt="Reunión retrospectiva del proyecto" 
     style="display: block; margin: 20px auto; max-width: 100%;" />

### Salidas

#### 1.4. Agreed Actionable Improvements

##### **Documento adjunto:**
 🗎 [Agreed Actionable Improvements](https://drive.google.com/file/d/1jf0-C1jj2O-vxFQOLiz9tEewwV4o-Smc/view?usp=sharing)

#### 1.5. Assigned Action Items y fechas límite

##### **Documento adjunto:**
 🗎 [Assigned Action Items y fechas límite](https://docs.google.com/spreadsheets/d/16f0y_8pM4WOSZxDx-R0NMB7Coa02UQ5Tx6kEWbSnNhQ/edit?usp=sharing )

#### 1.6. Lecciones aprendidas

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
