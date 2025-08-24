# Colorizing

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

# Colorizing Frames

![image.png](Colorizing%2022ebf2ac914781b595cccbef7aee6ce2/image.png)

Once you have your imported line sequence, and at least one color reference, you are ready to colorize. You can colorize a single frame, or multiple frames at once. Hitting the “Colorize” button with no frames selected will default to Colorizing the current frame that you are on. Or you can select other frames, or all frames to process. If multiple frames are selected to colorize, Cadmium will first use your reference image, but then subsequently will use the last colorized frame as a new reference image for the next frame. Because of this, unfortunately any errors in frames will compound, and your results might be less accurate as the sequence progresses. For this reason, we might suggest starting out by analyzing 1 or only a few frames at first to see how well everything performs. If there are any manual corrections to be made, we would recommend doing that before continuing with the coloring process. You can learn more about how edit your frames in the [Editing Frames](Editing%20Frames%2022ebf2ac91478143b255da248016bf81.md) section of this documentation.

# Which reference frames are being used?

![image.png](Colorizing%2022ebf2ac914781b595cccbef7aee6ce2/image%201.png)

The Timeline displays line connections that visually show which frame is being used to make predictions, and it will always be the reference frame closest to the current frame you are coloring. Unfortunately at this time, Cadmium is only able to use one reference frame per color prediction, but we hope to be able to expand this to all reference frames very soon.

Please Note: you cannot re-colorize an image that is marked as a reference frame. You must first make the frame a non reference frame or delete it.

[Analyzing](Colorizing%2022ebf2ac914781b595cccbef7aee6ce2/Analyzing%2022ebf2ac9147815592f3e095909aad9c.md)