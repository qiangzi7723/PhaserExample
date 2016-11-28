# Phaser-Example
##### 24好玩 Phaser本地开发用脚手架

#### 项目依赖
- [Phaser](http://phaser.io/) - H5游戏引擎
- [Zepto](http://zeptojs.com/) - 轻量级的针对现代高级浏览器的JavaScript库
- [RequireJS](http://requirejs.org/) - JavaScript模块加载器

---

#### 目录结构
- assets
	- audio
	- images
- js
	- game-manager.js 游戏管理器
	- game-state.js 游戏场景（只需要在这个脚本中开发）
	- main.js 脚本总入口
	- music-manager.js 音乐管理器
- index.html

---

#### 游戏场景说明
游戏场景分为5个，其中主要游戏逻辑运行在play场景：
- boot 启动场景
- preload 加载场景
- create 开始场景
- play 游戏场景
- end 结束场景
