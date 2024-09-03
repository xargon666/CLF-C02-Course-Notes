## Course Summary
- CLF-C02 is gaining much traction, and this course is designed to prepare you for the exam.
	- More enthesis on security and compliance
	- Includes lots of practice, and test questions and access to labs and course materials

**After you pass you will be able to...**
- Explain the value of the AWS Cloud.
- Understand and explain the AWS shared responsibility model.
- Understand security best practices.
- Understand AWS Cloud costs, economics, and billing practices.
- Describe and position the core AWS services, including compute, network, database, and storage services.
- Identify AWS services for common use cases.

The course prepares you for the exam... 

90 minutes, 65 questions, with a a possible 1000 points.

You will get a notification if you passed a few days after you take the exam, and you can retake after 2 weeks. It costs $100 to take the exam. Certification lasts for 3 years.

**Exam breakdown:**
Cloud Concepts - 24%
Security and Compliance - 30%
Cloud Technology & Services 34%
Billing, Pricing & Support - 12%

## Cloud Use Cases
The cloud is used for a lot of things, and offers significant advantages, allowing business to focus on their products/services instead of buying the servers and infrastructure that amazon already provide for cheap. 
#### Advantages
- Instant Scaling
- Cost efficiency
- High Availabilty
- Redundancy
- Fault tolerance
- Security
- Easy to expand services globally
- A shift from capital to variable expenses: you don't need to buy and maintain the hardware!
- Access to all sorts of services and apps on demand
#### Elastic Beanstalk
No, don't laugh, that's what they named it, on purpose!
*Note: I have no idea what this is*
## The Shocking, Terrible Alternative! (According to Amazon)
The alternative is.... something called On-Prem-Isis Computing, which might be a form of terrorism.
### Advantages
- Bezos doesn't get your money
- You might not need to deploy an application in Dubai, New York and London at the same time
- My RaspberyPi server is just fine thank you very much
- You have total, absolute control of your own hardware/software/data
### Disadvantages
- Bezos will know...
- Scalability costs money
- Not very responsive to demand i.e. you can't actually download more ram
- Might be more expensive in the long run (man they are really hammering this home)

---
# Cloud Terms
## Software as a Service (SaaS)
Do you want your application's responsiveness to rely solely on your web browser and internet connection? Well tough, because everything is SaaS now.

SaaS has a lot of advantages, like being slow and frustrating, doesn't require installation, it works pretty much everywhere, and so deployment and maintenance is easy.
## Infrastructure as a Service (IaaS)
This is the big scalability part... Amazon will provide the hardware in the form of virtual machines, renting chunks of their server hardware.
## Platform as a Service (PaaS)
This is the means by which those cloud services can be delivered; Amazon may provide a suite of tools for creating/serving a website, database etc... in one user friendly package or platform.

---
# AWS technologies
## Examples
Amazon EC2 - Elastic Compute Cloud
Amazon S3 - something else
Databases - They have a lot of different types
AI probably? yup there it is
Amazon SageMaker - Machine Learning, easy to use apparently
AWS IoT - "Internet of Things" 
AWS Lambda - Something about servers and application development
## Who uses them?
- Netflix *(failing business model)*
- AirBnB *(falling stock price)*
- Slack *(nobody likes slack)*
- Nasa *(haven't taken us to the moon since the 60's)*
- Lyft 
- And many more!

---
# Feature Comparison
I fell asleep and missed the context for this, but I think it is about, the different levels of service that Amazon provide you based on your business plan type. Obviously a big boy company gets more rapid and comprehensive support, while a basic bitch gets nothing but a 12 month free tier slap in the face.

| Plan Type          | Programmatic case management | Case severity/response times                                                                                                                                                         | Architectural Guidance                                                     | Third-Party Software Support                                    |
| ------------------ | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- | --------------------------------------------------------------- |
| Basic              | None                         | None                                                                                                                                                                                 | None                                                                       | None                                                            |
| Developer          | None                         | General guidance: < 24 hours\*\*<br>System impaired: < 12 hours\*                                                                                                                    | General                                                                    | None                                                            |
| Business           | Using AWS support API        | General guidance: < 24 hours\*\*<br>System impaired: < 12 hours\*<br>Production system impaired: < 4 hours<br>Production system down: < 1 hour                                       | Contextual to your use-cases                                               | Interoperability and configuration guidance and troubleshooting |
| Enterprise On-Ramp | Using AWS support API        | General Guidance: < 24 hours<br>System impaired: < 12 hours<br>Production system impaired: < 4 hours<br>Production system down: < 1 hour<br>Business-critical system down: < 30 mins | Consultative review and guidance based on your applications (one-per-year) | Interoperability and configuration guidance and troubleshooting |
| Enterprise         | Using AWS support API        | General guidance: < 24 hours<br>System impaired: < 12 hours<br>Production system impaired: < 4 hours<br>Production system down: < 1 hour<br>Business-critical system down: < 15 mins | Consultative review and guidance based on your applications                | Interoperability and configuration guidance and troubleshooting |

