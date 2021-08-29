# Cloud-Computing-Foundation
![Overview of the Specialization](https://user-images.githubusercontent.com/79841341/125635618-6968b461-c5f7-44b3-a9f9-4f622e10509e.png)

![image](https://user-images.githubusercontent.com/79841341/131250280-675f5558-beb5-4247-aa23-cadaae77d420.png)

# Simple Storage Service (S3):
- Object-based storage service
- Serverless storage in the cloud
- Don't worry about file systems or disk space

## Introduction

### S3 object: consists
- Key: name of the object
- Value: data of the object
- Version ID: when versioning enabled, the version of object
- Metadata: addtional info attached to the object

### S3 Bucket:
- Bucket hold objects, buckets can have folders which in turn hole objects
- S3 is a universal namespace so bucket name must be unique.
- 
![image](https://user-images.githubusercontent.com/79841341/131250329-1ef716b9-fc88-46de-ae46-f5eb53395dfc.png)

## Storage Classes:

![image](https://user-images.githubusercontent.com/79841341/131250533-0f164471-fb0d-4871-89aa-f8680ea92aec.png)

![image](https://user-images.githubusercontent.com/79841341/131250574-aa62f02e-5a88-42cc-aa37-b30b446ed578.png)

## Security:
- All new buckets are **PRIVATE** by default
- Access control is configured using Bucket Policies and legacy Access Control Lists (ACL)

![image](https://user-images.githubusercontent.com/79841341/131250680-389fc6be-460b-4d52-b0e5-689785c50043.png)
