## RDF-Connect: An RDF-based framework for streaming and cross-environment data processing pipelines

__Getting started:__ 
* Check out [this publication](https://ceur-ws.org/Vol-3830/paper1.pdf)
* Check a [high-level overview](https://rdf-connect.github.io/)
* Check the [technical specification](https://rdf-connect.github.io/specification/)
* Or jump directly into some examples:
  * the [examples from the Maregraph project](https://github.com/rdf-connect/maregraph-examples) or
  * the [pipelines in the ERA RINF project](https://github.com/rdf-connect/RDF-Connect-RINF-LDES).

__Exisitn Processors:__

 * Incrementally mapping a file using [the RML Mapper processor](https://github.com/rdf-connect/rml-utils-processor-ts)
 * Replicating and synchronizing LDESs using [the LDES client](https://github.com/rdf-connect/ldes-client)
 * Loading data in the [LDES Server](https://github.com/rdf-connect/LDES-Solid-Server)
 * Loading LDES/TREE members [in MongoDB or Redis](https://github.com/rdf-connect/sds-storage-writer-ts)
 * Importing an [LDES into Piveau/Consus](https://github.com/rdf-connect/piveau-consus-importing-ldes), showing how you can use RDF Connect within other frameworks as well
 * Converting an [evolving RDF data dump into an LDES feed](https://github.com/rdf-connect/dumps-to-feed-processor-ts)
 * Importing data [into a triple store using SPARQL](https://github.com/rdf-connect/sparql-ingest-processor-ts)
 * Requesting any kind of data over HTTP using the [HTTP utils processor](https://github.com/rdf-connect/http-utils-processor-ts)
 * _And many more_

Want to start building a processor yourself? Check out the [template-ts-processor repository](https://github.com/rdf-connect/template-processor-ts)!

Currently, we run the workflows using a [JavaScript Runner](https://github.com/rdf-connect/js-runner). This runner can be used on the command line, in a Docker set-up, or in a CI/CD pipeline like Github Actions.
