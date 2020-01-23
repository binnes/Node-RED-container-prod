# Node-RED-container-prod

Late in 2019 Node-RED released version 1.0.  In the following video the use of Low Code development for production use cases is discussed.

[!["Node-RED development for production applications"](http://img.youtube.com/vi/UpdgM66Au_U/0.jpg)](https://youtu.be/UpdgM66Au_U "Node-RED development for production applications")

One of the reported difficulties with using Node-RED in production is how to integrate Node-RED into a DevOps process.  Here are a series of Tutorials to show how to integrate Node-RED into a dev ops pipeline and also the considerations that need to be made when creating the application, so it can be deployed to a cloud environment.

To use Node-RED in a DevOps pipeline, the development process needs to looks like other programming languages:

![Node-RED production pipeline](image/NRprod.png)

1. Developer works locally to create applications
2. Code is delivered to a version control system, such as Git
3. A build process creates the application from source, packages it as a container and stores it in a container registry
4. At deploy time the container is pulled from the registry and run, with configuration data being provided by a runtime management environment, such as Kubernetes or OpenShift

The 3 tutorials in this series show you how to use Node-RED so it fits this way of working so Node-RED can be used for production workloads.

* Tutorial 1 : [Version Control with Node-RED](Node-REDsourceControl/README.md)
* Tutorial 2 : [Package Node-RED app in a container](Packaging%20Node-RED%20apps%20in%20containers/README.md)
* Tutorial 3 : [Node-RED config from environment](Node-RED%20config%20from%20environment/README.md)
