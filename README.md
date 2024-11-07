# APP-ISM

Este proyecto es una aplicación desarrollada para la gestión y monitoreo de actividades específicas, que incluye funcionalidades para el manejo de libros, escáneres de código de barras y otras herramientas de interacción de usuarios.

## Estructura del Proyecto

- **client/**: Contiene el código fuente de la aplicación.
  - **App.js**: Archivo principal de la aplicación que inicia el flujo de la interfaz.
  - **app.json**: Configuración de la aplicación.
  - **babel.config.js**: Configuración para Babel, el compilador de JavaScript.
  - **eas.json**: Configuración para Expo Application Services.
  - **index.js**: Punto de entrada de la aplicación.
  - **metro.config.js**: Configuración para Metro bundler.
  - **tsconfig.json**: Configuración para TypeScript.
  - **assets/**: Carpeta que almacena recursos gráficos como logotipos, íconos, banners, etc.
  - **src/components/**: Contiene componentes React organizados por funcionalidad en `atoms`, `molecules`, y `pages`.
  - **src/modules/**: Contiene módulos de infraestructura, dominio y lógica específicos de cada función.

## Características

- **Gestión de Libros**: Permite a los usuarios agregar, editar y eliminar libros con una interfaz intuitiva.
- **Escáner de Código de Barras**: Integración de una funcionalidad de escáner de códigos para la identificación rápida de elementos.
- **Interfaz de Usuario Dinámica**: Incluye botones, menús de perfil y vistas específicas que hacen la aplicación interactiva.
- **Gestión de Sesiones de Usuario**: Manejo de usuarios, registro y autenticación.

## Instalación y Configuración

1. **Clona este repositorio** en tu máquina local:

   ```bash
   git clone https://github.com/juannhm02/APP-ISMFront.git
   ```

2. **Accede a la carpeta del proyecto:**

```bash
cd APP-ISM-main/client
```

3. **Instala las dependencias necesarias para el proyecto:**

```bash
npm install
```

4. **Configura las variables de entorno:**

- Asegúrate de incluir cualquier variable de entorno necesaria en un archivo .env en la raíz del proyecto si se requieren configuraciones específicas (por ejemplo, claves de API o URLs de servicios).
- Asegúrate de configurar correctamente los datos en eas.json si usas servicios de Expo.

5. **Inicia el proyecto en modo de desarrollo:**

```bash
npm start
```

Este comando abrirá Expo Developer Tools en tu navegador, desde donde puedes ejecutar la aplicación en un emulador, dispositivo físico o navegador web.

## Scripts Disponibles

- **npm start:** Inicia la aplicación en modo desarrollo usando Expo.
- **npm run build:** Compila la aplicación para producción (requiere configuración adicional si se despliega en producción).
- **npm test:** Ejecuta las pruebas.

## Tecnologías Utilizadas

- **React Native:** Framework para el desarrollo de la aplicación móvil.
  Expo: Herramienta para el desarrollo y despliegue de aplicaciones React Native.
  TypeScript: Lenguaje de programación usado para un tipado más fuerte y mejores herramientas de desarrollo.

## Contribución

1. Haz un fork de este repositorio.
2. Crea una rama nueva

```bash
git checkout -b feature-nueva-funcion
```

3. Realiza los cambios y haz un commit

```bash
git commit -m 'Agrega nueva función'
```

4. Envía los cambios a tu rama

```bash
git push origin feature-nueva-funcion
```

5. Abre un Pull Request

## Licencia

Este proyecto está bajo la licencia MIT.

Este `README.md` incluye todas las instrucciones para la instalación, arranque, scripts, tecnologías utilizadas y el proceso de contribución.

```

```
