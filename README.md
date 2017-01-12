# Git Flow
- [企业级开发：Gitflow Workflow工作流](http://www.jianshu.com/p/104fa8b15d1e)

# 配置文件
> 在`Git` or `GitHub`中某些文件拥有特殊的作用

### `.gitignore`
> 这个文件的作用就是告诉Git哪些文件不需要添加到版本管理中

### `.gitattributes`
> 告诉Github，咱们项目是啥类型

### `.gitkeep`
> Git会忽略空的文件夹, 这时可以把.gitkeep放入空文件夹  **非git标准**

### `.babelrc`
> babel的配置文件

### `.eslintrc`
> ESLint的配置文件，支持JSON和YAML两种语法

### `.eslintignore`
> 和.gitignore文件一样，都是用来说明需要忽略的文件。

### `.github`文件夹
> 可定义一些`GitHub`的样式 或 个性化

### `.editorconfig`
> 定义不同编辑器相同的规范

### `.travis.yml`  [TravisCI](https://travis-ci.org/) OR [CircleCI](https://circleci.com/)
> Travis Ci的配置说明文件

-------------------

# GitHub相关工具

### CI
> 自动化的单元测试, 显示构建状态改变

[TravisCI](https://travis-ci.org/) OR [CircleCI](https://circleci.com/)

### Reviewable

[Reviewable](https://reviewable.io/)

### 代码覆盖率
> 结合着TravisCI的自动化单元测试，加上这个测试覆盖率

[Coveralls](https://coveralls.io/)

### 快速进行沟通
> Slack
> Slack接入GitHub只是其中的一个小功能而已，更强大的在于Slack本身

[Slack](https://slack.com/)

-------------------

# GitHub 使用小技巧

### 精准分享关键代码
- #L行号
> [URL]#L行号

- #L开始行号-L结束行号
> [URL]#L开始行号-L结束行号

### 通过提交的msg自动关闭issues

message:
```message
fix [ISSUES URL]
```
**相关指令**
- close
- closes
- closed
- fixes
- fixed
- resolve
- resolves
- resolved

### 通过HTML方式嵌入Github
**代码引入**
```html
 <iframe src="//ghbtns.com/github-btn.html?user=hocgin&repo=GitHub-Tips&type=watch&count=true" allowtransparency="true" frameborder="0" scrolling="0" width="110" height="20"></iframe>
```
> 需更改`user` and `repo`


### 其他
- issue中输入冒号 : 添加表情
- 任意界面，shift + ？显示快捷键
- issue中选中文字，R键快速引用
