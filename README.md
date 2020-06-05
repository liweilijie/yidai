# yidai

> it will teach me hard study.

**go**的一些琐碎的代码。

或者与我的个性一致，比较追求自由，追求完美。这个仓库的名字用易贷。也是想让自己保持努力学习的一颗心。

最近被`台下人走过不见旧颜色，台上人唱着心酸离别歌`迷住了。

人生如戏，戏如人生，又有多少人在生活与工作不是或多或少在扮演着自己的角色。

## 最爱的吉姆尼

![j0](images/j0.jpeg)

![j1](images/j1.jpeg)

![j3](images/j3.jpeg)

![j4](images/j4.jpeg)

![j2](images/j2.jpeg)

## 好习惯

```bash
# 初始化这个项目
go mod init github.com/liweilijie/yidai
# 在github上面创建仓库，并且在本地增加到github远程名称上面，进行双推
git remote add github git@github.com:liweilijie/yidai.git
git push -u github master

# 创建一个tag
git tag -a v2.0.0 -m "first go mod init"
# 推送tags
git push origin --tags
git push github --tags

# 双推代码
git push origin master
git push github master

# 创建一个develop分支进行开发
git checkout -b develop
git push -u origin develop
git push -u github develop
```
