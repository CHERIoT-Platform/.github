Welcome to the CHERIoT Platform!
================================

The Capability Hardware Extension to RISC-V for IoT (CHERIoT) platform was originally developed at Microsoft and is now part of an effort spanning multiple companies.
It builds on top of CHERI to provide a solid foundation for secure embedded devices.
CHERI provides referential integrity (pointers cannot be forged), spatial memory safety (pointers carry bounds that cannot be extended), call gates, and so on.

CHERIoT extends this with a complete platform providing deterministic use-after-free protection, a lightweight compartment model, lexically-scoped delegation of objects across compartment calls, and many more benefits.
