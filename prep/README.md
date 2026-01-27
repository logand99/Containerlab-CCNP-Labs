# Prep / Validation Labs

This directory contains **basic Containerlab test topologies** used to validate that
container images boot correctly and that Containerlab is functioning as expected.

These labs are intentionally minimal and are **not CCNP study scenarios**.

---

## Purpose

The labs in this folder were used to:

- Verify container images boot successfully
- Confirm basic node connectivity
- Validate Containerlab installation and environment setup
- Perform quick smoke tests before building full labs

---

## Characteristics

- Minimal topology (typically 1–2 nodes)
- No startup configurations
- No protocol configuration
- Focused on container and tooling validation only

---

## Usage

These labs can be deployed like any other Containerlab topology:

```bash
containerlab deploy -t <lab-file>.yml
They are useful as a quick sanity check before running more complex labs in the main labs/ directory.
```

## Notes

If you are looking for CCNP-focused labs, refer to the labs/ directory instead.
