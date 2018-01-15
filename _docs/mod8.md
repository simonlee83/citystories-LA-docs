---
title: "Module 8: Filling in the article data and content"
permalink: /docs/mod8/
---

Now that you have created your article Markdown file and uploaded some images, you are ready to begin filling in some of your article info. In addition to completing the frontmatter, you'll need to add and properly format your article text, images, and a bibliography. The following sections will show you how. 

#### Adding new content to your article
Whenever you want to add new content or edit your existing content, you'll need to use the **Edit** mode.
* Navigate to the `.md` file for your article in the `articles` directory.
* Click on the `.md` file to open it. - *Make sure you are opening and editing your group's article!*
* Click on the **pencil icon** in the top right of the file.
* Once you are in **Edit** mode, you can switch from "No wrap" to "**Soft wrap**" in the pull-down menu in the top right corner of the file area. This will wrap the text so you can see all your content in the window.
* Make any changes / additions to your `.md` file.
* When you are ready, scroll down to the bottom of the page, make sure "Commit directly to the gh-pages" branch is selected, then click on the "Commit changes" button.

#### Filling in the template
We are going to fill in some of your content here in class to get you started.

##### The Front matter
The first section is the front matter where we will put the metadata for our articles. (What's metadata?)
* `layout: post`-- Leave this as-is! 
* `title:` This is where you will put the title of your article. It's best if you enclose it in quotation marks. `title: "My article title"` 
    * Also, make sure your title isn't the same as an article title from a previous class.
* `date:` Enter the date in machine-readable format (YYYY-MM-DD), for example `date: 2018-03-12`
* `categories:` List your category here, all lower-case, enclosed in quotes, inside square brackets, ex. `categories: ["politics and society"]`
* `author:` List the names of the authors here, separated by commas. Enclose the whole thing in quotes: `author: "Dawn, Niqui, Andy"`
    * You can use for full name, first name and last initial or first initial and lastname, or you can use "Anonymous."
* `lat:` and `lng:` This is where we'll put our geo-coordinates. We'll get to this in a bit.
* `collectiontitle:` Put the name of the collection that your object(s) are from here. Use the format recommended by the Curator. Enlcose the whole statement in quotes.
* `quarter:` List the current academic quarter here. Example: `quarter: Winter 2018`
* `desc:` This is for a short description of the place. It will display on the map popup. Limit this to **no more than 320 characters**.

<script src="https://gist.github.com/kirschbombe/48024b54c2ae787093dabdeae7a986aa.js"></script>

_Now, let's save our changes and check out the live page again to see the info we just added._ Remember, you may need to clear your browser's cache or try opening in a new browser to see your changes.

##### Images

_This step requires the information you gathered earlier in the Image Worksheet._

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

##### Bibliography
* Next, we'll add the citation(s) for the archival objects we will be writing about. You should already have this information in your Image Worksheet from your archives and special collections visit.
* Using MLA format, add your first citation as a numbered item (1.) just under the `{:.bibliography}` tag (no extra lines!).

{need new gist}

* Once you have more items for your bibliography, enter each item as a numbered list item. Be sure to put your citations in alphabetical order by author or, if no author, by title.

_Now, let's save our changes again and check out the live page again to see the info we just added._ Remember, you may need to [clear your browser's cache](../content/browser_cache.html) or try opening in a new browser to see your changes.
