## oci-storage-add-names "August 2016"

## NAME
oci-storage add-names - Add names to a layer/image/container

## SYNOPSIS
**oci-storage** **add-names** [*options* [...]] *layerOrImageOrContainerNameOrID*

## DESCRIPTION
In addition to IDs, *layers*, *images*, and *containers* can have
human-readable names assigned to them in *oci-storage*.  The *add-names*
command can be used to add one or more names to them.

## OPTIONS
**-n | --name** *name*

Specifies a name to add to the layer, image, or container.  If a specified name
is already used by another layer, image, or container, it is removed from that
other layer, image, or container.

## EXAMPLE
**oci-storage add-names -n my-awesome-container -n my-for-realsies-awesome-container f3be6c6134d0d980936b4c894f1613b69a62b79588fdeda744d0be3693bde8ec**

## SEE ALSO
oci-storage-set-names(1)
