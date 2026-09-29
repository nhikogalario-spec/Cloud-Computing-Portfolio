# Storage Types Research

## Comparison of Cloud Storage Types

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in fixed-size blocks that can be accessed individually. | Virtual machines, databases, and operating systems. | AWS EBS |
| File Storage | Stores data as files organized in folders and directories. | Shared files and documents that need access by multiple systems. | AWS EFS |
| Object Storage | Stores data as objects together with metadata and a unique identifier. | Images, videos, backups, and other unstructured data. | AWS S3 |

## Why Object Storage?

Object Storage is a good choice for the client's photo-sharing application because it is designed to store large amounts of unstructured data such as images. It can also scale as the number of uploaded photos grows, making it suitable for millions of user-uploaded files.
