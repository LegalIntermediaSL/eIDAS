# 49. Cadena de evidencia y riesgo probatorio

## Introduccion

Una de las ideas mas importantes de todo el tutorial es que la seguridad juridica de un proceso digital no depende solo de que exista un documento firmado.

Lo verdaderamente relevante suele ser la cadena de evidencia completa:

- quien intervino
- que hizo
- cuando lo hizo
- con que mecanismo se acredito
- como puede demostrarse despues

Por eso, hablar de eIDAS sin hablar de evidencia y prueba deja incompleta la imagen real del problema.

## Que es la cadena de evidencia

La cadena de evidencia es el conjunto ordenado de elementos que permiten reconstruir y defender un proceso digital.

Puede incluir, por ejemplo:

- identificacion del interviniente
- autenticacion previa
- consentimiento o declaracion de voluntad
- firma o sello
- sello de tiempo
- registros de envio, recepcion o acceso
- resultado de validaciones
- trazas tecnicas
- politicas y procedimientos internos

No siempre haran falta todos estos elementos, pero cuanto mayor sea el riesgo del proceso, mas importante suele ser disponer de una cadena robusta.

## Que es el riesgo probatorio

El riesgo probatorio es la posibilidad de no poder demostrar adecuadamente un hecho digital cuando surja una controversia, una auditoria o una revision posterior.

Ese riesgo puede aparecer aunque la operacion haya funcionado bien en la practica.

Un proceso puede ser:

- operativo
- comodo para el usuario
- tecnicamente suficiente para el dia a dia

y, sin embargo, resultar debil cuando alguien impugna el consentimiento, la integridad del documento o la fecha de una actuacion.

## Error frecuente

Un error habitual es pensar que la prueba descansa solo en la firma.

En realidad, la firma suele ser una pieza importante, pero rara vez es la unica. Tambien importan:

- el contexto del acto
- la forma de obtencion del consentimiento
- la calidad de la identificacion previa
- la existencia de validaciones
- la conservacion de la evidencia

## Factores que elevan el riesgo probatorio

El riesgo probatorio suele crecer cuando concurren uno o varios de estos factores:

- alto valor economico
- potencial litigioso
- efectos regulatorios o administrativos
- relaciones a distancia
- intervencion de varias partes
- necesidad de prueba tiempo despues
- uso internacional o transfronterizo

Cuanto mayor sea el impacto de una impugnacion, mas sentido tiene reforzar la cadena de evidencia.

## Ejemplos de evidencia util

Segun el caso, pueden ser especialmente relevantes:

- un certificado cualificado valido en la fecha del acto
- un sello de tiempo
- evidencia de entrega o recepcion
- logs de sistema con integridad controlada
- evidencia de validacion
- copia de la politica o procedimiento aplicable
- metadatos del flujo seguido

La clave es que estos elementos no aparezcan aislados, sino como parte de un conjunto coherente.

## Relacion entre nivel de riesgo y nivel de formalidad

No todos los procesos requieren el mismo esfuerzo de evidencia.

En general:

- a menor riesgo, puede bastar una solucion mas sencilla
- a mayor riesgo, conviene reforzar identificacion, firma, sellado temporal, validacion y custodia

Esta proporcion es una de las decisiones mas importantes en implantacion.

## Importancia de la custodia

La evidencia no solo debe generarse. Tambien debe:

- conservarse
- poder recuperarse
- mantenerse interpretable
- poder defenderse con el paso del tiempo

Una evidencia excelente en el momento inicial puede perder valor si no existe una custodia razonable.

## Importancia del gobierno interno

El valor probatorio tambien depende de que la organizacion pueda explicar su sistema.

Por eso resultan utiles:

- roles definidos
- politicas internas
- criterios de decision
- revisiones periodicas
- procedimientos de auditoria y trazabilidad

Cuando la organizacion no puede explicar como funciona su propio proceso, la defensa probatoria se debilita.

## Preguntas practicas para evaluar un proceso

Antes de implantar o revisar un flujo digital, conviene preguntarse:

1. que hecho queremos poder demostrar
2. quien podria impugnarlo y por que
3. cuanto tiempo despues necesitaremos defenderlo
4. que evidencia estamos generando realmente
5. quien la conserva y en que condiciones
6. si esa evidencia sera interpretable dentro de anos

Estas preguntas suelen ser mas utiles que centrarse solo en la etiqueta comercial de la herramienta.

## Relacion con otras secciones del tutorial

Este capitulo se conecta especialmente con:

- [Conservacion y validacion](./22-conservacion-y-validacion.md)
- [Custodia y gestion de evidencias](./36-custodia-evidencias.md)
- [Custodia operativa de evidencias](./46-custodia-operativa.md)
- [Cuadro de decision por nivel de riesgo](./27-cuadro-decision-riesgo.md)
- [Cuadro de decision avanzado](./47-cuadro-decision-avanzado.md)

## Resumen rapido

La verdadera fortaleza de un proceso digital depende de su cadena de evidencia y no solo del documento final. Evaluar bien el riesgo probatorio ayuda a decidir cuando basta una solucion sencilla y cuando conviene reforzar identificacion, firma, sellado temporal, validacion y custodia.
