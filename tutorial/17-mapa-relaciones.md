# 17. Mapa de relaciones entre firma, sello, certificado y wallet

## Introduccion

Uno de los puntos que mas confusion genera en eIDAS es la relacion entre conceptos que se parecen, pero no son equivalentes. Esta seccion ofrece un mapa conceptual sencillo para entender como se conectan varias piezas del sistema.

## 1. Firma electronica

La firma electronica se vincula a una persona fisica y sirve para firmar datos electronicos.

Se relaciona con:

- identidad
- autenticacion
- prueba
- certificados

## 2. Sello electronico

El sello electronico se vincula normalmente a una persona juridica y sirve para acreditar origen e integridad documental en nombre de una entidad.

Se relaciona con:

- expedicion documental
- automatizacion
- certificados de sello

## 3. Certificado

El certificado es una pieza de base que vincula determinados datos de verificacion con una persona, entidad o sistema.

Se relaciona con:

- firma
- sello
- autenticacion de sitios web

## 4. Certificado cualificado

El certificado cualificado es la version reforzada del certificado dentro del marco eIDAS y es emitido por un prestador cualificado.

Se relaciona con:

- firma cualificada
- sello cualificado
- servicios de confianza cualificados

## 5. Sello de tiempo

El sello de tiempo vincula datos a un momento concreto.

Se relaciona con:

- prueba temporal
- trazabilidad
- integridad cronologica

## 6. Entrega electronica certificada

La entrega electronica certificada aporta evidencia sobre envio y recepcion de datos.

Se relaciona con:

- comunicaciones probatorias
- evidencias temporales
- integridad de datos transmitidos

## 7. Prestador de servicios de confianza

El prestador es la entidad que ofrece los servicios del ecosistema.

Se relaciona con:

- certificados
- firmas
- sellos
- sellos de tiempo
- entrega electronica certificada

## 8. Lista de confianza

La lista de confianza no crea por si sola el servicio, pero permite verificar oficialmente la condicion de cualificado del prestador y de determinados servicios.

Se relaciona con:

- supervisión
- confianza juridica
- verificacion oficial del estado del servicio

## 9. Wallet europea

La wallet europea no es lo mismo que una firma, un sello o un certificado, aunque puede interactuar con todos ellos.

Se relaciona con:

- identidad digital
- atributos verificables
- credenciales
- autenticacion
- firma en determinados contextos

## Relacion resumida

Puede verse asi:

1. la wallet ayuda a gestionar identidad y credenciales
2. los certificados sirven de base a varias funciones de confianza
3. la firma y el sello usan esos cimientos con finalidades distintas
4. el sello de tiempo fija el momento
5. la entrega certificada aporta evidencia sobre comunicacion
6. el prestador hace posible el servicio
7. la lista de confianza permite verificar el nivel cualificado

## Tabla conceptual rapida

### Firma

- sujeto principal: persona fisica
- funcion principal: firmar

### Sello

- sujeto principal: persona juridica
- funcion principal: origen e integridad

### Certificado

- sujeto principal: persona, entidad o sistema
- funcion principal: vincular datos de verificacion

### Wallet

- sujeto principal: titular de identidad digital
- funcion principal: gestionar identidad, atributos y credenciales

## Resumen rapido

Firma, sello, certificado y wallet son piezas conectadas, pero no equivalentes. El certificado aporta base de confianza, la firma y el sello cumplen funciones distintas, la wallet organiza identidad y credenciales, y todo ello puede integrarse en un ecosistema de servicios cualificados.
