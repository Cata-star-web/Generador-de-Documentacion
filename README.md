# Generador de Documentación Técnica Automatizada con IA

## Descripción
Se propone una herramienta automatizada con IA para generar documentación técnica de servicios de integración a partir de archivos como WSDL, XML, JSON, ESQL y README. Extrae, interpreta y transforma la información en documentos estandarizados (Home, Especificación y Mecanismos), garantizando calidad, coherencia y reducción del esfuerzo manual.

## Objetivo
Automatizar la generación de documentación técnica en formato Markdown, asegurando calidad, consistencia estructural y alineación con estándares definidos por la organización.

## Alcance de la Solución
La herramienta analiza una carpeta raíz y procesa archivos técnicos para generar automáticamente documentación estructurada mediante plantillas dinámicas.

Incluye:
- Extracción de información desde WSDL, XML, JSON, ESQL y README.md
- Generación de documentación en formato Markdown
- Uso de plantillas dinámicas reutilizables
- Construcción automática de descripciones, diagramas, tablas y ejemplos
- Construcción automática de mensajes de entrada y salida (headers, body, status)
- Construcción automática de mapeos (mensajes de solicitud, mensajes de respuesta exitosa y error)
- Generación de contenido técnico en lenguaje natural mediante IA
- Generación de descripciones funcionales y técnicas

## Estructura del Proyecto

```
/docs-generator
│
├── structures/ 
├── templates/ 
├── input/
├── output/ 
└── README.md
```

## Documentos Generados

### Documento Home
Punto de entrada del Servicio de Integración que contiene:
- Funcionalidad
- Nombre técnico
- Tipo de servicio (Atómico / Orquestado)
- Repositorios que soportan la funcionalidad

### Documento de Especificación
Define el contrato técnico del Servicio de Integración:
- Encabezado estandar para identificación correcta del documento
- Tabla de contenido
- Información general
- Descripción del servicio
- Diagramas (Integración, Secuencia y Componentes) en Mermaid
- Interfaces
- Mensajes de entrada y salida (Header, Body, Status)
- Ejemplos XML (request/response)
- Códigos IFX y HTTP
- Enlaces a Mecanismos de comunicación
- Reglas de datos sensibles

### Mecanismos de Comunicación
Documento generado por cada operación de la WSDL:
- Convención Nomenclatura: MC_"backend"_"operacion".md
- Encabezado estandar para identificación correcta del documento
- Información de mensajería
- Información del legado
- Contexto de exposición
- Mapeos de mensajes de solicitud, mensajes de respuesta exitosa y error (en formato HTML dentro de Markdown)
- Homologaciones

## Uso de Inteligencia Artificial
La IA complementa la automatización de la generacion de documentación permitiendo:
- Interpretar contratos WSDL/XML
- Analizar código ESQL para identificar reglas y transformaciones
- Generar descripciones funcionales y técnicas
- Construir diagramas y tablas estructuradas automáticamente
- Garantizar coherencia semántica entre secciones

## Funcionamiento
1. Ubicar los artefactos técnicos en la carpeta "/input"
2. Ejecutar la herramienta de generación
3. Procesar archivos y extraer información estructurada
4. Aplicar plantillas Markdown
5. Generar documentos en la carpeta "/output"

## Criterios de Calidad
- Generación automática en formato Markdown
- Consistencia estructural en todos los documentos
- Diagramas en formato Mermaid
- Tablas correctamente estructuradas
- Mapeos en formato HTML dentro de Markdown
- Ejemplos XML válidos
- Coherencia entre descripciones, tablas y ejemplos
- Identificación correcta de datos sensibles

## Beneficios
- Reducción significativa del esfuerzo manual
- Estandarización de la documentación de Servicios de Integración
- Mejora en la calidad y claridad técnica
- Aceleración del proceso de desarrollo
- Facilita el entendimiento para equipos técnicos y funcionales

## Tecnologías
- Markdown
- XML / JSON
- WSDL
- ESQL
- Mermaid (diagramas)
- Inteligencia Artificial
