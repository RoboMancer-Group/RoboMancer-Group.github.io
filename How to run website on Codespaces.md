## 为方便动态调式网页，这里推荐利用Github Codespaces作为云端开发平台。

1、首先，打开Codespaces

2、找到Gemfile文件，将其中的 `gem "jekyll", "~> 4.3"` 改为 `gem "jekyll", "~> 4.4"`

3、接着在终端运行如下指令：
- gem install bundler
- bundle update jekyll jekyll-sass-converter sass-embedded
- bundle install
- bundle exec jekyll serve --livereload --host 0.0.0.0 --port 4000

4、此时便可以在浏览器中打开网页。在Codespaces中进行的修改，在网页处进行刷新后便可以立刻看到修改。

5、将修改的内容推送到repo时，注意不要将Gemfile与Gemfile.lock推送了！
![请不要提交Gemfile与Gemfile.lock的更改！](images/codespace.png)

这是因为Codespaces的环境与原repo中的环境不一致。
