The Supply Chain Project is an open source community providing standards and tools for producing trustworthy products. The goal is to support the delivery of products that are authentic, reliable, tamper-free, certified and licensed.

![Supply Chain Project Overview](SupplyChainProjectOverview.png)

_Job to be Done: As a participant in a supply chain, I can produce and consume trustworthy products._

## Supply Chain

A supply chain is a sequence of links in which _producers_ provide items (_artifacts_), and information (_bills of materials_) to _consumers_ who then receive and _verify_.

![Supply Chain Project Concepts](SupplyChainProjectConcepts.png)

## Artifacts
Artifacts are items produced and consumed in a supply chain:

* Physical goods including hardware and devices
* Digital goods including software, firmware and cloud-based services
* Certifications attesting to artifact reliability, integrity, authenticity, security and license.

## Bills of Materials
Bills of Materials provide information about artifacts that allows artifacts to be received and verified.

* Identity - the name, producer, version, and unique identifier for the artifact.
* Integrity - information that allows verifying that the artifact is free from tampering.
* Relationships - a listing of relationships including contents and dependencies between this artifact and others.
* Creation - information about how the artifact was created.
* Assurance - information about how the item was assessed and validated.
* License - intellectual property requirements governing use of the artifact.

The Supply Chain Quality project defines a specification for the exchange of artifacts and bills of materials between producers and consumers.

## Policy

Policy describes requirements for artifact consumption, including the following:

*   Allowed producers
*   Allowed licenses
*   Allowed build environments and configurations
*   Required security steps (e.g. scanning)
*   Required certifications (e.g. SDL, industry audits)
*   Expected order of steps in the chain (e.g. to prevent man in the middle attacks)

## Verification

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
