# FinalTrade-flask-classic
Sitio web de intercambio de Euros y criptomonedas

## Para usar la app web

1. Clonar el repositorio
# con ssh
```
git clone ssh://.....
```
# con https
```
git clone https://.....
```
2. Crear un entorno virtual dentro de la raíz del repositorio
```
cd easyTrade
python3 -m venv env
```
# windows
```
.\env\Scripts\activate
```
# linux / MacOs
```
source ./env/bin/activate
```
3. Instalar las dependencias
```
pip install -r requirements.txt
```
4. copiar el archivo .env_template dentro de la raiz del programa
```
cp .env_template .env
```

5. Configurar las variables de entorno
```
(Estos son los valores por defecto en el repo)
asignarles el valor

FLASK_APP=run
FLASK_ENV=production
FLASK_SECRET_KEY=tu_token_secrto 
(El token secreto lo puedes asiganar con el valor que tu quieras)
```
6. Arrancar la App Web
```
flask run
```

7. Seguri el link que muestra la terminal


