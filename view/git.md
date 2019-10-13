### git下载

> 由于翻墙的原因可以在国内开源进行下载，比如[淘宝镜像](https://npm.taobao.org/mirrors/git-for-windows)



### 一些环境配置

```shell
# 配置用户名
git config --global user.name "username"
# 配置邮箱
git config --global user.email "username@email.com"

```



### 生成ssh

```shell
ssh-keygen -t rsa
#连续默认回车，最后在C:\Users\你的用户名.ssh找到公钥id_rsa.pub
#在github的个人设置页面设置后生成的ssh
#ssh密钥链接避免每次git与github操作时需要输入密码等
```



### 验收ssh

```shell
ssh -T git@github.com
# 出现<hi 你的github名>时表明链接成功
```

