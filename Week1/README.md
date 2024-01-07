# Week 1 Challenge: Static website hosting on AWS, Azure or GCP and implement CICD 🚀

This week's challenge will explore critical concepts and services related to cloud storage, content delivery, and DNS management 🔍 We will also implement CICD for automated changes to your website.

## Technologies Covered 📚 ( Use either of the below options)
- **AWS**: Amazon S3, CloudFront, and Route 53
- **Azure**: Azure Storage, Azure CDN, and DNS Management
- **Google Cloud**: Cloud Storage, Load Balancing, and Content Delivery Networks (CDN)

## Get Started 🚀
- Review the challenge requirements. ✔️
- Dive into AWS, Azure, or GCP documentation to get familiar with the services mentioned. 📖
- Start building your architecture diagram. 🏗️
- Document your progress in a blog or GitHub Readme. 📝

## Deliverables 📦

In this challenge, you are expected to produce the following deliverables:

### 1. Architecture Diagram 🏗️
![Day4 Diagram](https://github.com/abinshihab/10weeksofcloudops/assets/22618390/e9404ad1-2bd8-40e8-b506-7dff949d8ea9)


### 2. Blog or GitHub Readme 📄

Here's a suggested outline for your documentation:

- **Introduction**: I
- We will be using Amazon S3 to store our static website content, CloudFront as our CDN to improve the website's performance, ACM to manage SSL/TLS certificates, CodePipeline for CICD pipeline automation, and Namecheap for DNS management.
- ### Step 1 — Setup the bucket and make it static website.
![Create S3 click create button](https://github.com/abinshihab/100DaysofCloud/assets/22618390/ec550213-ffbe-4d48-ae79-5dd0b1854c87)
<img width="950" alt="image" src="https://github.com/abinshihab/100DaysofCloud/assets/22618390/f2e91302-a9ab-4120-9712-42e3523a3e54">


### Step 2 — Create AWS cloudfront

![create cloud front distrubtion 1 ](https://github.com/abinshihab/100DaysofCloud/assets/22618390/4e30b7a0-c356-44e6-8ef9-b14f82c6094d)

![create cloud front distrubtion 2 ](https://github.com/abinshihab/100DaysofCloud/assets/22618390/50abe006-fa37-4876-b958-aa1e5602117d)
![Request a certificate0](https://github.com/abinshihab/100DaysofCloud/assets/22618390/c841b2c0-29bb-451b-a4d2-d6996004336a)

### setup 3 - Create HTTPS certificate
![Request a certificate 1](https://github.com/abinshihab/100DaysofCloud/assets/22618390/d4bcd4ba-fc79-4839-9a68-c3999864778a)
![Request a certificate final](https://github.com/abinshihab/100DaysofCloud/assets/22618390/88c42879-99a1-43ba-a9b6-cf02a1f68b12)

### setup 4 - Finalize the setup of CloudFront creation

![create cloud front distrubtion enable Web Application Firewall  ](https://github.com/abinshihab/100DaysofCloud/assets/22618390/300c0d47-fb15-4702-8e2b-40d254500a10)

![create cloud front distrubtion final step ](https://github.com/abinshihab/100DaysofCloud/assets/22618390/4730265b-72ab-4bcc-b604-33483c3289f6)




- **Challenges Faced**: Discuss any challenges you encountered and how you overcame them. 🤔
- **Key Takeaways**: Share your key learnings from this week's challenge. 🧐
- **Resources**: List any helpful resources or references you used. 📚
for more information you can see the youtube video I followed up 
https://www.youtube.com/watch?v=UVvc_RtOoWg&list=PLl4APkPHzsUUc8HOEIwfB3Z2uxRv2SKOG&index=3



### Reference resources: ✅
💡 If you are an absolute beginner to the cloud and CICD, get yourself. Familiarize with the concepts, you can refer to the below documentation and study material:

**For AWS**
https://docs.aws.amazon.com/AmazonS3/latest/userguide/HostingWebsiteOnS3Setup.html
https://docs.aws.amazon.com/AmazonS3/latest/userguide/website-hosting-cloudfront-walkthrough.html

**For Azure**

https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website-how-to?tabs=azure-portal
https://learn.microsoft.com/en-us/azure/storage/blobs/storage-custom-domain-name?tabs=azure-portal

**For GCP**
https://cloud.google.com/storage/docs/hosting-static-website
https://www.cloudskillsboost.google/focuses/1251?parent=catalog

We encourage you to ask questions, seek help from the community by posting your queries/question in the help channel after joining our Discord community

## 🔗 Join our community 👇


<a href="https://discord.com/invite/FMtJ2bVRUE"><img src="https://img.icons8.com/color/2x/discord--v2.png" height="60px"></img></a>
<a href="https://github.com/TheCloudOpsCommunity"><img src="https://user-images.githubusercontent.com/91791257/235086411-9ec7aa5e-c095-44ce-b9e6-57b3bc3fead2.png" height="60px"></img></a>
<a href="https://twitter.com/thecloudopscomm"><img src="https://i.postimg.cc/pVqVTNJd/X-logo.png" height="60px"></img></a>
<a href="https://www.linkedin.com/company/thecloudopscomm/"><img src="https://img.icons8.com/fluency/2x/linkedin.png" height="60px"></img></a>
<a href="https://www.instagram.com/techtutorialswithpiyush/"><img src="https://user-images.githubusercontent.com/91791257/235086447-47658b7b-71fa-4baf-830a-3ba9b3a76a47.png" height="60px"></img></a>



Have fun and learn during this Week 1 Challenge! 🤗

Good luck, and happy cloud computing! 🌟
