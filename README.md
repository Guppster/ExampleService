# ExampleTool
An example tool for the MDM Delivery microservice architecture 

# Deploying the Service
* Clone the repository
* Run the following command and populate each build arg (captialized) with your own data
* `docker build -t mdmtool:1.0.0 --build-arg NAME=ToolName --build-arg COREURL=http://FrameworkURL.com --build-arg TOOLURL=http://localURL.com:4567 --build-arg PORT=4567 .`
* `docker run -p 4567:4567 -t mdmtool:1.0.0`

