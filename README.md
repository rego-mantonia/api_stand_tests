# Proyecto de Pruebas Automatizadas de API

### Requisitos y Tecnologías Usadas:
- Python 3.14
- PyCharm 2026.2.3
- Pip --> Instalación de PyTest y Librería Requests

## Solicitudes HTTP y Endpoints:
### GET

- Solicitud para acceder a la documentación de la API (API Docs) de Urban Grocers `/docs/`
- Solicitud para recibir los Logs del servidor principal `/api/logs/main/`

### POST

- Solicitud para crear un nuevo usuario `/api/v1/users/`
- Solicitud para buscar los kits por productos `/api/v1/products/kits/`

## Pruebas:
Comprobar que el parámetro **`firstName`** cumpla con los requisitos:
- El nombre sólo puede contener letras latinas
- La longitud debe ser de 2 a 15 caracteres