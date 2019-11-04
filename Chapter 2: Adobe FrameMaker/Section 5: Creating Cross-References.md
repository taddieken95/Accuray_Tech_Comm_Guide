# Cross-References

> This section will provide an overview of creating Cross-References within Adobe FrameMaker. 

## What are Cross-References?

A **cross-reference** is a piece of text that is linked to another element within a document (such as a **Figure Caption**, **Heading**, **Step Number**, etc.). 

Creating **cross-references** is recommended best practice for any instance of referring to an element that could change orders in future revisions, as the **cross-reference** will automatically update should the linked element change.

## Creating Cross-References

To create a **cross-reference**, perform the following:

1. Place your cursor at the desired location for the **cross-reference** within the document.
2. Go to the **cross-reference** pod in the floating side panel (the same side panel with the **Paragraph** and **Object Properties** pods).

> **NOTE:** If the **cross-reference** pod is not currently displayed, go to **View**, **Pods**, then click **cross-references...** The **cross-reference** pod should appear.

3. Select **Paragraph** from the **Source Type:** dropdown menu in the **Cross-Reference** pod.
4. Select the appropriate attribute for the content you are trying to establish a **Cross-Reference** to (**FigureCaption**, **Heading 1**, **Steps**, etc).
5. Ensure the proper format is selected from the **Format:** dropdown menu.

> **NOTE:** The format is dependent on the attribute. It is advised to use the **FigureCaption** format for **FigureCaption** Paragraph Tabs, **Heading** for section heading Paragraph Tabs, etc.

6. Click **Insert**. The appropriate **cross-reference** should now appear.

As mentioned previously, the **cross-reference** will now be updated should the linked attribute change. In order to update, click the **Update Book** button in the FrameMaker file panel.

Should an attribute that a **cross-reference** is linked to be deleted, an error will occur when updating the book. Be sure to delete any **cross-references** attached to content being deleted.

* **

> Click [here](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/Chapter%202:%20Adobe%20FrameMaker/Section%206:%20Exporting%20to%20PDF.md) to continue to the next section regarding the PDF creation process, or click [here](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/tree/master/Chapter%202:%20Adobe%20FrameMaker) to return to the chapter overview.
