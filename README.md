## Trove Dataset Constructor

This is a multi-container Docker application which integrates the [TroveProxy](https://github.com/Conal-Tuohy/TroveProxy) and [TroveQueryBuilder](https://github.com/Conal-Tuohy/TroveQueryBuilder) docker images into a single web application
with which users can use a form to specify a Trove API query, preview the results, and harvest the dataset from Trove, converting it into one of various formats. 

To run the docker application:

```bash
docker compose up
```

The application is a web server listening on port 80. If run locally, you can visit it in your browser at `http://localhost/`