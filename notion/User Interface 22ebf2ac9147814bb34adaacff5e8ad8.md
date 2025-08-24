# User Interface

---

<aside>
📜 **TABLE OF CONTENTS**

- [**Introduction**](../Cadmium%20Technical%20Documentation%2022ebf2ac914780e38715f6f9f06d9432.md)
    - [About Cadmium](../Cadmium%20Technical%20Documentation%2022ebf2ac914780e38715f6f9f06d9432.md)
    - [Key Features](../Cadmium%20Technical%20Documentation%2022ebf2ac914780e38715f6f9f06d9432.md)
    - [Contacting Support](../Cadmium%20Technical%20Documentation%2022ebf2ac914780e38715f6f9f06d9432.md)

[Getting Started](Getting%20Started%2022ebf2ac9147815ea681d7184c0029b0.md)

- [User Interface](User%20Interface%2022ebf2ac9147814bb34adaacff5e8ad8.md)
    
    [User Interface](User%20Interface%2022ebf2ac9147814bb34adaacff5e8ad8.md)
    
    - [The Canvas](User%20Interface%2022ebf2ac9147814bb34adaacff5e8ad8.md)
    - [The Timeline](User%20Interface%2022ebf2ac9147814bb34adaacff5e8ad8.md)
    - [Key Frames](User%20Interface%2022ebf2ac9147814bb34adaacff5e8ad8.md)

[Importing Frames](Importing%20Frames%2022ebf2ac914781148e2efef468b66e13.md)

[Reference Frames](Reference%20Frames%2022ebf2ac9147811b93f3f52d4f96aefb.md)

[Analyzing Frames](Analyzing%20Frames%2022ebf2ac9147815d8274e3ee2004ffe0.md)

[The Line Colorization Menu](The%20Line%20Colorization%20Menu%2022ebf2ac914781829ec0c0d0a4deec5c.md)

[The Color Menu](The%20Color%20Menu%2022ebf2ac914781c7af45d71b6cc890b6.md)

[Colorizing](Colorizing%2022ebf2ac914781b595cccbef7aee6ce2.md)

[Drawing Tools](Drawing%20Tools%2022ebf2ac9147813c9bf6f7b901dbda0b.md)

[Editing Frames](Editing%20Frames%2022ebf2ac91478143b255da248016bf81.md)

[Exporting](Exporting%2022ebf2ac91478124ba83e5064ecc8c1b.md)

[Keyboard Shortcuts](Keyboard%20Shortcuts%2022ebf2ac914781a1a536ed6f8d9d1141.md)

[FAQ](FAQ%2022ebf2ac914781aa9fd7c05c7d0683c9.md)

[Change Log](Change%20Log%2022ebf2ac9147816e8718e9dade5087a0.md)

</aside>

# The Canvas

![image.png](User%20Interface%2022ebf2ac9147814bb34adaacff5e8ad8/image.png)

As soon as you have imported artwork into Cadmium, the canvas will become visible, displaying your artwork. There are a few tools associated with how you view the canvas that can be found in the sidebar on the left side of the application:

## Hand Tool

Like other drawing programs, the hand tool allows you to move around your canvas by left clicking and dragging. The shortcut to use the hand tool is  holding space bar.

## Zoom Tool

The Zoom tool zooms in and out (toggled by the option/alt button). You can also use the middle mouse scroll, or right click and drag to zoom in and out of the canvas.

# Eyedropper

The eye dropper tool allows you to sample any pixel color on the canvas. If a semi transparent pixel is sampled, the eyedropper will return the full color value of your pixel

By default, the background color of the canvas is white, but you are able to change that in the Color Menu.

# The Timeline

![image.png](User%20Interface%2022ebf2ac9147814bb34adaacff5e8ad8/image%201.png)

The timeline is a standard system within animation programs, and its primary purpose is to display graphical representations of your animation frames, and allows you to select, those frames, remove them, and go to different images. 

- The Timeline can be shown and collapsed by clicking the little arrow in the top left corner, or pressing T.
- Once you have imported images, your timeline will display the image size next to the collapsible arrow in the upper left corner.
- Hitting the play button in the left top corner of the timeline, or pressing enter will play through your sequence at 24 frames per second. If your sequence is large, it might play a bit slower, sorry about that.
- Hitting the left and right arrow buttons go to the previous or next frame.
- Above the frame zones, there is a numbered area that tells you what frame you are on. You can click and drag in this area to go to different frames.

## Layers

The timeline has two layers, one for color, and one for line work. When you start a new file, each layer has a drop zone where you can drag and drop images or image folders to begin to populate the timeline. 

## Layer Visibility

You can turn on and off the visibility of each layer by clicking the eyeball icon next to each layer. The visibility of these layers will correspond to how your images are exported. You can read more about that in the Exporting section.

## Selecting Layers

It is important to keep track of which layer is currently selected, as it will affect where drawing actions occur. If you click on the name of each layer, you can select them. holding shift + up or down arrows allows you to toggle this selection.

![image.png](User%20Interface%2022ebf2ac9147814bb34adaacff5e8ad8/image%202.png)

## Outlines Layer

This is where you will import your line images. Next to the line layer, you will notice a little star icon. This is a button that allows you to turn on an experimental feature involving line colorization, which you can read more about here…..

## Color Layer

Below the Outlines Layer is the color layer. this is where you will import or create reference frames, and also where your colorized images will populate. The diamond icon next to the visibility eye icon indicates a reference frame is selected. if the diamond is half filled, both a reference and a non reference are selected. clicking this button will toggle the selected frames as reference images.

For more information about working with frames in the timeline, see the section about Importing Frames.

## Key Frames

![image.png](User%20Interface%2022ebf2ac9147814bb34adaacff5e8ad8/image%203.png)

The Gray boxes on the timeline represent your sequence’s unique drawings, and how many frames they are held for. If you import duplicates of an image, Cadmium will recognize this and group the images together. The purple dots represent reference frames that will be used to determine how to color the selected frame. You can learn more about reference frames [here.](Reference%20Frames%2022ebf2ac9147811b93f3f52d4f96aefb.md)