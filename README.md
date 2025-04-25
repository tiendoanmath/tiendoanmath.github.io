---
title: "About Me"
permalink: "/about/"
layout: page
---
mathjax: true
Welcome to my homepage.
My full name is Doan Quang Tien (and Doãn Quang Tiến in Vietnamese). I am a pre-PhD student at Institute of Mathematics, Vietnam Academy of Science and Technology, and under the supervision of Professor [Le Tuan Hoa](http://math.ac.vn/en/component/staff/?task=getProfile&staffID=25). 
## Research Interest


## Education
 - 05/2024 -- present : pre-PhD student at VAST.
 - 08/2019 -- 12/2023 : Bachelor in Mathematics, Vietnam National University Ho Chi Minh City - University of Science.

## Research Projects
**1. Theory of Fourier Transform for $\mathcal{D}$-modules**
- Mentor: Prof. Jiangxue Fang -- Capital Normal University.
  - Aim:

 **2. Exponential Sums and Rigid Cohomology**
- Mentor: Prof. Peigen Li -- Beijing Institute of Mathematical Sciences and Applications.
  - Aim: 

 **3. Equidistributions of Generalized Jacobi Sums**
- In this project, we investigate the Jacobi sums
## Installation (jekyll-remote-theme method)

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast@v2.11

plugins:
  - jekyll-remote-theme
```

Note: to enable icons you also need to copy over the `_data` folder.

## Config

Your `_config.yml` could for example look like this:

```yaml
title: "Blog Title"
author: "Blog Author"
description: "My personal blog about ... something"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"

# Layout

show_excerpts: true        # show article excerpts on the home page
show_frame: true           # adds a gray frame to the site
show_sidebar: false        # show a sidebar instead of the usual header

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "index.html"}
  - {file: "README.md"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:niklasbuschmann@users.noreply.github.com"}
  - {title: Github, icon: github, url: "https://github.com/niklasbuschmann/contrast"}
  - {title: Subscribe, icon: rss, url: "/feed.xml"}

comments:
#  disqus_shortname: ""    # see https://disqus.com/
#  isso_domain: ""         # see https://posativ.org/isso/

plugins:
 - jekyll-feed

```

## MathJax

Contrast comes preinstalled with a leightweight alternative to MathJax called [KaTeX](https://katex.org/). To display equations in a post simply set `mathjax: true` in the article's front matter.

## License

[public domain](http://unlicense.org/)

## Screenshots

![screenshot](https://user-images.githubusercontent.com/4943215/109431850-cd711780-7a08-11eb-8601-2763f2ee6bb4.png)

![screenshot](https://user-images.githubusercontent.com/4943215/109431832-b6cac080-7a08-11eb-9c5e-a058680c23a1.png)

![screenshot](https://user-images.githubusercontent.com/4943215/73125194-5f0b8b80-3fa4-11ea-805c-8387187503ad.png)
