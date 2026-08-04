V8官方客服【Q-——333307——】V8官方客服【 辋芷《888yx●vip》 】
V8官方客服【Q-——333307——】V8官方客服【 辋芷《888yx●vip》 】

 从零搭建个人博客：Github Pages + Hexo 完整教程（2025版）

你是否想过拥有一个完全属于自己的技术博客？不需要购买服务器，不用维护数据库，甚至零成本就能上线——没错，我说的就是 Github Pages + Hexo 组合。今天这篇文章，手把手带你从环境配置到域名绑定，30分钟搞定一个高颜值、可定制的个人博客。

 一、为什么选择 Github Pages + Hexo？

在开始之前，先解决“为什么”的问题。与WordPress、Typecho等动态博客相比，静态博客的优势非常明显：

- 加载速度快：纯静态HTML，CDN分发，全球访问无压力
- 安全性高：无数据库、无后端，天然免疫SQL注入
- 版本管理：所有文章都是Markdown文件，Git历史记录可追溯

而Hexo作为最受欢迎的静态博客框架，拥有庞大的插件生态和主题市场，特别适合技术人群。

 二、环境搭建：三步到位

第一步：安装必要工具
你需要准备Node.js（建议v18+）、Git，以及一个Github账号。这些基础环境安装完成后，在终端执行：

```bash
npm install -g hexo-cli
```

第二步：初始化博客项目
使用以下命令快速创建项目骨架：

```bash
hexo init my-blog
cd my-blog
npm install
```

第三步：本地预览
执行 `hexo s` 后，浏览器访问 `http://localhost:4000`，如果看到默认页面，恭喜你，本地环境已OK！

 三、部署到Github Pages（关键步骤）

这里有个易错点要提醒：Github Pages支持两种部署方式，推荐使用分支部署。

1. 在Github新建仓库，命名为 `你的用户名.github.io`
2. 修改根目录 `_config.yml` 中的deploy配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

3. 安装自动部署插件：`npm install hexo-deployer-git --save`
4. 执行 `hexo g && hexo d` 一键部署

等待1-2分钟，访问 `https://你的用户名.github.io`，你的博客就上线了！

 四、进阶优化：让博客更专业

自定义域名：在仓库Setting的Pages选项中，绑定你的私有域名，然后在域名服务商添加CNAME记录即可。

主题美化：推荐几个热门主题：NexT（经典稳重）、Butterfly（颜值担当）、ocean（极简风）。更换主题只需下载到 `themes/` 目录，修改 `_config.yml` 中的 `theme` 字段。

SEO优化：安装 `hexo-generator-seo` 插件，自动生成sitemap，并确保每篇文章都填写Keywords和Description。

 五、常见问题排查

部署失败：检查本地是否已安装Git，以及远程仓库权限是否正确。

样式丢失：部署前先执行 `hexo clean` 清除缓存。

图片无法显示：确保图片路径是绝对路径（以 `/` 开头）。

---

现在，你已经拥有了自己的技术博客。下一步就是持续产出优质内容——记住，SEO的核心永远是内容为王。

如果你在搭建过程中遇到任何问题，欢迎在评论区留言，我会第一时间为你解答。觉得有用的话，点赞 + 收藏支持一下，你的反馈是我持续输出干货的最大动力！

> 互动话题：你准备用博客记录什么方向的内容？分享你的想法，说不定下篇文章就是为你定制！

相关推荐：

https://github.com/stoneconnor94/facjpk/blob/main/2026%E5%AE%98%E6%96%B9%E7%83%AD%E6%A6%9C%EF%BC%9AV8%E6%B3%A8%E5%86%8C%E5%A8%B1%E4%B9%90_%E6%B0%90%E8%AF%92%E9%9D%A1%E6%88%BF%E5%86%88UMTGA.md

<img src="https://i.postimg.cc/W4Nx0Vgy/V8-00017.png" />

相关推荐：

https://github.com/stoneconnor94/facjpk/commit/3b7e2efca10fd4a0e77eb0991840660da0e8bccb

<img src="https://i.postimg.cc/5tbnDmt0/V8-00001.png" />
相关推荐：

https://github.com/hamiltonlinda25/thgubw/blob/main/2026%E7%A7%91%E6%8A%80%E6%8C%87%E5%8D%97%EF%BC%9AV8%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86_%E8%84%B1%E7%8B%AC%E8%82%9A%E9%A3%9E%E5%90%AENAHUN.md

<img src="https://i.postimg.cc/3Rw9xJm7/V8-00005.png" />
相关推荐：

https://github.com/hamiltonlinda25/thgubw/commit/7e6ac6358f9497d8b14df1f579c99ecb9155a4b8

<img src="https://i.postimg.cc/5tbnDmt0/V8-00001.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
