**第一步：建立git仓库，cd到你的本地项目根目录下，执行git命令**

```text
git init
```

**第二步：将项目的所有文件添加到仓库中**

```c
git add .
```

**第三步：将add的文件commit到仓库**

```text
git commit -m "注释语句"
```

**第四步：去github上创建自己的Repository，创建后的页面如下图所示：** 

![img](https://pic1.zhimg.com/v2-a4e249c5e85f6f5ca6c56fc916c150ac_b.jpg)

点击**Clone or download**按钮，复制弹出的地址**[git@github.com](mailto:git@github.com):\**\*/test.git**，记得要用SSH的地址，尽量不要用HTTPS的地址，如上图所示

**第五步：将本地的仓库关联到github上---把上一步复制的地址放到下面**

```text
git remote add origin git@github.com:***/test.git
```

**第六步：上传github之前，要先pull一下，执行如下命令：**

```text
git pull origin master
```

**第七步，上传代码到github远程仓库**

```text
git push -u origin master
```

