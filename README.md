# Reposter Share

一个用于将 DOCX、PDF、PPT、文字或图片资料整理为海报的 Codex Skill。

A Codex skill for turning DOCX, PDF, PPT, text, or image-based project materials into editable Chinese  report posters.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a42fbbca-d7ed-49b9-8502-b7a0ecb1efed" alt="Reposter Share BIM海报制作流程" width="100%">
</p>

---

## 中文说明

### 功能

Reposter Share 提供一套完整、可执行的海报制作流程，包括：

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
使用 $reposter-share，将这份项目 Word 文档制作成一张 项目汇报海报。
```

### 工作流程

1. 读取并核对项目资料。
2. 整理标题、项目概况、应用点和成果文案。
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


# Reposter Share

一个将 DOCX、PDF、PPT、文字或图片资料整理为专业项目汇报、展示海报与可编辑视觉版面的 Codex Skill。BIM 项目汇报是适用场景之一，但不是唯一用途。

A Codex skill for turning DOCX, PDF, PPT, text, or image-based materials into professional project presentations, posters, and editable visual layouts. BIM reporting is one supported use case, not the only one.

<p align="center">
  <img src="https://github.com/user-attachments/assets/c4a6d2c2-c24d-4c6f-a7db-08b9bdbfe071" alt="Reposter Share 项目汇报与海报制作流程" width="100%">
</p>

---

## 中文说明

### 功能

Reposter Share 提供一套完整、可执行的项目汇报与海报制作流程，包括：

- 从 DOCX、PDF、PPT、文字或图片中提取关键内容
- 将长篇资料压缩为标题、概况、核心内容与成果文案
- 识别并选择主图、辅助图、分析图、对比图和展示素材
- 清理、裁剪或按需重建视觉素材
- 使用 HTML/CSS、PPT、PDF、Figma 或 Illustrator 建立可编辑版式
- 根据项目属性匹配技术、教育、商业、文化或宣传视觉风格
- 保持中文、数据、标题和标注为真实可编辑文本
- 输出适合汇报、展示和传播的 PNG 或 PDF

### 适用范围

适用于项目汇报、课程作业、研究成果展示、技术展板、BIM 成果展示、产品或服务介绍、文化宣传、活动海报及常规视觉版面制作。

本共享版不保证生产级超高清输出，也不包含专用高清渲染配方、固定生成提示词、精确版式参数或私有后处理流程。实际效果取决于输入资料、图像工具和排版环境。

### 安装

使用 Codex 的 Skill Installer，从以下仓库安装根目录：

```text
https://github.com/arthurjindev/poster
```

安装后重启 Codex。

### 使用示例

```text
使用 $reposter-share，将这份项目资料制作成一张专业、可编辑的项目汇报海报。
```

### 工作流程

1. 读取并核对原始资料。
2. 整理标题、概况、核心内容和成果文案。
3. 分类并选择一张主图及三至四张辅助图。
4. 清理、裁剪或按需重建视觉素材。
5. 建立可编辑的项目汇报或海报版式。
6. 匹配项目所需的视觉风格并输出 PNG/PDF。

---

## English

### Features

Reposter Share provides a complete and practical workflow for project presentations and posters:

- Extract key information from DOCX, PDF, PPT, text, or images
- Condense long materials into titles, summaries, core points, and results
- Select main visuals, supporting images, analysis graphics, and comparisons
- Clean, crop, or recreate visual assets when needed
- Build editable layouts with HTML/CSS, PowerPoint, PDF, Figma, or Illustrator
- Match technical, educational, commercial, cultural, or promotional visual styles
- Keep text, facts, captions, and annotations editable
- Export presentation-ready PNG or PDF deliverables

### Intended Use

Suitable for project reports, coursework, research displays, technical boards, BIM result presentations, product or service introductions, cultural communications, event posters, and general visual layouts.

This shared edition does not guarantee production-grade ultra-high-resolution output. It does not include proprietary rendering recipes, fixed generation prompts, exact layout parameters, or private post-processing workflows. Results depend on the source material, image tools, and layout environment.

### Installation

Use the Codex Skill Installer with the repository root:

```text
https://github.com/arthurjindev/poster
```

Restart Codex after installation.

### Example

```text
Use $reposter-share to turn these project materials into a professional, editable presentation poster.
```

### Workflow

1. Read and verify the source material.
2. Organize the title, summary, core content, and results.
3. Select one main visual and three to four supporting visuals.
4. Clean, crop, or recreate visual assets when needed.
5. Build an editable project-report or poster layout.
6. Match the required visual style and export PNG/PDF.

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
<img width="3180" height="2160" alt="clipboard" src="https://github.com/user-attachments/assets/c4a6d2c2-c24d-4c6f-a7db-08b9bdbfe071" />
