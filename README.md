# 马来西亚学校 Logo 收集项目 🇲🇾

## 项目简介

**马来西亚学校 Logo 收集项目** 旨在建立一个集中化、标准化的开源资源库，收录马来西亚各级教育机构（幼稚园、小学、中学、大学）及其附属社团/团学组织的标志（Logo）。

本项目为教育工作者、设计师、研究者、校友及其他有兴趣的人士提供高质量的学校及社团标志资源，方便在非商业用途下进行设计和参考。

---

## 项目结构

以下是项目的目录结构说明：

```plaintext
Malaysia_School_Logo_Collection/
│
├── README.md
├── LICENSE
│
├── 幼稚园 (Kindergarten)/
│   ├── 某某幼稚园/
│   │   ├── logo.png
│   │   ├── logo.svg
│   │   ├── README.md
│
├── 小学 (Primary_School)/
│   ├── 吉隆坡XX小学/
│   │   ├── logo.png
│   │   ├── logo.svg
│   │   ├── 社团 (Clubs)/
│   │   │   ├── XX小学舞蹈团/
│   │   │   │   ├── logo.png
│   │   │   │   ├── logo.svg
│   │   │   │   ├── README.md
│
├── 中学 (Secondary_School)/
│   ├── 永平独中/
│   │   ├── logo.png
│   │   ├── logo.svg
│   │   ├── 社团 (Clubs)/
│   │       ├── 永平独中篮球队/
│   │       │   ├── logo.png
│   │       │   ├── logo.svg
│   │       │   ├── README.md
│
├── 大学 (University)/
│   ├── 马来亚大学 (UM)/
│   │   ├── logo.png
│   │   ├── logo.svg
│   │   ├── 社团 (Clubs)/
│   │       ├── UM戏剧社/
│   │       │   ├── logo.png
│   │       │   ├── logo.svg
│   │       │   ├── README.md
│
├── 其他教育机构 (Other_Educational_Institutions)/
│   ├── 教育培训中心 (XYZ Learning Center)/
│   │   ├── logo.png
│   │   ├── logo.svg
│   │   ├── README.md
│
└── 附录与工具 (Assets_and_Tools)/
    ├── template/          # 提供README模板和文件格式要求
    ├── logo_guidelines/   # 标志上传与格式指南
    └── resources/         # 相关资源（如教育机构列表、设计规范等）
```

---

## 如何贡献

我们欢迎任何人提交或完善项目中的标志资源。

### **1. 提交流程**

1. **Fork 本仓库** 到你的 GitHub 账号。
2. **Clone** 仓库到本地：
   ```bash
   git clone https://github.com/你的用户名/Malaysia_School_Logo_Collection.git
   ```
3. 在相应目录下创建文件夹，并上传标志文件：
   - 确保按以下规范命名：
     - `logo.png`（PNG 格式，透明背景）
     - `logo.svg`（矢量图）
   - 在文件夹中添加 **README.md**，提供学校/社团的基本信息。
4. **提交更改**：
   ```bash
   git add .
   git commit -m "Add logo for [学校/社团名称]"
   git push origin main
   ```
5. 提交 **Pull Request**，描述你的贡献内容。

### **2. Logo 文件要求**

- **格式**：SVG（矢量图） 和 PNG（透明背景）。
- **尺寸**：建议 1024px x 1024px。
- **命名规范**：
  - 学校标志：`logo.png`、`logo.svg`
  - 社团标志：`logo.png`、`logo.svg`。
- **README.md 内容模板**：
  ```markdown
  # 学校/社团名称

  - **成立年份**：xxxx 年
  - **所在地**：马来西亚 xxx 州 xxx 地区
  - **标志意义**：简要描述 Logo 设计及颜色的象征意义。
  - **用途**：学校/社团标志使用场景。
  ```

---

## 使用条款与许可证

- **许可证**：本项目基于 [MIT License](LICENSE) 开源发布。
- **Logo 版权声明**：
  - 仓库中所有标志版权归原始学校或组织所有。
  - 本项目仅供学习、参考及非商业用途，任何商业用途需获得原始版权方授权。

---

## 常见问题（FAQ）

1. **我可以上传非马来西亚的学校 Logo 吗？**
   - 不可以，目前本项目仅收录马来西亚教育机构及其社团标志。有需求或者提议，欢迎 Issue！
2. **我需要提供什么文件？**
   - 至少包括 `logo.png` 和 `logo.svg`，并填写 README 文件。
3. **如何联系项目维护者？**
   - 请通过 GitHub 提交 Issue，或发送 Pull Request 进行讨论。

---

## 特别鸣谢

感谢所有为此项目贡献标志、维护内容及提供资源的朋友们！你的支持让项目持续发展。

---

## 未来发展方向

- 添加自动化工具检查提交的 Logo 文件格式。
- 在 GitHub Pages 上构建一个在线 Logo 画廊展示。
- 增加学校和社团分类的详细列表，方便快速查找。

---

**让我们一同打造属于马来西亚教育的视觉文化资源库！** 🇲🇾
