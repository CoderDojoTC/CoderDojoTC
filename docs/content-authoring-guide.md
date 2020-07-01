We use [Markdown](https://en.wikipedia.org/wiki/Markdown) for all our content.  A good way to learn Markdown is to use a [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/).  We want you to put many images into
your classes so make sure to use the image links!

We use [GitHub](https://github.com/) to store our content.  GitHub is free for all public content and has many advanced features that allow team to work together to build and test learning content.  Many of our
content authors are familiar with GitHub.

We use [GitHub Pages](https://pages.github.com/) to publish our content to microsites.  Each coding group has their own microsite and search does not currently work across the microsites (we are working on fixing this). All content should be published into a gh-deploy branch.  If you change content using the web-based editor (the pencil in the upper right
corner of the github page viewer - you may need to have a friend help republish the content to the GitHub Pages site.)

We use [mkdocs](https://www.mkdocs.org/) for our publishing tool.  To deploy mkdocs you will need to have python installed on your local computer.  You must run the "mkdocs gh-deploy" command every time you make changes.

We use the [mkdocs material theme](https://squidfunk.github.io/mkdocs-material/).  We encourage you to learn to add custom material widgets to your content.

We use [CoderDojo style guide](https://company-51033.frontify.com/d/E6KNDhunr9mR/coderdojo-style-guide-1460385526) for our colors, icons and fonts.  Please try to stay close to these guidelines so that mentors, parents, and students
all know they are on a kid-safe site.

Try to avoid links to resources that are not kid-safe.

By using these standards it will enable us to reuse this content for search, recommendation and building tools that allow students to use chatbots to help them code.

## Images
All images should be stored in the doc/img directory in your site.  Please keep images reasonably small (under 50K) to keep the load times fast.

## Navigation
Make sure when you add a new content file you link it into the navigation menu.  Try to keep navigation lists under 30 items.  Try using nesting if your lists get too long.

## Mkdocs commands
There are only four mkdocs commands.  You will rarely need to use the new command.

#### **mkdocs build**
Build the MkDocs documentation.  We use this to test at the nav pages all match a document.
If you get error messages in the build process you work on fixing them until the build
does not return any errors.

#### **mkdocs gh-deploy**
Deploy your documentation to GitHub Pages.  Run this when you want to take your local changes and push them to the web site.

Here is an example of this run:

```sh
$ mkdocs gh-deploy
INFO    -  Cleaning site directory 
INFO    -  Building documentation to directory: /Users/dmccrea1/Documents/ws/CoderDojoTC/site 
INFO    -  Documentation built in 0.90 seconds 
INFO    -  Copying '/Users/dmccrea1/Documents/ws/CoderDojoTC/site' to 'gh-pages' branch and pushing to GitHub. 
INFO    -  Your documentation should shortly be available at: https://CoderDojoTC.github.io/CoderDojoTC/ ```

#### **mkdocs new**
Create a new MkDocs project.  Most of our mentors will not need to do this.  We will supply you with a template zip file with all the right content if you need to create a new CoderDojo microsite of your own.

#### **mkdocs serve**
Run the builtin development server and display the web site on your local computer.  This is a great way to quickly check your changes since the server watches for any file changes and immediately updates the web page.

## Material examples

We chose the Google Material theme because there are tens of thousands of components you can add to your pages.  You can get a sample of them here:

[Material Components](https://material.io/components)