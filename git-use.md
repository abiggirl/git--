git使用前配置
配置提交人姓名 git config --global user.name;
配置提交人邮箱 git config --global user.email
查看修改 git config --list
提交步骤
git init 初始化git仓库
git status 查看文件状态
git add 文件列表，追踪文件
git commit 向仓库中提交代码 必须要有提交说明：git commit -m（空格） 提交信息
git log 查看提交记录
撤销步骤
用暂存区文件覆盖工作目录中的文件： git checkout 文件
将文件从暂存区删除： git rm --cached 文件
将git仓库中指定的更新记录恢复出来，并且覆盖暂存区和工作目录：git rest --hard commitID
