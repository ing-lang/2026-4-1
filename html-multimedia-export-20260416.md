# 对话导出 | 0416 HTML多媒体学习 Skill

**导出时间**：2026-04-16 23:22  
**作业名称**：0416 HTML/CSS 知识点学习  
**作业要求**：完成 Skill 的安装和使用；完成 HTML 或 CSS 某一个知识点的学习；将学习过程使用 Skill 保存到个人仓库；提交仓库链接。

---

## 作业背景

### 上一次作业回顾
- 已完成：math-formula-query Skill 创建（0408skill创建）
- 仓库地址：https://github.com/ing-lang/2026-4-1

---

## 对话过程

### 用户：帮我完成这个作业

（上传截图：0416 HTML/CSS 知识点学习作业说明）

作业内容：
- 完成 Skill 的安装和使用
- 完成 HTML 或 CSS 某一个知识点的学习
- 将学习过程使用 Skill 保存到个人仓库
- 提交仓库链接

---

### AI助手：分析作业要求

确认作业步骤：
1. 完成 Skill 的安装（已有 math-formula-query）
2. 学习 HTML 或 CSS 某一知识点
3. 创建对应的学习 Skill
4. 导出对话并上传 GitHub

---

### 用户：多媒体

---

### AI助手：创建 HTML 多媒体学习 Skill

加载了 `skill-creator` skill，按照标准流程创建 Skill。

#### 创建过程

**Step 1：初始化目录结构**

在用户级别路径创建 Skill 目录：
```
C:\Users\hp\.workbuddy\skills\html-multimedia\
├── SKILL.md
└── references\
    └── media-guide.md
```

**Step 2：编写媒体标签参考文档 `references/media-guide.md`**

包含以下内容：
- `<img>` 图片标签：基本语法、常用属性、示例
- `<audio>` 音频标签：controls、autoplay、loop、多格式支持
- `<video>` 视频标签：poster、playsinline、字幕轨道
- `<source>` 标签：多格式兼容、MIME类型
- `<picture>` 响应式图片：media查询、srcset
- `<track>` 字幕标签：kind属性、srclang
- 嵌入外部内容：`<iframe>`、`<embed>`、YouTube嵌入
- 媒体文件路径建议
- 最佳实践：懒加载、多格式兼容、性能优化

**Step 3：编写 `SKILL.md`**

```yaml
---
name: html-multimedia
description: >
  This skill should be used when the user asks about HTML multimedia elements,
  media tags, or how to embed audio/video/images in web pages. Trigger when
  users ask questions like: "HTML音频", "video标签", "插入图片", "音频标签",
  "视频标签", "多媒体标签", "img标签", "audio标签", "video属性",
  "HTML媒体元素", "网页嵌入视频", "网页嵌入音频", "响应式图片",
  "picture标签", "字幕轨道", "媒体格式", "MP4播放", "背景音乐".
---
```

工作流程设计：
1. 识别用户需求（图片/音频/视频/嵌入）
2. 查阅 `references/media-guide.md` 找到对应文档
3. 呈现使用指南（语法、属性、格式、示例、最佳实践）
4. 生成实战代码

**Step 4：打包 Skill**

生成打包文件：`html-multimedia.zip`

---

#### Skill 成果展示

| 标签 | 说明 |
|------|------|
| `<img>` | 图片插入、懒加载、响应式 |
| `<audio>` | 音频播放、多格式支持 |
| `<video>` | 视频播放、封面、静音播放 |
| `<source>` | 多格式兼容 |
| `<picture>` | 响应式图片 |
| `<track>` | 视频字幕 |
| `<iframe>` | 外部嵌入（YouTube等） |

---

### 用户：/export

---

### AI助手：导出本次对话

生成对话导出文件：`html-multimedia-export-20260416.md`

---

## 创建的 Skill 文件

### SKILL.md 完整内容

```markdown
---
name: html-multimedia
description: >
  This skill should be used when the user asks about HTML multimedia elements,
  media tags, or how to embed audio/video/images in web pages. Trigger when
  users ask questions like: "HTML音频", "video标签", "插入图片", "音频标签",
  "视频标签", "多媒体标签", "img标签", "audio标签", "video属性",
  "HTML媒体元素", "网页嵌入视频", "网页嵌入音频", "响应式图片",
  "picture标签", "字幕轨道", "媒体格式", "MP4播放", "背景音乐".
---

# HTML 多媒体标签 Skill

## 目的

To provide comprehensive reference for HTML multimedia elements including
<img>, <audio>, <video>, <source>, <picture>, and <track>.

## 工作流程

### Step 1：识别用户需求
### Step 2：查阅参考文档（references/media-guide.md）
### Step 3：呈现使用指南
### Step 4：实战代码生成
```

### references/media-guide.md 内容概要

- `<img>`：src、alt、width、height、loading、title 属性
- `<audio>`：controls、autoplay、loop、muted、preload，MP3/WAV/OGG格式
- `<video>`：controls、poster、playsinline、width、height，MP4/WebM/OGV格式
- `<source>`：src、type 属性，用于多格式兼容
- `<picture>`：media、srcset，用于响应式图片
- `<track>`：kind、src、srclang、label，用于字幕
- `<iframe>`：YouTube等外部嵌入
- 最佳实践：懒加载、多格式兼容、性能优化

---

## 总结

本次作业通过与 AI 对话，成功创建了一个**HTML 多媒体学习 Skill**：

- ✅ 选择学习 HTML 的"多媒体"知识点
- ✅ Skill 已安装到用户级别路径 `~/.workbuddy/skills/html-multimedia/`
- ✅ 包含完整的媒体标签参考文档（img/audio/video/source/picture/track/iframe）
- ✅ 已打包为 `html-multimedia.zip` 供分发使用
- ✅ 使用 `/export` 导出本次对话内容

**下一步**：将本文件上传至 GitHub 仓库完成作业提交。

---

## 相关资源

- **GitHub 仓库**：https://github.com/ing-lang/2026-4-1
- **本次作业文件**：html-multimedia-export-20260416.md
- **Skill 安装路径**：C:\Users\hp\.workbuddy\skills\html-multimedia\
- **Skill 打包文件**：html-multimedia.zip