The Supply Chain Project is an open source community providing standards and tools for delivering trustworthy products that are authentic, reliable, tamper-free, certified and licensed.

![Supply Chain Project Overview](SupplyChainProjectOverview.png)

_Job to be Done: As a participant in a supply chain, I can produce and consume trustworthy products._

## Supply Chain

A supply chain is a sequence of links in which _producers_ provide _artifacts_, and _bills of materials_ to _consumers_ who receive and _verify_.

![Supply Chain Project Concepts](SupplyChainProjectConcepts.png)

## Artifacts
Artifacts are items produced and consumed in a supply chain. Artifacts include the following:

* Physical goods including hardware and devices.
* Digital goods including software, firmware and cloud-based services.
* Documents attesting to the reliability, integrity, authenticity, security, license and other attributes of artifacts.

## Bills of Materials
Bills of Materials provide information about artifacts that allow artifacts to be received and verified. Bills of Materials include the following information:

* Identity - name, producer, version, and a unique identifier for an artifact.
* Integrity - information that allows verifying that an artifact is free from tampering.
* Relationships - a listing of relationships for an artifact, including contents and dependencies.
* Creation - information about how an artifact was created.
* Assurance - information about how an artifact was assessed and validated.
* License - intellectual property requirements governing use of an artifact.

The Supply Chain Project defines a specification for an artifact Bill of Materials.

## Policy

Policy describes requirements for artifact verification. Policy describes the following:

* Identity - allowed/disallowed names, producers, versions, unique identifiers.
* Integrity - allowed/disallowed integrity verification models.
* Relationship - allowed/disallowed artifact content, dependencies, etc.
* Creation - allowed/disallowed creation environments.
* Assurance - allowed/disallowed certifications.
* License - allowed/disallowed licenses.

The Supply Chain Project defines a specification for defining artifact policy.

## Verification

Consumers receive and verify artifacts. Specifically, consumers complete the following tasks:

* Request artifacts
* Request bills of materials
* Verify artifacts against policy

The Supply Chain Project defines a specification for requesting artifacts, reqesting bills of materials, and verifying artifacts against policy.
