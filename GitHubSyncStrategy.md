# 写在前面

> 在编辑与退出之前记得**同步**
>
> WorkFlow should be stricted as below:
>
> - **Snyc->Edit->Snyc->Quit**

***

# WindowsOS

## MarkdownFiles

>  使用***Typora***本地编辑
>
>  ->***GitHubDesk***客户端确认同步
>
>  > 进入项目界面左下角Commit
>  >
>  > ->上方菜单Fetch Origin

## SourceCode

### *Visual Studio*

> 使用内置Git功能

### *VScode*

> 内置Git策略

## 混合项目

> 可以说很多学习型的项目是混合的
>
> - Notes
> - SourceCode
>
> 一方面使用GitHubDesktop管理两个编辑器(Typora&IDE)是麻烦的
>
> 另一方面直接使用IDE管理项目不够轻量化

### 解决方案

> 先用GithubDesktop克隆Git到VS本地Git库
>
> - 轻量级编辑时只需GitHub+Typora，不必打开VS
> - 编译项目源码时只需打开VS拉取、操作、提交

### Issues

>  创建只有MD文档的空项目时，通过VS打开会自动添加一个`.vs`文件夹
>
> 不创建项目的话，每次打开VS时这个.vs文件夹都会更新
>
> 在VS工作开始前无法提交这个文件夹,显示正被VS使用
>
> > Solution:
> >
> > **不要**试图在混合型项目**创建源码前**通过**VS打开**该项目
