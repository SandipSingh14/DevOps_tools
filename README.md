# DevOps Tools to Hands-On


Goal
=======
To get familier with DevOps, tools and Technologies, Focus Areas;

# DevOps
DevOps (a portmanteau of "development" and "operations") is a software development method that stresses communication, collaboration, integration, automation and measurement between software developers and Information Technology professionals. DevOps is a response to the interdependence of software development and IT operations. It aims to help an organization rapidly produce software products and services and to improve operations performance, quality assurance. [More.]

![devops.png]

# Details on Tools and Techonologies

[Unix] : Unix is a family of multitasking, multiuser computer operating systems that derive from the original AT&T Unix, developed in the 1970s at the Bell Labs research center. [more.]

[AWS] : Amazon Web Services began offering IT infrastructure services to businesses in the form of web services -now commonly known as cloud computing. One of the key benefits of cloud computing is the opportunity to replace up-front capital infrastructure expenses with low variable costs that scale with your business. With the Cloud, businesses no longer need to plan for and procure servers and other IT infrastructure weeks or months in advance. Instead, they can instantly spin up hundreds or thousands of servers in minutes and deliver results faster.

![aws]

Products & Services
===================
# Compute
* [Amazon EC2] : Amazon Elastic Compute Cloud is a web service that provides resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers.
Amazon EC2’s simple web service interface allows you to obtain and configure capacity with minimal friction. It provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment. Amazon EC2 reduces the time required to obtain and boot new server instances to minutes, allowing you to quickly scale capacity, both up and down, as your computing requirements change. Amazon EC2 changes the economics of computing by allowing you to pay only for capacity that you actually use. Amazon EC2 provides developers the tools to build failure resilient applications and isolate themselves from common failure scenarios.

* [Amazon EC2 Container Service] : Amazon EC2 Container Service is a highly scalable, high performance container management service that supports Docker containers and allows you to easily run distributed applications on a managed cluster of Amazon EC2 instances. Amazon EC2 Container Service lets you launch and stop container-enabled applications with simple API calls, allows you to query the state of your cluster from a centralized service, and gives you access to many familiar Amazon EC2 features like security groups, EBS volumes and IAM roles. You can use EC2 Container Service to schedule the placement of containers across your cluster based on your resource needs, isolation policies, and availability requirements. Amazon EC2 Container Service eliminates the need for you to operate your own cluster management and configuration management systems or worry about scaling your management infrastructure.
* [AWS Lambda] : AWS Lambda is a compute service that runs your code in response to events and automatically manages the compute resources for you, making it easy to build applications that respond quickly to new information. AWS Lambda starts running your code within milliseconds of an event such as an image upload, in-app activity, website click, or output from a connected device. You can also use AWS Lambda to create new back-end services where compute resources are automatically triggered based on custom requests. With AWS Lambda you pay only for the requests served and the compute time required to run your code. Billing is metered in increments of 100 milliseconds, making it cost-effective and easy to scale automatically from a few requests per day to thousands per second.
* [Auto Scaling] : Auto Scaling helps you maintain application availability and allows you to scale your Amazon EC2 capacity up or down automatically according to conditions you define. You can use Auto Scaling to help ensure that you are running your desired number of Amazon EC2 instances. Auto Scaling can also automatically increase the number of Amazon EC2 instances during demand spikes to maintain performance and decrease capacity during lulls to reduce costs. Auto Scaling is well suited both to applications that have stable demand patterns or that experience hourly, daily, or weekly variability in usage. 
* [Amazon VPC] : Amazon Virtual Private Cloud lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways.
You can easily customize the network configuration for your Amazon Virtual Private Cloud. For example, you can create a public-facing subnet for your webservers that has access to the Internet, and place your backend systems such as databases or application servers in a private-facing subnet with no Internet access. You can leverage multiple layers of security, including security groups and network access control lists, to help control access to Amazon EC2 instances in each subnet.
Additionally, you can create a Hardware Virtual Private Network (VPN) connection between your corporate datacenter and your VPC and leverage the AWS cloud as an extension of your corporate datacenter.
* [Elastic Load Balancing] : Elastic Load Balancing automatically distributes incoming application traffic across multiple Amazon EC2 instances in the cloud. It enables you to achieve greater levels of fault tolerance in your applications, seamlessly providing the required amount of load balancing capacity needed to distribute application traffic.

