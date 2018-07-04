# Github Command
>github操作步骤:
>>第一步书序github的基本操作
>>>第二部关联git和github账户,使用ssh的方式
>>>>第三部提交你的push到github

 
 
第一步`github命令`:
```
1.进入当前目录,右键gitbashhere
2.进入你的github账户,创建一个工作空间,右键复制空间地址
3.通过clone命令将目录克隆到:git clone https://github.com/acierTest/,成功之后就在你的目录之中会有aciertest目录
4.选中你想要commit的文件,复制到你的acierTest中去
5.git add test.txt 将文件加入到临时文件夹之中
6.git commit test.txt 将文件commit
7.git push origin master 将文件push到github仓库之中

```

第二步`通过ssh关联你的github账户`
```
1.生成你的ssh,输入ssh 验证你是否可以生成ssh
2.生成ssh-->ssh -keygen -t rsa
3.windows进入用户-->查看ssh文件夹中的文件
4.进入github账户settting-->ssh and gpgkeys-->复制.pub文件内容到里面就可以了
5.验证你的ssh是否关联成功 --> ssh -t 228792908@qq.com

```
第三部`push到你的文件到github仓库`
```
1.git add test.txt
2.git commit test.txt
3.git push origin test.txt
大功告成!
```

