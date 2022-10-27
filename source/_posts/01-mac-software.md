---
title: mac工具笔记
banner_img: /images/background/1.jpeg
date: 2022-10-24 14:45:41
tags:
- Mac
categories: 
- [Mac软件]
---
### 软件[a-z排序]
mac软件下载地址：

1. [https://www.macwk.com/](https://www.macwk.com/) ：（以上提及软件大部分可从此网站下载，快速无广告，以关站）
1. [https://ourmacs.com/](https://ourmacs.com/) ：OurMacs - Mac搜索引擎
1. [https://macapp.org.cn/](https://macapp.org.cn/) ：MacApp分享频道
1. [https://www.macyy.cn]( https://www.macyy.cn) ：MacYY – 快速获取破解软件

---

1. anywhere：随启随用的静态文件服务器

```
下载：npm install anywhere -g
```

2.  autojump：输入 j 目录名 或 j 目录名包含的字符（这个目录必须是之前 cd 访问过的），就可直接切换到相应的目录

```
1.brew install autojump
2.在~/.zshrc，把autojump添加到.zshrc的插件列表中
3.新开一行，添加：[[ -s $(brew --prefix)/etc/profile.d/autojump.sh ]] && . $(brew --prefix)/etc/profile.d/autojump.sh
4.source ~/.zshrc 使配置生效
```

3. Beyond Compare：mac 上非常好的文件同步对比工具 ，专门用于帮助您比较，合并或同步文件夹和文件。
4. brew
5. bob : OCR翻译，选中翻译
6. 超级右键
7. CotEditor ：好用的编辑器，不能打开文件夹
8. Foxmail ：邮箱
9. Go2Shell ：当前位置打开shell
10. Hidden Bar 
11. IINA ：视频播放器
12. icopy : 替换Paste
13. iTrem2 + fig + oh-my-zsh

```
iTerm2下载地址：https://iterm2.com/downloads.html
将zsh设置成默认的shell：chsh -s /bin/zsh (重启shell)
```

14. KeePassXC 
15. Macs Fan Control ：控制mac风扇转速
16. MacZip
17. Mos ： 鼠标
18. MTMR ：
19. 妙言
20. Navicat Premium ：数据库管理
21. Paste：Mac 剪贴板工具
22. RDM ：redis图形界面管理
23. ShadowsocksX-NG-R8
24. SnippetsLab : 代码片段Solid Converter Mac记录
25. Solid Converter Mac : pdf转换
26. Sourcetree ：
27. Stats
28. Thor Launcher ：快捷键启动app
29. ToDesk
30. Typora： Mac 平台上的一款帮助用户编辑 markdown语法文本的 Mac 软件 
31. Tuxera Disk Manager
32. Unit : 把网站打包成app
33. WeChatVideoDownloader : 微信视频号下载
34. Wondershare PDFelement Pro ：万兴pdf编辑器
35. 右键专业助手 ： 可以替换超级右键
36. zsh-autosuggestions：zsh 命令自动补全插件

```
1-把插件仓库克隆到$ZSH_CUSTOM/plugins (默认位置是 ~/.oh-my-zsh/custom/plugins)
2-git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions，设置~/.zshrc，把zsh-autosuggestions添加到 Oh My Zsh 要加载的插件列表中1. 1-git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
3-在~/.zshrc，把zsh-syntax-highlighting添加到.zshrc 的插件列表中
4-source ~/.zshrc 使配置生效
```
37. zsh-syntax-highlighting：高亮显示常用命令

```
1-git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
2-在~/.zshrc，把zsh-syntax-highlighting添加到.zshrc 的插件列表中
3-source ~/.zshrc 使配置生效
```

---


### 谷歌插件

```
谷歌网上应用商店：https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo（科学上网）
Crx搜搜：https://www.crxsoso.com/webstore/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo
Edge外接程序：https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd
```

1. Tampermonkey（油猴）
实用脚本：
- 网盘直链下载助手：chrome-extension://gcalenpjmijncebpfijmoaglllgpjagf/ask.html?aid=ef8ad728-3d80-4cc4-a3d9-80411ef7a59a
- 搜素引擎切换器：chrome-extension://gcalenpjmijncebpfijmoaglllgpjagf/options.html#nav=7d0d69b8-e084-434e-9ba9-e0a36c3b1878+editor
- 网盘智能识别助手：chrome-extension://gcalenpjmijncebpfijmoaglllgpjagf/options.html#nav=d4e1099e-3cbf-439a-bfc6-b021595560e4+editor
- 网页加速器：chrome-extension://gcalenpjmijncebpfijmoaglllgpjagf/options.html#nav=25ed8cdf-5ba1-4a6b-8098-84ba92786e51+editor
- mactype助手：chrome-extension://gcalenpjmijncebpfijmoaglllgpjagf/options.html#nav=0bc215c8-8b68-40d8-8c8a-2cfbd6e4503d+editor
- IDM Integration Module ：使用Internet下载管理器下载文件
2. KeePassXC-Browser ：KeePassXC与现代Web浏览器的集成
3. Proxy SwitchyOmega ：轻松快捷地管理和切换多个代理设置。
4. The Great Suspender Original ：冻结暂时用不到的标签页，以便释放系统资源。

---


windows软件下载：https://winwk.com/
a姐资源分享：https://www.abskoop.com/
百度开发者搜索：https://kaifa.baidu.com/
pikpak网盘：https://mypikpak.com/（科学上网）
Hexo + fluid + github page blog：https://lambert-pro.github.io/

🔓解锁复制/右键限制

```
javascript:!function()%7Bfunction t(e)%7Be.stopPropagation(),e.stopImmediatePropagation%26%26e.stopImmediatePropagation()%7Ddocument.querySelectorAll("*").forEach(e%3D>%7B"none"%3D%3D%3Dwindow.getComputedStyle(e,null).getPropertyValue("user-select")%26%26e.style.setProperty("user-select","text","important")%7D),%5B"copy","cut","contextmenu","selectstart","mousedown","mouseup","mousemove","keydown","keypress","keyup"%5D.forEach(function(e)%7Bdocument.documentElement.addEventListener(e,t,%7Bcapture:!0%7D)%7D),console.log("解除限制成功啦！")%7D()%3B
```

🔑显示密码

```
javascript:!function()%7Bfor(var t%3Ddocument.getElementsByTagName("input"),e%3D0%3Be<t.length%3Be%2B%2B)"password"%3D%3D%3Dt%5Be%5D.getAttribute("type")%26%26t%5Be%5D.setAttribute("type","text")%7D()%3B
```

重启Chome

```
chrome://restart
```

### phpstrom插件
1. Chinese 中文包
1. Chinese PHP Document
1. CodeGlance3
1. Codelgniter 3
1. Dash
1. GitHub Copilot
1. IDE Eval Reset
1. PHP Annotations
1. Rainbow Brackets
1. Swoole IDE Helper