Storage & Content Delivery
=========================
* [Amazon S3] : Amazon Simple Storage Service, provides developers and IT teams with secure, durable, highly-scalable object storage. Amazon S3 is easy to use, with a simple web services interface to store and retrieve any amount of data from anywhere on the web.
* [Amazon Glacier] : Amazon Glacier is a secure, durable, and extremely low-cost storage service for data archiving and online backup. Customers can reliably store large or small amounts of data for as little as $0.01 per gigabyte per month, a significant savings compared to on-premises solutions. To keep costs low, Amazon Glacier is optimized for infrequently accessed data where a retrieval time of several hours is suitable.
* [Amazon EBS] : Amazon Elastic Block Store provides persistent block level storage volumes for use with Amazon EC2 instances in the AWS Cloud.  Each Amazon EBS volume is automatically replicated within its Availability Zone to protect you from component failure, offering high availability and durability. Amazon EBS volumes offer the consistent and low-latency performance needed to run your workloads. With Amazon EBS, you can scale your usage up or down within minutes – all while paying a low price for only what you provision.
* [Amazon CloudFront] : Amazon CloudFront is a content delivery web service. It integrates with other Amazon Web Services products to give developers and businesses an easy way to distribute content to end users with low latency, high data transfer speeds, and no minimum usage commitments.

Databases 
==========
* [Amazon RDS] : Amazon Relational Database Service is a web service that makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while managing time-consuming database management tasks, freeing you up to focus on your applications and business.
* [Amazon DynamoDB] : Amazon DynamoDB is a fast and flexible NoSQL database service for all applications that need consistent, single-digit millisecond latency at any scale. It is a fully managed database and supports both document and key-value data models. Its flexible data model and reliable performance make it a great fit for mobile, web, gaming, ad-tech, IoT, and many other applications.
* [Amazon Redshift] : Amazon Redshift is a fast, fully managed, petabyte-scale data warehouse solution that makes it simple and cost-effective to efficiently analyze all your data using your existing business intelligence tools. 
* [Amazon ElastiCache] : ElastiCache is a web service that makes it easy to deploy, operate, and scale an in-memory cache in the cloud. The service improves the performance of web applications by allowing you to retrieve information from fast, managed, in-memory caches, instead of relying entirely on slower disk-based databases. ElastiCache supports two open-source in-memory caching engines:
    *   [Memcached] - a widely adopted memory object caching system. ElastiCache is protocol compliant with Memcached, so popular tools that you use today with existing Memcached environments will work seamlessly with the service.
    * [Redis] – a popular open-source in-memory key-value store that supports data structures such as sorted sets and lists. ElastiCache supports Master / Slave replication and Multi-AZ which can be used to achieve cross AZ redundancy.

# Networking
* [AWS Direct Connect] : AWS Direct Connect makes it easy to establish a dedicated network connection from your premises to AWS. Using AWS Direct Connect, you can establish private connectivity between AWS and your datacenter, office, or colocation environment, which in many cases can reduce your network costs, increase bandwidth throughput, and provide a more consistent network experience than Internet-based connections.
* [Amazon Route 53] : Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect to each other.

# Deployment & Management
* [AWS CloudFormation] : AWS CloudFormation gives developers and systems administrators an easy way to create and manage a collection of related AWS resources, provisioning and updating them in an orderly and predictable fashion.
You can use AWS CloudFormation’s sample templates or create your own templates to describe the AWS resources, and any associated dependencies or runtime parameters, required to run your application.
[more....]

[Jenkins] : Jenkins is an award-winning application that monitors executions of repeated jobs, such as building a software project or jobs run by cron. Among those things, current Jenkins focuses on the following two jobs:
* Building/testing software projects continuously, just like CruiseControl or DamageControl. In a nutshell, Jenkins provides an easy-to-use so-called continuous integration system, making it easier for developers to integrate changes to the project, and making it easier for users to obtain a fresh build. The automated, continuous build increases the productivity.
* Monitoring executions of externally-run jobs, such as cron jobs and procmail jobs, even those that are run on a remote machine. For example, with cron, all you receive is regular e-mails that capture the output, and it is up to you to look at them diligently and notice when it broke. Jenkins keeps those outputs and makes it easy for you to notice when something is wrong. [more..]

![jenkins]

[Git and GitHub] : Git is a repository for storing versions of code, otherwise known as a revision-control system; GitHub is a publicly hosted repository of code that can be downloaded and shared.

![git]

