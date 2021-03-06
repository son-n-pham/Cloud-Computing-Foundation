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
 
![image](https://user-images.githubusercontent.com/79841341/131250329-1ef716b9-fc88-46de-ae46-f5eb53395dfc.png)

## Storage Classes:

![image](https://user-images.githubusercontent.com/79841341/131250533-0f164471-fb0d-4871-89aa-f8680ea92aec.png)

![image](https://user-images.githubusercontent.com/79841341/131250725-f44a8f97-2de2-4b5b-81ec-82ceb5281e80.png)

## Security:
- All new buckets are **PRIVATE** by default
- Access control is configured using Bucket Policies and legacy Access Control Lists (ACL)

![image](https://user-images.githubusercontent.com/79841341/131250680-389fc6be-460b-4d52-b0e5-689785c50043.png)

## Encryption

![image](https://user-images.githubusercontent.com/79841341/131250742-70e9f968-3770-4e92-be87-a36d2318a236.png)

## Data Consistency

![image](https://user-images.githubusercontent.com/79841341/131250806-cc6d3eae-e37f-406f-b196-bf360f918b37.png)

## Cross Region Replication (CRR)

![image](https://user-images.githubusercontent.com/79841341/131250838-0e8c9a07-4910-42a5-8d59-ff771a3b5bb4.png)

## Versioning

![image](https://user-images.githubusercontent.com/79841341/131250876-598a2275-c2a8-4219-8dbf-9fe3639eb5a0.png)

## Lifecycle Management

![image](https://user-images.githubusercontent.com/79841341/131250930-f49700f3-5ca1-416d-8d2f-56d09724f019.png)

## Transfer Acceleration:

![image](https://user-images.githubusercontent.com/79841341/131250959-c71bffaf-9f3e-4b2d-8355-419d32ff411a.png)

## Presigned Urls
![image](https://user-images.githubusercontent.com/79841341/131251028-e43baefa-1acf-4534-8853-333a235f8298.png)

## MFA Delete

![image](https://user-images.githubusercontent.com/79841341/131251056-821a07d9-88a6-42ce-b344-b8007f313952.png)

## CheatSheet

![image](https://user-images.githubusercontent.com/79841341/131255428-65493aad-6f20-48e7-a6c7-f74ebc4f26e8.png)

![image](https://user-images.githubusercontent.com/79841341/131255461-a069bb69-6950-4754-b6f1-f5b925dff621.png)

![image](https://user-images.githubusercontent.com/79841341/131255498-2339e3d6-0472-414b-8779-bea40b5abd19.png)

# AWS Snowball, Snowball Edge, Snowmobile

- Snowball: Petabyte-scale data transfer service. Move data onto AWS via physical briefcase computer.

![image](https://user-images.githubusercontent.com/79841341/131255574-7672d12b-6ef2-4664-86cb-8d7089e3c999.png)

- Snowball Edge: Similar to Snowball but with more storage and with local processing

- Snowmobile: A 45-foot long ruggedized shipping container, pulled by a semi-trainler truck, transfer up to 100PB per Snowmobile.

![image](https://user-images.githubusercontent.com/79841341/131255775-8dc82cfd-ce2c-4143-bda8-36ff6bfcacc0.png)

# Virtual Private Cloud (VPC)

![image](https://user-images.githubusercontent.com/79841341/131255823-a7596f0a-e1aa-4adf-9891-16c1a6420883.png)

