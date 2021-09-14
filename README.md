# Peder Larson Research Lab Website (BETA)

Building off the Mediumish theme, which I think is used by https://github.com/qMRLab/qmrlab.github.io

## How to add new posts?

### 1) Add author information to the _config.yml file.

Please add an entry in this file (under the 'authors' field) to link your name and GitHub account (along with additional information). For example:

```
nickname:
  name: Jon Doe
  display_name: Jonny Doe
  email: jonny@gmail.com
  git_name: jodoe
  web: http://jondoe.com
  twitter: https://twitter.com/jodoe
  description: `Interested in qMRI. He is a coffee master ....`
```
* `name`: Self-explanatory
* `nickname`: Displayed under your profile photo in a blog post. Please keep it short (due to layout concerns).
* `github`: Your GitHubhandle. *Required*
* `twitter`: (Optional) Your twitter handle. A link will appear under your image in a blog post.
* `website`: (Optional) A link to your personal website (or other). A link will appear under your image in a blog post.

### 2) Creating a new post

All blog posts that are written in markdown language are stored in `_posts` directory.
Please respect the following convention for naming of the markdown files:

`YYYY-MM-DD-the_name_oft_the_file.md`

All `.md` posts must start with the following snippet:

```
---
layout: post
title:  "The title of the post"
author: Author's_Nickname
categories: [ jekyll ]
image: assets/images/image_name.png
featured: false
hidden: false
---

```

* `title` is the title of the post.
* `author`  is the nickname of the author (see previous step).
* `image` is the link to the featured image (e.g. assets/images/foo.png).  
* The `featured` and `hidden` takes boolean inputs (true/false) to set the visibility of the post and that of the featured image, respectively.

* IMPORTANT NOTE: Please avoid modifications to the layout of the snippet. The `categories` tag should always contain the '[ jekyll ]' entry.


After completing these steps, you can start creating the body your post.

* NOTE: As stated above, posts should be written in markdown language.
Once you are done with creating the post, please save it in the '_posts' folder by following the naming convention described above. Commit your changes and make a pull request.


## Mediumish - Jekyll Theme

[Live Demo](https://wowthemesnet.github.io/mediumish-theme-jekyll/) &nbsp; | &nbsp; [Download](https://github.com/wowthemesnet/mediumish-theme-jekyll/archive/master.zip) &nbsp; | &nbsp; [Documentation](https://bootstrapstarter.com/template-mediumish-bootstrap-jekyll/) &nbsp; | &nbsp; [Buy me a coffee](https://www.wowthemes.net/donate/)

### Copyright

Copyright (C) 2019 Sal, https://www.wowthemes.net

**Mediumish for Jekyll** is designed and developed by [Sal](https://www.wowthemes.net) and it is *free* under MIT license. 

<a href="https://www.wowthemes.net/donate/" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
