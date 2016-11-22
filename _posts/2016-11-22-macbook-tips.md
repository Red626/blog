---
layout: post
categories: tools
---
##软件
- Charles（抓包工具）
- Atom（编辑器，插件：activate-power-mode、atom-beautify、color-picker、markdown-writer）
- Karabiner（外接键盘修改）
- BombSquad（炸弹游戏，可用多个iphone连接对战）
- VLC（多格式视频播放器）
- ShadowsocksX（翻墙软件）
- Google Chrome（最强播放器，插件：Gloria、OneTab、Postman、DownFaster、Web Developer、FeHelper、广告终结者、掘金、阅读模式、网页截图、有道云笔记网页剪报、Clear Cache）
- musicbox（网易云音乐python版）

##相关问题解决
- MacOS10.12以上开启安装任意来源软件：终端执行sudo spctl --master-disable
- 安装Command Line Tools for Xcode：xcode-select --install
- 安装homebrew：uby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

##Jekyll编译网站和博客
- 安装：sudo gem install -n /usr/local/bin/ jekyll bundler
- 编译&运行：bundle exec jekyll serve
