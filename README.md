# Supply Chain Project 
The Supply Chain Project is an open source community providing standards and tools for managing products and services across supply chains. The goal is to allow supply chain participants in a supply chain to produce and consume quality (timely, reliable, tamper-free, authentic, secure, certified and licensed) products and services.

![Supply Chain Project Overview](images/SupplyChainProjectOverview.png)

# Concepts

## Supply Chain

A supply chain is a sequence of links in which producers provide artifacts and metadata to consumers.

![Supply Chain Project Concepts](images/SupplyChainProjectConcepts.png)

## Artifacts and Metadata
Artifacts are items passed from producers to consumers along the supply chain. Examples include the following:

* Digital goods, e.g. software
* Physical goods, e.g. hardware and devices
* Certifications, e.g. documents attesting to attributes (reliability, integrity, authenticity, security, license, etc.) of a product or service.

Metadata is information about artifacts that allows artifacts to be verified and managed.

* Identity - a name, producer, version, and unique identifier for an artifact.
* Authenticity - a cryptographic signature for the producer of an artifact.
* Materials - a listing of other artifacts used in the creation of an artifact.
* Creation - information about the process followed for creating an artifact.
* License - information that identifies how an artifact can be used.
* Integrity - information that allows verifying that a received artifact is free from tampering during transmission.

The Supply Chain Quality project defines a specification for the exchange of artifacts and metadata between producers and consumers.

## Artifact and Metadata Stores

Artifact and metadata stores allow query and distribution of artifacts. Examples of artifact and metadata stores include the following:

*   Source code repositories
*   Application, container, package and artifact stores, registries and repositories
*   Software metadata providers (e.g.[Software Heritage metadata](https://www.softwareheritage.org/2019/05/28/mining-software-metadata-for-80-m-projects-and-even-more/), [Clearly Defined](https://clearlydefined.io/), [Go checksum database](https://go.googlesource.com/proposal/+/master/design/25530-sumdb.md))
*   Installed package databases (e.g. RPMDB)

The Supply Chain Project provides a certification program for artifact and metadata stores implementing the Supply Chain Quality artifact and metadata exchange specifications.

## Policy

Policy describes requirements for artifact consumption, including the following:

*   Allowed producers
*   Allowed licenses
*   Allowed build environments and configurations
*   Required security steps (e.g. scanning)
*   Required certifications (e.g. SDL, industry audits)
*   Expected order of steps in the chain (e.g. to prevent man in the middle attacks)


## Artifact Clients

Artifact clients query metadata stores to receive and process metadata. They may also obtain and inspect artifacts and enforce policy.

Artifact clients query metadata stores to receive information such as the following:

*   Lists of artifacts available
*   Lists of artifacts containing specific metadata values
*   Metadata values across multiple artifacts
*   Metadata values for specific artifacts

 Artifact clients handle policy verification and enforcement including the following:

*   Signature verification
*   Artifact hash verification
*   License verification
*   Build/build environment verification (e.g. reproducible build)
*   Required steps verification
*   Required certification verification
