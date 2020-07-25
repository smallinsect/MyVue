# MyVue
# 搭建Vue的环境
node.js教程

- https://www.runoob.com/nodejs/nodejs-tutorial.html

node.js官网

- https://node.js.org/en

安装node.js

查看版本

```
node -v
```

## nvm工具，管理多个node.js版本

### Linux环境

- https://github.com/nvm-sh/nvm

安装

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
```

### windows环境

- https://github.com/coreybutler/nvm-windows

下载

- https://github.com/coreybutler/nvm-windows/releases

点击下载

[nvm-noinstall.zip](https://github.com/coreybutler/nvm-windows/releases/download/1.1.7/nvm-noinstall.zip)

安装包

[nvm-setup.zip](https://github.com/coreybutler/nvm-windows/releases/download/1.1.7/nvm-setup.zip)

安装好了，在终端输入，查看版本。

```
nvm version
```

查看node.js所有版本

```
nvm ls-remote
```

### 安装node.js

设置淘宝镜像

打开nvm的安装路径，默认安装路径是：C:\Users\zhong\AppData\Roaming\nvm

打开settings.txt，加入下面文件

```
root: C:\Users\zhong\AppData\Roaming\nvm  
path: C:\Program Files\nodejs 
arch: 64 
proxy: none
node_mirror: http://npm.taobao.org/mirrors/node/
npm_mirror: https://npm.taobao.org/mirrors/npm/
```

安装指定版本

```
nvm install v10.14.2
```

安装最新版本

```
nvm install node
```

下载长期维护版本

```
nvm install --lts node
```

列出已经安装的版本

```
nvm list
```

卸载

```
nvm uninstall 11.13.0
```

### node命令

查看node版本

```
node -v
```

切换node版本

```
node use v12.16.1
node use v10.14.2
```

## yarm

下载链接

- https://classic.yarnpkg.com/zh-Hans/docs/install/#windows-stable

查看安装的版本，在终端输入

```
yarn -v
```

## vue cli

官网

- https://cli.vuejs.org/guide/installation.html

安装

```bash
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```

查看版本

```bash
vue --version
```

更新

```bash
npm update -g @vue/cli

# OR
yarn global upgrade --latest @vue/cli
```

# 开发Vue