# Documenting differences between this repo and the Official Hasishcorp

The purpose of this document is to record any differences in this repo compared to the official Hashicorp Terraform vsphere provider.

| Tag | Change |
|-----|--------|
| v.0.0.5 | Increased maxitems per vm for disks to allow for 64 disks per controller. |
| v.0.0.4 | Switch persist_sessions default to true. |
| v.0.0.3 | Add reconfigure_timeout to allow user defined timeouts for long reconfigure operations, such as adding multiple and/or large disks. |
| v.0.0.2 | Added support for 64 disks per scsi controller. |
