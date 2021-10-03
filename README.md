# Terraform module of  AWS - S3 Bucket for Datalake Replication (versioning and encryption) - Just for learn purpose!!!

All terraform modules from my repositories is only for learn purpose, so it can be broken, incomplete or not working well!

So if you use that code be careful and you will be at your own!!! Good lucky!!!

Terraform doc: https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket

# What is an S3 Bucket and your relation to Public Access Block?
Amazon Simple Storage Service (Amazon S3) is storage for the Internet. It is designed to make web-scale computing easier.

Amazon S3 has a simple web services interface that you can use to store and retrieve any amount of data, at any time, from anywhere on the web. It gives any developer access to the same highly scalable, reliable, fast, and inexpensive data storage infrastructure that Amazon uses to run its own global network of web sites. The service aims to maximize benefits of scale and to pass those benefits on to developers.

Source of information: https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html

# And about the Datalake?
For Data Lakes I recommend that it has versioning (in Amazon S3 is a means of keeping multiple variants of an object in the same bucket) ,encription (ou can set the default encryption behavior for an S3 bucket so that all new objects are encrypted when they are stored in the bucket. The objects are encrypted using server-side encryption with either Amazon S3-managed keys (SSE-S3) or AWS KMS keys stored in AWS Key Management Service (AWS KMS) (SSE-KMS)) and replication (is an elastic, fully managed, low cost feature that replicates objects between buckets. S3 Replication offers the most flexibility and functionality in cloud storage, giving you the controls you need to meet your data sovereignty and other business needs).

Source of information:
* https://docs.aws.amazon.com/AmazonS3/latest/userguide/Versioning.html
* https://docs.aws.amazon.com/AmazonS3/latest/userguide/bucket-encryption.html
* https://aws.amazon.com/s3/features/replication/?nc1=h_ls


# Motivation
I wrote a lot of codes using terraform modules and for each individual project I had to replicated the modules.

Therefore as terraform accept to work with remote repositories I decided to use github as my source of terraform modules.

# About the project
This project just store the common git files (license and readme.md) and terraform files (main, var and output).