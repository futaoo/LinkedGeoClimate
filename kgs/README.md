
# readme

# KGs Implementations

## Primer

The triple store implemented in the paper is based on the [Apache Jena Fuseki.](https://jena.apache.org/documentation/fuseki2/) We added configurations in the Fuseki triple store to enable OGC’s [GeoSPARQL](https://opengeospatial.github.io/ogc-geosparql/geosparql11/spec.html) semantics and correlated subqueries (by availing of its [service enhancer](https://jena.apache.org/documentation/query/service_enhancer.html#programmatic-setup)). The triple store is the key to SPARQL federation over Linked Data. The correlated queries and GeoSPARQL contribute greatly to the complex geospatial queries in SPARQL.

## Open to use

The configured Fuseki triple store can be retrieved from [here](https://drive.google.com/drive/folders/135cKwxmmQgXKGaXOMLCr8y42nYUJXxn3?usp=sharing).
