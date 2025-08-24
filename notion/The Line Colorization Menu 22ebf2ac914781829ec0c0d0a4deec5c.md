# The Line Colorization Menu

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

The Line Colorization is a more experimental feature of Cadmium, and it was created to enable automatic coloring of line work, similar to a program like PaintMan. If your linework has different colors to indicate different colors for the line to be changed to, then this feature might be helpful for you.

To access the line colorization feature, press the button located in the upper right corner: 

![image.png](The%20Line%20Colorization%20Menu%2022ebf2ac914781829ec0c0d0a4deec5c/image.png)

The first toggle button will enable this feature, and also the star-like button to the right of the Outlines Layer name will do the same:

![image.png](The%20Line%20Colorization%20Menu%2022ebf2ac914781829ec0c0d0a4deec5c/image%201.png)

Notice that when the feature is turned on, a third set of frames above your line frames will appear on the timeline:

![image.png](The%20Line%20Colorization%20Menu%2022ebf2ac914781829ec0c0d0a4deec5c/image%202.png)

When in “EL” (Enhanced Line) mode, any actions done on the line layer will be on the Enhanced Line layer. You can use the pen tool to manually color your lines new colors. (Note that the pen tool only allows you to draw “within” on the EL layer.) If you use the fill tool on the EL layer, then the line work surrounding the segment you are filling will be filled with your currently selected color.

You can draw over any existing line that matches the color within your Enhanced Line Color palette.  By default, Red, Green and Blue are selected, but you can add other colors, or temporarily disable any by pressing these icons: 

![image.png](The%20Line%20Colorization%20Menu%2022ebf2ac914781829ec0c0d0a4deec5c/image%203.png)

So for instance: if your line work is red and black, and only red is in your EL palette, then you will only be able to edit the red lines. To edit the black lines, add the color black to your EL palette. If the EL layer is activated, you can turn off your normal line layer by pressing the eye button next to the layer as before. This might be helpful to get a sense of what is being edited on the EL layer vs the normal line layer.

## Extracting Lines from color frame on Import

If the last toggle button in the menu is on, you are able to extract EL line colors from a color image for reference. Here’s how: 

1. import your line images first as you normally would. 
2. Enable Line Colorization, and also enable the “Extract Lines From Color On Import” button.
3. import a color image that contains colored line work how you want the final image to look.

What should happen is your colored line work will appear on the EL layer, separated from your normal line work, and your color image, which will perfectly separate the colors. You also don’t need to manually add your EL colors to your EL palette, Cadmium will be able to figure this out for you.

## Colorizing Line work

You are able to automatically colorize line work as you normally would for colorizing fills. If the EL layer is activated, whenever you colorize a frame, Cadmium will also process the line work. You might need to be a little more patient, as this can take a bit longer, depending on the complexity of your image. Also note that if you color line work around a segment, and that line work is continuous and the same color with other lines, that will be filled as well. At this time, your initial line work will need to have a color change in order for Cadmium to know where to stop coloring.