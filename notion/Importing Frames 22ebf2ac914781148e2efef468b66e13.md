# Importing Frames

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

# Importing Frames

In order to work in Cadmium, you will need to import frames. You can import to both the line layer, and the color layer. It is usually recommended to first import your line images to the line layer. 

### File Type

- Export your line frames from your animation software of choice. Make sure they are exported as PNG +alpha. Place your images in a unique 
folder and make sure the frames are numbered, starting with 1. ex: *"sharkdadLine_001.png".*
- For Pro users, we allow image sizes of up to 4HD (7680 x 4320 pixels or equivalent of any aspect ratio). The free tier is limited to HD (1920 x 1080).

## **Importing images to the Line Layer**

![image.png](Importing%20Frames%2022ebf2ac914781148e2efef468b66e13/image.png)

 Most often, you will want to start by importing frames to your line layer. In the menu, click File/Import/Line Layer. Or you can simply select a folder with your images, and drag the folder into the drop area on the timeline.

## **Importing images to the Color Layer**

Importing images to the Color Layer is primarily for the purpose of providing a reference for how Cadmium should color your frames. You can read more about reference Frames [here](Reference%20Frames%2022ebf2ac9147811b93f3f52d4f96aefb.md).

You are also able to import color images before line images. In this event, Cadmium will attempt to retroactively create a line image from your color frame. This is not commonly used, but some users have found it helpful to be able to manipulate the colors or export each color separately of an already colored sequence.

## **Importing images to the Reference Panel**

![image.png](Importing%20Frames%2022ebf2ac914781148e2efef468b66e13/image%201.png)

Sometimes you might have style frames of your animation frame that are not within your sequence, but you want to be able to reference the colors. You can import these images into the Reference Panel, which can be found in the top right corner. In the Library Drop down, click the + sign to add a reference image. you can middle mouse scroll to zoom in and out, or you can use the zoom tool. you can resize the panel window by hovering over the edges of the panel and dragging. You can select colors with the eyedropper tool as well.

## Duplicate Frames

 When you import a line or color image sequence that has multiple duplicates of images (which is quite often the case for cel animation to create the proper timing), Cadmium will recognize this and if they are concurrent frames, it will “de-duplicate” the images, extending the image for the amount of duplicate frames as one selectable block. In this way, Cadmium preserves your animation timing while simplifying the coloring process to avoid unnecessary work. 

If your sequence has duplicate images that are *not* next to each other (such as how a looping cycle might repeat frames), Cadmium will recognize these frames as “clones” of one another, and so whatever you do to one frame will be done to the other. Notice that selecting one of these frames will automatically select the others.

---