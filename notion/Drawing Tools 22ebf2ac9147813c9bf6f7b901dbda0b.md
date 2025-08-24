# Drawing Tools

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

# Pen/Eraser Tool

![image.png](Drawing%20Tools%2022ebf2ac9147813c9bf6f7b901dbda0b/image.png)

- The Pen/Eraser Tool is toggled by hitting alt or option.
- The Pen size can be adjusted with the slider, or when the pen tool is selected, but holding ‘control,’ and right click dragging left or right.
- The pressure sensitivity can be turned on and off as well from this panel.

## Draw Options

There are also a few different drawing modes, ‘over’ performs like normal where new lines are drawn over old ones, ‘under’ draws under any existing pixels, and within is confined to only the existing pixels.

# Eraser Tool

![image.png](Drawing%20Tools%2022ebf2ac9147813c9bf6f7b901dbda0b/image%201.png)

There is also a dedicated eraser tool, in case you want to have a different size eraser from your pen.

# Common Uses For Pen and Eraser Tool

After analyzing your frames, you may find some gaps in your linework. In addition to adjusting the [Analyze Settings](Analyzing%20Frames%2022ebf2ac9147815d8274e3ee2004ffe0.md), you can use the Pen/Eraser tool to make any manual adjustments.  You can also use the Pen Tool on the Color layer to make any small tweaks to frames. At the time of this writing, drawing on the color layer does not update the segmentation mask, and so any manual changes might not remain upon repeat colorizations. 

# Fill Tool

![image.png](Drawing%20Tools%2022ebf2ac9147813c9bf6f7b901dbda0b/image%202.png)

Regardless of what layer is selected, the fill tool will always fill on the color layer. The Fill tool corresponds to the segment map of each image, and any changes that you make with this tool will always propogate to other frames, if used as a reference tool.

# Eyedropper

The eye dropper tool has no settings, and functions like any other eyedropper. Any color on the canvas is selectable. holding shift is the shortcut to eyedrop while using another tool. 

![image.png](Drawing%20Tools%2022ebf2ac9147813c9bf6f7b901dbda0b/image%203.png)