V8注册地址【Q-——333307——】V8注册地址【 辋芷《888yx●vip》 】
V8注册地址【Q-——333307——】V8注册地址【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 保姆级教程

最近不少朋友在后台问我，想拥有一个属于自己的技术博客，但又不想折腾服务器和域名。其实，用 GitHub Pages 免费托管 + Hexo 静态框架，半小时就能上线一个高颜值、支持 Markdown 的专属站点。今天这份教程，我尽量把每一步都拆解到鼠标点击级别，保证你跟着操作就能成功。

 为什么推荐 GitHub Pages + Hexo？

- 完全免费：无需云服务器，GitHub 提供 1GB 静态空间，流量无限制。
- 极速访问：全球 CDN 加速，国内访问速度也不错。
- 专注写作：Hexo 对 Markdown 支持极佳，`hexo new` + 拖拽图片即可发文。
- 版本管理：文章天然纳入 Git 历史记录，改坏了随时回滚。

 一、前置准备（5 分钟）

1. 注册 [GitHub](https://github.com) 账号（已有请忽略）。
2. 安装 [Git](https://git-scm.com/) 和 [Node.js](https://nodejs.org/)（LTS 版本即可）。
3. 安装 Hexo 脚手架：打开终端/命令提示符，执行：

``` bash
npm install -g hexo-cli
```

 二、初始化博客项目（10 分钟）

在本地新建一个文件夹，例如 `my-blog`，然后运行：

``` bash
hexo init my-blog
cd my-blog
npm install
```

启动本地预览：

``` bash
hexo server
```

浏览器访问 `http://localhost:4000`，看到默认主题页面即成功。

 三、部署到 GitHub Pages（10 分钟）

1. 在 GitHub 新建仓库，名称必须为 `你的用户名.github.io`（如 `abc.github.io`）。
2. 安装部署插件：

``` bash
npm install hexo-deployer-git --save
```

3. 编辑站点的 `_config.yml`，末尾 `deploy` 部分改为：

``` yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

4. 发布文章并部署：

``` bash
hexo clean && hexo generate
hexo deploy
```

稍等 1 分钟，访问 `https://你的用户名.github.io` ，你的博客已上线！

 四、写文章与进阶技巧

- 新建`hexo new "post-title"`，文章会生成在 `source/_posts` 目录，用任意编辑器打开编写即可。
- 换主题：去 [Hexo Themes](https://hexo.io/themes/) 下载，复制到 `themes` 文件夹，修改 `_config.yml` 里的 `theme` 字段，重新部署。
- 绑定独立域名：在仓库 Settings → Pages 中设置 Custom domain，并在阿里云/腾讯云控制台添加 CNAME 解析即可。

 五、常见问题与踩坑提醒

- 部署后不生效：记得勾选仓库 Settings → Pages 的 `Source` 为 `Deploy from a branch`，分支选择 `main`。
- 图片无法显示：确保图片路径使用绝对路径或相对仓库的根路径。
- 本地预览正常，线上空白：检查 `_config.yml` 中 `root` 字段是否设置为 `/`。

 动手试试吧！

理论上到这你已经拥有一个完全可控的个人博客了。第一步永远是先建仓库，卡壳了随时在评论区留言，我会逐一回复。

如果这篇教程对你有帮助，点个赞或转发给同样想开博客的朋友，支持我继续产出更多干货！你们的下一个问题，就是我的下一个选题。

相关推荐：

https://github.com/millerdonna9312/pwnxnv/blob/main/2026%E5%AE%98%E7%BD%91%E6%95%99%E7%A8%8B%EF%BC%9AV8%E4%B8%BB%E7%AE%A1%E5%AE%98%E6%96%B9_%E9%81%93%E4%B9%88%E9%82%AA%E5%8F%B2%E7%97%9BSLEMZ.md

<img src="https://i.postimg.cc/2SFPqybC/V8-00015.png" />

相关推荐：

https://github.com/millerdonna9312/pwnxnv/commit/b5f08072a444c2bfe0b799d563c609e360d26aa7

<img src="https://i.postimg.cc/ZYWtfJ2Z/V8-00011.png" />
相关推荐：

https://github.com/yangpatricia1/ybxyao/blob/main/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%EF%BC%9AV8%E4%B8%BB%E7%AE%A1%E7%BD%91%E5%9D%80_%E8%AF%B1%E5%93%A6%E9%9F%B6%E7%97%98%E7%82%AFDDRYT.md

<img src="https://i.postimg.cc/13Zk5wzH/V8-00013.png" />
相关推荐：

https://github.com/yangpatricia1/ybxyao/commit/c36857a74ae4c73334633cbb3f410522e6f0c810

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
