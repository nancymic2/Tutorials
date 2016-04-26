---
title: Internet of Things (IoT) Explore the SAP HCP IoT Services
description: Part 6 of 8, Setup and configure the use of the IoT Services with SAP HANA Cloud Platform
tags: [products>sap-hana, topic>big-data, topic>internet-of-things, tutorial>beginner ]

---

## Prerequisites  
 - **Proficiency:** Beginner
 - **Tutorials:** [Internet of Things (IoT) Check your data](http://go.sap.com/developer/tutorials/iot-part5-inserting-tessel-data.html)


## Next Steps
 - [Internet of Things (IoT) Adding a new device to the IoT Services](http://go.sap.com/developer/tutorials/iot-part7-add-device.html)

## Details
### You will learn  

This tutorial will detail the steps needed to simply the process of connecting your hardware device to SAP. As you saw in the previous section connecting our device directly to an SAP HANA server left plenty of room for errors as well as a number of security holes.


This procedure assumes you are using the trial edition of the SAP HANA Cloud Platform, but you can use a production account if you have one.  

### Time to Complete
**15 Min**.

---


2. One you log in, click on **Services** in the left-hand navigation bar, scroll down to find **Internet of Things Services** and click on that tile.

    ![Services](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/iot-part6-hcp-services/p6_2.png)

3. Click on the **Enable** button. After a few seconds the page will update and show **Enabled**.

    ![Enable Service](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/iot-part6-hcp-services/p6_3a.png)

4. Once the service is enabled click the **Go to Service** link and a new browser tab will open.

    ![Access Service](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/iot-part6-hcp-services/p6_4.png)



6. Enter in your information in the fields, where your account ID is your p-number with the world “trial” (no space between the p-number and trial) and your user name is just your p-number.
    ![Deploy Service](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/iot-part6-hcp-services/p6_6a.png)

    ![Deployed application](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/iot-part6-hcp-services/p6_7.png)

    ![Authorizations](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/iot-part6-hcp-services/p6_8.png)

9. Then under **Individual Users**, click **Assign** and enter your HCP user ID (e.g. your p-number without the word “trial” on the end). With that complete it is time to add our device.
 - [Next tutorial in the series...](http://go.sap.com/developer/tutorials/hcp-create-destination.html)