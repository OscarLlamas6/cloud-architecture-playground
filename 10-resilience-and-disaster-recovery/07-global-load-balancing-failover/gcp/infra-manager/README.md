# Infrastructure Manager: Global load balancing failover on GCP

**Status:** ⬜

Infrastructure Manager is Google's managed service that runs Terraform. Deployment Manager,
its predecessor, is discontinued. The configuration here is Terraform HCL deployed through
Infrastructure Manager instead of a local `terraform apply`.

## Expected layout
main.tf, variables.tf, outputs.tf, plus the Cloud Storage or Git source used by the deployment

## Prerequisites
TODO: enable the Infrastructure Manager API, service account and its roles, state bucket

## Deploy
    gcloud infra-manager deployments apply TODO --location TODO --service-account TODO --local-source .

## Destroy
    gcloud infra-manager deployments delete TODO --location TODO

## Resources created
TODO

## What differs from the plain terraform/ folder
TODO: managed state, service account execution, previews, deployment revisions

## Notes / learnings
TODO
