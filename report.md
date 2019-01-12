**The microservices are running at the start**

Account

![Figure 1](screenshots/AccountTerminal.PNG "Terminal account service")

![Figure 2](screenshots/AccountWeb.PNG "Web account service")

WebServer

![Figure 1](screenshots/WebServerTerminal.PNG "Terminal web service")

![Figure 2](screenshots/WebServerWeb.PNG "Web web service")

**And they are registrated as we can see here**

![Figure 1](screenshots/Registration.PNG "Registration of the instances")


**Now we add another account microservice changing the port in aplicacion.yaml file of account**

![Figure 1](screenshots/Account4444.PNG "Registration of the new instance")

![Figure 2](screenshots/Account4444Web.PNG "Terminal of the new instance in 4444 of account microservice")


**When one account microservice has fallen the load balancer replace it with the other one and web server still working**

![Figure 1](screenshots/Change.PNG "The provider has changed")