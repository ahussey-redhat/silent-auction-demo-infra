# silent-auction-demo-infra

This repository contains all the artefacts required to deploy the infra supporting the "silent auction" application.

## Setup

If you are deploying this on a new OCP cluster (ROSA/ARO/Bare Metal), you will need to change directory to the `1-bootstrap` directory, and run the setup script.

```bash
cd ./1-bootstrap
./run_playbook.sh
```
