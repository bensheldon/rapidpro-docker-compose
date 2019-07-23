# rapidpro-docker-compose

A functional [RapidPro](https://rapidpro.github.io/rapidpro/docs/components/) instance, including:

- RapidPro
- Celery job workers
- Mailroom
- Courier
- rp-indexer and rp-archiver

To deploy, copy `sample.env` to `.env`, edit it for correct values and then run `docker-compose up`

To test with ngrok/serveo.net, put the public domain as your RAPIDPRO_HOST environment in .env


