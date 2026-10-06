# qingjie-pcos-script

面向多囊健康调理与备孕赛道的中文短视频口播文案 Skill。

它用于把选题转化为受众明确、观点集中、表达克制、适合提词器朗读的完整逐字稿，并在交付前检查医学表达、平台风险和行动引导。

## 主要能力

- 根据备孕阶段与具体处境识别目标受众。
- 区分认识型内容与痛点型内容，避免混用内容目的。
- 使用五步口播结构组织开头、冲突、分析、方法和结尾。
- 检查绝对化医疗结论、效果承诺、恐惧表达和强行导流。
- 输出主标题、封面大字、备选标题和提词器版逐字稿。

## 安装

克隆到通用 Agents Skill 目录：

```powershell
git clone https://github.com/em19900822-sys/qingjie-pcos-script.git "$HOME\.agents\skills\qingjie-pcos-script"
```

也可以安装到 Codex 专用目录：

```powershell
git clone https://github.com/em19900822-sys/qingjie-pcos-script.git "$HOME\.codex\skills\qingjie-pcos-script"
```

安装或更新后，重新打开一个 Codex 对话，让 Skill 清单重新载入。

## 使用方式

提供目标人群、选题目的、原始素材和希望推动的行动，然后明确要求使用 `qingjie-pcos-script`。

示例：

> 使用 qingjie-pcos-script，把这个选题写成面向促排受挫期多囊女性的认识型口播稿。

## 更新

仓库是唯一主版本。修改 `SKILL.md` 后完成校验，再提交并推送到 GitHub。通过 Git 安装的电脑可以运行：

```powershell
git pull
```

## 内容边界

健康与备孕内容应核对可靠来源，区分医学事实、经验判断和个体建议。本 Skill 不替代医生诊断或个体化治疗。

## 许可

当前仓库未附开源许可证，内容版权保留。
