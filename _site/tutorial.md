# Useful Resources
    - list of variables:
        - https://jekyllrb.com/docs/variables/
    - Control flow and structure
        - https://jekyllrb.com/docs/step-by-step/02-liquid/
    - Cheat sheet:
        - https://devhints.io/jekyll
    - Some additional tidbits
        - https://mademistakes.com/articles/using-jekyll-2016/
    - Markdwon syntax guide
        - https://www.markdownguide.org/basic-syntax/


# Main folders
    - _includes (IMP):
        - contains the general components for the layout of the the main website.
        - This has contents that are used across the webpages

    - _sass
        - It has all the main css and icons and formatting related information.
        - (IMP) /_sass/_layout.scss   Contains the CSS style for the website
        - (IMP) /_sass/_variables.scss   Important dimension and color info

    - _layouts (IMP):
        - 'default' is the base layout
        - All other layouts import default
        - It contains all the major layout for different possible types of webpages.

    - _posts:
        - (IMP) look at the example-content.md for lots of useful examples!!
        - The actual posts which are invoked by the files in _layouts.
        
    - _bibliography:
        - contains .bib files of all the publications
        - More info: 
            - https://github.com/inukshuk/jekyll-scholar
            - http://www.mghassany.com/blog/From-Wordpress-to-Jekyll/
            - https://gykovacsblog.wordpress.com/tag/jekyll-scholar/
    - _site:
        - Dont touch this. This is dynamically overwritten by jekyll

    - assets:
        - Ignore.

    - docs:
        - Contains all the additional documents.

    - images:
        - Contains all the images.

    - blog
        - _posts/ contain all the post with desired header/front-matter
        - if more flexibility is needed, look at "category" layout on https://fongandrew.github.io/hydeout/

# Main files
    - _config.yml (IMP):
        - The main config file for the website.
        - Restart jekyll serve after making any changes to this.

    - index.html:
        - The main landing page. Ignore this file and look at \_layouts\index.html

    - about.md:
        -

    - publications.md:
        -



