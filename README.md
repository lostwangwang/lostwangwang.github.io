## 博客

[迷途的汪汪的 BLOG](https://lostwangwang.github.io/)

## 部署方式

#### 1. 创建新文章.

```shell
hugo new posts/my-first-post.md
```

#### 2. 进入*站点根目录*，执行

```shell
hugo
```

#### 3. 上传代码至 master

```shell
cd public
git init
git remote add origin https://github.com/jianzhnie/jianzhnie.github.io.git # 将本地目录链接到远程服务器的代码仓库
git add .
git commit -m "[介绍，随便写点什么，比如日期]"
git push -u origin master
```

### 4. 之后更新在`public`中更新即可。

```shell
git add -A
git commit -m "[介绍，随便写点什么，比如日期]"
git push -u origin master
```

## 参考链接

[Hugo + Github Pages 搭建个人博客](https://jianzhnie.github.io/post/hugo_site/)
