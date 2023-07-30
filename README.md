- [**AWS Cloud Use Cases**](#aws-cloud-use-cases)
- [**AWS Global Infrastructure**](#aws-global-infrastructure)
- [**AWS Regions**](#aws-regions)
- [**How to choose an AWS Region ?**](#how-to-choose-an-aws-region-)


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

<img src="https://github.com/divyanshursahu/AWS-SAA/assets/96013623/3b85f69a-8799-4f0f-986f-36d0ed8537b6" width="80%" height="90%" style="display: block; margin: 0 auto" >

## **AWS Regions**

- AWS has regions all around the world
- Names can be us-east-1, eu-west-3...
- A region is a cluster of data centers
- Most AWS services are region scoped(if you use the same service in two different regions, you will be charged twice)

## **How to choose an AWS Region ?**

If you need to launch a new application, where should you do it?

<img src ="assets/which region to choose.png" width="70%" height="">

- [Compliance]() with data governance and legal requirements: data never leaves a region without your explicit permission
- [Proximity]() to customers: reduced latency
- [Available services]() within a Region: new services
and new features aren’t available in every Region
- [Pricing:]() pricing varies region to region and is transparent in the service pricing page.