<img src="build/icons/128x128.png" alt="logo" height="80" align="right" />

# Electron Xiami

[English README](README.en.md)

Linux和macOS下的虾米客户端 (虾米播放器)，使用[Electron](https://electron.atom.io)构建。

![screenshot_macos](https://user-images.githubusercontent.com/13460738/34644583-38a2a2b6-f39e-11e7-8831-e21475427ccb.jpg)

![linux_player_full](https://user-images.githubusercontent.com/13460738/38477881-769de2b6-3c09-11e8-8c75-75a13da42df2.png)

![linux_player_mini](https://user-images.githubusercontent.com/13460738/38477883-79400990-3c09-11e8-804f-b2e7bdd262fc.png)

![linux_player_radio](https://user-images.githubusercontent.com/13460738/38477885-7bd5355e-3c09-11e8-93a5-794250b5ceb9.png)

*请注意：这个项目不是虾米音乐的官方客户端。如果有任何问题请反馈到[这个链接](https://github.com/eNkru/electron-xiami/issues)。*

## 功能
* 虾米音乐在线
* 虾米电台 （测试）
* 迷你播放模式
* 桌面歌词 （测试）
* 最小化到托盘
* 系统提示
* 播放控制
* 用户配置
* 多语言支持

## 安装需求
* [GIT](https://git-scm.com/)
* [NPM](https://www.npmjs.com/)

## 编译和安装
本地编译运行
```
git clone https://github.com/eNkru/electron-xiami.git
cd electron-xiami
npm install
npm start
```
编译打包版本
```
npm run dist:linux
```

## 发布
```
npm version (new release version)
git push origin master
git push origin --tags
npm publish
```

## 下载
预打包版本请点击[这个链接](https://github.com/eNkru/electron-xiami/releases)下载。

## 授权协议
[MIT](https://github.com/eNkru/electron-xiami/blob/master/LICENSE)
