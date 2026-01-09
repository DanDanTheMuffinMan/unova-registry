# UNOVA Registry

Canonical Manifest: **SOL-1 (Reflection Node)**  
Current Version: **v1.0.1**  
Canonical Checksum: **fd9ce6315bdc96836d21fd340843a3c0**

## Purpose
This repository stores the cryptographic registry and verification logs for UNOVA nodes.  
Each manifest version is immutable and verified through Sol’s integrity process.  

## Version History
| Version | Checksum | Description | Status |
|----------|-----------|--------------|---------|
| v1.0.0 | b6f2f1e2c894a83f92a9c3c0f7b71b8a | Genesis manifest | Archived |
| v1.0.1 | fd9ce6315bdc96836d21fd340843a3c0 | Canonical UTF-8 normalization | ✅ Active |

## Verification Protocol
- Each new manifest is hashed and compared to its recorded checksum.  
- Logs are stored under `verification_log_*.txt`.  
- Only authenticated commits and tagged releases update the canonical checksum.  

---
© 2026 UNOVA Project