[Chef] : Chef is a systems and cloud infrastructure automation framework that makes it easy to deploy servers and applications to any physical, virtual, or cloud location, no matter the size of the infrastructure.
* Chef has the following major components:
    *  [Chef-client] : The chef-client does the actual configuration on the nodes. The chef-client receives its instructions from cookbooks (recipes, mostly). The process of configuring a node is called the chef-client run. At the beginning of each run, the chef-client validates to the server, collects important data about that node, and then configures the node. At the end of each run, the chef-client reports the successes and failures that may have occurred.
    *  [Workstation] : A workstation is a computer that is configured to run knife, to synchronize with the chef-repo, and interact with a single Chef server. The workstation is the location from which most users will do most of their work.
    *  [Chef-server] : The Chef server acts as a hub for configuration data. The Chef server stores cookbooks, the policies that are applied to nodes, and metadata that describes each registered node that is being managed by the chef-client. Nodes use the chef-client to ask the Chef server for configuration details, such as recipes, templates, and file distributions. The chef-client then does as much of the configuration work as possible on the nodes themselves.

![chef]

[Knife] : Knife is a command-line tool that provides an interface between a local chef-repo and the Chef server. knife helps users to manage:
* Nodes
* Cookbooks and recipes
* Roles
* Stores of JSON data (data bags), including encrypted data
* Environments
* Cloud resources, including provisioning
* The installation of the chef-client on management workstations
* Searching of indexed data on the Chef server

[Berkshelf] :  A way of managing how cookbooks are fetched and deployed to a Chef server in order to make sure the right versions of cookbooks are being run.

[Kitchen] : Kitchen is an integration tool for developing and testing infrastructure code and software on isolated target platforms, a sort of dry run in the cookbook development process.

[Foodcritic] : A lint tool for your cookbooks, This is a really cool tool to look at a cookbook and test Chef correctness.
* Foodcritic has two goals:
    * To make it easier to flag problems in your Chef cookbooks that will cause Chef to blow up when you attempt to converge. This is about faster feedback. If you automate checks for common problems you can save a lot of time.
    * To encourage discussion within the Chef community on the more subjective stuff - what does a good cookbook look like? Opscode have avoided being overly prescriptive which by and large I think is a good thing. Having a set of rules to base discussion on helps drive out what we as a community think is good style.

[Puppet] : Puppet manages your servers: you describe machine configurations in an easy-to-read declarative language, and Puppet will bring your systems into the desired state and keep them there.
* Puppet has the following major components:
    * [Puppet Enterprise] : Puppet Enterprise is an IT automation software that allows system administrators to programmatically provision, configure, and manage servers, network devices and storage, in the data center or in the cloud.
    * [MCollective] : The Marionette Collective, also known as MCollective, is a framework for building server orchestration or parallel job execution systems. Most people use it to programmatically execute administrative tasks on clusters of servers.
    * [Puppet Dashboard] : Puppet Dashboard is a web interface for Puppet. It can view and analyze Puppet reports, assign Puppet classes and parameters to nodes, and view inventory data and backed-up file contents.
    * [PuppetDB] : PuppetDB collects data generated by Puppet. It enables advanced Puppet features like exported resources, and can be the foundation for other applications that use Puppet’s data.
    * [Hiera] : Hiera is a key/value lookup tool for configuration data, built to make Puppet better and let you set node-specific data without repeating yourself.
    * [Facter] : Facter is Puppet’s cross-platform system profiling library. It discovers and reports per-node facts, which are available in your Puppet manifests as variables.


![puppet]

[Ansible] : Ansible is an IT automation tool. It can configure systems, deploy software, and orchestrate more advanced IT tasks such as continuous deployments or zero downtime rolling updates.
    
![ansible]
    
[Vagrant] : Vagrant provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.
To achieve its magic, Vagrant stands on the shoulders of giants. Machines are provisioned on top of VirtualBox, VMware, AWS, or any other provider. Then, industry-standard provisioning tools such as shell scripts, Chef, or Puppet, can be used to automatically install and configure software on the machine.

![vagrant]

[Docker] : Docker is a platform for developers and sysadmins to develop, ship, and run applications. Docker lets you quickly assemble applications from components and eliminates the friction that can come when shipping code. Docker lets you get your code tested and deployed into production as fast as possible.
* Docker consists of:
    * The Docker Engine - Lightweight and powerful open source container virtualization technology combined with a work flow for building and containerizing your applications.
    * Docker Hub - SaaS service for sharing and managing your application stacks.

[Nagios] : Nagios is a powerful system monitoring tool that enables organizations to identify and resolve IT infrastructure problems before they affect critical business processes. Nagios monitors entire IT infrastructure to ensure systems, applications, services, and business processes are functioning properly. In the event of a failure, Nagios can alert technical staff of the problem, allowing them to begin remediation processes before outages affect business processes, end-users, or customers.

