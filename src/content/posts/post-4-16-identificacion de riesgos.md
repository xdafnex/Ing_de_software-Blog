---
title: "16. Identificación de riesgos"
meta_title: ""
description: "meta description"
date: 2025-05-10T15:00:00+00:00
image: "/images/posts/16-4-1.jpg"
categories: ["xp"]
authors: ["Dafne Huertas"]
tags: ["Riesgos"]
draft: false
---
### Entradas

#### 16.1. Lista de riesgos identificados

De los puntos anteriores hemos identificado los posibles riegos para el desarrollo de esta iteración del proyecto. Siendo los siguientes riesgos:

- El cliente no puede reservar su cita
- El comprobante del pago o foto de barbero no sube
- Reserva o datos de usuario se borran
- El sistema no responde al enviar o confirmar citas


<img src="/images/xp/riesgos_ident.png" 
     alt="Riesgos Identificados" 
     style="display: block; margin: 20px auto; max-width: 100%;" />


### Herramientas

#### 16.2. Reunión de revisión de riesgos
La reunión de revisión de riegos brinda una oportunidad para que el equipo XP y los clientes revisen y actualicen dichs riegos. En esta sesión,se analiza y ajusta los detalles necesarios para garantizar que la probabilidad de que sucedan sea baja.

<img src="/images/sprint_2/reunion_scrum_team.png" 
     alt="Reuniones de revision de riesgos" 
     style="display: block; margin: 20px auto; max-width: 100%;" />


### Salidas

#### 16.3. Matriz de riesgos

##### **Documento adjunto:**
 🗎 [Matriz de riesgos](https://docs.google.com/spreadsheets/d/1MOm5bw98UvvtJKUzlxV4OQ3lMuH34oEThaKOytMhA0s/edit?usp=sharing)

<img src="/images/xp/matriz_riesgos.png" 
     alt="Matriz de riesgos" 
     style="display: block; margin: 20px auto; max-width: 90%;" />

#### 16.4. Plan de mitigación de riesgos

**Paso 1: Garantizar la usabilidad en condiciones de mala conexión**

Objetivo: Evitar la pérdida de reservas cuando el cliente tiene problemas de internet.

- 1.1. Implementar funcionalidades offline que permitan llenar formularios sin conexión.

- 1.2. Mostrar mensajes claros de error cuando haya fallas de conexión.

- 1.3. Activar un modo "reintentar automáticamente" al recuperar la conexión.

Plazo estimado: 1 semana

Responsable: Equipo Frontend


**Paso 2: Mejorar la carga de imágenes al servidor (Cloudinary)**

Objetivo: Evitar la pérdida de comprobantes de pago por fallos en el envío.

- 2.1. Validar el tipo y tamaño de archivo antes de subir.

- 2.2. Incluir una lógica de reintento automático si la subida falla.

- 2.3. Mostrar al usuario el estado de la subida y un botón de "reintentar manualmente".

Plazo estimado: 4 días

Responsable: Desarrollador Backend


**Paso 3: Prevenir la pérdida de datos en base de datos**

Objetivo: Proteger la información crítica del sistema (reservas, usuarios, pagos).

- 3.1. Configurar backups automáticos diarios en el servidor o nube.

- 3.2. Realizar pruebas mensuales de recuperación de datos.

- 3.3. Implementar políticas de seguridad y cifrado de datos sensibles.

Plazo estimado: 2 semanas

Responsable: DevOps / DBA


**Paso 4: Fortalecer la disponibilidad del servidor**

Objetivo: Asegurar que la app siempre esté disponible para el usuario.

- 4.1. Usar proveedores con alta disponibilidad (HA) (como AWS, Azure, etc.).

- 4.2. Configurar herramientas de monitoreo en tiempo real (Ej: UptimeRobot, Datadog).

- 4.3. Implementar escalado automático y balanceo de carga.

Plazo estimado: 3 semanas

Responsable: Equipo DevOps / Arquitectura
