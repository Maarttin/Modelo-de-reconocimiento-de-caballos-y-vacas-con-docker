El archivo del modelo entrenado lo puedes descargarlo aquí: 
https://drive.google.com/file/d/1ybl-OZb_6dQgntjL--ikAYYmBSucmClT/view?usp=sharing
el archivo debe colocarce dentro de la carpeta app junto con el main

debe seguir los pasos:
# Docker build -t ufast .
# Docker compose up -d
# Docker exec -t ufast bash
# apt-get update
# apt install python3.12-venv
# python3 -m venv /venvfast
# python3 -m venv venvfast
# uvicorn main:app --host 0.0.0.0 --port 8000
# pip install pillow python-multipart
