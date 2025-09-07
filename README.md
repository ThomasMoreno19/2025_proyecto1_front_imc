# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

Despliegue del Frontend
Esta sección describe los pasos para desplegar el servicio del frontend en Vercel.

Inicio de sesión: Se inició sesión en la plataforma de Vercel.

Importación de Proyecto: Se seleccionó la opción de "Importar proyecto".

Conexión con GitHub: La cuenta de Vercel se conectó con la cuenta de GitHub para acceder a los repositorios.

Selección del Repositorio: Del repositorio de GitHub, se eligió el fork de 2025_proyecto_front_imc.

Despliegue: Se importó el proyecto al hacer clic en "Importar".

Configuración de la API: Una vez desplegado, se actualizó la URL de Axios en el código para que apuntara a la URL del backend recién desplegado, asegurando la comunicación entre ambos servicios.
