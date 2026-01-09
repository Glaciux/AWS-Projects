<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Host a Website on Amazon S3

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-host-a-website-on-s3)

**Author:** Etim Iniekung  
**Email:** etiminiekung@gmail.com

---

![Image](http://learn.nextwork.org/positive_olive_zany_sheep/uploads/aws-host-a-website-on-s3_5d4474f9)

---

## Introducing Today's Project!

### Project overview

In this project, I will demonstrate how to host a Website on Amazon S3 this project to learn about AW SS3 buckets

### Tools and concepts

Services I used were S3 bucket, and the key concepts I learnt include versioning, ACLs, and bucket policies

### Time, challenges, and wins

This project took me approximately 30 minutes.  It was most rewarding to do it myself and understand each step.

---

## How I Set Up an S3 Bucket

### What I did in this step

In this step, I will open Amazon S3 because I want to create a storage space for my website files

### How long it took to create the bucket

Creating an S3 bucket took me around 3 minutes

### Region selection

The Region I picked for my S3 bucket was us-east-2 because it's closest to me.

### Understanding bucket name uniqueness

S3 bucket names are globally unique! This means that names can't be repeated and must be different

![Image](http://learn.nextwork.org/positive_olive_zany_sheep/uploads/aws-host-a-website-on-s3_ba6d42ad)

---

## Upload Website Files to S3

### What I did in this step

In this step, I will download an HTML file that sets up my website as well as a zip file of images because I need to upload them to my S3 bucket to host my website.

### Files I uploaded

I uploaded two files to my S3 bucket - they were index.html and the zip folder

### How the files work together

Both files are necessary for this project because the zip file contains the images used in the index.html file (code).

![Image](http://learn.nextwork.org/positive_olive_zany_sheep/uploads/aws-host-a-website-on-s3_a265af88)

---

## Static Website Hosting on S3

### What I did in this step

In this step, I will configure your S3 bucket for static website hosting because I have to visit my website.

### Understanding website hosting

Website hosting is what makes your website accessible to the public on the internet.

### How I enabled website hosting

To enable website hosting with my S3 bucket, I selected my created bucket, properties, static website hosting, and host a static website.

### Access Control Lists (ACLs)

An ACL is a set of rules that decides who gets access to buckets

![Image](http://learn.nextwork.org/positive_olive_zany_sheep/uploads/aws-host-a-website-on-s3_c22c54c0)

---

## Bucket Endpoints

### Understanding bucket endpoint URLs

Once static website is enabled, S3 produces a bucket endpoint URL, which is used to visit the static website created.

### What I saw when I tested the endpoint

When I first visited the bucket endpoint URL, I saw a 404 error message. The reason for this error was to indicate that the uploaded files were still private and inaccessible.

![Image](http://learn.nextwork.org/positive_olive_zany_sheep/uploads/aws-host-a-website-on-s3_22ce4daf)

---

## Success!

### What I did in this step

In this step, I will make my website files accessible because I need my website to be live 

### How I resolved the 403 error

To resolve this 403 Forbidden error, I enabled "make public using ACL."

![Image](http://learn.nextwork.org/positive_olive_zany_sheep/uploads/aws-host-a-website-on-s3_5d4474f9)

---

## Bucket Policies

### What I did in this extension

In this project extension, I'm about to use bucket policies. I'm doing this so that I can control access to the index.html file.

### Understanding bucket policies

An alternative to ACLs is bucket policies, which are better suited for enhanced security. The benefit of using bucket policies is that they control who edits files, while ACLs are useful to give anyone access to files.

![Image](http://learn.nextwork.org/positive_olive_zany_sheep/uploads/aws-host-a-website-on-s3_sm2sm2sm)

### What my bucket policy does

My bucket policy gives advanced file permissions. I tested this by trying to delete the index.html file and saw a "failed to delete object" error message.

---

---
