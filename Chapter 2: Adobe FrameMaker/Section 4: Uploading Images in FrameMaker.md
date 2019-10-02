# Uploading Images to a Work Instruction in FrameMaker

> **NOTE:** This section will provide details on adding images to Accuray work instruction in Adobe FrameMaker.

## An Overview of How Images in FrameMaker Operate

A notable (and beneficial!) difference between how images operate within Adobe FrameMaker vs. how images operate within Microsoft Word is that Adobe FrameMaker images are not directly embedded in the document itself. Whereas one can copy and paste an image into Word, FrameMaker is reliant on file pathways to present an image. This means that the images "present" within an Adobe FrameMaker work instruction exist in a file location outside of the document itself.

For each Adobe FrameMaker file bundle, a folder titled "Images" should be present. This will be the file pathway destination for all relevant images within the work instruction, and should be included with the final .zip file produced. 

While this may be a tad confusing for beginners, the benifets lie in file size reduction. Relying on file pathways removes clutter inside a FrameMaker file, making it less prone to crash (though, saving often is still recommended best practice, see [this section]() for more information on authoring best practices).

## Importing an Image into FrameMaker

### Image File Location

First, before an image can be imported into FrameMaker, it must be in the proper file location. If you haven't already, do the following:

1. Go to the location of your FrameMaker file bundle.
2. Create a new folder titled **Images**.
3. Import all images you desire to use for this work instruction into this folder.

> **NOTE:** In order to easily locate desired images, it is recommended to ensure each image file shares the same title as your **FigureCaption** description.

### Anchored Frames

Think of an **Anchored Frame** as the "window" through which images can be viewed. It acts as both the vessel through which a file can be called into the document and as a static text box. Once an image is called in through a **Anchored Frame**, it will not be able to be dragged out of it (the image will become cropped once it surpasses the boundaries of the **Anchored Frame**.

> **NOTE:** It is worth noting that there is not a limit to the number of images one can place inside a single **Anchored Frame**. Should the writer decide to include two (2) images side-by-side, they may upload both to the same **Anchored Frame** and adjust location as deemed necessary


