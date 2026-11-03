# Security Policy

## Supported Versions

| Version | Supported | Security Maintenance |
| :--- | :--- | :--- |
| Default Branch (main) | Yes | Active maintenance |

---

## Vulnerability Disclosure Protocol

If you identify a security issue, credential exposure, or container configuration vulnerability in this repository, please report it via private email:

* **Security Contact**: goharrehmanfsd260@gmail.com
* **Repository Maintainer**: Gohar Rehman (@itsgoharrehman)
* **Response SLA**: Acknowledgment within 48 hours; resolution plan within 5 business days.

---

## Capstone Security Invariants

1. **Zero Hardcoded Secrets**: MongoDB connection strings, Django `SECRET_KEY` values, and database passwords must strictly be sourced from environment variables.
2. **Container Security**: The production Dockerfile must run under an unprivileged user where applicable and exclude unnecessary build dependencies.
3. **Academic Scope**: This repository represents academic capstone coursework and is not intended for mission-critical production environments without further hardening.
