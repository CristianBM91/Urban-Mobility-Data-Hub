---
layout: default
title: Urban Mobility Data Hub
---

# 🚏 Urban Mobility Data Hub

**Urban Mobility Data Hub (UMDH)** es un espacio de datos experimental centrado en el **intercambio seguro y gobernado de información sobre movilidad urbana**.  
Su objetivo es demostrar cómo los estándares europeos y las tecnologías abiertas pueden facilitar la colaboración entre administraciones públicas, operadores de transporte, empresas privadas y centros de investigación.

---

## 🌍 ¿Qué es UMDH?

El proyecto se basa en la arquitectura de referencia de **FIWARE Data Spaces**, combinando diversos componentes interoperables:

- **FIWARE Data Space Connector (DSC)** o **EDC** para la conexión y gestión de políticas de acceso a datos.  
- **Orion-LD / Scorpio Broker** como broker semántico NGSI-LD.  
- **TM Forum APIs** para la descripción de catálogos y ofertas de servicios.  
- **Keycloak** para autenticación y autorización OIDC.  
- **APISIX** como gateway API para exponer servicios protegidos.  
- **Kubernetes / Docker Compose** para el despliegue modular del ecosistema.

---

## ⚙️ Arquitectura

El ecosistema de UMDH implementa una arquitectura modular basada en componentes FIWARE:

