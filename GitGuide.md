## Guide for Git To Github
### 安装工具
#### 安装git工具
#### 配置SSH
* 密钥
使用`ssh-keygen -t rsa -C zhangsan@example.com`命令生成密钥对，并将pubkey放到github，
使用`ssh -T git@github.com`命令检查连接
* 设置global
```
git config --global user.name "zhangsan"
git config --global user.email "zhangsan@example.com"
```
### 建仓
* 本地仓
新建文件夹apple `git init`
* 远程仓
也取名叫apple
* 连接本地和远程仓
`git remote add origin git@github.com:zhangsan/apple`

### 提交修改
```
git add xxx
git commit -m "first commit"
git push origin master
```