---
title: "Module 6: Prepping your article stub"
permalink: /docs/mod6/
---

#### Create your article file
* 

#### Previewing your article stub
* To view your article stub, visit the live project site for your repository.
* Once there, click on the "hamburger" menu to expand and hover over "Articles". The first articles listed should have the name "[Article title]". You can click on any one of these to see how the template for your article looks.
* Take a look at the various sections and notice the placeholder text in "[ ]" -- these are text areas that you will complete as you work on your articles.

####Locating your article stub `.xml` file and making your first edits
* In your GitHub `lyricalmap` repository [githubusername / lyricalmap], navigate to the `articles` directory.
* In this directory you will find some .xml files named `f16_01.xml`, `f16_02.xml`, etc. These files serve as the templates for your articles. Click on the one that corresponds to your quarter and group number (f16 is the Fall 2016 quarter, 01 is group 1).
* We'll look at this in more detail shortly, but you might notice that the major sections of this .xml file correspond to the published article stub we just looked at. Let's make our first edits in this file.
* In the top right corner of the file, look for the pencil icon. Click this to edit the file. ![](https://help.github.com/assets/images/help/repository/edit-file-edit-button.png)
* While we're in edit mode, let's give the article a proper title. Look at the file around line 9. See where is says [Article title] in between the `<title>` tags? Let's replace this text _and the brackets_ with the title of your article. You can always change this later if you decide, so don't worry if it's not perfect.

{% gist id="https://gist.github.com/kirschbombe/b32bae349d186cfdd7e7" %}{% endgist %}

{% gist id="https://gist.github.com/kirschbombe/78b0aa0e99f734f2de56" %}{% endgist %}

* Scroll down to bottom of the page, make sure "**Commit directly to the `gh-pages` branch**" option is selected, then click on the "**Commit changes**" button.

####View your site with your new article title
* Return to the live project site again. Does your site load?
* Now click on the "hamburger" menu near the top of the page, hover over the "Articles" menu item, and make sure your article is listed there (it should now be the new article title that you entered into the `<title>` element). Go ahead and click on it to make sure it displays. If you don't see the changes, you may need to [clear your browser's cache](../content/browser_cache.html) or open in a new browser.
