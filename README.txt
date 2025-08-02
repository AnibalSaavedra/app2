
MBI360 - SISTEMA UNIFICADO FINAL

Autor: Aníbal Saavedra
Versión: FINAL

--------------------------------------
INSTRUCCIONES DE USO
--------------------------------------

1. 📁 ARCHIVOS INCLUIDOS:
   - app.py: Script principal de la aplicación.
   - modulo_disociacion.py: Módulo del test de disociación o trauma.
   - modulo_epigenetico.py: Módulo del test epigenético emocional.
   - modulo_condiciones.py: Módulo de condiciones clínicas.
   - inbound-augury-*.json: Credencial de Google Cloud para acceso a Google Sheets.
   - (Se generarán automáticamente archivos CSV y PDF según respuestas del usuario).

2. 📦 REQUISITOS:
   Instalar los siguientes paquetes:
   pip install streamlit gspread oauth2client fpdf twilio

3. 🔐 CONFIGURACIÓN GOOGLE SHEETS:
   - Compartir tu hoja con: streamlit-sheets-mbi360@inbound-augury-...iam.gserviceaccount.com (Editor).
   - Cambia el nombre de tu Google Sheet a: MBI360_Respuestas

4. 🧪 FUNCIONALIDADES:
   - Guarda las respuestas del usuario en Google Sheets.
   - Genera archivo PDF y CSV de resultados.
   - Envía resumen al WhatsApp del administrador +56967010107.
   - Deja botones para:
     • Ver Google Sheets directo
     • Descargar PDF
     • Descargar CSV
     • Confirmar mensaje enviado

5. 🚀 USO EN STREAMLIT:
   Ejecutar localmente:
   streamlit run app.py

   O subir a Streamlit Cloud con el archivo .json de credenciales y todos los .py.

--------------------------------------
CONTACTO
Aníbal Saavedra – Biotecnólogo MBI
WhatsApp: +56 9 6701 0107
--------------------------------------
