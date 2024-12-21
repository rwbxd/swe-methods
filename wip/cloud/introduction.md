# The Cloud - AKA Someone Else's Computer

## What is the Cloud?

You may think of several different things when you hear about "the cloud" - it's a bit of a catch-all term.
For many non-technical people, the extent of the involvement they have with "the cloud" may be their photo storage on their phone or computer.
For some business people, "the cloud" may be a buzzword that they don't fully understand, but might fetch them a promotion.
For developers, "the cloud" is and should be simple - someone else's computer.

Of course, there's more nuance than that, but for the sake of simplicity, that's the furthest we're going to go in defining "the cloud" as a concept.

## Who owns the Cloud?

Since "the cloud" is just someone else's computer, there isn't one "cloud".
Instead "the cloud" is a term that refers to any storing of data or processing done away from a local device.
- Steam, the popular PC game service, stores some save files in the "Steam Cloud" to allow you to retain your game state on multiple local devices.
- Apple's iCloud stores your phone's pictures as to not need to use your phone's local storage.
- Companies such as Amazon offer "cloud services" to allow companies to move their applications and computing power from on-premises resources into the "cloud" - this is the focus of this section.

## Cloud Service Providers

You may have heard of Amazon's Amazon Web Services, or AWS.
AWS is the cloud service provider with the largest marketshare (as of the time of writing, but with no signs of that metric changing anytime soon), followed by Microsoft's Azure platform, and Google's Google Cloud Platform.
There are many other cloud companies, some big (IBM and Oracle, for example have cloud offerings) and some comparatively small (such as DigitalOcean), but for the sake of simplicity, we will be focusing on the Big 3 (with the heaviest focus on AWS).

As previously mentioned, the cloud is not a single entity or use-case, which is why these are referred to as Cloud Service Providers.
What cloud services do they provide? AWS, as an example, offers over 200 services, ranging from
- Virtual servers
- Databases
- File storage
- User manangement
- Email/SMS services
- AI models
- Virtual networking
- Code editors/IDEs
- And much, much more

## The services that actually matter

Of course, not all companies and users will be using all 200+ services.
Most will only use a select subset, with a few being the most important.
Here are the services that (subjectively) matter the most, and will be explored in this section.

| Use Case             | AWS Name   | Azure Name             | GCP Name            |
| -------------------- | ---------- | ---------------------- | ------------------- |
| Virtual servers      | EC2        | Azure Virtual Machines | Compute Engine      |
| Databases            | RDS        | Azure SQL Database     | Cloud SQL           |
| File storage         | S3         | Azure Blob Storage     | Cloud Storage       |
| Serverless functions | Lambda     | Azure Functions        | Cloud Run Functions | 
| Log Management       | Cloudwatch | Azure Monitor          | Cloud Monitoring    |

If you can become comfortable with these services, you will be a software engineer ready to take on the cloud.
