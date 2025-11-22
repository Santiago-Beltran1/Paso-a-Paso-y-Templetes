# Guía Completa: Configuración del Proyecto y Conexión a GitHub

Para configurar el entorno, generar requirements, inicializar Git, hacer commit y subir el proyecto a GitHub, ejecuta los siguientes comandos en orden:

- python -m venv venv
- venv\Scripts\activate
- pip freeze > requirements.txt
- git --version
- git config --global user.name "Santiago-Beltran1"
- git config --global user.email "pedrazasantiago837@gmail.com"
- git init
- git config --global --add safe.directory C:\Users\usuario\Paso-a-Paso-y-Templetes
- git add .
- git commit -m "mi primer commit"
- git branch -M main
- git remote add origin https://github.com/Santiago-Beltran1/Paso-a-Paso-y-Templetes.git
- git push -u origin main
