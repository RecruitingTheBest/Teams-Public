# Summary
This is meant to be a general guide to learn about the different kinds of projects our engineering teams are working on at Teleport and to help decide which may be the best fit for those looking to join. 


## Core Teleport team
- U2F Protected Sessions.
- User locking (security controls).
- Approval workflows for dynamic access granting.
- [Scaling](https://github.com/gravitational/teleport/issues?q=is%3Aissue+is%3Aopen+label%3Ascale) Teleport to larger clusters (10k at the moment).
- Performance improvements to large clusters.
- Making Teleport CA easier to use.

### Backend, Windows 
- Porting Teleport server and client to Windows.
- Building hardened [security](https://github.com/gravitational/teleport/issues?q=is%3Aissue+is%3Aopen+label%3Asecurity) for Windows users.
- Implementing remote desktop support protocol for Teleport
- working with Direcx3D device drivers, video streaming etc.

### Teleport Security Engineering
- HSM support
- Internal PKIs
- User/session locking
- Access workflows

### Database and Application Access 
Application & Database Access team is one of the newer Teleport teams. We are focusing on design and development of the Teleport products providing access to [web applications](https://goteleport.com/docs/application-access/), [databases](https://goteleport.com/docs/database-access/) and various [cloud providers](https://goteleport.com/docs/application-access/guides/aws-console/).

#### Here are the examples of projects you may be working on:
* Adding support for more database access [protocols](https://github.com/gravitational/teleport/issues?q=is%3Aopen+is%3Aissue+label%3Adatabase-access+label%3Adb%2Frequested) and improving the existing ones.
* Working on [features](https://github.com/gravitational/teleport/issues?q=is%3Aissue+is%3Aopen+label%3Aapplication-access+label%3Afeature-request) for application access identity-aware proxy.
* Building advanced access controls such as [session recording](https://github.com/gravitational/teleport/issues/5799), [data masking](https://github.com/gravitational/teleport/issues/7150) and [per-session MFA](https://github.com/gravitational/teleport/issues/6172).
* Implementing cloud access solutions for AWS, GCP and Azure.
* Improving the UX of application and database access products.

The App & Database Access team is currently 2 people (part of the larger Teleport Core team of 20) in US and European timezones, looking to grow to 4-5 this year.

### Teleport Devops
Responsible for Building, Maintaining, and Testing open-source modules for various configuration management platforms. This will be the opensource code that enables both our OSS and Enterprise customers to deploy and maintain Teleport on their chosen configuration management system. We’re looking to cover kubernetes, terraform on various clouds, ansible, salt, puppet, etc.

## Cloud Platform team
The Teleport Cloud offering is new; we're on a journey of defining and building a culture around production, offering a secure and reliable hosted version of Teleport Enterprise as a service. 

Our mandate is straightforward; we need to be prepared to secure, monitor, maintain, scale, investigate, and automate our production environment for Teleport Cloud. Our work includes a wide variety of projects drawing on various skillsets, from ensuring we're up to date on patches to redesigning parts of the Teleport Core project to be more appealing to the Cloud.

#### Here are some of the projects we're working on right now:
- Rewriting the Teleport core project networking so that agents run by customers require fewer connections and overhead when phoning home.
- We are expanding Teleport Cloud to multiple regions, reducing latency between users and their infrastructure.
- We are deploying auto scalers, so no one needs to be paged to scale our infrastructure when there is a burst in new accounts.
- We're improving our security posture, currently focusing on ensuring we have an audit trail for generated and published assets and ensuring we're using encryption at rest in the right places.
- Progressing beyond minimum viable monitoring and alerting and fully adopting Grafana Cloud as our centralized metrics, alerting and logging platform.

#### The toolset we currently use is:
* Golang
* Terraform and Packer
* Kubernetes
* Prometheus / Alertmanager / Loki internally and on Grafana Cloud
* Amazon Web Services
* Drone.io
* and More

## Cloud Application team
- Automatic provisioning, management, and monitoring of customer Teleport infrastructure (aws, kubernetes, golang)
- Subscription management, billing and payments (PostgreSQL, plsql, golang, grpc, Stripe, React)
- Adding new features to Teleport Web Application (React, golang, websockets, grpc)
