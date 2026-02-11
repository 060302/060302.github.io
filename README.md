# 060302.github.io

随手记

## 项目介绍

这是一个基于 Vue 3 + TypeScript + Vite 的现代化 Web 应用。

## 技术栈

- **Vue 3.5.28** - 渐进式 JavaScript 框架
- **TypeScript 5.9.3** - JavaScript 的超集，提供类型安全
- **Vite 7.3.1** - 下一代前端构建工具
- **Composition API** - Vue 3 的组合式 API

## 开发

### 安装依赖

```bash
npm install
```

### 开发服务器

```bash
npm run dev
```

访问 http://localhost:5173 查看应用

### 构建

```bash
npm run build
```

构建产物将生成在 `dist` 目录

### 预览构建结果

```bash
npm run preview
```

## 项目结构

```
.
├── src/
│   ├── App.vue         # 根组件
│   ├── main.ts         # 应用入口
│   ├── style.css       # 全局样式
│   └── vite-env.d.ts   # TypeScript 类型声明
├── index.html          # HTML 模板
├── vite.config.ts      # Vite 配置
├── tsconfig.json       # TypeScript 配置
└── package.json        # 项目依赖
```

## 更新日志

### v1.0.0 (2026-02-11)

- 🎉 从 Vue 2 升级到 Vue 3
- 💪 添加 TypeScript 支持
- ⚡️ 使用 Vite 作为构建工具
- 📦 更新所有依赖到最新版本
