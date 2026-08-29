# Talento Caribe — plataforma educativa

Versión de demostración frontend de una plataforma educativa tecnológica con estética profesional.

## Incluye
- Landing page responsive y catálogo de cursos.
- Registro e inicio de sesión.
- Solicitud de matrícula por curso.
- Contacto y newsletter.
- Panel administrativo con métricas, usuarios y gestión de matrículas.
- Estados de matrícula: pendiente, aceptada y rechazada.
- Panel de egresados globales.
- Persistencia local con `localStorage`.

## Credenciales demo
Administrador: `admin@talentocaribe.com`
Contraseña: `Admin123!`

## Estructura
```text
Talento_Caribe/
├── index.html
├── css/styles.css
├── js/app.js
├── data/README.txt
└── README.md
```

## Importante para producción
`localStorage` es únicamente una base de datos simulada para una demo. Para producción se debe sustituir por una API/backend (por ejemplo Node.js + Express), PostgreSQL/MySQL, contraseñas con hash, sesiones/JWT, validación del servidor, control de roles y protección CSRF/CORS.
