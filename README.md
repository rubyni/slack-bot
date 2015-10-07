Slack Bot
=========

Robot para Slack con algunas gemas útiles para gente de Nicaragua

Este repositorio utiliza [Lita](https://www.lita.io/)

# Requerimientos

**Redis**

Variables de entorno

    SLACK_BOT_KEY
    REDISTOGO_URL

# Ejecutar

    $ bundle
    $ lita start

Este repositorio contiene un archivo Procfile para poder hacer deploy en heroku.

Para definir SLACK_BOT_KEY puedes obtener una llave aquí: https://[tu-cuenta].slack.com/services/new/bot

En heroku para definir REDISTOGO_URL puedes ejecutar este comando:

    heroku addons:create redistogo

Este repositorio ha sido probado en heroku y no ha presentado ningún problema.

# Plugins

* [TUC](https://github.com/rubyni/lita-tuc)
