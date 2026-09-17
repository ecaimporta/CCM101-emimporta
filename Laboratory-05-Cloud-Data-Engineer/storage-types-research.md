# Comparing Cloud Storage Types

Cloud computing uses different storage models depending on the type of data and how an application needs to access it. Block Storage, File Storage, and Object Storage each have their own purpose.

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in separate blocks that a system can read and write individually. | Commonly used for virtual machine disks, databases, and applications that require fast storage access. | AWS EBS |
| File Storage | Organizes information into files and folders using a familiar directory structure. | Useful when users or applications need to access and share the same files through a network. | AWS EFS |
| Object Storage | Stores data as separate objects together with information or metadata about each object. | Suitable for large collections of unstructured content such as images, videos, backups, and uploaded files. | AWS S3 |

## Storage Recommendation

I would choose Object Storage for the client's photo-sharing application. A photo-sharing service may receive a very large number of uploaded images, which are considered unstructured data. Object Storage is designed to handle this type of content at a large scale. Each uploaded photo can be stored as an individual object instead of depending on the normal file and folder structure of a server.
