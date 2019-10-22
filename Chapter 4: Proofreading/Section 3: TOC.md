# TOC Proofreading

> **NOTE:** This section will provide more in depth information regarding each of the bullet points in the TOC section of the checklist provided in [Section 1: Document Submission Readiness Checklist](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/Chapter%204:%20Proofreading/Section%201:%20Document%20Submission%20Readiness%20Checklist.md).

## TOC

* Added new TOC page in FrameMaker (if not already present)
* Title, document number, and revision letter are updated in the top margin
* Page numbers correctly correspond to the content
* Bottom margins have updated page number

* **


### Title, Document Number, and Revision Letter are Updated in the Top Margin

Ensure the Document Title and the WI Number listed at the top margin are both correct. If they are incorrect, adjust them using the **Doc Title** and **Version** sections of the **Variables** pod.

### Page Numbers Correctly Correspond to the Content

The TOC *should* be automatically linked to the _Content.fm file. If the page numbers displayed are not currently correct, click **Update Book**. If this does not resolve the issue, the crossreference in the TOC file are likely broken.

### Bottom Margins have Updated Page Number

Similar to the previous [section](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/Chapter%204:%20Proofreading/Section%202:%20Title%20Page.md), check the bottom margin of the document to ensure *FRM 1049647 Rev C* is displayed. If not, resolve this issue by editing the bottom margin within the **Master Pages** viewing mode (**esc + v + m**).

### Add a new TOC Page in FrameMaker

In certain cases, the crossreferences in FrameMaker's TOC page become broken. You will notice this when you click the **Update Book** button and the TOC remains unchanged and does not update with the proper page numbers or section titles. 

> **Tip:** Another way to tell if the crossreferences in a TOC are broken, is by looking at the color of the FrameMaker file icon next to the _TOC.fm file in the file display panel on the side of your screen. The file icon color should be orange. If it is white (similar to the file icons displayed for the _TitlePage.fm file and _Content.fm files), the TOC crossreference is broken.

If a TOC crossreference is broken, the best way to rectify is by creating a new TOC. Perform the following to generate a new TOC:

1. Go to the file display panel on the left side of the screen and click the **_Content.fm file**.

> **NOTE:** Only click the file once so that it is highlighted blue. Do not double-click as this will register as attempting to change the file name.

2. Go to the **Insert** dropdown menu and select **Create Standalone TOC...**. A **Set Up Table of Contents** dialog box will appear.
3. Ensure the **Suffix** states *TOC*.
4. Ensure **Before _Content.fm** is selected from the **Add File** dropdown menu.
5. Go to the **Do not Include:** section and double-click **Heading 1**. This will move **Heading 1** to the **Include:** section.
6. Click **OK**. An **Update Book** dialog box will appear. Click **Update***.

> **NOTE:** If an Inconsistent Numbering Properties dialog box appears, click **Continue**.

The new TOC will be generated; however, the formatting is not fully initialized. Perform the following to import the proper format:

1. Go to the **File** dropdown menu, go to **Import**, and then select **Formats...**.
2. An **Import Formats** dialog box will appear. Select the **_TOC.fm** option from the **Import from Document** dropdown menu.
3. Uncheck the box next to **Variable Definitions** in the **Import and Update:** section. The **Import and Update:** section should appear as shown in the figure below.
 
![alt text](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/img/Import%20and%20Updates%20Section.png "Import and Update Section")

4. Once the **Import and Update:** section is properly populated, click **Import**. The template will be imported.
5. Click **Update Book** one last time so that the page number formatting will appear properly.
6. The new TOC has been created, delete the previous TOC with broken crossreferences.


> **NOTE:** Click [here](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/Chapter%204:%20Proofreading/Section%204:%20Content.md) to continue to the next section on proofreading the content section of your FrameMaker book. Or click [here](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/Chapter%204:%20Proofreading/READme.md) to return to the chapter overview.
