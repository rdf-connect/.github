# An RDF-based framework for connecting data processors in a pipeline

## Getting started

Check out the [examples from the Maregraph project](https://github.com/rdf-connect/maregraph-examples) or the [pipelines in the ERA RINF project](https://github.com/julianrojas87/CA-RINF-LDES)

## Processors and scenarios

 * Incrementally mapping a file using [the RML Mapper processor](https://github.com/julianrojas87/rml-mapper-processor-ts)
 * Replicating and synchronizing LDESs using [the LDES client](https://github.com/rdf-connect/ldes-client)
 * Loading data in the [LDES Solid Server](https://github.com/rdf-connect/LDES-Solid-Server)
 * Loading data [in MongoDB](https://github.com/rdf-connect/sds-storage-writer-mongo)

Coming soon:
 * Loading an LDES into Piveau/Consus
 * SHACL validating data in a pipeline
 * Requesting data over HTTP, creating an RML Logical View, mapping the data
 * Loading an LDES into Grafana
 * Using one of the VSDS/LDIO processors into a pipeline
 * An RDF data dump to an incremental feed

Currently, we run the workflows using a [JavaScript Runner](https://github.com/rdf-connect/js-runner). This runner can be used on the command line, in a Docker set-up, or in a CI/CD pipeline like Github Actions.
