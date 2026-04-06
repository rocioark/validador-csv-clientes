\# Validador CSV de clientes



Automatización creada con n8n para validar registros de clientes desde un archivo CSV.



\## Funcionalidad



\- Lee un archivo CSV (`clientes.csv`)

\- Valida:

&#x20; - id no vacío

&#x20; - email válido

&#x20; - fecha en formato YYYY-MM-DD

\- Clasifica los registros en:

&#x20; - válidos

&#x20; - con error

\- Genera automáticamente:

&#x20; - `clientes\_validos.csv`

&#x20; - `clientes\_error.csv`



\## Tecnologías



\- n8n

\- Docker

\- JavaScript



\## Ejecución



1\. Colocar archivo `clientes.csv` en:

