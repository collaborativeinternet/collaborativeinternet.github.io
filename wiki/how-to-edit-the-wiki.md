---
published: false
layout: default
---

## How to Edit This Wiki

This wiki is hosted on [GitHub Pages](http://pages.github.com) and uses [Prose](http://prose.io) as a simple editor. GitHub Pages publishes [Markdown](http://daringfireball.net/projects/markdown/) to HTML using the [Jekyll](http://jekyllrb.com/) engine. This gives us a light-weight wiki application, with all of the collaborative editing features of Git and GitHub. 

### Editing a Page

1. Click on "Edit this page" on the left
2. Prose will ask you to authorize on GitHub. If you already have a GitHub account, sign in. Otherwise create a new one.
3. Do your thing
4. Preview your changes by clicking on the eye icon on the right
5. Save your changes by clicking the disk icon on the right

When you edit a page, Prose will clone this website into your GitHub account, save your changes there, and send a pull request. If you want to make a bunch of changes, contact us and we'll add you as a collaborator so you can just get down to it.

### Creating a New Page

1. Click on "Create a new page" on the left
2. Change the name of the file. It will start with something like  
   `2013-07-29-your-filename.md`. Change that to what you want (without 
   the date... unless you really want it).   
3. **IMPORTANT**: Click on the "Meta Data" icon on the right and enter  
   `layout: default`. If you miss this step your page won't show up correctly. 
   You can always go back if you forget...
4. Save your changes by clicking the disk icon on the right

### Linking Between Pages

Links are made using the standard Markdown link syntax. So to link to this page, you'd enter

    [How to Edit This Wiki](/wiki/how-to-edit-the-wiki.html)

Note that the name of the file in the link, as well as in the browser, ends with `.html`, while the file you edit ends in `.md`. That's Jekyll converting Markdown to HTML.

### Gotchas

- Prose is good at many things, but if you start clicking around on the dropdown menu on the left it *will* lose any unsaved changes. Save early and save often, just to be sure!