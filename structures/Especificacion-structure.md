# Documento Especificación Técnica de Requerimientos
### {{technical_service_name_from_readme}}
### Banco Popular
### Vicepresidencia de Tecnología

# Tabla de Contenido

* [Introducción](#introducción)
  * [Información General](#información-general)
  * [Descripción del Servicio](#descripción-del-servicio)
  * [Diagrama de Integración](#diagrama-de-integración)
  * [Diagrama de Secuencia](#diagrama-de-secuencia)
  * [Diagrama de Componentes](#diagrama-de-componentes)
  * [Descripción del Diagrama de Interacción de Componentes](#descripcion-del-diagrama-de-interaccion-de-componentes)
  * [Especificación Detallada del Servicio](#especificación-detallada-del-servicio)
  * [Descripción de Interface](#descripción-de-interface)
  * [Descripción Mensaje de Entrada](#descripción-mensaje-de-entrada)
  * [Descripción Mensaje de Entrada Header](#descripción-mensaje-de-entrada-header)
  * [Descripción Mensaje de Entrada Body](#descripción-mensaje-de-entrada-body)
  * [Ejemplo Mensaje de Entrada](#ejemplo-mensaje-de-entrada)
  * [Descripción Mensaje de Salida](#descripción-mensaje-de-salida)
  * [Descripción Mensaje de Salida Status](#descripción-mensaje-de-salida-status)
  * [Descripción Mensaje de Salida Header](#descripción-mensaje-de-salida-header)
  * [Descripción Mensaje de Salida Body](#descripción-mensaje-de-salida-body)
  * [Ejemplo Mensaje de Respuesta Exitosa](#ejemplo-mensaje-de-respuesta-exitosa)
  * [Ejemplo Mensaje de Respuesta Error de Negocio](#ejemplo-mensaje-de-respuesta-error-de-negocio)
  * [Códigos IFX de Respuesta y Error](#códigos-ifx-de-respuesta-y-error)
  * [Códigos HTTP de Respuesta](#códigos-http-de-respuesta)
  * [Mecanismos de Comunicación](#mecanismos-de-comunicación)
  * [Reglas](#reglas)

---

# Introducción

## Información General

| Item                              | Descripción                |
| --------------------------------- | -------------------------- |
| Nombre Servicio                   | {{service_name}}           |
| Nombre Técnico                    | {{technical_service_name_from_readme}} |
| Operaciones del Servicio          | {{service_operations}}     |
| Dominio del Servicio              | {{service_domain}}         |
| Exposición del Servicio           | {{service_exposure}}       |
| Proyecto                          |  MAPI - Modernización y Actualización Plataforma Integración |
| Consumidor (Frontend)             | {{consumer_system}}        |
| Proveedor (Backend)               | {{provider_system}}        |
| Contiene Reverso Manual           | {{manual_reverse}}         |
| Contiene Reverso Automático       | {{automatic_reverse}}      |
| Contiene Orquestaciones           | {{has_orchestration}}      |
| Tiene más de un componente simple | {{multiple_components}}    |

---

# Descripción del Servicio

{{service_functionality_from_readme}}

---

# Diagrama de Integración

```mermaid
{{integration_diagram}}
```

---

# Diagrama de Secuencia

```mermaid
{{Secuencia_diagram}}
```

---

# Diagrama de Componentes

```mermaid
{{Componentes_diagram}}
```

---

# Descripción del Diagrama de Interacción de Componentes

{{component_interaction_description}}

| Tipo                 | Nombre | Descripción |
| -------------------- | ------ | ----------- |
 {{components_table}} 

---

# Especificación Detallada del Servicio

---

## Descripción de Interface

| Item               | Descripción                 |
| ------------------ | --------------------------- |
| Operación          | {{operation_name}}          |
| Funcionalidad      | {{operation_functionality}} |
| Mensaje de Entrada | {{request_message}}         |
| Mensaje de Salida  | {{response_message}}        |
| Mensaje de Falla   | {{response_message}}        |

---

# Descripción Mensaje de Entrada

{{request_description}}

---

## Descripción Mensaje de Entrada Header

| Xpath Campo              | Tipo (Longitud) | Obligatorio | Opcional | Descripción |
| ------------------------ | --------------- | ----------- | -------- | ----------- |
 {{request_header_table}} 

---

## Descripción Mensaje de Entrada Body

| Xpath Campo            | Tipo (Longitud) | Obligatorio | Opcional | Descripción |
| ---------------------- | --------------- | ----------- | -------- | ----------- |
{{request_body_table}} 

---

## Ejemplo Mensaje de Entrada

```xml
{{request_example}}
```

---

# Descripción Mensaje de Salida

---

## Descripción Mensaje de Salida Status

| Xpath Campo               | Tipo (Longitud) | Obligatorio | Opcional | Descripción |
| ------------------------- | --------------- | ----------- | -------- | ----------- |
 {{response_status_table}} 

---

## Descripción Mensaje de Salida Header

| Xpath Campo               | Tipo (Longitud) | Obligatorio | Opcional | Descripción |
| ------------------------- | --------------- | ----------- | -------- | ----------- |
 {{response_header_table}} 

---

## Descripción Mensaje de Salida Body

| Xpath Campo             | Tipo (Longitud) | Obligatorio | Opcional | Descripción |
| ----------------------- | --------------- | ----------- | -------- | ----------- |
 {{response_body_table}} 

---

## Ejemplo Mensaje de Respuesta Exitosa

```xml
{{response_success_example}}
```

---

## Ejemplo Mensaje de Respuesta Error de Negocio

```xml
{{response_error_example}}
```

---

# Códigos IFX de Respuesta y Error

| Código              | Severidad | Descripción |
| ------------------- | --------- | ----------- |
 {{ifx_codes_table}} 

---

# Códigos HTTP de Respuesta

| Código               | Descripción |
| -------------------- | ----------- |
 {{http_codes_table}} 

---

# Mecanismos de Comunicación

| Destino                      | Descripción |
| ---------------------------- | ----------- |
{{communication_mechanisms}} 

---

# Reglas

| Nombre          | Descripción |
| --------------- | ----------- |
 {{rules_table}} 