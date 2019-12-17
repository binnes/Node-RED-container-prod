# Node-RED-container-prod
Tutorials to create production ready Node-RED applications

To use Node-RED in a DevOps pipeline the development process needs to looks like other programming languages:

1. Developer works locally to create applications
2. Code is delivered to a version control system, such as Git
3. A build process creates the application from source, packages it as a container and stores it in a container registry
4. At deploy time the container is pulled from the registry and run, with configuration data being provided by a runtime management environment, such as Kubernetes or OpenShift

The 3 tutorials in this series show you how to use Node-RED so it fits this way of working so Node-RED can be used for production workloads.

* Tutorial 1 : [Version Control with Node-RED](Node-REDsourceControl/README.md)
* Tutorial 2 : [Package Node-RED app in a container](Packaging%20Node-RED%20apps%20in%20containers/README.md)
* Tutorial 3 : [Node-RED config from environment](Node-RED%20config%20from%20environment/README.md)
