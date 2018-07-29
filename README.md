# CodeMash RFID Utilities

This repo represents a collection of tools, scripts, etc. that we used to support the CodeMash RFID systems for the conference. 

While it comes with no guarantees or comments regarding its suitability, anyone is welcome to use the contents of this repo for whatever purposes they deem appropriate. We are grateful to those who have contributed either directly or indirection via code contributions, publishing OSS libraries, etc.

## Initial Setup

- node 00
  - name: cmroomtest
  - ip: 192.168.2.149
  - raspbian/debian stretch
  - patch status: patched
- node 01
  - name: cm001
  - ip: 192.168.2.233
  - raspbian/debian stretch
  - patch status: patched
- node 02
  - name: cm002
  - ip: 192.168.2.235
  - raspbian/debian stretch
  - patch status: patched
- node 03
  - name: cm003
  - ip: 192.168.2.
  - raspbian/debian stretch
  - patch status: patched

Enabled SSH

copied ssh key to each machine to ease ssh operations

```bash
ssh-copy-id -i ~/.ssh/id_rsa pi@host
```

Configured each machine via the [Digital Signage Instructions](digital-signage/README.md)

