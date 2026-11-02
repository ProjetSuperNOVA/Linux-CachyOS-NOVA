# SuperNOVA Kernel

<div align="center">
  <h1 align="center">SuperNOVA Kernel</h1>
  <p align="center">A custom Linux kernel for the SuperNOVA gaming platform.</p>
  <p align="center">
    <strong>Experimental development branch (NOVA)</strong>
  </p>
</div>

> [!CAUTION]
> **NOT FOR GENERAL USE**
>
> The SuperNOVA Kernel is an experimental, highly specialized Linux kernel project developed exclusively for the SuperNOVA platform.
>
> This repository is not intended for general-purpose Linux distributions, personal computers, servers, or production environments.
>
> The kernel is under active development. Configurations, patches, build processes and hardware requirements may change without notice. Builds may be unstable, incomplete or incompatible with your hardware.
>
> **Do not install or use this kernel on a system you depend on.**

## About

SuperNOVA Kernel is the custom Linux kernel project for **SuperNOVA**, a planned gaming console running SuperNOperating System, a Fedora Atomic-based operating system.

This project builds upon the [CachyOS Linux kernel](https://github.com/CachyOS/linux-cachyos), incorporating selected upstream and downstream improvements alongside SuperNOVA-specific modifications.

Our objectives include:

- Optimizing Linux for dedicated gaming hardware.
- Improving frame-time consistency and system responsiveness.
- Tailoring kernel configuration to SuperNOVA hardware.
- Reducing unnecessary hardware and subsystem support.
- Improving AMD APU and GPU integration.
- Maintaining strong security and system integrity.
- Contributing generally useful improvements back to upstream Linux.

SuperNOVA Kernel is intended to evolve alongside SuperNOperating System and SuperNOVA hardware.

## Development Status

<badge>Experimental</badge>

This project is currently in its early development stages.

- Hardware specifications are not finalized.
- Kernel configuration is subject to change.
- Performance optimizations are experimental.
- SuperNOVA-specific patches are under development.
- Fedora RPM packaging and Atomic integration are planned.
- No production-ready builds are currently guaranteed.

The `NOVA` branch is the primary development branch for SuperNOVA-specific work.

## Scope and Compatibility

SuperNOVA Kernel is developed specifically for the intended SuperNOVA hardware platform.

It is not designed to provide broad compatibility with arbitrary computers or Linux distributions.

Compatibility with other systems is neither guaranteed nor supported.

## Relationship with Upstream Projects

SuperNOVA Kernel builds upon existing open-source projects, including, but not limited to:

- [Linux Kernel](https://github.com/torvalds/linux)
- [CachyOS](https://github.com/CachyOS)

We intend to preserve upstream attribution, respect applicable licenses and contribute generally useful improvements back to their respective projects.

SuperNOVA Kernel is an independent project. It is not an official CachyOS project and is not endorsed by the CachyOS developers.

## Contributions

Contributions are welcome where they align with the project's objectives.

Priority is given to:

- Kernel correctness and reliability.
- AMD hardware support.
- Gaming performance and frame-time consistency.
- Security and system integrity.
- Maintainability and upstream compatibility.

Changes should be accompanied by appropriate documentation, testing and benchmarks where applicable.

## Disclaimer

SuperNOVA Kernel is provided "as is", without warranties of any kind, to the extent permitted by applicable law.

Use of experimental builds is at your own risk.
