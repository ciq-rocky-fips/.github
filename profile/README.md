# CIQ FIPS for Rocky Linux

Welcome to the official GitHub repository for CIQ's FIPS (Federal Information Processing Standards) offering for Rocky Linux. Our mission is to meet the stringent security requirements of federal customers and beyond, ensuring the highest level of data protection and compliance.

## CIQ's FIPS Offering

CIQ has developed a robust FIPS solution on the x86_64 architecture for Rocky Linux, focusing on hardening critical security modules including:

- **Libgcrypt**
- **OpenSSL**
- **NSS (Network Security Services)**
- **GnuTLS**
- **Kernel**

These modules have been built from the ground up to meet the latest FIPS 140-3 standard and are released as updates to subscribed customers via Mountain.

## Independent Validation

Our FIPS modules undergo independent validation by the National Institute of Standards and Technology's Cryptographic Module Validation Program (NIST's CMVP), ensuring they adhere to the most rigorous security standards.

## Supported Versions and Lifecycle

Following the release timelines of Rocky Linux, CIQ offers extended support and updates for FIPS modules, aligning with our Long Term Support (LTS) offering. This ensures that even after a Rocky Linux version is declared EOL, your systems remain secure and compliant.

## FIPS / LTS Product Access

Access to repositories for FIPS and LTS updates is provided via Mountain, offering:

- **LTS Updates:** Containing Rocky 8.x & Rocky 9.x updates following our Security Vulnerability Policy.
- **FIPS Validated:** Modules validated by CMVP.
- **FIPS Compliant:** Security updates to FIPS modules post-validation.

## Security Vulnerability Policy

CIQ commits to the highest standards of security:

- **Backports for Critical or Important Issues:** Focusing on packages with a CVSS score of 8.0 or higher.
- **Discretionary Backports:** For packages with lower CVSS scores, based on CIQ's discretion.
- **Re-validation:** Updates impacting the FIPS modules' entropy functionality or algorithm integrity may be evaluated for CMVP re-validation.

## FIPS Modules & Versions

CIQ maintains a comprehensive list of FIPS modules and versions for both Rocky Linux 8 and Rocky Linux 9, ensuring your systems are equipped with the most secure and up-to-date components.

