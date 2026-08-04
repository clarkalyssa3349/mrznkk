V8主管网址【Q-——333307——】V8主管网址【 辋芷《888yx●vip》 】
V8主管网址【Q-——333307——】V8主管网址【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

还在羡慕别人的技术博客？其实搭建一个属于自己的博客，比你想的简单得多。今天这篇教程，手把手教你用 GitHub Pages 和 Hexo 免费搭建个人网站，不用买服务器，也不用懂后端。

 为什么选择 GitHub Pages + Hexo？

- 零成本：托管在 GitHub 上，完全免费，自带 HTTPS 证书。
- 速度快：全球 CDN 加速，国内访问也很快。
- Markdown 写作：专注内容，无需关心排版。
- 主题丰富：几百款免费主题，颜值即正义。

 前期准备：只需要两样东西

1. 一个 GitHub 账号（没有的话先去注册）。
2. 本地安装 Git 和 Node.js（建议 LTS 版本）。

 四步完成搭建（亲测有效）

第一步：安装 Hexo 脚手架

打开终端，输入以下命令：

```bash
npm install -g hexo-cli
```

第二步：初始化博客项目

```bash
hexo init my-blog
cd my-blog
npm install
```

此时你本地已经有一个基础博客了。运行 `hexo s` 可以在本地预览。

第三步：关联 GitHub 仓库

在 GitHub 上新建一个仓库，命名为 `你的用户名.github.io`。然后在博客根目录的 `_config.yml` 中修改部署配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

第四步：一键部署上线

依次执行：

```bash
hexo g
hexo d
```

等待十几秒，浏览器访问 `https://你的用户名.github.io`，你的博客就正式上线了！

 进阶技巧：让博客更好看、更好用

- 更换主题：搜索 “Hexo 主题推荐”，比如 `NexT`、`Fluid` 都是热门选择，复制主题仓库地址，在 `_config.yml` 中切换即可。
- 添加搜索功能：安装 `hexo-generator-searchdb` 插件，实现站内全文搜索。
- 绑定自定义域名：买一个域名，在仓库设置中绑定，瞬间拥有个人品牌专属地址。

 写在最后

技术博客是程序员成长路上最好的沉淀方式。无论是记录踩坑经验，还是分享学习笔记，坚持写下去，你会收获意想不到的认可和机会。

如果你在搭建过程中遇到任何问题，或者想了解某个具体的功能实现，欢迎在评论区留言。你的每一次反馈，都会成为下一篇教程的选题方向。觉得有用的话，点个 Star 支持一下，也欢迎把文章转发给同样在折腾博客的朋友，一起学习，一起进步！

相关推荐：

https://github.com/yangpatricia1/ybxyao/blob/main/2026%E7%AC%AC%E4%B8%80%E6%B1%87%E6%80%BB%EF%BC%9AV8%E7%BD%91%E5%9D%80%E6%B5%8B%E9%80%9F_%E5%85%8B%E7%BC%86%E4%B8%B6%E5%84%87%E8%AF%92YZHOI.md

<img src="https://i.postimg.cc/13Zk5wzH/V8-00013.png" />

相关推荐：

https://github.com/yangpatricia1/ybxyao/commit/e5bc7401dc0219bddf64b51d21f971786fceb018

<img src="https://i.postimg.cc/YCfJ40GQ/V8-00016.png" />
相关推荐：

https://github.com/hamiltonlinda25/thgubw/blob/main/%E6%95%B0%E5%AD%97%E6%96%87%E5%A8%B1%E5%8A%A8%E6%80%81%EF%BC%9AV8%E7%BD%91%E5%9D%80%E7%BD%91%E5%9D%80_%E8%B0%92%E5%B7%AB%E5%86%8D%E6%98%BE%E4%BC%97HHJDE.md

<img src="https://i.postimg.cc/5tbnDmt0/V8-00001.png" />
相关推荐：

https://github.com/hamiltonlinda25/thgubw/commit/c4b990816c52c543877a0717b5e4189c44bee3a1

<img src="https://i.postimg.cc/hGspn7JM/V8-00003.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
