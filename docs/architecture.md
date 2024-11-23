echo "# Arquitectura del Proyecto

## Visión General
Este servidor está diseñado para ser modular y escalable, lo que te permitirá agregar nuevos servicios o configuraciones según sea necesario.

## Diagrama de Arquitectura
\`\`\`plaintext
[ Usuario ] --> [ Router ] --> [ Raspberry Pi ]
                          ├── [ Docker ]
                          ├── [ NGINX ]
                          └── [ Herramientas de Monitoreo ]
\`\`\`

## Componentes
- **Docker**: Para aplicaciones contenerizadas.
- **NGINX**: Como proxy inverso o servidor web.
- **Prometheus/Grafana**: Para monitoreo (opcional).

## Descripción de Servicios
- **NGINX**: Actúa como un servidor web y proxy inverso para administrar el tráfico hacia aplicaciones contenerizadas.
- **Docker**: Permite ejecutar contenedores de forma eficiente y aislada." > docs/architecture.md
