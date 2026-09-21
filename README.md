# 精华经验启发的高三学习教练 Skill

一个面向高三、复读和艺考文化课学习的 Codex Skill。它把公开可查的全日制备考方法整理成可执行闭环：

> 三级目标 → 学情诊断 → 弱科补强 → 每日保温 → 错题复盘 → 阶段复测

本项目是基于公开资料进行的独立整理，不是精华学校官方产品，也不存在授权、合作或背书关系。

## 能做什么

- 根据最近考试成绩和排名判断主要矛盾；
- 区分知识漏洞、审题遗漏、计算错误、时间分配等失分原因；
- 制定有产出、有验收标准的日计划和周计划；
- 建立单项补弱、错题复原和阶段复测闭环；
- 为语文、数学、英语、物理、化学、生物、历史、地理、政治提供学科诊断框架；
- 支持高三、复读生和艺考文化课的学习复盘与陪学。

## 安装

### 用 Skill Installer 安装

在 Codex 中输入：

```text
使用 $skill-installer，从 https://github.com/1789705185-crypto/jinghua-gaosan-study-skill 安装 jinghua-gaosan-study。
```

### 手动安装

1. 点击 GitHub 页面上的 `Code` → `Download ZIP`；
2. 解压后确保 Skill 目录中直接包含 `SKILL.md`；
3. 将该目录放入 Codex 可读取的个人或项目 Skill 目录；
4. 如果没有立即显示，重启 Codex。

## 使用示例

```text
使用 $jinghua-gaosan-study，根据我的成绩、目标和可用时间制定本周高三学习计划。

地区与考试模式：北京新高考
选科：物理、化学、生物
最近三次成绩：……
目标成绩：……
学校固定作息：……
每天可支配时间：……
目前最弱模块：……
```

也可以直接提出单项任务：

```text
使用 $jinghua-gaosan-study，复盘这次数学考试。
使用 $jinghua-gaosan-study，给英语阅读做一个两周补弱计划。
使用 $jinghua-gaosan-study，把我今天晚上的三小时排成可验收的任务。
```

## 文件结构

```text
jinghua-gaosan-study/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── jinghua-basis.md
    ├── subject-playbooks.md
    └── templates.md
```

## 方法边界

- 不承诺具体提分幅度或录取结果；
- 不把个别高分经验当成普遍规律；
- 不照搬过期课表、教材版本或北京卷安排；
- 涉及当年考试政策时，应以省级考试院和教育部门的最新官方信息为准；
- 学习规划不能替代任课教师、学校心理教师或专业医疗支持。

## 公开资料来源

- [精华学校高考全日制官网](https://gaokao.jinghua.com/)
- [精华教育考试研究院《学生自主学习手册》](https://ksyun.jinghua.com/jinghuacom/test/shouce.pdf)
- [京报网：高考高分有何秘籍？精华学校学长传授攻略](https://news.bjd.com.cn/2025/07/01/11218209.shtml)
- [OpenAI：Build skills](https://learn.chatgpt.com/docs/build-skills)

## 许可证与商标

本项目代码和原创文本按 [MIT License](LICENSE) 提供。引用资料的权利归原权利人所有。“精华”等名称及相关商标归其合法权利人所有，本许可证不授予任何商标使用权。
