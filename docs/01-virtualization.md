## Virtualization Platform

VirtualBox was selected as the virtualization platform.

Reasons:

- Free
- Stable
- Easy to reproduce
- Large community support

VMware was considered but discarded because Broadcom's current download process introduced unnecessary complexity for this project.

## Virtual Machine Resources

The Wazuh Manager virtual machine was configured with:

- 2 vCPUs
- 2 GB RAM
- 40 GB dynamically allocated virtual disk

These values were selected to balance laboratory performance while considering the host's hardware limitations (8 GB RAM).