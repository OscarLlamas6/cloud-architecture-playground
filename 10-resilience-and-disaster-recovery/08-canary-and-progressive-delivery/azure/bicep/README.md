# Bicep: Canary and progressive delivery on Azure

**Status:** ⬜

## Expected layout
main.bicep, modules/, main.bicepparam

## Prerequisites
TODO

## Deploy
    az deployment group create --resource-group TODO --template-file main.bicep --parameters main.bicepparam

(Use `az deployment sub create` when the architecture is subscription or management-group scoped.)

## Destroy
TODO: delete the resource group or the deployment stack

## Resources created
TODO

## Differences versus Terraform and Pulumi
TODO

## Notes / learnings
TODO
