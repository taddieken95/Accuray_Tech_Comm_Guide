# Manufacturing Department Document Requests

> **NOTE:** This provides an overview of the means by which the Accuray Manufacturing Technical Writer receives requests for the creation / editing of a document.

## Configure Agile Interface

First thing's first, in order to efficiently receive SME requests, we must set up our Agile dashboard to receive document requests.

### Configure Agile Interface for TomoTherapy Document Requests

1. Go to *accuray.okta.com*, this will take you to a centralized hub of different enterprise programs used here at Accuray Incorporated. Click the **Oracle Agile PLM** widgit.
2. You will most likely be routed to the **Workflow Routings** tab of the Accuray Agile Interface. Go toward the top of the screen, and select the **Dashboard** tab.
3. You will now be presented with a screen featuring four (4) empty tables. Click the **Configure** button in the center of the top-left table.
4. Change the **Table Name** to *TT ECRs*. Ensure **Display Type** is set to **Table** then click **Next** at the bottom-right corner of the window.
5. Select the **Advanced Search** radio button and click **Define Query**. A new window will appear.
6. Go to the empty dropdown menu at the top of the window (next to the **Changes** dropdown) and select **ECR** from the selection (listed under **Change Requests**).
7. Go to the **Attribute** dropdown and select **ECR Type**.
8. Click inside the **Value** search bar with your cursor, and type *Product_Doc*.
9. Click **Finish**, go to the **Join** dropdown menu and select **And**.
10. A new row will appear. Go to the **Attribute** dropdown and select **Product Line(s)**.
11. Go to the **Operator** dropdown and select **Equal To**. 
12. Go to the **Value** search bar and enter **TomoTherapy**. Click **Finish** at the bottom-right corner of the window.

The TT ECR Window should now be configured and appear as shown in the figure below.

![alt text](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/img/TT%20ECRs.png "TT ECR Example")

### Configure Agile Interface for CyberKnife Document Requests

Next, you will also need to create a window for CyberKnife document requests. The process for creating a CK ECR window should be nearly identical to the previous section, with the following differences:

* In Step 3, click the **Configure** button in the center of the top-right table.
* In Step 4, assign the **Table Name** to *CK ECRs*
* In Step 12, enter **CyberKnife** in the **Value** search bar.

The CK ECR Window should now be configured and appear as shown in the figure below.

![alt text](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/img/CK%20ECRs.png "CK ECR Example")

Your ECR dashboard is now set up and ready to use. Document requests will appear via ECR in each respective window.
