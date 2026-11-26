# Proceso de publicación de Supérate para Android

Este repositorio se utiliza exclusivamente para distribuir versiones oficiales de la aplicación Supérate mediante GitHub Releases.

## Alcance

- Contiene los archivos APK publicados y la información pública de cada versión.
- No contiene el código fuente de la aplicación.
- No contiene bases de datos, información de usuarios, datos de menores, claves, contraseñas, tokens ni archivos de firma privados.
- Cada versión publicada debe conservarse como una versión histórica; no se deben reemplazar APK de versiones anteriores.

## Requisitos antes de publicar

Antes de crear una versión, el responsable debe verificar:

1. Que la versión fue aprobada expresamente para distribución.
2. Que el APK corresponde al paquete Android oficial: `com.superate.clubconquistadores`.
3. Que la firma del APK es la misma que la de las versiones anteriores, para permitir actualizaciones normales.
4. Que el número de versión y el código de versión son correctos.
5. Que el APK se instala y abre correctamente en un dispositivo compatible.
6. Que se calcula y registra el hash SHA-256 del archivo.
7. Que no se incluyeron secretos ni datos privados en el APK o en los archivos adjuntos.

## Formato de publicación

- Crear una GitHub Release por cada versión.
- Usar una etiqueta clara, por ejemplo `v1.0.0`.
- Adjuntar el APK con un nombre descriptivo, por ejemplo `superate-android-v1.0.0.apk`.
- Incluir en las notas de la versión el número de versión, los cambios principales, los requisitos de Android y el SHA-256 del APK.
- No borrar ni sobrescribir versiones anteriores.

## Instalación y actualizaciones

GitHub Releases proporciona la descarga del APK. La instalación y las actualizaciones se realizan en el dispositivo Android y requieren la confirmación del usuario cuando Android la solicite. La publicación del APK no concede acceso a la aplicación ni sustituye sus controles de autenticación.

## Estado actual

El repositorio está preparado para documentar el proceso. Todavía no se ha publicado ningún APK oficial.
