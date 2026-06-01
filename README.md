# Traje a la Medida TDAH

Aplicacion HTML local-first para registrar el seguimiento diario de tratamiento TDAH.

## Uso

Abre `index.html` en el navegador. No requiere build ni servidor.

## Funciones

- Acceso con email y password guardado localmente.
- Acceso tipo Google para perfiles locales en este navegador.
- Historial clinico por usuario en `localStorage`.
- Registro diario de tratamiento, dosis, hora, sintomas y notas.
- Edicion y eliminacion de registros.
- Analisis visual con Chart.js.
- Exportacion a PDF, CSV y respaldo JSON.
- Importacion de respaldo JSON.
- Asistente educativo con respuestas locales.

## Datos y privacidad

La app guarda los datos en el `localStorage` del navegador. No sincroniza con servidores externos.

El boton de Google funciona como acceso local con un email Google. Para convertirlo en OAuth real se debe configurar Google Identity Services con un Client ID y, de preferencia, un backend para validar tokens.

## Aviso medico

Esta herramienta no sustituye consulta medica profesional. Sirve como bitacora para preparar conversaciones con el equipo tratante.
