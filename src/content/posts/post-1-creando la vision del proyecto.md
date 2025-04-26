---
title: "1. Creando la vision del proyecto"
meta_title: ""
description: "En este apartado se definirá la visión del proyecto, los objetivos, los objetivos específicos y la solución tecnológica propuesta."
date: 2025-04-19T05:00:00Z
image: "/images/posts/01.png"
categories: ["sprint-1"]
authors: ["Dafne Huertas"]
tags: ["vision", "proyecto"]
draft: false
---

### Entradas

#### 1.1. Caso de negocio del proyecto

##### 1.1.1. Nombre del proyecto
> Sistema de Gestión para Barbería – *Diamond Barbershop App*

##### 1.1.2. Antecedentes del proyecto
*Diamond Barbershop* es una barbería en crecimiento ubicada en Villa María del Triunfo, que ofrece servicios de cuidado personal para hombres, como cortes de cabello, arreglo de barba, tratamientos capilares, entre otros.
Actualmente, su operativa diaria depende de medios informales como WhatsApp, cuadernos físicos o notas del celular para agendar citas y llevar el control de los clientes, lo cual genera:
Desorganización en la programación de turnos.

- Pérdida de historial de servicios.
- Dificultad para hacer seguimiento a clientes frecuentes.
- Limitaciones para escalar y profesionalizar el negocio.

##### 1.1.3. Objetivo del proyecto
El objetivo general del proyecto es desarrollar una aplicación móvil que digitalice y optimice los procesos internos de Diamond Barbershop, brindando una mejor experiencia tanto al personal como a los clientes.

##### 1.1.4. Objetivos específicos:
- Permitir al personal registrar y consultar datos de los clientes.
- Buscar clientes rápidamente por nombre o número telefónico.
- Gestionar reservas desde una interfaz intuitiva.
- Consultar el historial de servicios realizados por cada cliente.
- Registrar la disponibilidad de los barberos por día y hora.
- Acceder mediante login privado (solo personal autorizado).

##### 1.1.5. Solución Tecnológica Propuesta
Para cumplir con los objetivos del proyecto, se plantea el desarrollo de una aplicación móvil nativa en Android utilizando Java como lenguaje principal, acompañada de un backend desarrollado con Spring Boot y una base de datos MySQL.

###### Justificación técnica:

- Compatibilidad directa: El negocio actualmente utiliza un celular Android para operar y recibir mensajes mediante WhatsApp Business, por lo que una app nativa asegura un rendimiento óptimo y aprovechamiento total del dispositivo.
- Simplicidad y control: Al no depender de plataformas externas como Firebase o soluciones híbridas, se tiene un mayor control sobre la lógica de negocio, datos y seguridad.
- Escalabilidad: Spring Boot permite construir servicios robustos y escalables que pueden adaptarse fácilmente a nuevas funcionalidades como reportes, estadísticas o módulos administrativos.
- Mantenibilidad: La separación entre frontend (app móvil) y backend (API REST) facilita futuras actualizaciones o migraciones tecnológicas si fueran necesarias.
- Gratuito y de código abierto: Se utilizan tecnologías Open Source, sin licencias de pago, lo que permite un desarrollo sostenible para un negocio local con recursos limitados.

#### 1.2. Visión de la empresa
> Ser reconocida como la barbería de preferencia en el distrito de Villa Maria del Triunfo por ofrecer un servicio de alta calidad, atención personalizada y una experiencia moderna, combinando estilo tradicional con tecnología para la comodidad de nuestros clientes.

#### 1.3. Visión de la empresa
> Ofrecer servicios de corte de cabello, afeitado y cuidado personal con calidad, compromiso y atención al cliente, en un ambiente cómodo y profesional que promueva el bienestar y la confianza de cada persona que nos visita.

### Herramientas

#### 1.4. Reunion de vision del proyecto
(inserte imagen)

#### 1.5. Análisis FODA
##### Fortalezas
- Ubicación accesible en una zona con alto tránsito de personas.
- Barberos con experiencia y trato directo con los clientes.
- Relación cercana y de confianza entre barberos y clientes.
- Costos operativos relativamente bajos debido a una estructura sencilla.
- Flexibilidad en los horarios de atención.

##### Oportunidades
- Implementación de un sistema de reservas para ordenar el flujo de atención.
- Digitalización de pagos, agendas y control de servicios para mayor transparencia.
- Fidelización de clientes mediante recordatorios, promociones y seguimiento.
- Diferenciación frente a la competencia al ofrecer una experiencia más moderna.
- Potencial expansión de servicios (venta de productos, promociones, combos).

