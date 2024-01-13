# AWX custom Execution Environment

This repo builds several costumized Ansible execution environments tailored for special needs.
This repo got forked from the ansible/awx-ee repo.

## Build the image locally

First, [install ansible-builder](https://ansible-builder.readthedocs.io/en/stable/installation/).

Then run the following command from the root of this repo:

```bash
$ ansible-builder build -v3 -t quay.io/ansible/awx-ee # --container-runtime=docker # Is podman by default
```
