VILLA REAL - LISTO PARA GITHUB Y RENDER

Estructura correcta:
app.py
requirements.txt
render.yaml
VILLAREAL PAGINA.xlsm
templates/index.html
static/css/style.css
static/images/logo-villareal.jpg

En Render:
Build Command: pip install -r requirements.txt
Start Command: gunicorn app:app

Las fotos de los pisos no necesitan estar en GitHub; se leen desde los enlaces de Google Drive guardados en el Excel.
