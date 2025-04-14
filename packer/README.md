# VPN Server Image with Packer

To create a machine image for a VPN server.

---

## File Structure

`vpn.pkr.hcl` – Packer configuration file to build the VPN server image.

---

## Prerequisites

- [Packer](https://developer.hashicorp.com/packer/install) installed (v1.7 or later)
- VPN setup scripts (if any)
- Cloud provider credentials (e.g., AWS, Azure, etc.)

---

## Getting Started

### 1. Initialize Packer
```bash
packer init .
```

### 2. Validate the Template
```bash
packer validate vpn.pkr.hcl
```
### 3. Build the VPN Image
```bash
packer build vpn.pkr.hcl
```

