# EBS
WORKING WITH EBS
```
NAME: KISHORE G
REGISTER NO:212225040191
```
AIM:
In this lab environment, access to AWS services and service actions might be restricted to the ones that are needed to complete the lab instructions. You might encounter errors if you attempt to access other services or perform actions beyond the ones that are described in this lab.

OBJECTIVE:
*Create an Amazon EBS volume *Attach and mount your volume to an EC2 instance *Create a snapshot of your volume *Create a new volume from your snapshot *Attach and mount the new volume to your EC2 instance

Illustration:
STEP 1:
In this step, you will create and attach an Amazon EBS volume to a new Amazon EC2 instance.You will see an existing volume that is being used by the Amazon EC2 instance. This volume has a size of 8 GiB, which makes it easy to distinguish from the volume you will create next, which will be 1 GiB in size.
<img width="1873" height="837" alt="Screenshot 2026-08-03 140253" src="https://github.com/user-attachments/assets/bb8ea9c3-15b9-4826-8129-995af9cf5194" />


STEP 2:
In this step, you will connect to the Lab EC2 instance using Session Manager.You can now attach your new volume to the Amazon EC2 instance.
<img width="1031" height="768" alt="Screenshot 2026-08-03 140315" src="https://github.com/user-attachments/assets/44f692b7-bc6f-47bc-9004-47367344a75b" />


STEP 3:
In this step, you will add the new volume to a Linux instance as an ext3 file system under the /mnt/data-store mount point.

<img width="1028" height="821" alt="Screenshot 2026-08-03 140330" src="https://github.com/user-attachments/assets/37d3a3c7-724f-4127-839f-7c7fc991afd3" />


STEP 4:
You can create any number of point-in-time, consistent snapshots from Amazon EBS volumes at any time. Amazon EBS snapshots are stored in Amazon S3 with high durability. New Amazon EBS volumes can be created out of snapshots for cloning or restoring backups. Amazon EBS snapshots can also be easily shared among AWS users or copied over AWS regions.

STEP 5:

<img width="833" height="786" alt="Screenshot 2026-08-03 140404" src="https://github.com/user-attachments/assets/a072d83e-667f-4fab-87e6-40757881f2e0" />
<img width="713" height="510" alt="Screenshot 2026-08-03 140416" src="https://github.com/user-attachments/assets/3a9f2fe4-a6b8-4d9e-b7e6-5f26552e6ca2" />


RESULT:
Successfully created, managed, and deleted an EBS bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon EBS.
