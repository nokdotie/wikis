# Production
Nok.ie often contains two environments: production and other. To run the application in the production environment, you must set the `ENV` environment variable.

```sh
ENV=production sbt api/run
```

Beware, the production environment should be kept for production use.
