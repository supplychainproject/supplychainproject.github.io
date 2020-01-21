The Supply Chain Project is an open source community providing standards and tools for delivering trustworthy products - products that are authentic, reliable, tamper-free, certified and licensed.

![Supply Chain Project Overview](SupplyChainProjectOverview.png)

_Job to be Done: As a participant in a supply chain, I can produce and consume trustworthy products._

### Supply Chain

A supply chain is a sequence of links in which _producers_ provide items (_artifacts_) and information (_bills of materials_) to _consumers_. Artifact repositories, policies and clients assist with transfer, receipt and verification.

![Supply Chain Project Concepts](SupplyChainProjectConcepts.png)

### Artifacts
Artifacts are items produced and consumed in a supply chain. Artifacts include the following:

* Physical goods including hardware and devices.
* Digital goods including software, firmware and cloud-based services.
* Documents attesting to the reliability, integrity, authenticity, security, license and other attributes of artifacts.

### Bills of Materials
Bills of materials provide information about artifacts that allow artifacts to be verified. Bills of materials include the following information:

* Identity - name, producer, version, and a unique identifier for an artifact.
* Integrity - information that allows verifying that an artifact is free from tampering.
* Relationships - a listing of relationships for an artifact, including contents and dependencies.
* Creation - information about how an artifact was created.
* Assurance - information about how an artifact was assessed and validated.
* License - intellectual property requirements governing use of an artifact.

The Supply Chain Project defines a specification for an artifact bill of materials.

### Repositories
Repositories allow requesting and receiving artifacts and bills of materials.

The Supply Chain Project defines a specification for repositories to respond to requests for artifacts and bills of materials.

### Policy

Policy describes requirements for artifact verification. Policy describes the following:

* Identity - allowed/disallowed names, producers, versions, unique identifiers.
* Integrity - allowed/disallowed models for verifying that an artifact is free from tampering.
* Relationship - allowed/disallowed artifact content, dependencies, etc.
* Creation - allowed/disallowed creation environments.
* Assurance - allowed/disallowed certifications.
* License - allowed/disallowed licenses.

The Supply Chain Project defines a specification for defining artifact policy.

### Clients

Consumers receive and verify artifacts. Specifically, consumers complete the following tasks:

* Request artifacts
* Request bills of materials
* Verify artifacts against policy

The Supply Chain Project defines a specification for requesting artifacts and bills of materials, and for verifying artifacts against policy.
