# Business Applications by jBPM - Dashboard Demo

This is a demo business application built with https://start.jbpm.org and expanded
to add a dashboard demo. 


![Sample of demo](dashboard.png?raw=true)


## Getting Started 
1. Clone and build the needed kie server thymeleaf dialect project:
```
git clone https://github.com/tsurdilo/thymeleaf-kie-server-dialect.git
cd thymeleaf-kie-server-dialect
mvn clean install
```

2. Clone this repository locally and start the demo app:

```
git clone https://github.com/business-applications/sample-dashboard-thymeleaf.git
cd sample-dashboard-thymeleaf
cd sample-dashboard-thymeleaf-service
chmod 755 launch.sh (only needed for unix environments , use launch.bat for windows)
./launch.sh (or launch.bat for windows)
```


## Accessing your application

Once the app has started you cann access the landing page at 

```
localhost:8090/demo
```

## More info
For more info and a walkthrough for this demo 
see the blog post http://mswiderski.blogspot.com/2018/10/jbpm-business-apps-dashboard-demo.html
