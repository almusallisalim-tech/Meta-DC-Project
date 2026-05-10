# Meta Data Center Lab Project

**Engineer:** Salim | **Date:** May 2026 | **Platform:** Ubuntu 22.04 on Android (UserLAnd)

## Objective
Provision and harden a Linux server to Meta's 'Secure by Default' standard, demonstrating core Data Center Technician skills.

## Day 1: Baseline & Patching
- Performed full system update: 53 packages upgraded
- Documented compliance in `Day1-Baseline-v2.md`
- Skills: `apt`, `Vulnerability Management`, `Audit Documentation`

## Day 2: IAM & SSH Hardening  
- Created dedicated admin user `meta-tech` with verified `sudo` escalation
- Hardened SSH: `PermitRootLogin no` - blocks #1 brute-force vector
- Performed RCA on `policy-rc.d denied` container limitations
- Skills: `Identity & Access Management`, `RBAC`, `Attack Surface Reduction`, `Root Cause Analysis`

## Day 3: GitOps Implementation
- Initialized Git repository and version controlled all artifacts
- Authored professional documentation for audit trail
- Skills: `Git`, `Version Control`, `Technical Writing`

## Key Takeaway
This lab proves ability to secure, troubleshoot, and document Linux systems to production standards used at Meta's 200k+ host fleet.

**Status:** Day 3 Complete. Ready for GitHub deployment.
