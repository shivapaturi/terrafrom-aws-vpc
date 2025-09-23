# VPC Module
This module is developed by joindevops company. Projects inside joindevops follows this module to create this VPC.

## Inputs
* project (required) - users should specify their project name
* environment (required) - users should specify their environment name
* cicr_block (optional) - users can provide their CICR block. Default is 10.0.0.0/16

## Outputs
* vpc_id - Exports VPC ID created
* sg_id - Exports SG ID created