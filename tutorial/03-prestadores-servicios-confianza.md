# 03. Prestadores de servicios de confianza

## Introduccion

Dentro del ecosistema eIDAS, los prestadores de servicios de confianza son actores esenciales. Son las entidades que emiten certificados, prestan servicios de firma, sello, validacion, conservacion, entrega electronica certificada y otros servicios vinculados a la confianza digital.

No todos los prestadores tienen la misma posicion juridica. El propio marco eIDAS distingue entre prestadores cualificados y prestadores no cualificados, y esa diferencia tiene consecuencias practicas muy importantes.

## Que es un prestador de servicios de confianza

De forma sencilla, un prestador de servicios de confianza es una persona fisica o juridica que presta uno o varios servicios de confianza.

Estos servicios pueden incluir, entre otros:

- expedicion de certificados electronicos
- servicios de firma electronica
- servicios de sello electronico
- sellos de tiempo electronicos
- entrega electronica certificada
- validacion de firmas o sellos
- conservacion de firmas o sellos
- autenticacion de sitios web

## Prestadores cualificados y no cualificados

El Reglamento eIDAS y la normativa complementaria espanola distinguen dos grandes categorias:

1. prestadores cualificados de servicios de confianza
2. prestadores no cualificados de servicios de confianza

La diferencia no es solo terminologica. Afecta al nivel de supervision, a los requisitos exigibles y a los efectos juridicos asociados a los servicios prestados.

## Prestadores cualificados

Un prestador cualificado es aquel al que el organismo de supervision ha concedido formalmente la cualificacion para prestar uno o varios servicios de confianza cualificados.

### Rasgos principales

- debe cumplir requisitos tecnicos, organizativos y juridicos reforzados
- esta sometido a verificacion previa y supervision continuada
- sus servicios cualificados deben figurar en la lista de confianza
- sus servicios pueden beneficiarse de efectos juridicos reforzados en el marco eIDAS

### Por que son importantes

La inclusion de un prestador y de sus servicios en la lista de confianza tiene un valor central en eIDAS. En la practica, un servicio solo es cualificado si aparece como tal en la lista oficial correspondiente.

Esto aporta seguridad juridica porque facilita comprobar:

- si el prestador tiene la condicion de cualificado
- que servicios concretos estan cualificados
- el estado actual del servicio
- el historial de situacion del prestador o del servicio

## Prestadores no cualificados

Un prestador no cualificado tambien puede prestar servicios de confianza, pero no dispone de la cualificacion formal para ofrecerlos como servicios cualificados.

### Rasgos principales

- no necesita una verificacion administrativa previa para iniciar su actividad en los mismos terminos que un cualificado
- debe comunicar su actividad al organo supervisor en Espana
- sus servicios no tienen automaticamente el mismo estatuto juridico reforzado que los cualificados
- esta sujeto a control posterior, seguimiento e inspeccion

### Que significa esto en la practica

Un servicio no cualificado no es necesariamente invalido o inutil. Puede ser perfectamente funcional y util para muchos casos de uso. Sin embargo, no debe confundirse con un servicio cualificado ni presentarse como tal.

En un conflicto juridico o en un proceso de verificacion formal, esta distincion puede ser muy relevante.

## Supervision en Espana

En Espana, la supervision y publicacion de informacion sobre prestadores de servicios electronicos de confianza se articula dentro del marco del Reglamento eIDAS y de la `Ley 6/2020, de 11 de noviembre, reguladora de determinados aspectos de los servicios electronicos de confianza`.

La ley deja clara una diferencia importante:

- los prestadores cualificados estan sujetos a un sistema de verificacion previa y posterior
- los prestadores no cualificados quedan sometidos a un modelo de control posterior y deben comunicar su actividad

## La lista de confianza

La lista de confianza, conocida habitualmente como `TSL` por sus siglas en ingles (`Trusted List`), es el instrumento oficial donde se publica la informacion sobre los prestadores cualificados y los servicios cualificados que estan bajo supervision de un Estado miembro.

### Funcion de la TSL

La lista de confianza o `TSL` sirve para:

- identificar que prestadores tienen condicion de cualificados
- comprobar que servicios concretos son cualificados
- conocer el estado del servicio
- apoyar la interoperabilidad y la validacion transfronteriza

