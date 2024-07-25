Integrantes: Mauro Kein, Nicolás Rodrigo Citro, Félix Oyuela, Ramiro Aguirre.

La ejecución de la aplicación debe ser hecha de la siguiente manera:
Primero, instalar requerimientos. Para ello, situarse en la carpeta de la aplicación en la terminal y ejecutar el siguiente comando: pip install -r requiriments.txt (se recomienda hacerlo en un entorno virtual).
Luego, situado en la misma carpeta en la terminal, ejecutar el siguiente comando: python manage.py runserver (es necesario tener python instalado y actualizado en la version 3.12.2).

Informacion de APIS:

Librerías utilizadas:

Consideraciones especiales:
En caso de que no le funcionen "pip install -r requiriments.txt" puede instalar los de forma manual con los siguientes comandos de ayuda para la instalacion utilizando "gitbash": 

git init
python -m venv venv
source venv\Scripts\activate

pip install django
django-admin --version
pip install django-ckeditor
pip install Pillow

git clone https://github.com/NicolasRodrigoCitro/Ingenieria-de-software-2-proyecto-truequetools.git