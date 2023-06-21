---
title: Why would you use this service?
parent: FAQ
---
{{site.data.naming.servicename}} is powered by the repository management software of [gitlab](https://about.gitlab.com). Gitlab is also available as a publicly hosted (free) service at gitlab.com. Also, there is the well-known service github.com that provides similar services.

So why would a researcher use {{site.data.naming.servicename}} and not one of these free services?

First of all: TU Delft thoroughly supports the FAIR principles, so if your project can use a public service that makes the data/program FAIR, there is no reason at all NOT to use these services. This is at the discretion of the researcher herself!

Having said that, we encounter a number of reasons why people do prefer using {{site.data.naming.servicename}}:


##### Use of netid

Researchers can use their netid to access the repository and grant access to others, making it easier to determine that the 'right' people have access.

##### TU Delft branding

Having your repository on a url that clearly names TU Delft can help your software's reputation.

##### Repository durability

We promise to keep your repository available for {{site.data.naming.defaultrepottl}}. Many public providers in practice do this as well, however they do not issue any guarantees. We recognize the importance of your published software and therefore do give this guarantee. See also our @@@TODO@@@: policy

##### (Dis)trust

Some researchers are uncomfortable using cloud services provided and managed by 'big tech'. {{site.data.naming.servicename}} is managed by TU Delft staff members. We strive to keep the data in control of TU Delft and secure. 

### Reasons not to use {{site.data.naming.servicename}}

We feel it's only fair to also give you some reasons why you might not wish to use {{site.data.naming.servicename}}. You should at least be aware of these so you can make an informed decision:

##### Stability

{{site.data.naming.servicename}} is hosted at TU Delft. We do our best to maintain a stable environment, and we are proud of the level of service we achieve, but it is a fact that we do not have the resources that the large service providers have at their disposal. That means we have regular service-windows (usually at weekends) where we do maintenance of our servers and network. This can cause downtime for (usually short) periods.


##### Performance

TU Delft has dedicated less compute-resources to spend than the commercial big hosters. This means you may experience latencies as a result of peak usage of our servers. Of course we monitor our service and try to react as soon as possible when problems arise!

##### Functionality

One of the reasons the big tech providers provide their free service is for showcasing all functionality of their products. That means that often you can use a lot of 'extra' functions in these environments (such as website hosting, workers for CICD, etc). You may not even realize these functions are not part of the basic product. At TU Delft we unfortunately cannot afford to blindly add all functions to our setup: the amount of maintenance personnel required to keep this running is simply not available! We of course always strive to be as efficient as possible, so if there is functionality you would really like to see added to our environment, please let us know. The more people request functionality, the easier it is for us to decide to dedicate our resources to that functionality.