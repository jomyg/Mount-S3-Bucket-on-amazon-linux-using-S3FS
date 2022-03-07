# Mount-S3-Bucket-on-amazon-linux-using-S3FS

[![Build](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


## Description

S3FS is FUSE (File System in User Space) based solution to mount an Amazon S3 buckets, We can use system commands with this drive just like as another Hard Disk in the system. On s3fs mounted files systems we can simply use cp, mv and ls the basic Unix commands similar to run on locally attached disks.

## Pre-Requests
- Need to install or configure the aws cli. By default the amazon ec2 have awscli and moslty no need to install
