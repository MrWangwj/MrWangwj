基于Hexo搭建的个人博客

### 1. 克隆项目

> git clone git@github.com:MrWangwj/MrWangwj.github.io.git

### 2. 进入根目录

> cd MrWangwj.github.io.git

### 3. 切换到博客文件分支

> git checkout -b hexo origin/hexo

### 4. 安装主题

> git clone https://github.com/tufu9441/maupassant-hexo.git themes/maupassant

### 5. 安装依赖

> npm install

### 6. 编译、查看、提交

> hexo g
>
> hexo s
>
> hexo d

### 7. 提交 markdown 文件

> git add .
>
> git commit -m '新增博客'
>
> git push origin hexo
