Image transformation may need to happen for many reasons, to make files
more accessible to the scientific community, to avoid the necessity of
using licensed software, or to fit community standards. Let’s dive
deeper into what happens each time you transform an image. What changes
about the details of the data? What is lost? What is gained?

1.  Download ImageJ (Fiji)
    > <img src="media/image1.png" style="width:0.20833in;height:0.20833in" />-
    > [<u>https://imagej.net/software/fiji/</u>](https://imagej.net/software/fiji/)

    - Fiji is an image processing package—a “batteries-included”
      > distribution of ImageJ2, bundling a lot of plugins that
      > facilitate scientific image analysis.

    - When opened, Fiji should look something like this:

<img src="media/image2.png" style="width:6.4375in;height:0.9375in" />

2.  File -\> Open

    - Select the file to open, we will use the image TXM.tif from the
      > dataset https://doi.org/10.7302/day1-6d63

3.  This image is a TIFF z-stack, and you can view images by using the
    > scroll bar at the bottom. The image within the stack you are
    > currently viewing is in the top left corner. (ex. 84/1020)

4.  In the metadata, it states “<span class="mark">It is recommended
    > that the raw images initially be normalized to narrow the range of
    > grayscale intensities before any segmentation. This will help
    > reduce the high brightness on first opening.”. So let’s adjust the
    > brightness and contrast of the image</span>

    - <span class="mark">Select the image</span>

    - <span class="mark">In the top tool bar select Image -\> Adjust -\>
      > Brightness/Contrast…</span>

    - <span class="mark">Click Auto to automatically adjust the
      > brightness and contrast</span>

    - <span class="mark">Close the B&C window</span>

5.  To convert the file from a TIFF to a JPEG, select File -\> Save As
    > -\> Jpeg…

6.  Let’s take a look at what changes with this conversion. Open the
    > Jpeg file with File -\> Open…

    - First, we can see this is no longer an image stack, only the image
      > from the stack we were looking at when the file was exported was
      > saved

7.  Let’s export the stack of interest to compare. Select the original
    > tiff file: Image \> Stacks \> Tools \> Make substack…

    - Enter the number of the image of interest

8.  For each of our images, select/highlight the image of interest and
    > then open the metadata for each image by selecting Image -\> Show
    > Info…

9.  We can see that one major change is that the pixel size has changed
    > between the jpeg and tiff file. What other changes happened when
    > the image was transformed?

10. At a glance, the images may appear to be the same, but when we zoom
    > in far enough, there are features that can be lost. Zoom in by
    > selecting the magnifying on the tool bar and selecting the area on
    > the image to zoom in.

<img src="media/image3.png" style="width:6.5in;height:0.98611in" />

Additional Resources:

See Cornell’s list of preservation format recommendations:
[<u>http://guides.library.cornell.edu/ecommons/formats</u>](http://guides.library.cornell.edu/ecommons/formats)

Library of Congress - Sustainability of Digital Formats:

[<u>https://www.loc.gov/preservation/digital/formats/content/still.shtml</u>](https://www.loc.gov/preservation/digital/formats/content/still.shtml)
