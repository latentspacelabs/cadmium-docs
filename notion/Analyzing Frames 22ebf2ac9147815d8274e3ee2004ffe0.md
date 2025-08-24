# Analyzing Frames

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

# Analyzing Frames

Analyzation is a crucial step in the coloring process. In order for Cadmium to infer predictions about how to color frames, the images need to be interpreted as multiple regions or “segments” within an image. Comparing these segments in the reference image with the segments in the target image is the basis for Cadmium’s color predictions. If you’re curious to know more about the technical details of how this is done, **here** is a link to a research paper published by one of our founders, Evan Casey.

# When does this happen:

Whenever you have a line frame with no corresponding imported color frame, this frame will need to be analyzed. Analyzation will occur when you press the “Analyze” button on whatever frame you are currently on, or whichever frames you have selected. It is automatically triggered when you hit the Colorize button, but it is often helpful at first to only analyze the image in order to get a sense of how your artwork is being interpreted. It can be helpful to see where there might be gaps in your art, and it saves you time and credits. Cadmium will remember and save a copy of your analyzed segment map, but if the line image is alterered, or if the analyzation settings are changed, a new segmentation map will be needed.

# Analyzing Settings Panel

As to exactly how the image is segmented depends on how the line image is interpreted.  You can adjust various settings with the **Analyze Settings panel**  in the upper right hand corner of the screen:

![image.png](Analyzing%20Frames%2022ebf2ac9147815d8274e3ee2004ffe0/image.png)

---

- Threshold Settings determine how opaque a line image pixel needs to be in order for it to be considered as part of a segment’s boundary. By default, this is set to Auto, which relies on **this** algorithm in order to alter the brightness and contrast of various pixels in your image. Manual allows you to set a thresholding alpha value between 0 and 255. A higher value will include more semi transparent pixels, and a lower value will exclude more.
- Gap Closing, like many animation programs, determines the size of a gap between pixels to be considered closed. We use an algorithm based on the Trapped Ball algorithm, adapted from this methodology **here.**
- Minimum Segment Size determines the smallest amount of pixels allowed in any individual segment. Any segment found with a lower amount of pixels in its area will be dissolved and combined into a neighboring segment. This can be useful if the particular line quality is more charcoal like and creates lots of small unintended segments within the line work.
- Rainbow Return is on by default, and when the “Analyze” button is pressed, each segment will be colored a different random color. This can be helpful to very quickly find gaps. But beware it will replace any colors frames you may already have, so in some cases you might want to turn it off.

After this step, you are able to colorize your Frames…

[Analyzing](Analyzing%20Frames%2022ebf2ac9147815d8274e3ee2004ffe0/Analyzing%2022ebf2ac9147812c84cde6511a502316.md)