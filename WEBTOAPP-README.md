# WebToApp 前端打包说明

这个工程已经整理成可被 WebToApp「Frontend / 前端」流程识别的标准项目根目录。

## 关键结构

- `package.json`：提供 NPM 项目入口与 `npm run build`
- `build.mjs`：无第三方依赖的构建脚本
- `dist/`：构建后输出目录
- `index.html`：PWA 主入口
- `assets/`：CSS、JavaScript、图标等静态资源

## 在 WebToApp 中

框架可以保持 `static website`，包管理器选择 `NPM`，输出目录填写 `dist`，然后执行/构建。

这个项目不依赖 Vite、React、Vue 等第三方构建依赖，因此不需要联网安装前端依赖即可执行 `npm run build`。

如果 WebToApp 直接要求选择「Frontend」的构建产物，也可以直接指定这个工程里的 `dist` 目录。


本版本同时包含 v1.44 的语言断句开关与记忆总结预设管理改动。推荐使用 `Frontend` → `NPM`，输出目录填写 `dist`。
