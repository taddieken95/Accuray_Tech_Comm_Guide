# FrameMaker Authoring Interface

> **NOTE:** This section details the various features within Adobe FrameMaker, along with how to author using our unstructured (non-DITA/XML) template.

## Launching FrameMaker

To fully open a FrameMaker file, do the following:

1. Go to the desired FrameMaker file folder location.
2. Double-click the FrameMaker **.book** file. FrameMaker will open.
3. Go to the **Navigation Pane** on the left side of the FrameMaker interface. 
4. Double click each of the three (3) files listed below the **.book** file (**_TitlePage.fm**, **_TOC.fm**, and **_Content.fm**). Each of the three (3) files should now be open. Your interface should look similar to the image displayed below.

![alt text](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/img/FrameMaker%20Interface%20Example.png "FrameMaker Interface Example")

## Authoring Options - Paragraph Catalog

A floating side panel featuring the **Paragraph Catalog** should be present inside the FrameMaker interface. If this is not the case, perform the following:

1. Go to the **View** dropdown at the top of the screen.
2. Go to **Pods** then select **Paragraph Catalog**.
3. The sidepanel should now appear. It is likely that additional pods (such as **Variables**, **Character Designer**, and **Cross References**) will appear as well. Ignore these tabs for now and go to the **Paragraph Catalog** tab.

The final result should appear as shown **below**:

![alt text](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/img/Paragraph%20Catalog%20Tab.png "Paragraph Catalog Tab")

These options listed in the **Paragraph Catalog** pod are the different authoring text styles that come with the Accuray Manufacturing FrameMaker template. These, of course, can be stylistically modified through the **Character Designer** tab, but for the majority of work instructions, this list should contain all of the needed elements to producing robust documentation.

## Paragraph Catalog Functionality

The following table will provide an explanation for different features of the **Paragraph Catalog**.

|Paragraph Feature | Description | Ideal Usage|
|---------------------------|-------------|------------|
|**Heading 1**| Creates a section heading along with an ordered numerical value (1.0, 2.0, etc.). This will be automatically linked to the **Table of Contents** file.| Use to provide a title for each overall section. Each FrameMaker work instruction should have a minimum of one (1) **Heading 1**.|
|**Heading 2**| Creates a heading for a subsection. Will have a numeric value in the tenth decimal place (e.g. 1.1, 1.2, etc.) Barring special circumstances, subsection headings will not be featured in a **Table of Contents**. | Use to provide a title for a subsection. Subsections should likely be created in place of sections if ordered numerical list surpasses ten (10) steps.|
|**Heading 3**| Creates a subsection for a subsection. Will have a numeric value in the hundredth decimal place (e.g. 1.1.1, 1.1.2, etc.)| Use to provide a title for a subsection of a subsection. It is recommended to create one if content within a subsection surpasses ten (10) steps.|
|**Body Text**| Think of this authoring feature as your "standard." **Body Text** authoring allows the user to create unordered blocks of text.|  **Body Text** is often used in instances where step-by-step instructions are not required|
|**Step 1**| Initializes an ordered list. Further steps can be created by pressing **Enter** after Step 1 has been generated.| Use at the beginning of a section / subsection. Ordered steps will *NOT* automatically reset at 1 with each section. It must be manually entered.|
|**Steps**| Continues an ordered list.| As previously mentioned, ordered steps should be automatically entered after **Step 1** by pressing **Enter**.|
|**StepNoNum**| Creates an opportunity to produce text at the same indentation level of an ordered **Step** without continuing the ordering level| **StepNoNum** is best used with trying to separate two (2) or more sentences in a **Step** into separate lines. In this case, **StepNoNum** would be used on the second line, so that it does not separate this line into an additional **Step**.|
|**Sub Step_a**| Initializes an ordered list (level "a") within a step inside of an ordered list (substep)| Use when two (2) or more clarifying substeps are deemed necessary for a user to follow a step. |
|**Sub Steps**| Continues an ordered sublist| Use to continue a sublist after initializing it with **Sub Step_a**|
|**Bullet List**| Creates an unordered, bulleted list | Use for instances where further clarification is required, but order is not of importance. ***OR*** Use in place of steps when only an unordered list is deemed neccessary (such as an **Tools Required** list.|
|**Sq. Bullet List**| Use as an unordered sublist beneath a **Bullet List** or a **Sub Step**| Use when further clarification is required for an ordered sublist or an unordered list.|
|**FigureCaption**| Automatically creates a numerically ordered **Figure Number** along with space to create a descriptive caption of the **Figure** shown above | Use after every **Figure** added to the document. Captions are not required by FrameMaker but best practices would suggest providing a descriptive phrase to each image added. See [this section]() for more information on how to incorporate images into a work instruction.|

> To continue to the next section of this user guide, click [here]().

> To return to the main overview, click [here](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/README.md)
