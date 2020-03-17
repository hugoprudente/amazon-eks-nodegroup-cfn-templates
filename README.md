# Amazon EKS NodeGroup CloudFormation templates

The samples in this repository each demonstrate how to improve the [AWS Official Provided](https://docs.aws.amazon.com/eks/latest/userguide/launch-workers.html) templates.

## AWS Provided

* AWS Official Provided, without modifications.

## Custom

### ALL
* ability to enable and disable `AssociatePublicIpAddress`
* ability to launch EC2 with `on-demand` and `spot`
* ability to control number of `on-demand` vs `spot`

### Amazon Linux 2 (EKS Optimized)
*
### Amazon Linux 2 ARM (EKS Optimized)
*

### Windows 2019 (1809/1809)
* `ssm-parameters` for windows for the two instances types
* added OpenSSH and Chocolatey installation
* added extra taint

### Bottlerocket-OS
* introduce *preview* template on us-west-2

# License
These samples and templates are all licensed under Apache 2.0.