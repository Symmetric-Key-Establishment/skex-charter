### SKEX IETF Working Group Charter

The SKEX (Symmetric Key Establishment) Working Group will work on protocols to assist with the secure deployments of pre-shared keys (PSKs) for use with other protocols (such as IPsec with RFC 8784, TLS 1.3, and MACsec) to attain post-quantum security without the need for implementing specific and complex post-quantum algorithm support in those protocols supporting PSKs. This will specifically include benefitting light weight devices.

Asymmetric cryptography, while widely used, has limitations such as computational overhead and susceptibility to emerging threats like cryptographically relevant quantum computers (CRQC). Symmetric cryptography-based key establishment offers a lightweight and resilient alternative, enabling secure key distribution without reliance on public-key infrastructure (PKI).

SKEX offers a plugin solution that avoids network redesign and support enrollment, security and usability with less complexity compared to adding pure or hybrid post-quantum algorithm support to existing hardware and software.
Scope of Work

### The SKEX WG will:
1. Define protocols for symmetric key establishment and distribution.
2. Standardize integration of symmetric key systems with existing protocols (e.g., RFC 8784 for IPsec, MACsec, and TCP-AO for BGP).
3. Explore extending encryption/authentication methods in other protocols to support SKEX protocols.

### Deliverables
The SKEX WG will produce:
1. Protocols for symmetric key distribution.
2.  A recommendations document on integrating SKEX protocols with existing security protocols.
3. Protocol extensions for integration of SKEX into existing protocols supporting PSK/PPK.
