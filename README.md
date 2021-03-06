# WurstScript Webpage & Documentation

Live at https://wurstscript.github.io/

This folder contains the complete source of the WurstScript website, configured as jekyll project and deployed via github-pages.

The design is based on https://github.com/xriley/PrettyDocs-Theme

## Tutorials

Tutorials are included as part of the documentation in their own section.

To create a new tutorial:

* Create a new table of contents file in `_doc/tutorials/`, for example `cp wurstbeginner.md new_tutorial.md`.
* Create a new set of tuturial pages in `_doc/tutorials/` - e.g. `cp -r wurstbeginner new_tutorial`.
* Define the pages by changing the contents of `_doc/tutorials/new_tutorial/` - usually one or two markdown files will suffice.
* Add the new tutorial to the tutorials listing in `_doc/tutorials.md` - just need to add a uri in the `navigation` section.
* Setup `new_tutorial.md` as necessary for your pages:
    - Edit the title, excerpt, date, icon, color.
    - Change the `sections` to match the uri of the pages of your tutorial.
* Write your tutorial pages, being sure to update the heading sections as necessary.


## Serving the page locally:

1. Check whether you have Ruby 2.1.0 or higher installed:

    `ruby --version`

2. Install Bundler:

    `gem install bundler`

3. Execute `bundle install` in this repository.
4. Run the server with:

    `bundle exec jekyll serve`
