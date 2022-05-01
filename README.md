# SDI-for-Disaster-Management
Spatial data is at the center of responding to disaster. Organizations dealing with disaster management on the other hand operate in separetly and hardly share their datasets.
This leads to lack of coordination, duplication of data collection efforts which in turn leads to higher costs in data collection.
To tackle this issue, a spatial data infrastructure approach has been adopted, using the open-source GeoNode. 
Steps for setting up GeoNode are available at https://docs.geonode.org/en/master/

After setting the components of Geonode on my Ubuntu 20.04, the architecture looks like the diagram below;
![GeoNode-Components-architecture](https://user-images.githubusercontent.com/42302441/166161923-dc55d41c-dd6c-4885-8e97-937c6a69ef5b.png)

GeoNode CMS, is built to separate the components of an SDI, which are data, users, standards, policies and network.
Built on Django framework, Geo Node uses the authentication contrib of Django to manage users and access to data. A user has to sign up to use the datasets of access self-service mapping in the system.
![SIGNUP](https://user-images.githubusercontent.com/42302441/166161977-0f2ebd63-6be1-4888-8963-a6198ae35812.png)

The geoportal of the SDI was customised and is as illustrated below;
![GeoportalView](https://user-images.githubusercontent.com/42302441/166162014-3fd722be-9c7c-42bf-a9e6-d66954ea12ef.png)
![GeoportalView2](https://user-images.githubusercontent.com/42302441/166162020-c52d6236-25e0-4512-8452-349d51c08d30.png)
