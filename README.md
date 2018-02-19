# CleverAnalytics REST API

Visit the [docs on apiary.io](https://cleveranalytics.docs.apiary.io/)

## Contribution

You can easily run the Apiary documentation locally. Use the prepared `docker-compose.yml` file and run

```bash
docker-compose up
```

Then visit [http://127.0.0.1:18080](http://127.0.0.1:18080) with your browser and you are set. 
Changes in the `apiary.apib` file are immediately visible, just refresh your browser window.

Alternatively you can run preview using [aglio](https://github.com/danielgtaylor/aglio):

```bash
npm install aglio
aglio --input apiary.apib --server --theme-template triple
```

## References

* https://github.com/apiaryio/api-blueprint/blob/master/API%20Blueprint%20Specification.md