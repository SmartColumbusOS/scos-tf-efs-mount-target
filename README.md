# scos-tf-efs-mount-target
Terraform module for EFS mount target

Used in conjunction with [scos-tf-efs](https://github.com/SmartColumbusOS/scos-tf-efs)
to access, create, delete and mount an [elastic file system target](https://docs.aws.amazon.com/efs/latest/ug/manage-fs-access-create-delete-mount-targets.html).

Currently this is used by the SmartColumbusOS to solely to set up storage for Jenkins.