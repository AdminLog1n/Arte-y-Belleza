# Arte Belleza

Plataforma profesional para la venta, gestión y promoción de eBooks de arte y belleza.  
Incluye sitio web, app móvil y panel de administración.

## Estructura del proyecto

- `/backend` → Lógica del sistema, base de datos, métodos de pago, administración.
- `/web` → Sitio web para clientes y administración.
- `/mobile` → App móvil para clientes y administración.

## ¿Dónde editar?

- **Diseño y contenido web:** `/web/src/pages` y `/web/src/components`
- **Diseño y contenido móvil:** `/mobile/screens` y `/mobile/components`
- **Lógica de negocio, administración, métodos de pago:** `/backend/src`

## Instalación rápida

1. Clona el repositorio o descarga el código.
2. Instala dependencias en cada carpeta (`npm install` en `/backend`, `/web`, `/mobile`)
3. Configura la base de datos en `/backend/src/app.js`
4. Corre el backend: `npm run start`
5. Corre el frontend web: `npm start`
6. Corre la app móvil: `npx expo start`

---

**¡Edita los archivos en las carpetas indicadas para personalizar Arte Belleza a tu gusto!**
