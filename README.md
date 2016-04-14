
## WebStorm Chinese Language Pack（中文语言包）

准备尝试使用WebStorm做开发，因为英文本身也不好，所以做了这个汉化包；

把压缩包里的"resources_zh_CN.jar"拷贝到WebStorm安装目录下的lib目录，重启即可！


因为开始使用了大量的自动翻译，虽然几经校对，加上英文水平有限，应该还有大量的翻译错误在里面！


![image](https://raw.github.com/ewen0930/WebStorm-Chinese/master/images/screen-01.jpg)

![image](https://raw.github.com/ewen0930/WebStorm-Chinese/master/images/screen-02.jpg)


## 解决 markdown 插件乱码的问题

不知道是不是个别情况，在 markdown 插件预览时全是乱码。

解决方法是修改插件下 `idea-markdown.jar` 的预览样式表

以 win7 下 WebStorm8 为例：

在 `C:\Users\TW\.WebStorm8\config\plugins\idea-markdown\lib` 里面的 `idea-markdown.jar`

替换掉文件里的 `net\nicoulaj\idea\markdown\preview.css`；或者直接替换掉这个jar；

![image](https://raw.github.com/ewen0930/WebStorm-Chinese/master/images/markdown-css.png)


同系列：[PhpStorm 中文语言包](https://github.com/ewen0930/PhpStorm-Chinese) 和 [PyCharm 中文语言包](https://github.com/ewen0930/PyCharm-Chinese)
