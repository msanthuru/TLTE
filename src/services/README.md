# services/

This directory contains public-safe service modules for the VinMin project
under TLTE C.I.C. These modules typically handle interactions with 
external services or provide simple service abstractions.

Services placed here must be:

- non-sensitive  
- free of internal TLTE logic  
- safe for open-source release  
- simple wrappers or helpers  
- unrelated to identity, authentication, or region-sensitive systems  

Examples that may belong here:

- fetch wrappers  
- public API callers  
- third-party integration helpers  
- safe external service utilities  

Sensitive or internal services (identity systems, verification,
authentication, operational infrastructure, or protected integrations)
must remain private and are **not** placed here.
