# 基于昇腾的具身系统智能实践

这是一个展示 IPADS 实验室在昇腾平台上具身智能实践成果的网页项目。
https://sjtu-ipads.github.io/Ascend-Embody-Web/

## 🚀 快速开始

### 安装依赖

```bash
npm install
```

### 本地开发

```bash
npm run dev
```

访问 `http://localhost:5173` 查看网页

### 构建生产版本

```bash
npm run build
```

构建结果将生成在 `dist` 目录

### 预览生产版本

```bash
npm run preview
```

## 📁 项目结构

```
Ascend-Embody-Web/
├── index.html          # 主 HTML 文件
├── style.css           # 样式文件
├── main.js            # JavaScript 交互逻辑
├── package.json       # 项目配置
├── design.md          # 设计文档
└── videos/            # 视频资源目录（待添加）
```

## 🎨 设计特点

- **学术简约风格**：参考 MotionTrans 网站设计
- **响应式布局**：适配各种屏幕尺寸
- **动态交互**：平滑滚动、卡片动画、视差效果
- **数据可视化**：清晰展示性能指标和对比数据

## 📝 内容板块

1. **首屏展示区**：项目标题、机构信息、资源链接
2. **核心价值**：昇腾平台的三大优势
3. **适配能力**：多模型、多机械臂支持
4. **技术攻关**：关键技术突破点
5. **落地实践**：真实场景演示视频
6. **横向评测**：跨平台性能对比

## 🎬 添加视频和图片

将您的视频和图片文件放入 `videos/` 目录，然后在 HTML 中替换占位符：

```html
<!-- 替换视频占位符 -->
<div class="video-placeholder">
    <video autoplay loop muted playsinline>
        <source src="videos/your-video.mp4" type="video/mp4">
    </video>
</div>

<!-- 或使用 GIF -->
<img src="videos/robot-demo.gif" alt="机械臂演示">
```

## 🔧 自定义

### 修改颜色主题

编辑 `style.css` 中的 CSS 变量：

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --accent-color: #f59e0b;
    /* ... */
}
```

### 添加新内容

在 `index.html` 中添加新的 section 即可，样式会自动应用。

## 📄 许可

版权所有 © 2025 IPADS Lab, Shanghai Jiao Tong University
