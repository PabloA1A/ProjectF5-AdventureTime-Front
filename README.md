# Adventure Time

Adventure Time es una aplicación web diseñada para gestionar eventos en línea como talleres, masterclass o webinars. Los usuarios pueden ver la descripción de un evento, registrarse y cancelar su registro. También pueden ver la lista de eventos a los que se han registrado. Los administradores tienen herramientas para la gestión completa (CRUD) de los eventos.

## Requisitos del Sistema

- Node.js v14 o superior
- npm v6 o superior

## Configuración Recomendada del IDE

- Visual Studio Code
- Extensión: Volar (deshabilitar Vetur)

## Configuración del Proyecto

### Instalación

Para instalar las dependencias del proyecto, ejecuta:

```sh
npm install
```

### Compilar y Recargar en Caliente para Desarrollo

Para iniciar el servidor de desarrollo con recarga en caliente, ejecuta:

```sh
npm run dev
```

### Compilar y Minificar para Producción

Para compilar el proyecto para producción, ejecuta:

```sh
npm run build
```

### Ejecutar Pruebas Unitarias con Vitest

Para ejecutar las pruebas unitarias, ejecuta:

```sh
npm run test:unit
```
## Flujo de Usuario

<img width="1376" alt="User Flow Upcoming Events" src="https://github.com/user-attachments/assets/2fe5107d-125c-4abb-82f7-813c5af05df2">

## Estructura del Proyecto

```sh
AdventureTime/
├── .vscode/
│   ├── extensions.json
│   └── settings.json
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── __tests__/
│   │   ├── dashboard/
│   │   ├── icons/
│   │   ├── Card.vue
│   │   ├── Carrusel.vue
│   │   ├── Event.vue
│   │   ├── Login.vue
│   │   ├── NavBar.vue
│   │   ├── Register.vue
│   │   └── RegisterIn.vue
│   ├── composables/
│   ├── core/
│   ├── layouts/
│   ├── router/
│   ├── services/
│   │   ├── RegisterEventRepository.js
│   │   └── RegisterEventService.js
│   ├── stores/
│   ├── views/
│   ├── App.vue
│   ├── main.js
│   └── assets/
├── .env
├── .gitignore
├── index.html
├── jsconfig.json
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
└── vitest.config.js
```

## Contribución

Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
3. Realiza tus cambios y haz commit (git commit -m 'Añadir nueva funcionalidad').
4. Sube tus cambios (git push origin feature/nueva-funcionalidad).
5. Abre un Pull Request.

## Licencia

Este proyecto está licenciado bajo la Licencia ISC. Consulta el archivo LICENSE para más detalles.

¡Gracias por usar Adventure Time!