# Checkpoint 5: Technical Documentation (MinIO Deployment)

## Deployment Overview
To deploy an S3-compatible Object Storage server locally, Docker was used to instantiate a MinIO container with custom environment credentials and forwarded ports.

## Technical Details
* **Docker Deployment Command:**
  ```bash
  docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
  -e "MINIO_ROOT_USER=cloudadmin" \
  -e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
  minio/minio server /data --console-address ":9001"
