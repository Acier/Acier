# github常用命令
> 常用命令
>>工作流程
>>> github的概念

* github`常用`命令
```
1.验证ssh有效性: ssh
2.生成你的ssh :git ssh -keygen -t rsa
3.设置你的用户名 git config --global user.name "你的名字"
4.设置你的邮箱 git config --blobal user.email "你的邮箱"
5.clone github上面的项目到本地仓库git clone https://github.com
6.git reset HEAD //清除缓存中的内容
7.git rm -f fileName //清除缓存中的file
```
***

* 上传文件
```
1.复制你的文件到git目录之中
2.git add test.txt
3.git commit -m"你的描述"
4.git push

```
* 分支相关
```
1.git branch Test 创建分支
2.git checkout Test 进入创建的分支
3.git branch -d Test 删除分支
```

***

* github的概念
```
1.你的本地仓库由 git 维护的三棵"树"组成。第一个是你的 工作目录，它持有实际文件；第二个是 暂存区
（Index），它像个缓存区域，临时保存你的改动；最后是 HEAD，它指向你最后一次提交的结果。

2.使用git add 将文件转入缓冲区内,使用git commit 将文件转入head,使用git push将文件提交github!

3.

```









