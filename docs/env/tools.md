# 开发环境

## 版本管理
[git](https://git-scm.com/)  
[svn](https://subversion.apache.org/)

## Node
[node](https://nodejs.org/en)  
[nvm](https://github.com/coreybutler/nvm-windows/releases)
- nvm ls  列出所有安装的版本
- nvm install   安装指定版本，如：安装v4.4.0，nvm install v4.4.0
- nvm uninstall   删除已安装的指定版本，语法与install类似
- nvm use   切换使用指定的版本node
- nvm --help 查看所有帮助命令

## 包管理器
### npm
```bash
# 查看当前源地址
npm config get registry
# 切换至淘宝源
npm config set registry=http://registry.npm.taobao.org/
# 切换至npm源
npm config set registry=http://registry.npmjs.org
```
pnpm、yarn

## 开发工具
VSCode  
VSCode常用插件
- git相关：Git Graph、GitLens
- 汉化：Chinese(Simplified)
- 静态服务器：Live Server
- 格式化： EditorConfig for VS Code、ESLint、Prettier - Code formatter
- TODO提示：Todo Tree
- 开发提示：Auto Close Tag、Auto Complete Tag、Auto Rename Tag
- vue3： Volar
