第一步：建立git仓库 
cd到你的本地项目根目录下，执行git命令

git init
第二步：将项目的所有文件添加到仓库中

gitadd
 .
如果想添加某个特定的文件，只需把.换成特定的文件名即可

第三步：将add的文件commit到仓库

git commit -m "注释"

第五步：重点来了，将本地的仓库关联到github上

git remote add origin https://github.com/xiangzhihong/gpuimage

第六步：上传github之前，要先pull一下，执行如下命令：

git pull origin master

第七步，也就是最后一步，上传代码到github远程仓库

git
push
 -u origin master