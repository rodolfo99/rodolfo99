<div align="center">

# 👋 Rodolfo Valencia Rodríguez

### Software Developer · Java · Spring Boot · Angular · Artificial Intelligence · Semantic Web

Desarrollo software y proyectos técnicos enfocados en **Java, Spring Boot, Angular, bases de datos, búsqueda, grafos, RDF/BIBFRAME e inteligencia artificial**.

[![GitHub](https://img.shields.io/badge/GitHub-rodolfo99-181717?logo=github)](https://github.com/rodolfo99)
![Java](https://img.shields.io/badge/Java-21-007396?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-20%2B-DD0031?logo=angular&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?logo=docker&logoColor=white)

</div>

---

## 👤 Carta de presentación

Soy **Rodolfo Valencia Rodríguez**, ingeniero en Telemática por la Universidad de Colima. Desde **2005** desarrollo mi trayectoria profesional en esta institución, donde he desempeñado funciones de programación, desarrollo de servicios web y administración de un centro de cómputo, además de participar en el desarrollo de **SIABUC** con JavaScript y React.

Mi experiencia abarca Visual Basic, PHP y tecnologías web. En mis proyectos utilizo **Java, Spring Boot, Angular, APIs y bases de datos**. También desarrollo proyectos de búsqueda de información, grafos y Web Semántica, con especial interés en la integración de datos bibliográficos mediante MARC21 y BIBFRAME. Complemento esta práctica con formación de posgrado en ingeniería de software e inteligencia artificial.

Aporto experiencia en el entorno universitario, conocimientos de desarrollo de aplicaciones y documentación que facilita la instalación, el uso y el mantenimiento del software. Me interesa construir soluciones útiles y seguir profundizando en la integración de sistemas, los datos y la inteligencia artificial aplicada. Este portafolio complementa mi currículum con código, guías y evidencias de validación que permiten conocer el alcance de cada proyecto.

### Formación y certificación

- **Ingeniería en Telemática** — Universidad de Colima.
- **Maestría en Ingeniería de Software y Sistemas Informáticos** — UNIR México.
- **Maestría en Inteligencia Artificial e Ingeniería del Conocimiento** — Universidad TECH.
- **Certificación como programador Java.**

### Áreas de interés

- ☕ Java, Spring Boot y APIs REST
- 🅰️ Angular, TypeScript y aplicaciones web
- 🐘 PostgreSQL y persistencia relacional
- 🔎 Apache Solr y búsqueda de información
- 🕸️ Neo4j, GraphDB, RDF y SPARQL
- 📚 MARC21, BIBFRAME y tecnologías para bibliotecas
- 🤖 Inteligencia artificial, modelos de lenguaje y automatización
- 🐳 Docker y entornos reproducibles

---

## ⭐ Proyectos destacados

### 📚 [Marc2BF — MARC21 → BIBFRAME](https://github.com/rodolfo99/Marc2BF)

Conversor en **Java 21** de registros MARC21 bibliográficos a **BIBFRAME/RDF**, incorporando el motor de conversión de Library of Congress. Soporta ISO2709, MARCXML, RDF/XML, Turtle, N-Triples y JSON-LD, además de validación, reparación de registros y ejecución con Docker.

**Tecnologías:** Java · Maven · MARC21 · BIBFRAME · RDF · XSLT · Docker

---

### 🛠️ [SIABUC Helpdesk](https://github.com/rodolfo99/helpdesk-siabuc)

Sistema independiente para gestionar el **soporte técnico a instituciones usuarias de SIABUC**, con servidor Spring Boot, cliente Angular y PostgreSQL. **Versión 1.6.0**, que amplía el soporte y la cobranza con cotizaciones, solicitudes de pago, renovaciones, portal financiero configurable, recibos, conocimiento, encuestas y respaldos programados.

- **Instituciones y acceso:** cuentas con contraseña y permisos separados para Administración, clientes institucionales y Cobranza. El cliente consulta su saldo e historial, abre casos y aporta comentarios y archivos; un administrativo puede tomar los casos sin responsable.
- **Atención y seguimiento:** estados Abierto/Cerrado, historial con detalle y regreso al listado, notas públicas/internas, categorías, prioridades, ficha técnica, SLA con horario laboral, adjuntos protegidos, cronómetro con confirmación antes del descuento y agenda de sesiones remotas.
- **Tiempo y avisos:** bolsas independientes de minutos para correo y remoto, alertas configurables de saldo bajo y campana de avisos. La pausa del correo conserva la actividad del portal; al reanudar sólo se envían avisos nuevos.
- **Pólizas y cobranza:** contratos y pagos en MXN por transferencia, depósito, efectivo, tarjetas, cheque u otro método; parcialidades, acreditación de horas por canal y protección ante duplicados. El pago y sus minutos se guardan juntos; crear una póliza no acredita tiempo.
- **Cotizaciones y renovaciones:** emisión y aceptación documentadas, conversión única de cotización a póliza y seguimiento de renovaciones vinculadas a la póliza anterior, sin acreditar horas automáticamente.
- **Validación de pagos:** solicitudes pendientes con evidencia PDF/PNG/JPEG antes de aprobar; Administración/Cobranza verifica importe y minutos y registra el pago y el crédito en una transacción. Rechazar exige motivo y conserva la evidencia sin modificar el saldo.
- **Portal financiero institucional:** **desactivado por defecto** y habilitable exclusivamente por Administración para cada institución. Sus usuarios pueden consultar sus pólizas, pagos, recibos y comprobantes históricos y enviar solicitudes; las notas técnicas internas y las observaciones privadas de aprobación permanecen reservadas.
- **Comprobantes, recibos y reportes:** archivos de evidencia por pago con autor y fecha, recibos administrativos PDF con folio estable y estado de anulación, y reportes financieros por institución, método y periodo, separados por moneda, con exportación Excel/PDF. Los reportes técnicos de consumo son exclusivos de Administración; los recibos no son facturas fiscales.
- **Conocimiento y satisfacción:** artículos por categoría y versión de SIABUC, borradores privados, publicación y enlaces desde los casos; encuestas institucionales de 1 a 5 al cierre y reportes de satisfacción para Administración.
- **Respaldos automáticos:** servicio Docker con horario diario, retención, historial y alertas de error, **desactivado por defecto**, también al actualizar. Administración puede activarlo o desactivarlo; se conservan las copias existentes y los respaldos manuales. Los adjuntos están incluidos en PostgreSQL.
- **Operación en Linux y Windows:** scripts `.sh` para Bash y `.bat` para CMD/PowerShell, con configuración, compilación, inicio, detención, respaldo y restauración con nombre de archivo configurable. Docker Compose integra Postfix SMTP interno, puertos y credenciales configurables. Windows requiere Docker Desktop con contenedores Linux y Python 3.10+; el desarrollo nativo Java/Angular se mantiene en Linux/WSL2.

**Instalación y operación:** [Guía principal](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/README.md) · [Actualizar a 1.6](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/VERSION-1.6.md) · [Windows](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/WINDOWS.md) · [Linux/Docker](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/OPERACION.md) · [Respaldo y restauración](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/RESPALDO-RESTAURACION.md) · [Respaldos automáticos](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/RESPALDOS-AUTOMATICOS.md)

**Guías funcionales:** [Soporte](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/HELPDESK-1.4.md) · [Pólizas y pagos](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/POLIZAS-COBRANZA.md) · [Comprobantes](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/COMPROBANTES-PAGO.md) · [Reportes de cobranza](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/REPORTES-COBRANZA.md) · [SMTP interno](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/SMTP-INTERNO.md) · [Pausa de correo](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/DESACTIVAR-CORREO.md)

**Guías de 1.6:** [Cotizaciones y renovaciones](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/COTIZACIONES-RENOVACIONES.md) · [Solicitudes de pago](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/SOLICITUDES-PAGO.md) · [Portal financiero](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/PORTAL-FINANCIERO.md) · [Recibos PDF](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/RECIBOS-PAGO.md) · [Base de conocimientos](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/BASE-CONOCIMIENTOS.md) · [Encuestas](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/ENCUESTAS-SATISFACCION.md)

**Estado de 1.6.0:** código y guías en `main`, con respaldos automáticos apagados por defecto. La validación documentada registra 155 pruebas Java de integración y 5 unitarias, 71 escenarios de navegador con API simulada y 14 recorridos Angular → Spring → PGlite sin interceptar la API. También pasaron 62 pruebas Python, 6 de lógica del cliente y las comprobaciones SQL de migración y worker. Docker completo, restauración real y ejecución nativa de Windows siguen pendientes; los procedimientos están documentados.

**Validación histórica de 1.5.0:** la [validación documentada del 13/10/2026](https://github.com/rodolfo99/helpdesk-siabuc/blob/main/docs/VALIDACION.md) registra 104 pruebas Java de integración y 5 unitarias, 61 escenarios de navegador con API simulada y 13 recorridos Angular → Spring → PGlite sin interceptar la API. Estas cifras corresponden a 1.5.0 y no se atribuyen a 1.6. PGlite con una conexión no acredita PostgreSQL 17 nativo/Flyway ni contención multiconexión. La ejecución completa y restauración con Docker y la ejecución nativa de Windows siguen pendientes de comprobación; estas pruebas no se presentan como validación de esos entornos. La evidencia de cada versión se mantiene separada en la guía de validación.

**Tecnologías:** Java · Spring Boot · Angular · PostgreSQL · Docker Compose · Postfix SMTP · Python · Bash · Windows Batch

---

### 🧠 [Spring Data GraphDB](https://github.com/rodolfo99/Spring-Data-GraphDB)

Implementación orientada a desarrolladores para integrar **Spring Boot con GraphDB/RDF4J**, acompañada de un backend de ejemplo y un cliente Angular.

**Tecnologías:** Java · Spring Boot · GraphDB · RDF4J · SPARQL · Angular · Docker

---

### 🔎 [CRUD Spring Boot + Apache Solr + Angular](https://github.com/rodolfo99/CRUD-Solr-con-cliente-angular)

Aplicación full stack para gestionar y buscar libros mediante **Apache Solr**, una API REST en Spring Boot y un cliente Angular.

**Tecnologías:** Java · Spring Boot · Apache Solr · Angular · REST · Docker

---

### 🕸️ [CRUD Spring Boot + Neo4j + Angular](https://github.com/rodolfo99/CRUD-LIBROS-NEO4J)

Ejemplo completo de persistencia en una **base de datos de grafos** utilizando Spring Data Neo4j y Angular.

**Tecnologías:** Java · Spring Boot · Spring Data Neo4j · Neo4j · Angular · Docker
rodolfo99
---

### 🐘 [CRUD Spring Boot + PostgreSQL + Angular](https://github.com/rodolfo99/CRUD-PostgreSQL-Libros-con-cliente-angular)

Aplicación de referencia para un CRUD REST con Spring Data JPA, PostgreSQL y Angular.

**Tecnologías:** Java · Spring Boot · Spring Data JPA · PostgreSQL · Angular · Docker

---

### ⚡ [CRUD GraphQL + PostgreSQL + Angular](https://github.com/rodolfo99/crud-GraphQL-con-cliente-angular)

Aplicación full stack basada en **Spring for GraphQL**, PostgreSQL y Angular, con queries y mutations para administrar un catálogo de libros.

**Tecnologías:** Java · Spring Boot · GraphQL · PostgreSQL · Angular · Docker

---

### 🎮 [The Mana World para Ubuntu 26.04](https://github.com/rodolfo99/The-Mana-World-Ubuntu-26.04)

Adaptación del cliente **Mana** y el servidor **TMWA** para jugar en Ubuntu 26.04, con scripts de instalación, administración local y una primera traducción automática al español de los diálogos de NPC. Basado en las fuentes abiertas originales; la traducción requiere revisión.

**Tecnologías:** C++ · SDL2 · CMake · Bash · Git · Docker Compose

---

### ⚔️ [Aincrad — SAO Aincrad Online MMORPG](https://github.com/rodolfo99/SAO-Aincrad-online-mmrpg)

Proyecto semilla de un **MMORPG 3D inspirado en Sword Art Online**, con servidor autoritativo Java/Spring Boot, cliente web Angular/Three.js y cliente de escritorio **JavaFX + jMonkeyEngine/OpenGL**. Ambos clientes comparten servidor, cuentas, personajes, chat y reglas de juego. Incluye dos pisos jugables, personajes personalizables, cinco razas, clases y especialidades, combate, progresión y PvP con ciudadanía.

- **Cuentas y administración:** registro e inicio de sesión, recuperación por correo y panel root para editar mundo, personajes y catálogos.
- **Economía y oficios:** bolsa persistente, recolección, herrería, sastrería y mercado con compra de armas, ropa y armaduras y venta de recursos.
- **NPC con IA:** integración configurable con Spring AI y Ollama, opcional para jugar.
- **Publicado en GitHub:** fuentes, JAR v0.2.0, Angular compilado, recursos originales, scripts y configuración Docker en `main` desde el 29 de septiembre de 2026.
- **Cliente Java Desktop 0.1.0 publicado:** `client-java/`, fuentes, recursos, pruebas, guías y scripts integrados como carpeta normal en `main` el 30 de septiembre de 2026. Añade renderizado OpenGL con sombras, SSAO y bloom, y administración root nativa; conserva la convivencia con Angular.
- **Ejecución documentada:** arranque con Java 17/21, puerto alternativo 8081, proxy Angular, Docker Compose y reconstrucción con Maven/Node.js.

**Guías:** [Instalación y puerto 8081](https://github.com/rodolfo99/SAO-Aincrad-online-mmrpg/blob/main/docs/ARRANQUE-Y-PUERTOS.md) · [Publicación y actualización](https://github.com/rodolfo99/SAO-Aincrad-online-mmrpg/blob/main/docs/PUBLICACION.md) · [Operación](https://github.com/rodolfo99/SAO-Aincrad-online-mmrpg/blob/main/docs/OPERACION.md) · [Pruebas y límites del servidor/web](https://github.com/rodolfo99/SAO-Aincrad-online-mmrpg/blob/main/docs/VALIDACION.md) · [Uso del cliente Java](https://github.com/rodolfo99/SAO-Aincrad-online-mmrpg/blob/main/client-java/README.md) · [Funciones, gráficos y validación Java](https://github.com/rodolfo99/SAO-Aincrad-online-mmrpg/blob/main/docs/CLIENTE-JAVA.md) · [Fuentes Java y estado publicado](https://github.com/rodolfo99/SAO-Aincrad-online-mmrpg/blob/main/README-FUENTES-JAVA.md)

**Estado — servidor v0.2.0 y cliente Java Desktop 0.1.0:** prototipo fan funcional de dos pisos, con gráficos propios y estilo 3D estilizado. Partida completa con el cliente web en Ubuntu 26.04 realizada y confirmada por el usuario el 29 de septiembre de 2026. El cliente Java tiene comprobaciones documentadas de compilación, contratos y convivencia visual con Angular en Linux x86_64 con Mesa/OpenGL por software; no se presenta esa partida web como validación completa de Java. Siguen pendientes las pruebas de escala masiva y la validación gráfica Java en GPU física y Windows/macOS.

**Tecnologías:** Java · Spring Boot · Angular · Three.js · JavaFX · jMonkeyEngine · OpenGL · Spring AI · Ollama · Maven · Docker Compose

---

## 🧰 Tecnologías

### Backend

![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?logo=graphql&logoColor=white)

### Frontend

![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)

### Datos y búsqueda

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?logo=neo4j&logoColor=white)
![Apache Solr](https://img.shields.io/badge/Apache%20Solr-D9411E?logo=apache-solr&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

### Semantic Web & bibliotecas

`RDF` · `SPARQL` · `GraphDB` · `RDF4J` · `Apache Jena` · `MARC21` · `BIBFRAME` · `JSON-LD`

### DevOps y herramientas

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?logo=apachemaven&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

---

## 📌 Portafolio

| Proyecto | Enfoque | Tecnologías principales |
|---|---|---|
| [Marc2BF](https://github.com/rodolfo99/Marc2BF) | MARC21 → BIBFRAME | Java, RDF, BIBFRAME, Docker |
| [SIABUC Helpdesk](https://github.com/rodolfo99/helpdesk-siabuc) | Soporte institucional, cotizaciones, pólizas, validación de pagos, portal financiero y respaldos programados | Java, Spring Boot, Angular, PostgreSQL, Docker Compose, Postfix SMTP |
| [Spring Data GraphDB](https://github.com/rodolfo99/Spring-Data-GraphDB) | Web Semántica / RDF | Spring Boot, GraphDB, RDF4J, Angular |
| [CRUD Solr](https://github.com/rodolfo99/CRUD-Solr-con-cliente-angular) | Búsqueda | Spring Boot, Apache Solr, Angular |
| [CRUD Neo4j](https://github.com/rodolfo99/CRUD-LIBROS-NEO4J) | Grafos | Spring Data Neo4j, Neo4j, Angular |
| [CRUD PostgreSQL](https://github.com/rodolfo99/CRUD-PostgreSQL-Libros-con-cliente-angular) | Base de datos relacional | Spring Data JPA, PostgreSQL, Angular |
| [CRUD GraphQL](https://github.com/rodolfo99/crud-GraphQL-con-cliente-angular) | API GraphQL | Spring GraphQL, PostgreSQL, Angular |
| [The Mana World para Ubuntu 26.04](https://github.com/rodolfo99/The-Mana-World-Ubuntu-26.04) | MMORPG cliente/servidor con diálogos NPC en español (traducción preliminar) | C++, SDL2, CMake, Bash, Docker Compose |
| [Aincrad — SAO Aincrad Online MMORPG](https://github.com/rodolfo99/SAO-Aincrad-online-mmrpg) | Semilla MMORPG 3D con clientes web y Java, dos pisos, mundo editable, economía y NPC con IA opcional | Java, Spring Boot, Angular, Three.js, JavaFX, jMonkeyEngine, OpenGL, Spring AI, Ollama, Docker Compose |

---

## 🔍 Perfil técnico

Palabras clave que describen el contenido de este perfil:

**Java Developer · Spring Boot Developer · Angular Developer · Full Stack Developer · Artificial Intelligence · Semantic Web · RDF · SPARQL · BIBFRAME · MARC21 · Apache Solr · Neo4j · GraphDB · PostgreSQL · GraphQL · Docker · REST API**

---

<div align="center">

### Construyendo proyectos para aprender, documentar y compartir soluciones técnicas.

**GitHub:** [github.com/rodolfo99](https://github.com/rodolfo99)

</div>
