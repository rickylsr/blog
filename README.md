rickylee.monster博客，基于 [Stuart Geiger](https://github.com/staeiou)在[Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/),（© 2016 Michael Rose，MIT License）的academicpages主题，托管于Github Pages上。

博客中的静态资源采用jsDelivr CDN进行加速。目前可移植性不高，部分加速资源需要逐个修改链接，之后会尝试改善。

### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

# 使用指南（利用Github Pages）

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/
