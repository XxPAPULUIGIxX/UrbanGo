# UrbanGo

**UrbanGo** es una aplicación diseñada para mejorar y reemplazar la actual aplicación "YOVOY", buscando hacerla más eficiente y fácil de manejar para cualquier usuario. Con una interfaz intuitiva y fácil de entender, **UrbanGo** es la mejor opción para los ciudadanos de Aguascalientes que necesitan una forma sencilla de consultar rutas, hacer seguimientos en tiempo real, y gestionar trámites de manera eficiente.

## Características Principales

- **Capacitación de Trámites**: Proceso simplificado para ayudar a los usuarios con la gestión de trámites relacionados con el transporte.
- **Vista de Rutas**: Visualización clara y sencilla de las rutas disponibles para el transporte público.
- **Tracking en Tiempo Real**: Seguimiento eficiente y en tiempo real de las rutas de transporte, asegurando que los usuarios siempre tengan información actualizada.
- **Envío de Reportes**: Los usuarios pueden enviar reportes de manera rápida para mejorar el servicio o informar sobre incidencias.
- **Consulta de Saldo y Movimientos**: Posibilidad de consultar el saldo y los movimientos recientes en las tarjetas YOVOY.
- **Interacción Intuitiva**: La interfaz de usuario está diseñada para ser fácil de entender y navegar, asegurando que cualquier persona pueda usar la aplicación sin problemas.

## Tecnologías Utilizadas

- **Frontend**: **Kotlin** (para el desarrollo de la interfaz y la lógica de la aplicación móvil).
- **Backend**: **Java** (para el desarrollo del servidor y la lógica de negocio).
- **Base de Datos**: **MongoDB Atlas** (base de datos NoSQL para el almacenamiento de rutas, reportes, usuarios y ubicaciones).
- **Plataforma**: **Android** (actualmente disponible como archivo APK para instalación manual).

## Estructura de la Base de Datos

### Tablas en la Base de Datos:

1. **Rutas**:
   - Información sobre las rutas de transporte disponibles, incluyendo paradas y horarios.
   
2. **Reportes**:
   - Almacena los reportes enviados por los usuarios para incidencias o mejoras.
   
3. **Usuarios**:
   - Información sobre los usuarios de la aplicación, incluyendo sus credenciales, saldos y movimientos.
   
4. **Ubicación**:
   - Datos de ubicación en tiempo real para el seguimiento de las rutas y el envío de reportes.

## Flujo de Usuario

1. **Registro de Usuario**: Los usuarios deben registrarse en la aplicación con sus credenciales. 
2. **Consulta de Rutas**: Una vez registrados, los usuarios pueden consultar las rutas disponibles y obtener información detallada sobre cada una.
3. **Seguimiento en Tiempo Real**: Los usuarios pueden seguir en tiempo real la ubicación de las rutas y recibir actualizaciones de su progreso.
4. **Envío de Reportes**: Si los usuarios tienen problemas o incidencias, pueden enviar reportes desde la aplicación.
5. **Consulta de Saldo**: Los usuarios pueden ver el saldo actual y los movimientos realizados en sus tarjetas YOVOY.
6. **Finalización de Sesión**: Al finalizar, los usuarios pueden cerrar sesión de manera sencilla.

## Instalación

1. **Descarga del APK**: Actualmente, la instalación de la aplicación se realiza mediante la descarga del archivo APK desde el repositorio en GitHub. 
2. **Instrucciones**:
   - Descarga el archivo APK desde el enlace proporcionado.
   - Asegúrate de habilitar la opción para instalar aplicaciones de fuentes desconocidas en tu dispositivo Android.
   - Instala la aplicación como cualquier otro APK.
   
   **Nota**: A futuro, se planea implementar la aplicación en la **Google Play Store** para facilitar su instalación.

## Pruebas

La aplicación ha sido probada en diversos dispositivos Android para garantizar su funcionalidad y compatibilidad. Las pruebas se realizaron asegurando que la experiencia de usuario fuera fluida y sin errores, dentro de los límites de los dispositivos utilizados.

### Dispositivos probados:
- **Samsung Galaxy S22 Ultra**
- **Xiamoi Redmi 10C**
- **Honor X6b**
- **Huawei Y9s**
-   
### Resultados:
- La aplicación ha demostrado ser completamente funcional y compatible en estos dispositivos. No se encontraron errores graves durante las pruebas.

## Futuras Mejoras

- **Google Play Store**: A futuro, planeamos publicar la aplicación en **Google Play Store** para hacerla más accesible y simplificar su instalación.
- **Integración con otros servicios**: Se planean nuevas funcionalidades como la integración con otras plataformas de pago y mejoras en la gestión de rutas y reportes.

## Conclusión

**UrbanGo** es una solución moderna, eficiente y fácil de usar para la gestión de rutas y el seguimiento del transporte público en Aguascalientes. Con su interfaz intuitiva, funciones de seguimiento en tiempo real, y la capacidad de consultar saldos y movimientos en tarjetas YOVOY, se presenta como la mejor opción para los ciudadanos de la ciudad.
