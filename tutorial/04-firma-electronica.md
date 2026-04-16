# 04. Firma electronica simple, avanzada y cualificada

## Introduccion

Uno de los puntos mas importantes del reglamento eIDAS es la distincion entre distintas categorias de firma electronica. Esta diferencia es clave porque no todas las firmas ofrecen el mismo nivel de garantias tecnicas ni el mismo peso juridico.

En la practica, muchas dudas sobre eIDAS aparecen precisamente aqui:

- que se considera una firma electronica
- que diferencia hay entre una firma simple y una avanzada
- cuando una firma puede considerarse cualificada
- que valor probatorio tiene cada una

## Punto de partida

eIDAS no parte de una unica firma electronica, sino de una categoria general y de modalidades con requisitos adicionales.

De forma simplificada, podemos hablar de:

1. firma electronica simple
2. firma electronica avanzada
3. firma electronica cualificada

Aunque en lenguaje cotidiano se usa mucho la expresion `firma simple`, conviene recordar que eIDAS define formalmente la `firma electronica` como categoria general. La expresion `firma electronica simple` se utiliza de forma practica para referirse a la firma electronica que no alcanza los requisitos de avanzada o cualificada.

## 1. Firma electronica simple

### Que es

Es cualquier conjunto de datos en formato electronico que una persona utiliza para firmar otros datos electronicos.

En terminos muy amplios, puede abarcar desde una aceptacion por clic hasta la insercion de un nombre al final de un correo, pasando por mecanismos de firma digital con garantias limitadas.

### Rasgos principales

- tiene un concepto amplio y flexible
- no exige por si misma requisitos tecnicos reforzados
- puede servir como medio de prueba
- su fuerza juridica dependera mucho del contexto y de la evidencia disponible

### Ejemplos habituales

- marcar una casilla de aceptacion
- firmar en una tableta sin un sistema robusto de trazabilidad
- escribir el nombre al final de un correo electronico
- aceptar unas condiciones pulsando un boton

### Ventajas

- es facil de implantar
- tiene bajo coste
- resulta util en procesos sencillos o de bajo riesgo

### Limitaciones

- ofrece menos garantias sobre identidad, integridad y control del acto de firma
- puede ser mas facil de impugnar
- suele requerir prueba adicional para acreditar quien firmo y en que condiciones

## 2. Firma electronica avanzada

### Que es

Es una firma electronica que cumple requisitos adicionales destinados a reforzar el vinculo entre la firma y su firmante, asi como la integridad de los datos firmados.

De forma general, debe estar:

- vinculada de manera unica al firmante
- capacitada para identificar al firmante
- creada utilizando datos de creacion de firma que el firmante pueda utilizar con un alto nivel de confianza bajo su control exclusivo
- vinculada a los datos firmados de modo que cualquier modificacion posterior sea detectable

### Que aporta frente a la simple

La firma avanzada no es solo un gesto o una aceptacion. Requiere un marco tecnico y operativo que permita demostrar mejor:

- quien firma
- que se ha firmado
- que el contenido no ha sido alterado despues

### Ventajas

- mejora notablemente la capacidad probatoria
- reduce el riesgo de impugnacion
- resulta adecuada para multitud de operaciones empresariales y contractuales

### Limitaciones

- no alcanza automaticamente el maximo nivel juridico reforzado de eIDAS
- su validez practica depende de como se haya implementado el sistema
- puede generar controversia si la trazabilidad tecnica o la identificacion del firmante no son solidas

## 3. Firma electronica cualificada

### Que es

Es una firma electronica avanzada que cumple dos requisitos adicionales de maxima relevancia:

1. se basa en un certificado cualificado de firma electronica
2. se crea mediante un dispositivo cualificado de creacion de firma electronica

### Por que es especial

Dentro del sistema eIDAS, la firma cualificada es la que recibe el reconocimiento juridico mas fuerte.

En terminos generales:

