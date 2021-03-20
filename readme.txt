I am learning git!
try again!
create a new branch-dev!
pip install jupyter_contrib_nbextensions
jupyter contrib nbextension install --user

本地电脑创建仓库
1、mkdir 文件名（仓库名）
2、进入仓库名所在目录
3、git init  --把刚创建的本地仓库变成远程仓库
4、git switch 分支名   --切换分支
5、git add 文件名      --将本地修改过的文件添加到缓存区
6、git commit -m "备注信息” --将缓存区信息提交到工作区
7、git status  --查看状态
8、git diff 文件名   --参看本地文件修改前后对比
9、git log --查看日志
10、git reset -hard HEAD^   --本地版本回退（一个版本）
11、git cheackout --文件名   --回退工作区的修改
12、 git reset HEAD 文件名  --彻底回退
13、git branch  --查看当前分支



本地修改文件
vim 文件名  --创建/修改已有文件
输入 i    --插入编辑内容
按esc      --退出编辑状态
同时shift+:   wq    --保存退出
cat 文件名   --查看文件内容
ls   --查看当前名录下所有文件


创建远程库
1、网页github提前新建一个仓库（建议与本地连接的仓库同名）
2、git remote add origin 远程仓库地址   --创建本地与远程仓库连接
3、git push -u origin 分支名  --第一次将本地仓库文件推到远程仓库对应分支上 （以后不需要-u）
4、git remote -v   --查看连接状态
5、git remote rm origin（远程仓库别名） --删除远程仓库连接
6、git clone  远程仓库地址    --直接将远程仓库内容下载下来
7、git switch -c 分支名        --创建并切换分支
8、git branch -d  分支名     --删除分支


合并分支：
1、git switch 主分支    --切换到需要合并分支的主分支路径上
2、git merge   分支名    --合并需要合并的分支到当前主分支下
3、cat 文件名    --确认是否合并成功
4、git branch -d  子分支名   --合并后删除子分支 
5、git pull origin 主分支名   --将远程仓库最新内容拉取下来，再进行编辑修改
6、git push origin 主分支名   --将本地修改后的文件再次推到远程仓库上。




