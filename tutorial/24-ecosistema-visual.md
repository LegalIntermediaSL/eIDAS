# 24. Esquema visual del ecosistema eIDAS

## Introduccion

Este esquema ofrece una vision sintetica de como se relacionan los elementos principales del ecosistema eIDAS.

```mermaid
flowchart TD
    A["Reglamento eIDAS"] --> B["Identificacion electronica"]
    A --> C["Servicios de confianza"]
    A --> D["Prestadores de servicios de confianza"]
    D --> E["Prestadores cualificados"]
    D --> F["Prestadores no cualificados"]
    E --> G["Lista de confianza"]
    C --> H["Firma electronica"]
    C --> I["Sello electronico"]
    C --> J["Sello de tiempo"]
    C --> K["Entrega electronica certificada"]
    C --> L["Autenticacion de sitios web"]
    H --> M["Certificado cualificado"]
    I --> N["Certificado cualificado de sello"]
    J --> O["Evidencia temporal"]
    K --> P["Prueba de envio y recepcion"]
    A --> Q["eIDAS 2.0"]
    Q --> R["Wallet europea"]
    R --> S["Credenciales y atributos verificables"]
    R --> T["Usuarios"]
    R --> U["Relying parties"]
```

## Como leerlo

- el reglamento eIDAS es la base del sistema
- de el salen dos grandes bloques: identificacion electronica y servicios de confianza
- los prestadores hacen operativos esos servicios
- la lista de confianza ayuda a verificar el nivel cualificado
- eIDAS 2.0 amplifica el marco con la wallet europea

## Utilidad del esquema

Este diagrama no sustituye a las definiciones juridicas, pero ayuda a visualizar rapidamente como encajan las piezas principales del sistema.

## Resumen rapido

El ecosistema eIDAS conecta normas, prestadores, servicios, certificados, evidencias y, en la nueva etapa, wallets y credenciales verificables.
