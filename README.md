## 网上的一个_config.yml文件

# Name of your blog (this will show up at the top of your page and in the RSS feed)
name: Sample Jekyll Blog

# Short description (goes below the title; it will also be used in the RSS feed)
description: This is a sample Jekyll Blog.

# Your name, as you want it to appear underneath each post and in the footer
author: Your Name

# Your email if you want it to be linked on the contact page
author_email: you@example.com

# The directory for category index pages. Change it to something else if
# for example you want links like /categories/category1 instead of /category1
category_dir: /

# Uncomment if you are planning to run the blog in a subdirectory
# Note - if you enable this, and attempt to view your site locally you have to use the baseurl in your local path.
# Example, you must use http://localhost:4000/path/to/blog
#baseurl: /path/to/blog
baseurl:

# The URL of your actual domain. This will be used to make absolute links in the RSS feed.
url: http://yourdomain.com/

#### Under the Hood Stuff #####

# Use rdiscount as the markdown engine because it generates html5 compliant code for stuff like footnotes
# If you use maroku (default engine) some of your generated pages may not validate or lint as html5
# If you don't have it install it via gem install rdiscount
markdown: rdiscount

# Makes pretty (descriptive) permalinks. See Jekyll docs for alternatives.
permalink: pretty

# How many articles do you wish to appear on the front page:
paginate: 3

# Exclude metadata and development time dependencies (like Grunt plugins)
exclude: [README.markdown, package.json, grunt.js, Gruntfile.js, Gruntfile.coffee, node_modules]



sdfsdfs
