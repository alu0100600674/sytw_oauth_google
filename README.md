# Autenticación con Google

### Instalar las gemas
Para instalar las gemas, ejecutar el comando:
```
bundle install
```


### Ejecutar en local
Para ejecutar la aplicación en local:
```
rackup
```

Luego, acceder en el navegador a la dirección: `http://localhost:9292`


### Implantación en Heroku
La aplicación se ecuentra en Heroku: [http://oauth-google.herokuapp.com](http://oauth-google.herokuapp.com)


### Mas información
See these links:

* [Strategy to authenticate with Google via OAuth2 in OmniAuth.](https://github.com/zquestz/omniauth-google-oauth2)
* [A gem containing a generic OAuth2 strategy for OmniAuth](https://github.com/intridea/omniauth-oauth2) 

Get your API key at: 

[https://code.google.com/apis/console](https://code.google.com/apis/console/)

Note the *Client ID* and the *Client Secret*.

For more details, read the Google docs: 

[https://developers.google.com/accounts/docs/OAuth2](https://developers.google.com/accounts/docs/OAuth2)
