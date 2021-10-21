git init 初始化仓库
git add . 将所有文件添加到暂存区
git commit -m '提交时的说明' 提交本地仓库
线上创建新仓库：
复制git remote add origin https://github.com/Shadow-hao/dg.git将本地仓库和线上仓库做关联
git push -u origin master 将本地仓库上传到线上仓库
git config --global http.sslVerify "false" 解决报错
