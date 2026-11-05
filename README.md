```
# Yilin 7A English Lesson Plan Skill
译林版牛津七年级英语教案生成技能

> 🎯 面向：学科教学（英语）研究生、初中英语教师
> 📄 输出：标准化 Markdown 教案，可直接在 GitHub / Obsidian / 语雀 预览使用
> 📚 适配教材：译林版牛津初中英语 7A（七年级上册）

## ✨ 支持课型
本技能支持译林7A每个单元六大板块：
- Welcome to the unit（听说导入）
- Reading（阅读课）
- Grammar（语法课）
- Integrated skills（综合技能）
- Study skills（学习策略）
- Task（写作课）

设计依据：义务教育英语新课标，围绕英语四大核心素养，常用 PWP / TBLT / PPP 教学模式。

## 🚀 快速上手
1. 打开仓库里的 [`prompt.md`](./prompt.md)，复制全部提示词
2. 修改提示词末尾的参数：单元、板块、额外需求
3. 发给AI，AI会直接输出 Markdown 格式教案
4. 复制生成结果，保存为 `.md` 文件，可上传到 examples 文件夹作为样例

## 📂 仓库结构
```

├── README.md                  # 仓库说明（当前文件）
├── prompt.md                  # AI 生成教案的核心提示词
├── template-lesson.md         # 教案 Markdown 模板
├── examples/
│   └── sample-7a-unit1.md     # 成品样例教案
└── .gitignore                 # 忽略文件配置

```

## 📖 样例预览
👉 查看样例教案：[examples/sample-7a-unit1.md](./examples/sample-7a-unit1.md)

## ⚠️ 重要说明 & 免责声明
1. AI生成内容仅作为**备课支架、初稿参考**，一定要人工核对难度、活动可行性、学情适配性，不能直接照搬进课堂。
2. 本项目仅用于教学研究、微格教学、研究生课程作业，教材版权归出版社所有，仓库内不存放教材原文。
3. 生成教案适合提交作业、微格试讲，正式授课请结合班级真实情况调整。

## 📝 更新日志
- v1.0：基础版本，支持译林7A六大板块教案生成，固定Markdown输出模板
```
