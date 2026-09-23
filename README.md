# zococity-compliance-docs

Documentos públicos de cumplimiento normativo (GPSR — Reglamento (UE) 2023/988) para los
listados de Amazon de Zococity S.L. / Vulkkano. Estos ficheros se referencian desde el
atributo `compliance_media` de Listings Items API para que Amazon los enlace desde la ficha
de producto.

Repositorio deliberadamente público y sin JavaScript de por medio: Amazon necesita poder
descargar el fichero directamente (URL estática), sin pasar por ningún control de acceso.

## Ficheros

- `gpsr/safety-notice-es.pdf` — advertencias de seguridad (ES)
- `gpsr/safety-notice-fr.pdf` — advertencias de seguridad (FR)
- `gpsr/safety-notice-it.pdf` — advertencias de seguridad (IT)
- `gpsr/safety-notice-de.pdf` — advertencias de seguridad (DE)
- `gpsr/safety-notice-nl.pdf` — advertencias de seguridad (NL)
- `gpsr/safety-notice-sv.pdf` — advertencias de seguridad (SE)
- `gpsr/safety-notice-pl.pdf` — advertencias de seguridad (PL)

Para Bélgica (BE) se reutiliza `safety-notice-fr.pdf` con `content_language: fr_FR` (mercado
predominantemente francófono en Seller Central para esta cuenta).
