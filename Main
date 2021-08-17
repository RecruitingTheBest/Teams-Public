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
- Working on a proposed approach to move off of AWS managed LBs and use our own design to avoid AWS limits
- Working on deploying network policy to network isolate customer deployments from each other
- Investigating tooling for managing terraform via PR process
- Doing research into process approaches to limit impacts to customers during cloud maintenance (IE how to drain a node of persistent SSH connections)

## Cloud Application team
- Automatic provisioning, management, and monitoring of customer Teleport infrastructure (aws, kubernetes, golang)
- Subscription management, billing and payments (PostgreSQL, plsql, golang, grpc, Stripe, React)
- Adding new features to Teleport Web Application (React, golang, websockets, grpc)
