# rickylee.monster博客

基于 [Stuart Geiger](https://github.com/staeiou)在[Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/)（© 2016 Michael Rose，MIT License）的academicpages主题，托管于Cloudflare Pages上。

### 👬 特点

博客中的静态资源采用jsDelivr CDN进行加速,在中国大陆地区有着不错的访问速度。目前，本份代码的可移植性不高，部分加速资源需要移植后逐个修改链接，之后如有余力会尝试改善。

对于博文内容、博客程序的讨论，都欢迎在issue中提出。

### ⚠️ 注意

如果在使用过程中遇到安全提示，直接删除 Gemfile.lock 文件就好. 

### 🧭 使用指南（利用Github Pages）

1. 你如果没有Github账号，首先应当注册一个GitHub账号，并确认你的注册邮箱。 (必须步骤！)
1. 点击上面右边的fork按钮，fork [本 repository](https://github.com/rickylsr/blog) 或者[原作者的 repository](https://github.com/academicpages/academicpages.github.io)。
1. 前往repository的settings界面（在有"Code"等按钮一排的最右边)。重命名repository为"[你的github账户名].github.io"这也将成为你的网站的URL.
1. 编辑config.yml，以进行站名、域名等全站设置 (可以参考[this set of diffs](http://archive.is/3TPas) )
1. 如果需要上传文件 (例如PDF, .zip文件等)，可以上传至files/ directory。这些文件将会出现在 https://[你的github账户名].github.io/files/example.pdf.  
1. 在repository settings的"GitHub pages" section，你可以检查你的网站编译状态。
1. (可选) 使用 `markdown_generator` 目录中的 Jupyter notebooks 或 python 脚本以生成markdown文件。

你还可以前往原作者的网站获取更多信息： https://academicpages.github.io/
