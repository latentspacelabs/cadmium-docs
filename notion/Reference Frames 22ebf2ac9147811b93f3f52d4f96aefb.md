# Reference Frames

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

## What is a reference frame?

In order for Cadmium to color your frames, we need an example of how the frames should be colored. Reference frames are denoted on the timeline with a purple dot. You can import one or multiple reference frames by dragging them onto the color layer. These reference frames must be numbered in order to appear in the correct position on the timeline. For example: "reference_04.png" will appear at frame 4. You can also color your own reference frames in Cadmium. 

## Preprocessing Color Frames

 Once you’ve selected or dragged your image to the color layer, Cadmium will first “preprocess” the color frame. If there is a corresponding line image, the line image will be used to define the color boundaries of your reference image, and the most prominent color in each segment will be filled in. Additionally your color palette will populate with all of the colors.

## Creating Color References

There are two ways to create color references: either by importing a frame, or by creating a frame in Cadmium. Any color frame that you import to the color layer or color manually becomes a reference frame. Right clicking on any color frame will allow you to change whether or not that frame is a reference.

## Reference Panel

If you have a style frame of how you want your character to look, but the frame is not part of your animation sequence, you can import it into the reference panel. The button to open the image is in the top right corner next to the help button.

![image.png](Reference%20Frames%2022ebf2ac9147811b93f3f52d4f96aefb/image.png)

To add images, press the plus icon in the LIBRARY drop down, and navigate to your file. You can import multiple style frames at once, selecting the filename that you want to view. You can zoom into the image either with the zoom tool, or by middle mouse scrolling. The eyedropper allows you to select colors from your reference image to apply to the canvas.