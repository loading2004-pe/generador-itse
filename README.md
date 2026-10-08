# Generador ITSE

Plataforma web de Safety Through Design para:
- llenar los anexos ITSE y los Word;
- armar el plan de seguridad y la memoria de extintores;
- ordenar las carpetas de cada expediente.

Por: Favio Arrese.

- **Datos:** cada expediente se guarda en el Google Drive del usuario (carpeta «Generador ITSE»), al iniciar sesión con Google.
- **Lo que no está en este código:** el banco de cocinas ocultas (certificados, DNI, vigencias, fichas RUC), la lista de apoderados y la firma viven solo en ese Drive.
- **Archivos:** `index.html` es la aplicación completa. `ocr/` trae el lector de texto (pdf.js y Tesseract) que funciona en el navegador.
