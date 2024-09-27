# Basic Site Settings
locale                   : "en-US"
title                    : "Xiaoxue Zhao's Website"
title_separator          : "-"
name                     : &name "Xiaoxue Zhao"
description              : &description "A personal website for Xiaoxue Zhao"
url                      : https://iris1z.github.io # Your site URL
baseurl                  : "" # the subpath of your site
repository               : "iris1z/iris1z.github.io"

# Author Information
author:
  avatar           : "profile.png" # Ensure you have an image called "profile.png" in your assets
  name             : "Xiaoxue Zhao"
  bio              : "A student at UCB studying computational social science."
  location         : "Berkeley, CA"
  email            : "youremail@example.com" # Add your actual email

  # Social Links
  github           : "iris1z"
  googlescholar    : "https://scholar.google.com/citations?user=PS_CX0AAAAAJ"
  linkedin         : "https://linkedin.com/in/yourprofile"
  orcid            : "http://orcid.org/yourorcidurl"

# Simplified Navigation Bar
navigation:
  - name: "Home"
    link: "/"
  - name: "Projects"
    link: "/projects/"
  - name: "About Me"
    link: "/about/"
  - name: "Contact"
    link: "/contact/"

# Simplified Sections - Remove unused sections
collections:
  publications:
    output: true
    permalink: /:collection/:path/

# SEO and Social Sharing
google_site_verification :
bing_site_verification   :
social:
  type                   : "Person"
  name                   : "Xiaoxue Zhao"
  links:
    - "https://github.com/iris1z"
    - "https://scholar.google.com/citations?user=PS_CX0AAAAAJ"

# Reading Files
include:
  - .htaccess
  - _pages
exclude:
  - "*.sublime-project"
  - node_modules
  - tmp

# Markdown and Plugins
markdown: kramdown
highlighter: rouge
plugins:
  - jekyll-feed
  - jekyll-sitemap

# Output Settings
permalink: /:categories/:title/
timezone: America/Los_Angeles

# Minimal Plugin Configuration
whitelist:
  - jekyll-feed
  - jekyll-sitemap
