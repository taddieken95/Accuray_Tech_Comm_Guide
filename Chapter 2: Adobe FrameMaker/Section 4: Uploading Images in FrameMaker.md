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

> **NOTE:** It is worth noting that there is not a limit to the number of images one can place inside a single **Anchored Frame**. Should the writer decide to include two (2) images side-by-side, they may upload both inside the same **Anchored Frame** and adjust location as deemed necessary

To create an **Anchored Frame**, perform the following:

1. Place the cursor in the desired location within the document (ensure you are authoring within the **Body Text** style).
2. Go to the **Insert** dropdown at the top of the screen.
3. Click **Anchored Frame...**. A new **Anchored Frame** window should appear on your screen (see figure below).

![alt text](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/img/Anchored%20Frame%20Window.png "Anchored Frame Window")

4. Ensure proper alignment is set inside the window (it is advised to have it set to **Center**).
5. Click the **New Frame** button. An **Anchored Frame** should now appear. Adjust to desired size by dragging relevant sides to length.

![alt text](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/img/Anchored%20Frame%20Example.png "Anchored Frame Example")

You have now successfully created an **Anchored Frame**. Next we look at importing images into an **Anchored Frame**.

### Importing Images

To import an image into an **Anchored Frame**, perform the following:

1. Select the **Anchored Frame** with your cursor.
2. Go to the **Insert** dropdown menu at the top of the screen.
3. Select **Image..**. An Alert will appear stating, *This operation doesn't have undo support, you will not be able to revert. Do you want to continue?*, select **OK**.
4. A File Explorer window will appear. Go to the previously created images folder for this work instruction. Select the desired image and click **Insert**. The image will now be present inside the **Anchored Frame**.
5. Adjust the image size by clicking the image and going to the **Object Properties** pod (this should be in the same window as the **Paragraph Catalog** pod). File size is adjusted in the **DPI** input section.

> **NOTE:** The recommended DPI for an image is 150. However, certain images may be too large for this to function successfully, adjust DPI as needed (the larger the DPI, the higher the resolution and smaller the image).

### Figure Captioning

A **Figure Caption** should be present beneath each image in an Adobe FrameMaker work instruction. **Figure Captions** allow for easy and organized cross-references, along with providing more context for the reader. To create a **Figure Caption**, perform the following:

1. Place your cursor immediately below the **Anchored Frame**.
2. Go to the **Paragraph Catalog** pod and select **FigureCaption**. A numbered **Figure Caption** will appear below your image.

![alt text](https://github.com/taddieken95/Accuray_Tech_Comm_Guide/blob/master/img/Figure%20Caption%20Example.png "Figure Caption Example")

3. Provide a description to further contextualize the image for the reader (it is recommended that the **Figure Caption** description and the file name of the image be the same).

> **NOTE:** See [this section]() for further information on generating cross-references to **Figure Captions**
