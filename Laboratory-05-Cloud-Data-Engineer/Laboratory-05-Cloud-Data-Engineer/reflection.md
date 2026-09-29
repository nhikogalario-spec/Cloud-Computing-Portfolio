# Mission Reflection

## Reflection

Object storage is better suited for storing millions of photos because it is designed for large amounts of unstructured data such as images, videos, and backups. Unlike traditional block storage, object storage organizes data as objects with metadata and unique identifiers, making it easier to manage a large collection of files. Object storage can also scale as the number of photos increases.

Docker made it easier to deploy the MinIO storage server because the application can run inside a ready-made container. Instead of manually installing and configuring many dependencies, I only needed to use the Docker command with the required ports and environment variables. This made the deployment faster and more consistent.

A bucket is a logical container used to organize and store objects in object storage. In this activity, the bucket named `client-photos` is used to store the sample files uploaded for the photo-sharing application.

Large enterprise companies can protect object storage data from physical server failures by keeping multiple copies of data and using redundancy across different servers or locations. They can also use backups, replication, versioning, and monitoring to reduce the risk of permanent data loss.

My confidence in navigating the Linux command line is growing because I am becoming more comfortable running Docker commands, checking containers, and working with cloud services from the terminal. At first, the commands looked complicated, but completing each step helped me understand what the commands were doing. This activity also showed me how Linux command-line skills are useful for cloud engineering tasks.
