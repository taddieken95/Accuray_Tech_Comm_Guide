# FrameMaker Files and File Functionality

> **NOTE:** This section provides information regarding how Adobe FrameMaker files operate and function within Accuray Incorporated.

## Structure of FrameMaker File

Accuray's manufacturing work instructions are generated via FrameMaker books. A FrameMaker book is a collective body of individual FrameMaker files. The appeal to this, is the ability to separate sections / chapters of a publication into files that can be easily moved around to different locations within that publication. 

In the context of manufacturing work instructions, a standard FrameMaker book will contain three (3) files:

* **Title Page**
* **Table of Contents**
* **Content**

### Title Page

As mentioned above, the first of the three (3) files is the Title Page. See the table below for descriptions of all the features present in an Accuray Manufacturing work instruction.

| Feature       | Description                                 |
|---------------|---------------------------------------------|
|**Title**| The title of the work instruction. Displayed at the top-right corner of the title page|
|**Document Number**|The specialized number for locating the document in Agile. See [this article] for information on how to assign a number.|
|**Revision Table**|A brief outline of each prior revision, consisting of the **Revision Letter**, **Date of Release**, **Description of Change**, and the **Originator(s)**.|
|**Revision Letter**|Labeled as **Rev** in the table, this informs the reader as to when a particular version was released. **Revision Letters** begin at A.|
|**Date of Release**|The date the revision was released in Agile. The most recent revision should say *See Agile*, as the technical writer will not be able to predict which date it will be officially released in Agile.|
|**Description of Change**|A brief, 1-2 sentence summary of the change being made. Rev. A should say *Initial Release*|
|**Originator(s)**| The first initial and last name of the SME(s) & technical writer(s) involved with a stage of release|
|**Materials Required** (optional)|A separate (optional) table below the **Revision Table** that lists the tools and materials involved in performing a work instruction.| 
|**Reference Work Instructions** (optional)|A separate (optional) table below the **Revision Table** (and the **Reference Table**, if present) that lists any corresponding work instructions or SOPs.|

Upon completion, a finished Title Page should appear as shown in the image below.

![alt text](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/img/Title%20Page%20Example.png "Title Page Example")

The file name for the **Title Page** will be *(insert document number)_TitlePage.fm* (*ex: **T-MFG-R2000_TitlePage.fm***)

### Table of Contents

The second of the three (3) files is the **Table of Contents**. The **Table of Contents** (also referred to as the **TOC**) is automatically linked to any primary headings throughout the document. See [this article] for information regarding generating / troubleshooting FrameMaker TOCs. 

The file name for the **Table of Contents** will be *(insert document number)_TOC.fm* (*ex: **T-MFG-R2000_TOC.fm***)

### Content
