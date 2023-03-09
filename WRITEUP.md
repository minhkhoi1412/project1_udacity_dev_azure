# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*As the program had been operating for a considerable amount of time, the computers and environment had been entirely modified to meet its requirements. The team will need to recreate the environment within the VM in order to migrate from a bare-metal system to a VM in the cloud. Reinstalling the operating system, platform, and middleware to support the application, libraries, and frameworks is what "recreation" refers to.

About the program, I think certain adjustments should be made to optimize the use of resources like memory and CPU, prevent expensive IO, and enhance some cache technologies. These adjustments are required since the program did not take resource usage into account prior to the transfer. Finding the application's component that can be turned into a module, service, or even distributed as an App Service should be fascinating to find after the migration.* 

### Virtual Machines

Internally, I already have a program running. It is planned to transition from bare-metal computers to cloud-based "Virtual Machines" first.

Both the infrastructure team and the software development team have prior knowledge of the procedures involved in building, continuous integration, and deployment.

Although Virtual Machine is more expensive than App Service, maintaining the application in the cloud will be less expensive than with bare-metal computers.

### Compare between Virtual Machines and App Service

#### Maintenance

Compared to App Services, Virtual Machine needs a lot more work and upkeep. Developers just need to concentrate on the technologies utilized in the application when using an app service.
For applications that require more flexibility and changeability, virtual machines are considerably superior.

#### The time spent creating an application

Developing using App Service is more easier and quicker than with Virtual Machines.

#### Price

Because the virtual machine is continuously operating and using resources like CPU and memory even when the program is not in use, it costs more than the app service. Frequently, a plan must be purchased in order to access the app service. If you use the "Virtual Machine," you must pay for it (pay-as-you-go).

#### Scalability

There are scaling limitations with Azure App Service.
Apps with future expansion potential are preferable for Azure VMs.