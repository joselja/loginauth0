# Ejemplo de autenticación en Python usando Auth0

Este ejemplo muestra como añadir autenticación a una web python usando Auth0.

# Ejecutar la App

Para ejecutar el ejemplo asegurate de que tienes `python` y `pip` instalado.

Renombra `.env.example` to `.env` y completa los campos client ID, domain, secret, callback URL and audience para tu Auth0 app.
En caso de que no sea una API puedes usar `https://YOUR_DOMAIN.auth0.com/userinfo` como audience.
También añade callback URL a los settings de tu Auth0 client.

Registra `http://localhost:50000/callback` como `Allowed Callback URLs` y `http://localhost:50000` 
como `Allowed Logout URLs` en los setting de tu configuración en la Web de Auth0.

Ejecuta `pip install -r requirements.txt` para instalar las dependencias y ejecutar con `python server.py`. 
La app estará escuchando en [http://localhost:50000/](http://localhost:50000/).



