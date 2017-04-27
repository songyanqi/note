# sublime配置

## 安装常用插件

- 按Ctrl+`调出console<br>
- 粘贴以下代码到底部命令行并回车：
  ```
  import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
  ```
- 重启Sublime，如果在Perferences->package settings中看到package control这一项，则安装成功。
- 按下Ctrl+Shift+P调出命令面板
- 输入install 调出 Install Package 选项并回车，然后在列表中选中要安装的插件。
  常用插件
  - A File Icon
  - BracketHighlighter
  - HTML-CSS-JS Prettify
  - Jade
  - Material Theme
  - Pug
  - Sass
  - Vue Syntax Highlight
  - zzz A File Icon zzz
