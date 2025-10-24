# Terraform Accelerator

[![CI](https://github.com/mikeshobes718/terraform-accelerator/actions/workflows/ci.yml/badge.svg)](https://github.com/mikeshobes718/terraform-accelerator/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Accelerate Terraform authoring: module/variable generation from canonical inputs; bulk tfvars updater with validation and dry‑run.

## Features
- Generate module and variable scaffolds
- Bulk tfvars update across workspaces with validation
- Dry‑run plans and changeset preview

## Quickstart
```bash
# Coming soon: CLI entrypoint
python -m terraform_accelerator --help
```

## Architecture
- Python + HCL parsing helpers
- Canonical input schema to enforce consistency

## Roadmap
- Module registry sync
- Lint rules for input/output consistency

## License
MIT
