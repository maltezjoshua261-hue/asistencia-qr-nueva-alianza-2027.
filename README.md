# ASISTENCIA QR – NUEVA ALIANZA 2027

Interfaz web independiente para probar el escáner QR desde una página HTTPS de GitHub Pages. El backend sigue siendo el proyecto existente de Google Apps Script y la hoja de cálculo actual.

## Estado

- [x] Interfaz independiente con la misma identidad visual.
- [x] Selector manual ENTRADA / SALIDA.
- [x] Escáner QR con Html5Qrcode.
- [x] Registro mediante el endpoint JSONP existente de Apps Script.
- [ ] Consultas de resumen diario, mensual e historial desde esta interfaz.
- [ ] Acceso administrativo protegido en el servidor.
- [ ] Prueba real de cámara y registro con un carnet de prueba autorizado.

## Publicación

En GitHub, abre **Settings → Pages** y configura:
- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

La dirección esperada será:
https://maltezjoshua261-hue.github.io/asistencia-qr-nueva-alianza-2027./

## Conexión

La interfaz apunta a la implementación existente de Apps Script. La clave de conexión se introduce en el navegador y no está escrita en este repositorio público.

**Importante:** no publicar ni compartir claves de conexión. Antes de usar con estudiantes, hay que proteger también el acceso en el servidor y probar con un registro de prueba autorizado. Las secciones de reportes están visibles pero deshabilitadas hasta implementar endpoints JSONP protegidos para administración.

Este repositorio no modifica ni contiene copias de los otros sistemas escolares.
