## STORAGE : 
There are two storage system in AWS ,

**Block Storage :** 

- Block storage is very efficient and high performance storage system in AWS .It can be accessed only by instances in AWS

- Once a value is changed in block storage it will overwrite the part of storage which is changed. 
*Highly useful in intensive task oriented usage like database storage root file system .*

**Object Storage** : 

- Object storage stores data in format of objects and accessed via api's through internet .

- It is highly scalable and with high data redundancy for data.

- Data inside object storage is completely over written once values are changed.It can be useful for data archiving and backups . 
	*Can be useful in storing data like text image and plain files*

### EBS(ELASTIC BLOCK STORAGE) : 

- Amazon EBS is a block storage service designed for use with Amazon EC2 instances. It provides persistent storage that can be easily attached to running instances.

- It is configured as AWS block storage and it can be used for AWS ec2 instances volumes and volume snapshots.

### S3(SIMPLE STORAGE SERVICE) : 

- Amazon S3 is an object storage service that provides scalable, high-speed storage for a wide range of data types.

It can be ideal for 
- Backup and archival of data.
- Hosting static websites and content distribution.
- Data lakes for big data analytics.
- Application data storage for web applications.

S3 can be divided further based on optimization of storage and usage of data by user .
S3 glacier is ideal for storing data which is achived and be accessed only after a long period of time 

| **Storage Class**      | **Use Case**                          | **Durability** | **Access Frequency**   |
| ---------------------- | ------------------------------------- | -------------- | ---------------------- |
| S3 Standard            | Frequently accessed data              | 99.999999999%  | Frequent               |
| S3 Intelligent-Tiering | Unpredictable access patterns         | 99.999999999%  | Varies                 |
| S3 Standard-IA         | Infrequently accessed data            | 99.999999999%  | Infrequent             |
| S3 One Zone-IA         | Infrequent data without AZ redundancy | 99.999999999%  | (single AZ)	Infrequent |
| S3 Glacier             | Long-term archival                    | 99.999999999%  | Rarely                 |
| S3 Glacier DeepArchive | Lowest-cost long-term archival        | 99.999999999%  | Very Rare              |
| S3 Outposts            | Local data storage with Outposts      | 99.999999999%  | Varies                 |