## Listas oficiales en Espana

Para Espana, las referencias oficiales mas utiles son estas:

- Consulta de prestadores cualificados: [Prestadores cualificados](https://sedeaplicaciones.minetur.gob.es/prestadores/)
- Consulta de prestadores no cualificados: [Prestadores no cualificados](https://sedeaplicaciones.minetur.gob.es/Prestadores/NoCualificados.aspx)
- Lista de confianza espanola en formato TSL: [TSL de Espana](https://sedediatid.mineco.gob.es/Prestadores/TSL/TSL.xml)
- Version PDF de la TSL espanola: [TSL de Espana en PDF](https://sedediatid.mineco.gob.es/Prestadores/TSL/TSL.pdf)

Estas referencias son especialmente utiles porque permiten consultar la informacion oficial publicada por la Administracion competente.

## Lista europea de prestadores cualificados

La Comision Europea mantiene el acceso a las listas de confianza nacionales y a herramientas de consulta a escala de la Union.

Referencias oficiales:

- Portal europeo de listas de confianza: [EU Trusted Lists](https://digital-strategy.ec.europa.eu/en/policies/eu-trusted-lists)
- Buscador europeo de listas de confianza: [Trusted List Browser](https://webgate.ec.europa.eu/tl-browser/)

Estas herramientas permiten localizar prestadores y servicios cualificados de distintos Estados miembros.

## Relacion con otras secciones del tutorial

Este capitulo ofrece la vision institucional y de supervision. Para profundizar en el significado juridico de los servicios cualificados y en su uso practico, conviene completar la lectura con:

- [Servicios de confianza cualificados](./09-servicios-confianza-cualificados.md)
- [Cuadro comparativo entre prestadores cualificados y no cualificados](./19-cuadro-prestadores.md)

## Importante sobre la lista de prestadores

La lista de prestadores no es estatica. Cambia con altas, bajas, modificaciones de servicios y cambios de estado.

Por eso, en lugar de copiar una relacion cerrada dentro del tutorial, lo mas riguroso es remitir siempre a las listas oficiales vivas. Esta recomendacion es especialmente importante si:

- se va a confiar en un certificado concreto
- se necesita verificar si un servicio sigue siendo cualificado
- se requiere evidencia actualizada para un procedimiento juridico o administrativo

## Como leer correctamente una lista de prestadores

Cuando se consulte la lista, conviene fijarse al menos en estos puntos:

1. nombre exacto del prestador
2. tipo de servicio ofrecido
3. si el servicio aparece como cualificado o no
4. estado actual del servicio
5. pais y autoridad supervisora

## Ejemplos de prestadores que suelen aparecer en el mercado espanol

En las consultas oficiales de Espana suelen encontrarse entidades conocidas del sector, como por ejemplo FNMT-RCM, ACCV, Camerfirma, Firmaprofesional, Izenpe, Logalty, Lleida.net, Signaturit, Viafirma, Validated ID o Uanataca, entre otras.

No obstante, esta relacion es meramente orientativa y puede variar. La comprobacion valida debe hacerse siempre en la lista oficial correspondiente.

## Diferencia clave para el usuario

Si una persona, empresa o Administracion va a contratar un servicio de confianza, la pregunta esencial no es solo quien presta el servicio, sino:

- si el prestador es cualificado o no
- que servicio concreto ofrece
- si ese servicio figura oficialmente como cualificado

La respuesta a esas preguntas condiciona el nivel de confianza juridica y tecnica que puede atribuirse al servicio.

## Resumen rapido

Los prestadores de servicios de confianza son las entidades que hacen posible gran parte de la confianza digital en Europa. eIDAS distingue entre prestadores cualificados y no cualificados, y reserva a los primeros un regimen reforzado de supervision y reconocimiento.

Para verificar la situacion real de un prestador, lo correcto es acudir a la lista oficial espanola o a las listas europeas de confianza, no a listados informales o desactualizados.

## Nota de actualidad

Los enlaces y referencias de esta seccion fueron verificados el `16 de abril de 2026`. Dado que la informacion sobre prestadores puede cambiar, conviene revisar siempre la fuente oficial mas reciente.
