---
{"dg-publish":true,"permalink":"/使用quartz部署Obsidian部署步骤/","noteIcon":""}
---

[[数字花园\|数字花园]]

1. 首先前往[Quartz](https://github.com/jackyzha0/quartz)的仓库地址，点击页面中的`Use this template`按钮。
2. 在创建的项目-设置-页面里面自定义域名（对应自己的域名要cn自己名字.github.io）
3. 使用的是[sublime merge](https://www.sublimemerge.com/)作为`git`的可视化客户端，下载填入自己项目Clone，本地化。
4. 在sublime merge修改文件.github-FUNDING.yml，修改里面的[]内容为你的github名字。
5. 用obsidian打开本地化的项目文件，设置-文件与链接。
- 开启“始终更新内部链接”。
- 新建笔记存放目录为根目录。
- 内部链接类型为基于根目录的绝对路径。
- 开启使用wiki链接。

6. 写完笔记后，到sublime merge点击右边的stage，在右上输入栏输入任意内容，再点击右上的commit，左边会出现向上的小箭头，点击它，弹出push选择。这样笔记的更新会自动同步到github仓库。