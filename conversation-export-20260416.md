# 对话导出 | 0408skill创建 作业记录

**导出时间**：2026-04-16 19:26  
**作业名称**：0408skill创建  
**作业要求**：参考教师演示过程，使用对话创建学习skill，完成后将对话过程使用/export 导出对话内容，上传个人github仓库。

---

## 对话过程

### 用户：帮我完成这个作业

（上传截图：0408skill创建作业说明）

作业内容：
- 题量：1，满分：100
- 作答时间：04-08 12:11 至 04-17 12:12
- 要求：参考教师演示过程，使用对话创建学习skill，完成后将对话过程使用/export 导出对话内容，上传个人github仓库。
- 作业提交案例：https://github.com/yangjh-xbmu/2024news-1

---

### AI助手：分析作业要求

作业步骤拆解：

**第一步：使用对话创建一个学习 Skill**  
在 WorkBuddy 中通过对话来创建一个 Skill。

**第二步：导出对话内容**  
完成 Skill 创建后，在对话框中输入 `/export` 导出本次对话内容。

**第三步：上传到个人 GitHub 仓库**  
将导出的内容上传到个人 GitHub 仓库。

---

### 用户：帮我创建一个数学公式查询的skill

---

### AI助手：创建数学公式查询 Skill

加载了 `skill-creator` skill，按照标准流程创建 Skill。

#### 创建过程

**Step 1：初始化目录结构**

在用户级别路径创建 Skill 目录：
```
C:\Users\hp\.workbuddy\skills\math-formula-query\
├── SKILL.md
└── references\
    └── formulas.md
```

**Step 2：编写公式参考文档 `references/formulas.md`**

包含以下数学公式分类：
- 一、代数公式（乘法公式、一元二次方程求根公式、指数对数运算）
- 二、三角函数公式（基本关系、和差角、二倍角、半角、积化和差）
- 三、平面几何公式（三角形、圆、各类图形面积）
- 四、立体几何公式（表面积与体积对照表）
- 五、数列公式（等差数列、等比数列）
- 六、微积分公式（常用导数、运算法则、常用积分、基本定理）
- 七、概率与统计（排列组合、概率基础、统计量）

**Step 3：编写 `SKILL.md`**

```yaml
---
name: math-formula-query
description: >
  This skill should be used when the user asks about mathematical formulas,
  equations, or mathematical concepts. Trigger when users ask questions like:
  "查数学公式", "数学公式查询", "求导公式", "积分公式", "三角函数公式",
  "二次方程求根公式", "等差数列求和", "等比数列", "概率公式", "排列组合",
  "几何面积公式", "体积公式", "微积分", "导数", "面积公式", "勾股定理",
  "余弦定理", "正弦定理", "对数公式", "指数运算", "二项式定理",
  "统计公式", "方差", "标准差", "帮我查一下…公式", "…怎么算",
  "数学题怎么解", "这道数学题", "公式是什么".
---
```

工作流程设计：
1. 识别查询类别（代数/三角/几何/数列/微积分/概率统计）
2. 查阅 `references/formulas.md` 找到对应公式
3. 以 LaTeX 格式呈现公式，附中文说明
4. 如用户提供具体数学题，应用公式逐步求解

**Step 4：打包 Skill**

生成打包文件：`math-formula-query.zip`

---

#### Skill 成果展示

| 分类 | 内容 |
|------|------|
| **代数** | 乘法公式、二次方程求根公式、韦达定理、指数/对数运算 |
| **三角函数** | 基本关系、和差角、二倍角、半角、积化和差 |
| **平面几何** | 三角形（海伦公式/正余弦定理）、圆、各类面积公式 |
| **立体几何** | 正方体/圆柱/圆锥/球的表面积与体积 |
| **数列** | 等差数列、等比数列通项与求和公式 |
| **微积分** | 常用导数表、运算法则、常用积分表、基本定理 |
| **概率统计** | 排列组合、二项式定理、概率公式、均值/方差/标准差 |

---

### 用户：/export

---

### AI助手：导出本次对话

生成对话导出文件：`conversation-export-20260416.md`

---

## 创建的 Skill 文件

### SKILL.md 完整内容

```markdown
---
name: math-formula-query
description: >
  This skill should be used when the user asks about mathematical formulas,
  equations, or mathematical concepts. Trigger when users ask questions like:
  "查数学公式", "数学公式查询", "求导公式", "积分公式", "三角函数公式",
  "二次方程求根公式", "等差数列求和", "等比数列", "概率公式", "排列组合",
  "几何面积公式", "体积公式", "微积分", "导数", "面积公式", "勾股定理",
  "余弦定理", "正弦定理", "对数公式", "指数运算", "二项式定理",
  "统计公式", "方差", "标准差", "帮我查一下…公式", "…怎么算",
  "数学题怎么解", "这道数学题", "公式是什么".
---

# 数学公式查询 Skill

## 目的

To provide quick and accurate lookup of mathematical formulas across key areas 
including algebra, trigonometry, geometry, calculus, and statistics.

## 触发场景

Use this skill when:
- Users ask to look up any mathematical formula or theorem
- Users need help with derivations, integration, or algebraic identities
- Users ask "how to calculate X" for a math concept
- Users reference a specific math topic

## 工作流程

### Step 1：识别查询类别
### Step 2：查阅公式参考文档（references/formulas.md）
### Step 3：呈现公式（LaTeX格式 + 中文说明 + 示例）
### Step 4：解答延伸问题
```

---

## 总结

本次作业通过与 AI 对话，成功创建了一个**数学公式查询学习 Skill**：

- ✅ 使用对话驱动的方式完成 Skill 创建
- ✅ Skill 已安装到用户级别路径 `~/.workbuddy/skills/math-formula-query/`
- ✅ 包含完整的数学公式参考文档（7大类，100+公式）
- ✅ 已打包为 `math-formula-query.zip` 供分发使用
- ✅ 使用 `/export` 导出本次对话内容

**下一步**：将本文件上传至个人 GitHub 仓库完成作业提交。
