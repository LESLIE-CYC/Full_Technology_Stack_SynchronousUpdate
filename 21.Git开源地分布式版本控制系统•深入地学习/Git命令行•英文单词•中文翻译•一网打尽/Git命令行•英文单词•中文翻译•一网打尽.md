##                      Git命令行•英文单词•中文翻译•一网打尽

**温馨提示：**   一般情况下，输入命令是不要忘记了，先是输入了  **git**  开头！

| git命令行            | 中文翻译       | 作用说明             | 顺序 |
| -------------------- | -------------- | -------------------- | ---: |
| branch               | 分支           | 查看本地所有分支     |      |
| status               | 状态           | 查看当前状态         |      |
| commit               | 提交           | 提交                 |      |
| branch               | 分支           | 查看所有的分支       |      |
| remote               | 远程           | 远程仓库             |      |
| add                  | 增加           | 增加文件             |      |
| add .                | 增加全部       | 增加全部地文件       |      |
| origin               | 起源           | 来自那里的超源       |      |
| push                 | 推向           | 推送到那个远程的仓库 |      |
| master               | 主要的         | 远程仓库中的主支     |      |
| show                 | 给...展示      | 想给什么...展示出来  |      |
| develop              | 开发           |                      |      |
| checkout             | 检验           |                      |      |
| track                | 跟踪           |                      |      |
| dev                  | 偏向           |                      |      |
| file name            | 文件名         |                      |      |
| log                  | 日志           |                      |      |
| diff                 | 比较           |                      |      |
| stash                | 隐藏           |                      |      |
| pull                 | 拉过来         |                      |      |
| push                 | 推向           |                      |      |
| serverfix            | 服务器         |                      |      |
| awesomebranch        | 令人敬畏的支行 |                      |      |
| fetch                | 去...拿        |                      |      |
| log_message          | 日志信息       |                      |      |
| mkdir                | 创建目录       |                      |      |
| WebApp               | 网络应用程序   |                      |      |
| touch                | 接触 / 联系    |                      |      |
| README               | 自述文件       |                      |      |
| first commit         | 首次提交       |                      |      |
| config               | 配置           |                      |      |
| global               | 全局的         |                      |      |
| name                 | 名字           |                      |      |
| email                | 邮箱           |                      |      |
| pwd                  | 路径           | 当前工作的路径       |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
|                      |                |                      |      |
| 未完成，日后还要继续 |                |                      |      |

### **一、 Git 常用命令速查**

-----------------------------------------------------------------------------------------------------------------------------------------------------------

>**git status**   ☛查看当前状态
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git brach**  ☛查看本地的所有分支
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git commit**   ☛提交
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git branch -a**   ☛查看所有的分支
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git branch -r**    ☛查看远程所有分支
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git commit -am "init"**    ☛提交并且加注释
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git push origin master**     ☛将文件给推到服务器上
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git remote show origin**     ☛显示远程库origin里的资源
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git push origin master:develop**  ☛ 将本地库与服务器上的库进行关联
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git push origin master:hb-dev**    ☛ 将本地库与服务器上的库进行关联
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git checkout --track origin/dev**     ☛切换到远程dev分支
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git branch -D master develop**    ☛删除本地库develop
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git checkout -b dev**    ☛建立一个新的本地分支dev
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git merge origin/dev**    ☛将分支dev与当前分支进行合并
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git checkout dev**    ☛切换到本地dev分支
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git remote show**  ☛查看远程库
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git add .**  ☛增加全部文件
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git rm**    ☛文件名(包括路径) 从git中删除指定文件
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git clone git://github.com/schacon/grit.git**  ☛ 从服务器上将代码给拉下来
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git config --list**   ☛看用户列表信息
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git ls-files**   ☛看已经被提交的
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git rm [file name]**   ☛删除一个文件
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git commit -a**  ☛ 提交当前repos的所有的改变
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git add [file name]**  ☛ 添加一个文件到git index
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git commit -v**    ☛当你用－v参数的时候可以看commit的差异
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git commit -m "This is the message describing the commit"**    ☛添加commit信息
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git commit -a**    ☛-a是代表add，把所有的change加到git index里然后再commit
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git commit -a -v**    ☛一般提交命令
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git log** 看你commit  ☛的日志
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git diff**   ☛ 查看尚未暂存的更新
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git rm a.a**   ☛移除文件(从暂存区和工作区中删除)
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git rm --cached a.a**   ☛移除文件(只从暂存区中删除)
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git commit -m "remove"**    ☛移除文件(从Git中删除)
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git rm -f a.a**    ☛强行移除修改后文件(从暂存区和工作区中删除)
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git diff --cached 或 $ git diff --staged**   ☛查看尚未提交的更新
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git stash push**    ☛将文件给push到一个临时空间中
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>**git stash pop**    ☛将文件从临时空间pop下来
>
>----------------------------------------------------------------------------------------------------------------------------------------------------
>
>资源来源于☛https://www.jb51.net/article/55442.htm
>
>----------------------------------------------------------------------------------------------------------------------------------------------------

### 相关信息说明：

>【署 名】：LESLIE_CYC
>
>【建 库】：2020年04月04日
>
>【重 要】：♕♕♕♕♕♕♕♕♕♕
>
>【状 态】：未完成•有待持续更新中
>
>【最 近】：源码在码云官网上，同步更新到GitHub官网上
>
>【同 步】：已经同步更新到GitHub的官网上面了
>
>【注 明】：爱好者更改后必须署名与日志记录 ！
>
>【修 复】：看心情好坏 + 灵光一闪 + 永久修复 + 持续更新
>
>【资料来源】：各大前端•技术栈•爱好社区
>
>【温馨提示】：更新以码云的官网上的更新时间为准，不是以GitHub官网，测试过不同库有时不能同步更新
>
>---------------------------------------------------------------------------------------------------------------------------------------------------
>
>**注：比较认可这个可爱的胖子【LINUS•技术栈•元老级】的为人编程开发思想：**
>
>【开源思想+资源共享+爱好者共同维护+爱好者共同修复+增加实用功能+少些图形界面+少些占用CPU运行】
>
>----------------------------------------------------------------------------------------------------------------------------------------------------