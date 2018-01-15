---
title: "Module 7: Adding images"
permalink: /docs/mod7/
---

#### Step 1: Upload your images
* The project images are hosted in our GitHub repository in the `images` folder.
* To upload your images there are two methods:
    * Navigate to the `images` folder, then drag and drop the images directly onto the page. If necessary, add additional images.
    * Once you've added all your images, scroll down to the bottom of the page, make sure "Commit directly to the `gh-pages` branch" is selected, then click on the green "Commit changes" button.  <br />--Or--<br />
    * From the `images` directory, you can select the "Upload Files" button, then continue as directed above.
![](https://img.labnol.org/di/upload-files.png)
* Navigate back to your `images` folder to verify that your new images are there and that you can view them.

#### Step 2: Adding the images to your article
Now that your images are uploaded, let's return to your article Markdown file and add the information about the images so they display.

_This is all the information you gathered earlier in the Image Worksheet._

A complete image will look like this in your Markdown file:

<script src="https://gist.github.com/kirschbombe/824930bbe036dec9b40ff08943cb9500.js"></script>

The first part contains the Alt-Text followed and the image path:
* Alt-Text is surrounded by square brackets `[]`
* The image path will be `images/[filename].jpg` - inserting the name of the image file in place of `[filename]`
* Notice there is no space between the Alt-Text and the image path segments
* On the next line, add the tag `{:.image}` - this is important! This makes the Lightbox feature work.

The second part contains the title and attribution statemtment:
* List the title first, followed by a period `.`
* Follow this with the attribution statement.
    * The attribution statement should contain the creator and date, if known, followed by a statement like "Image courtesy of UCLA Library Special Collections." If you visited a library unit other than the UCLA Library Special Collections (for example, the Chicano Studies Research Center), use their name in place of "UCLA Library Special Collections."
* On the next line, ad the `{:.caption}` tag - this is import to format the caption properly!

Repeat for each image.

Once you've completed these steps and have verified that your site loads with your new images, submit a new Pull Request.
