# Documento Mecanismo de Comunicación
### "Nombre Técnico"
### Banco Popular
### Vicepresidencia de Tecnología


# Información Mensajería

| No.   | Nombre Servicio | Descripción Interfaz | Canal | Proveedor | Nombre Operación | Dominio |
| ------------------------- | --------------- | -------------------- | ----- | --------- | ---------------- | ------- |

# Información del Legado

| Item               | Descripción              |
| ------------------ | ------------------------ |
| Servicio           |     |
| Operación          |     |
| Entidad            |     |
| Plataforma Origen  |     |
| Plataforma Destino |     |
| Protocolo          |     |
| Formato            |     |
| Modelo Consumo     |     |

# Contexto de Exposición Backend

| Item                    | Descripción          |
| ----------------------- | -------------------- |
| Contexto                |     |
| Seguridad               |     |
| Nombre MPG/WSP          |     |
| Internal/External       |     |
| Contrato (WSDL/Swagger) |     |


# Mapeos

# Mensaje Solicitud

<table border="1" cellspacing="0" cellpadding="5">
<thead>
<tr>
<th colspan="14">Mensaje Solicitud</th>
</tr>
<tr>
<th colspan="5">Campo Origen<br>ACE</th>
<th colspan="9">Campo Destino<br>"backend"</th>
</tr>
<tr>
<th>Nombre</th>
<th>Tipo</th>
<th>Cardinalidad</th>
<th>Longitud</th>
<th>Formato</th>
<th>Nombre</th>
<th>Tipo</th>
<th>Cardinalidad</th>
<th>Longitud</th>
<th>Formato</th>
<th>Procedimiento</th>
<th>Descripción</th>
<th>Ejemplo</th>
<th>Método Ofuscación</th>
</tr>
</thead>
<tbody>

</tbody>
</table>

# Mensaje Respuesta

## Mensaje Respuesta Exitosa

<table border="1" cellspacing="0" cellpadding="5">
<thead>
<tr>
<th colspan="14">Mensaje Respuesta Exitosa</th>
</tr>
<tr>
<th colspan="5">Campo Origen<br>"backend"</th>
<th colspan="9">Campo Destino<br>ACE</th>
</tr>
<tr>
<th>Nombre</th>
<th>Tipo</th>
<th>Cardinalidad</th>
<th>Longitud</th>
<th>Formato</th>
<th>Nombre</th>
<th>Tipo</th>
<th>Cardinalidad</th>
<th>Longitud</th>
<th>Formato</th>
<th>Procedimiento</th>
<th>Descripción</th>
<th>Ejemplo</th>
<th>Método Ofuscación</th>
</tr>
</thead>
<tbody>

</tbody>
</table>


## Mensaje Respuesta Error

<table border="1" cellspacing="0" cellpadding="5">
<thead>
<tr>
<th colspan="14">Mensaje Respuesta Error</th>
</tr>
<tr>
<th colspan="5">Campo Origen<br>"backend"</th>
<th colspan="9">Campo Destino<br>ACE</th>
</tr>
<tr>
<th>Nombre</th>
<th>Tipo</th>
<th>Cardinalidad</th>
<th>Longitud</th>
<th>Formato</th>
<th>Nombre</th>
<th>Tipo</th>
<th>Cardinalidad</th>
<th>Longitud</th>
<th>Formato</th>
<th>Procedimiento</th>
<th>Descripción</th>
<th>Ejemplo</th>
<th>Método Ofuscación</th>
</tr>
</thead>
<tbody>

</tbody>
</table>

## Homologaciones

| Item          | Descripción    |
| --------------| -------------- |
| Nombre de la BD                         | AUDITORIA          |
| Nombre de la tabla en BD                | ESB_HOMOLOGATION   |
| Si se guarda en cache indicar su nombre | HOMOLOGATIONS      |
| Indicar Atributo (NOM_ATTRIBUTE)        |                    |

| Item          | Descripción        |
| ------------- | ------------------ |
| Nombre de la BD                         | AUDITORIA                       |
| Nombre de la tabla en BD                | ESB_DETAIL_ERROR <br> ESB_ERROR |
| Si se guarda en cache indicar su nombre | ERRORS                          |
| Indicar Atributo (NOM_ATTRIBUTE)        | N/A                             |