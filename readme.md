### SKEX IETF Working Group Charter

As networks and data centres scale to tens of thousands of endpoints, the need for efficient and secure symmetric key exchange becomes critical. Many security protocols currently rely on symmetric encryption for data encryption and asymmetric mechanisms for key-exchange. However asymmetric key-exchange mechanisms do not fully address several challenges in these contexts, for example assured resilience against evolving quantum-computer attacks, potential mathematical attacks or have high CPU and memory requirements which is problematic for lightweight IoT devices. 

SKEX is intended to support keying of point-to-point secure protocols such as TLS for VPNs and IPsec that need not fit a client-server model. In general, SKEX protocols should not rely on 'all knowing' central servers that may constitute single-point vulnerabilities. Browser communication and other widespread server-centred communication is not intended to be a typical application of SKEX.

Due to the lack of prior standards, current methods for symmetric key distribution frequently depend on manual provisioning, static pre-shared keys (PSKs), or centralized key management, creating operational bottlenecks and security risks. Dynamic environments, such as large-scale data centres, cloud networks, and service provider infrastructures, routing protocols, control plane authentication, and encrypted transport layers require a scalable, automated, and secure approach to symmetric key establishment and distribution that are not addressed by currently available solutions.

Asymmetric cryptography, though widely adopted, presents challenges such as high computational overhead and vulnerability to emerging threats, including cryptographically relevant quantum computers (CRQC) and as-yet unknown potential vulnerabilities of lattice-based cryptography. Existing symmetric key distribution solutions pose security risks due to their reliance on centralized key storage, which creates a single point of compromise.

In contrast to PKI and PQC, symmetric-cryptography-based key establishment mechanisms don't rely on asymmetric algorithms to provide keys for secure internet communications offering a lightweight and resilient alternative.

The Symmetric Key Establishment and Exchange (SKEX) Working Group (WG) aims to address this challenge by developing standardized mechanisms for secure, automated symmetric key establishment, ensuring that high-speed, high-density networks can maintain strong security without sacrificing efficiency or scalability. SKEX WG will work on protocols to assist with the secure deployments of pre-shared keys (PSKs) for use with other protocols (such as IPsec with RFC 8784, TLS 1.3, MACsec, TCP-AO, etc) to attain post-quantum security without the need for implementing specific and complex post-quantum algorithm support in those protocols supporting PSKs. This has applicability with devices with highly constrained resources.

With the widespread adoption of IP communication for IoT devices, which can be extremely limited in both memory and processing capabilities, support for strong cryptographic solutions that do not involve public-key cryptography is necessary. The use of only symmetric key cryptography is necessary for such lightweight devices.

SKEX offers plugin solutions that support enrollment, security and usability with less implementation and management system complexity compared to PKI-like solutions for TPM-based security, and per-device managed or resource-constrained hardware and software.

### Scope of Work
The SKEX WG will:
1. Define protocols for symmetric key establishment and distribution.
2. Standardize integration of symmetric key systems with existing protocols (e.g., RFC 8784 for IPsec, MACsec, and TCP-AO for BGP).
3. Explore extending encryption/authentication methods in other protocols to support SKEX protocols.

### Deliverables
The SKEX WG will produce:
1. A protocol for Unmediated Symmetric Key Establishment
2. A protocol for Distributed Symmetric Key Establishment (https://datatracker.ietf.org/doc/draft-mwag-dske/)
3. Recommendation documents on integrating SKEX protocols with existing security protocols.
4. Identification of, and suggestions to other WGs for, extensions to protocols to ingest symmetric keys or for integration of SKEX developed protocols into existing protocols that already support PSK as a key source.
