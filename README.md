The Supply Chain Project is an open source community providing standards and tools for delivering trustworthy products that are authentic, reliable, tamper-free, certified and licensed.

![Supply Chain Project Overview](SupplyChainProjectOverview.png)

_Job to be Done: As a participant in a supply chain, I can produce and consume trustworthy products._

## Supply Chain

A supply chain is a sequence of links in which _producers_ provide items (_artifacts_), and information (_bills of materials_) to _consumers_ who then receive and _verify_.

![Supply Chain Project Concepts](SupplyChainProjectConcepts.png)

## Artifacts
Artifacts are the items produced and consumed in a supply chain:

* Physical goods including hardware and devices.
* Digital goods including software, firmware and cloud-based services.
* Documents attesting to the reliability, integrity, authenticity, security, license and other attributes of artifacts.

## Bills of Materials
Bills of Materials provide information about artifacts that allow artifacts to be received and verified:

* Identity - name, producer, version, and a unique identifier for the artifact.
* Integrity - information that allows verifying that the artifact is free from tampering.
* Relationships - a listing of relationships for the artifact, including contents and dependencies.
* Creation - information about how the artifact was created.
* Assurance - information about how the artifact was assessed and validated.
* License - intellectual property requirements governing use of the artifact.

The Supply Chain Project defines a specification for an artifact Bill of Materials.

## Policy

Policy describes requirements for artifact verification:

* Identity requirements (allowed/disallowed names, producers, versions, unique identifiers)
* Integrity requirements (allowed/disallowed integrity verification models) 
* Relationship requirements (allowed/disallowed artifact content, dependencies, etc.)
* Creation environment requirements (allowed/disallowed creation environments)
* Assurance requiremets (allowed/disallowed certifications)
* License requirements (allowed/disallowed licenses)

The Supply Chain Project defines a specification for defining artifact policy.

## Verification

Consumers receive and verify artifacts. Specifically, they complete the following tasks:

* Request artifacts
* Request bills of materials
* Verify artifacts against policy

The Supply Chain Project defines a specification for requesting artifacts, reqesting bills of materials, and verifying artifacts against policy.
