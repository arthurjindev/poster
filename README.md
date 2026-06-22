# Reposter Share

一个用于将 DOCX、PDF、PPT、文字或图片资料整理为中文 BIM 项目汇报海报的 Codex Skill。

A Codex skill for turning DOCX, PDF, PPT, text, or image-based project materials into editable Chinese BIM report posters.

---

## 中文说明

### 功能

Reposter Share 提供一套完整、可执行的 BIM 海报制作流程，包括：

- 提取项目名称、地点、面积、用途及 BIM 应用点
- 将长篇项目资料压缩为适合海报展示的简洁文案
- 识别建筑效果图、机电模型、局部节点、剖面、点云及优化对比等图片类型
- 使用 HTML/CSS、PPT、PDF、Figma 或 Illustrator 建立可编辑版式
- 保持中文、数据、标题和标注为真实可编辑文本
- 输出适合普通汇报与方案展示的 PNG 或 PDF

### 适用范围

适合学校作业、项目汇报、BIM 成果展示、技术展板和常规宣传海报。

本共享版不保证生产级超高清输出，也不包含专用高清渲染配方、固定生成提示词、精确版式参数或私有后处理流程。实际效果取决于输入资料、图像工具和排版环境。

### 安装

使用 Codex 的 Skill Installer，从以下仓库安装根目录：

```text
https://github.com/arthurjindev/poster
```

安装后重启 Codex。

### 使用示例

```text
使用 $reposter-share，将这份项目 Word 文档制作成一张中文 BIM 项目汇报海报。
```

### 工作流程

1. 读取并核对项目资料。
2. 整理标题、项目概况、BIM 应用点和成果文案。
3. 分类并选择一张主图及三至四张辅助图。
4. 清理、裁剪或按需重建视觉素材。
5. 建立可编辑的蓝白技术风格版式。
6. 输出 PNG/PDF，并检查文字、图片和模块层级。

---

## English

### Features

Reposter Share provides a complete and practical workflow for BIM report posters:

- Extract project names, locations, areas, functions, and BIM application points
- Condense long project documents into concise poster copy
- Classify architectural, MEP, node-detail, section, point-cloud, and comparison visuals
- Build editable layouts with HTML/CSS, PowerPoint, PDF, Figma, or Illustrator
- Keep Chinese text, project facts, captions, and annotations editable
- Export presentation-ready PNG or PDF deliverables

### Intended Use

Suitable for coursework, project presentations, BIM result boards, technical displays, and general promotional posters.

This shared edition does not guarantee production-grade ultra-high-resolution output. It does not include proprietary rendering recipes, fixed generation prompts, exact layout parameters, or private post-processing workflows. Results depend on the source material, image tools, and layout environment.

### Installation

Use the Codex Skill Installer with the repository root:

```text
https://github.com/arthurjindev/poster
```

Restart Codex after installation.

### Example

```text
Use $reposter-share to turn this project Word document into a Chinese BIM report poster.
```

### Workflow

1. Read and verify the source material.
2. Organize the title, project facts, BIM applications, and results.
3. Select one main visual and three to four supporting visuals.
4. Clean, crop, or recreate visual assets when needed.
5. Build an editable blue-and-white technical layout.
6. Export PNG/PDF and validate text, images, and hierarchy.

---

## Repository Structure

```text
poster/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── content-mapping.md
    ├── image-rendering.md
    └── style-guide.md
```
