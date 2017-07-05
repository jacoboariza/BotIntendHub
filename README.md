# BotIntendHub - Implementación en Python para integrar servicios con API-AI

This is a really simple webhook implementation that gets Api.ai classification JSON (i.e. a JSON output of Api.ai /query endpoint) and returns a fulfillment response.

Documentación sobre Api.ai webhooks:
[Api.ai Webhook](https://docs.api.ai/docs/webhook)

# Desplegar en:
[![Desplegar en Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

# ¿Qué ofrece este servicio?
Inicialmente se utiliza el servicio de información meteorológica de Yahoo utlizando [Yahoo! Weather API](https://developer.yahoo.com/weather/).

El servicio utiliza el parámetro `geo-city` desde las acciones en API.AI para determinar la ciudad a consultar y devuelve la predicción del tiempo 
