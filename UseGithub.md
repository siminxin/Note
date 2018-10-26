## git基本使用
- git clone【https://github.com/siminxin/Note】  首先添加远程地址（精确到库，无【】）

- rm 删除文件

- git add [url OR FileName]  添加一些文件到缓存区

- git commit -m '介绍内容'    把缓冲区的文件添加到本地

- git -u push origin master  将本地仓库推送到远程服务器

另外

- dir                      查看有哪些文件夹

- git rm -r --cached target          删除target文件夹

- git commit -m '删除了target'       提交,添加操作说明

- git pull origin master     将远程仓库里面的项目拉下来


## git进一步使用


一个仓库可有三个分支：

1.master

2.dev（developer开发）  接收自己master,但达到一定量时再提交到master    

3.自己   可随意更改 （本地仓库），可提交到dev.
