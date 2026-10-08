# Generador ITSE

Plataforma web de Safety Through Design para:
- llenar los anexos ITSE y los Word (la fecha va solo en los documentos que elijas);
- armar el plan de seguridad y la memoria de extintores;
- ordenar y verificar las carpetas de cada expediente;
- mantener al día el banco de cocinas ocultas (se suelta el certificado nuevo y va a su lugar; el anterior queda como respaldo).

Por: Favio Arrese.

- **Cuentas:** cada persona se registra con su correo y contraseña. Al administrador le llega un correo con botones para aprobarla, y decide a qué entra: ITSE, SUNARP y el banco de cocinas. También se administra en la pestaña Usuarios.
- **Datos:** todo se guarda en el Google Drive del administrador a través de su servidor (Google Apps Script). Cada usuario tiene su propia carpeta.
- **Lo que no está en este código:** el banco de cocinas ocultas (certificados, DNI, vigencias, fichas RUC), la lista de apoderados, la firma y las contraseñas viven solo en ese Drive y en el servidor.
- **Archivos:** `index.html` es la aplicación completa. `ocr/` trae el lector de texto (pdf.js y Tesseract) que funciona en el navegador.
