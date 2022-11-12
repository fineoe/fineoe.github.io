# git的基本使用方法

#### 1. 初始化
```
git init
```

#### 2. 添加待提交任务(添加到仓库缓存区)
```
git add .
```

#### 3. 查看Git文档的状态
```
git status 
```

#### 4. 提交任务
```
git commit - m "first version"
```

#### 5. 显示已提交版本
```
git log
```

#### 6. 查看修改部分内容对比
> 对于修改版本和原来的版本也就是缓冲区版本哪里修改了
```
git diff
```

#### 7. 选中你想提交的文件
> 可以将不同的修改分次提交
```
git add 文件名 -p
```

#### 8. 修改默认的编译器
> 默认是vim,下面示例修改为vscode
```
git config --global core.editor "code --wait"
```

#### 9. 查看某一次修改的详细
> 用来查看某一次修改的详细,[1657db...]是一个commit_id编号
```
git show 1657db...
```
#### 10. 查看远程仓库
```
git remote --verbose
```
#### 11. 添加远程仓库
```
git remote add 远程仓库名 仓库链接
```
#### 12. 绑定仓库,默认push到该仓库
> master为分支
```
git push -u 远程仓库名 master
```

[github page](https://fineoe.github.io/git2020/hello.html)

#### 13. 查看git版本号
```
git --version
```

#### 14. 查看远程仓库信息
```
git remote -v
```

#### 15.删除远程仓库 
```
git remote remove 仓库名
```

#### 16. 修改仓库地址
```
git remote set-url 仓库名 仓库新地址
```

#### 17. 下载仓库
```
git clone 仓库地址
  eg:https://github.com/fineoe/fineoe.github.io
```

#### 18. 把远程仓库和本地仓库合并
```
git pull
```

