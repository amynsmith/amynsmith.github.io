---
title:  "Start with Jekyll"
date:   2023-07-15 08:07:09 +0800
categories: jekyll
---

below are some problems and solutions:

1. `bundle install` Failed to open TCP connection to rubygems.org:443

   Create .gemrc file in your home dir (user folder in windows or linux) and set the proxy settings there:
   `http_proxy: http://[user]:[password]@[server]:[port]`

2. Jekyll GitHub Metadata: No GitHub API authentication could be found.
   
   add this line to _config.yml:
   `github: [metadata]`

3. `bundle exec jekyll serve` Load error: cannot load such file – webrick
   
   `bundle add webrick`