- tiene un estatus reforzado en toda la Union Europea
- equivale juridicamente a la firma manuscrita en los terminos previstos por la norma
- descansa en prestadores y servicios sometidos a requisitos reforzados

### Ventajas

- ofrece el mayor nivel de seguridad juridica
- facilita el reconocimiento transfronterizo
- reduce la discusion sobre la identidad del firmante y la integridad del documento

### Limitaciones o costes

- exige una infraestructura mas exigente
- puede implicar mayores costes operativos
- no siempre es necesaria para todos los casos de uso

## Comparativa rapida

### Firma electronica simple

- nivel de formalidad: bajo
- garantias tecnicas: basicas o variables
- facilidad de uso: muy alta
- fuerza probatoria: dependiente del contexto

### Firma electronica avanzada

- nivel de formalidad: medio o alto
- garantias tecnicas: reforzadas
- facilidad de uso: media
- fuerza probatoria: superior a la simple

### Firma electronica cualificada

- nivel de formalidad: alto
- garantias tecnicas: maximas dentro del marco eIDAS
- facilidad de uso: mas exigente
- fuerza probatoria: especialmente robusta

## Que firma conviene usar

No existe una unica respuesta valida para todos los casos. La eleccion depende de factores como:

- el riesgo juridico de la operacion
- el valor economico del acto o contrato
- la necesidad de prueba futura
- el nivel de seguridad exigido
- si hay dimension transfronteriza
- si una norma concreta exige una modalidad determinada

## Regla practica orientativa

### Firma simple

Puede ser suficiente para:

- procesos de baja criticidad
- aceptaciones internas
- tramites donde el riesgo de conflicto es reducido

### Firma avanzada

Suele ser adecuada para:

- contratos privados
- procesos de onboarding
- aceptaciones con necesidad de trazabilidad
- operaciones empresariales con riesgo medio

### Firma cualificada

Es especialmente recomendable cuando:

- se necesita maxima seguridad juridica
- el riesgo de litigio es alto
- hay exigencias regulatorias o sectoriales reforzadas
- se quiere facilitar el reconocimiento mas solido dentro del marco europeo

## Error frecuente

Un error muy comun es pensar que toda firma digital es automaticamente una firma cualificada. No es asi.

Para que una firma sea cualificada no basta con que se haya usado tecnologia digital o criptografia. Deben concurrir especificamente los requisitos previstos en eIDAS para certificado cualificado y dispositivo cualificado.

## Relacion con los prestadores de servicios de confianza

La firma cualificada no puede entenderse sin los prestadores cualificados de servicios de confianza. Son ellos quienes emiten los certificados cualificados y operan dentro del ecosistema supervisado que hace posible este nivel reforzado de confianza.

Por eso esta seccion se conecta directamente con:

- [Prestadores de servicios de confianza](./03-prestadores-servicios-confianza.md)

## Impacto en un conflicto o juicio

Cuanto mayor sea la robustez de la firma y de la evidencia asociada, mas facil suele ser defender su validez en caso de impugnacion.

Esto no significa que una firma simple carezca de valor, sino que:

- puede requerir mas prueba complementaria
- puede ser mas discutida por la otra parte
- puede generar mayores costes de acreditacion

En cambio, la firma cualificada parte de una posicion juridica notablemente mas fuerte.

## Resumen rapido

La firma electronica simple es la modalidad mas abierta y flexible, pero tambien la mas debil desde el punto de vista probatorio. La firma avanzada introduce garantias tecnicas y de vinculacion con el firmante. La firma cualificada, ademas, se apoya en un certificado cualificado y en un dispositivo cualificado, lo que le otorga el nivel mas alto de reconocimiento dentro de eIDAS.

## Siguiente lectura recomendada

Despues de esta comparativa, el siguiente paso natural del tutorial puede ser:

1. profundizar en los servicios de confianza cualificados
2. explicar el valor de los certificados cualificados
3. desarrollar una seccion sobre eIDAS 2.0
