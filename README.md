- [**AWS Cloud Use Cases**](#aws-cloud-use-cases)
- [**AWS Global Infrastructure**](#aws-global-infrastructure)
- [**AWS Regions**](#aws-regions)
- [**How to choose an AWS Region ?**](#how-to-choose-an-aws-region-)
- [**AWS Availability Zones**](#aws-availability-zones)
- [**Tour of the AWS Console**](#tour-of-the-aws-console)


## **AWS Cloud Use Cases**

- AWS enables you to build sophisticated, scalable applications
- Applicable to a diverse set of industries
- Use cases include
  - Enterprise IT, Backup & Storage, Big Data analytics
  - Website hosting, Mobile & Social Apps
  - Gaming
 
## **AWS Global Infrastructure**

- AWS Regions
- AWS Availability Zones
- AWS Data Centers
- AWS Edge Locations/Points of Presence
- https://infrastructure.aws/

![image](https://github.com/divyanshursahu/AWS-SAA/assets/96013623/3b85f69a-8799-4f0f-986f-36d0ed8537b6)

<!-- <img src="https://github.com/divyanshursahu/AWS-SAA/assets/96013623/3b85f69a-8799-4f0f-986f-36d0ed8537b6" width="80%" height="90%" style="display: block; margin: 0 auto" > -->

## **AWS Regions**

- AWS has regions all around the world
- Names can be us-east-1, eu-west-3...
- A region is a cluster of data centers
- Most AWS services are region scoped(if you use the same service in two different regions, you will be charged twice)

## **How to choose an AWS Region ?**

If you need to launch a new application, where should you do it? 

<img src ="assets/which region to choose.png" width="70%" height="" style="display: block; margin: 10 auto">

- [Compliance]() with data governance and legal requirements: data never leaves a region without your explicit permission
- [Proximity]() to customers: reduced latency
- [Available services]() within a Region: new services
and new features aren’t available in every Region
- [Pricing:]() pricing varies region to region and is transparent in the service pricing page.

## **AWS Availability Zones**

- Each region has many availablility zones(usually 3, min is 3, max is 6). Example:
  - ap-southeast-2a
  - ap-southeast-2b
  - ap-southeast-2c

- Each availability zone(AZ is one or more discrete data centers with redundanct power, networking, and connectivity)
- They're separate from each other,so that the're isolated from disasters
- They're connected with high bandwidth, ultra-low latency networking
  
  <img src="assets/Availability zones.png" width="50%" height="" >

## **Tour of the AWS Console**

- #### AWS had Global Services: <img src="assets/aws global service.png" width="2%" height="">
  - Identity and Access Management (IAM)
  - Route 53 (DNS Service)
  - CloudFront (Content Delivery Network)
  - WAF (Web Application Firewall)

- #### Most AWS services are Region-scoped:  <img src="assets/region scoped.png" width="2%" height="">
  - Amazon EC2 (IAAS)
  - Elastic Beanstalk (PAAS)
  - Lambda (Function as a Service)
  - Rekognition (Software as a Service)

- #### Region Table: https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services

