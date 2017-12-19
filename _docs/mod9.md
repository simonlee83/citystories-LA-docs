---
title: "Module 9: Adding images"
permalink: /docs/mod9/
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

* A URL (`<graphic url="../images/academyawards.jpg"/>`)
    * Since our images are in a sub-directory named `images`, we're going to use a _relative link_ to point to the image. The relative link to our images directory is `images/[imagefilename.jpg]`. So, if we have an image named `image1.jpg`, the relative link to the image will be `images/image1.jpg`.
* Title and Attribution statement, `Title. Creator, date. Image courtesy of ...`
    * In this section, add the creator and date, if known. This should be followed by a statement like "Image courtesy of UCLA Library Special Collections." If you visited a library unit other than the UCLA Library Special Collections (for example, the Chicano Studies Research Center), use their name in place of "UCLA Library Special Collections."
* Alt-text for screen readers
* `{:.image} tag - 

Once you've completed these steps and have verified that your site loads with your new images, submit a new [Pull Request](https://kirschbombe.gitbooks.io/citystories-la/content/module08.html).