##### Debilidades
- Gestión administrativa limitada (registro manual de pagos y citas).
- Falta de control automatizado sobre el flujo de dinero y reservas.
- Ausencia de historial de clientes o métricas de rendimiento.
- Posible desorganización en la atención por no contar con una agenda digital.
- Dependencia de los barberos para cobros y coordinación.

##### Amenazas
- Competencia cercana con precios similares o servicios más tecnológicos.
- Cambios en el comportamiento del cliente (más exigente con el tiempo y la puntualidad).
- Riesgo de errores en cobros o citas al manejar todo de forma manual.
- Limitado conocimiento tecnológico del equipo, lo que puede dificultar una transición.
- Inestabilidad económica local que puede reducir la frecuencia de visitas.

#### 1.6. Análisis de brecha
La brecha principal se encuentra en la ausencia de una solución digital centralizada que permita una gestión eficiente, ordenada y escalable de los clientes y sus servicios. Actualmente, Barbershop Diamond opera bajo un sistema informal o manual, lo que limita la calidad del servicio, la fidelización del cliente y la eficiencia operativa.
El desarrollo de esta aplicación móvil cerrará esta brecha al automatizar procesos clave, mejorar la experiencia del cliente, y proporcionar herramientas digitales adaptadas al negocio, con posibilidad de escalar en el futuro.

##### Estado actual
- Registro de clientes realizado de forma manual o no sistematizado.
- Información del cliente (nombre, contacto, observaciones) se pierde o no se conserva correctamente.
- No se lleva un historial de los servicios realizados por cliente.
- La búsqueda de clientes es lenta y depende de la memoria del barbero o anotaciones físicas.
- No hay un sistema que permita conocer con rapidez el tipo de corte, fecha o preferencias anteriores del cliente.
- La barbería no cuenta con herramientas digitales propias adaptadas a su flujo de trabajo.

##### Estado deseado
- Aplicación móvil que permita registrar y consultar los datos completos de cada cliente.
- Historial detallado de los servicios realizados (tipo de corte, tratamiento, fecha, observaciones).
- Búsqueda rápida de clientes por nombre o número telefónico.
- Información accesible en tiempo real desde un solo dispositivo.
- Atención personalizada basada en preferencias y servicios anteriores del cliente.
- Digitalización del proceso de gestión con una app intuitiva, hecha a medida del negocio.
- Base tecnológica que permita futuras mejoras, como agendamiento de citas, promociones o estadísticas.

##### Brecha identificada
- **Tecnológica**: Ausencia de una solución digital adaptada a las operaciones de la barbería.
- **Organizacional**: Falta de sistematización en los procesos de atención al cliente y registro de servicios.
- **Operativa**: Dificultad para acceder de manera rápida y precisa a la información del cliente y su historial.
- **Personalización**: Imposibilidad de brindar un servicio personalizado por falta de datos previos accesibles.
- **Escalabilidad**: La operación actual no permite crecimiento eficiente ni integración de nuevas funcionalidades.
- **Productividad**: Tiempos prolongados en la atención por búsqueda manual o incertidumbre sobre servicios anteriores.

### Salidas

#### 1.7. Product Owner identificado
Posterior a la reunión interna que se tuvo entre los involucrados en el proyecto, se llegó al acuerdo que la integrante: Smith Seleni Ramos Sanchez, es la elegida para ser Product Owner del equipo debido a las siguientes razones:
- Experiencia en el framework Scrum (Participó en el curso Scrum el ciclo pasado)
- Cercanía al establecimiento, vive en Villa María del Triunfo

##### **Reunión para elección del Product Owner:**

 📷 Imagenes de [La reunión de elección del Product Owner](https://drive.google.com/file/d/1pmTF5lISDfFUe6mt7At1ThlGu26HtGcK/view?usp=sharing)

#### 1.8. Declaración de la visión del proyecto
##### **Documento adjunto:**
 🗎 [Declaración de la visión del proyecto - Diamond BarberShop App](https://docs.google.com/document/d/10uRcqr6bJ-H-qqzbuojhRv3YDPEu_928QwsCWa_LyCU/edit?usp=sharing)

#### 1.9. Acta constitutiva del proyecto
##### **Documento adjunto:**
 🗎 [Acta constitutiva del proyecto - Diamond BarberShop App](https://docs.google.com/document/d/12Lj1nKgszMkJ1KYNiAHo-kwDx8nVd0Ph/edit?usp=sharing&ouid=105357714069578698229&rtpof=true&sd=true)

#### 1.10. Presupuesto del proyecto

