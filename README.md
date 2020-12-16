<div style="text-align:center"><img src="https://github.com/agalvezcorell/iron_flask/blob/main/images/cover.jpg?raw=true" /></div>

# Creando una API básica explain Flask en el Bootcamp de Data en Ironahck.
La api tendrá un método POST para introducir datos y un método GET para extraer datos

# ¿Cómo Funciona?

# @POST
Endpoint
- /nueva/frase

De esta manera insertamos una frase en la base de datos.


# @GET
Endpoint
- /frases/<name>

Extraemos todas las frases que tenemos de un usuario en la base de datos

```
url_frases = "http://localhost:5000/frases/"
person = "Albus Dumbledore"
```