![nagios]

[Newrelic] : New Relic is a Software Analytics tool that makes sense of billions of metrics across millions of applications. It's help people who build modern software understand the stories their data is trying to tell them. It’s about gaining actionable, real-time business insights from the billions of metrics your software is producing, including user click streams, mobile activity, end user experiences and transactions.

![newrelic]

[Datadog] : Datadog is a monitoring service for IT, Operations and Development teams who write and run applications at scale, and want to turn the massive amounts of data produced by their applications, tools and services into actionable insight.

![datadog]

[Unix]:http://en.wikipedia.org/wiki/Unix
[more.]:http://en.wikipedia.org/wiki/Unix
[devops.png]:(/home/sandip/DevOps_tools/images/devops.png)
[Jenkins]:http://jenkins-ci.org/
[more..]:https://wiki.jenkins-ci.org/display/JENKINS/Meet+Jenkins
[jenkins]:/home/sandip/DevOps_tools/images/jenkins.png
[More.]:http://en.wikipedia.org/wiki/DevOps
[AWS]:http://en.wikipedia.org/wiki/Amazon_Web_Services
[aws]:/home/sandip/DevOps_tools/images/aws.jpg
[Amazon EC2]:http://aws.amazon.com/ec2/
[Amazon EC2 Container Service]:http://aws.amazon.com/ecs/
[AWS Lambda]:http://aws.amazon.com/lambda/
[Auto Scaling]:http://aws.amazon.com/autoscaling/
[Amazon VPC]:http://aws.amazon.com/vpc/
[Elastic Load Balancing]:http://aws.amazon.com/elasticloadbalancing/
[Amazon S3]:http://aws.amazon.com/s3/
[Amazon Glacier]:http://aws.amazon.com/glacier/
[Amazon EBS]:http://aws.amazon.com/ebs/
[Amazon CloudFront]:http://aws.amazon.com/cloudfront/
[Amazon RDS]:http://aws.amazon.com/rds/
[Amazon DynamoDB]:http://aws.amazon.com/dynamodb/
[Amazon Redshift]:http://aws.amazon.com/redshift/
[Amazon ElastiCache]:http://aws.amazon.com/elasticache/
[Memcached]:http://www.memcached.org/
[Redis]:http://redis.io/
[AWS Direct Connect]:http://aws.amazon.com/directconnect/
[Amazon Route 53]:http://aws.amazon.com/route53/
[AWS CloudFormation]:http://aws.amazon.com/cloudformation/
[more....]:http://aws.amazon.com/products/
[Git and GitHub]:http://en.wikipedia.org/wiki/Git_(software)
[git]:/home/sandip/DevOps_tools/images/git.png
[Chef]:https://docs.chef.io/
[Chef-client]:http://docs.chef.io/client/
[Workstation]:https://docs.chef.io/workstation.html
[Chef-server]:https://docs.chef.io/chef_server.html
[chef]:/home/sandip/DevOps_tools/images/chef.jpg
[Knife]:https://docs.chef.io/knife.html
[Berkshelf]:http://berkshelf.com/index.html
[Kitchen]:https://github.com/test-kitchen/test-kitchen
[Foodcritic]:http://acrmp.github.io/foodcritic/
[Puppet]:http://puppetlabs.com/
[Puppet Enterprise]:https://docs.puppetlabs.com/pe/latest/overview_about_pe.html
[MCollective]:https://docs.puppetlabs.com/mcollective/
[Puppet Dashboard]:https://docs.puppetlabs.com/dashboard/manual/1.2/#overview
[PuppetDB]:https://docs.puppetlabs.com/puppetdb/latest/
[Hiera]:https://docs.puppetlabs.com/hiera/1/
[Facter]:https://docs.puppetlabs.com/facter/latest/
[puppet]:/home/sandip/DevOps_tools/images/puppet.jpg
[Ansible]:http://www.ansible.com/
[ansible]:/home/sandip/DevOps_tools/images/ansible.jpg
[Vagrant]:https://www.vagrantup.com/
[vagrant]:/home/sandip/DevOps_tools/images/vagrant.jpg
[Docker]:https://www.docker.com/
[docker]:/home/sandip/DevOps_tools/images/docker.jpg
[Nagios]:http://www.nagios.org/
[nagios]:/home/sandip/DevOps_tools/images/nagios.jpg
[Newrelic]:http://newrelic.com/
[newrelic]:/home/sandip/DevOps_tools/images/newrelic.png
[Datadog]:https://www.datadoghq.com/
[datadog]:/home/sandip/DevOps_tools/images/datadog.png



