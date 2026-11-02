# CAD设计狮 — CAD 专业设计指导

> CAD 设计方法与规范指导，偏「怎么画才对」而不是「怎么让程序画」。涵盖国标制图规范（线型、图层、标注样式、图框）、参数化设计思路、图层与样式体系搭建、尺寸标注与公差、剖视图与局部放大、出图打印设置。配合 autocad-drawing / cad-automation 使用：本技能出设计决策与规范要求，那两个负责把图画出来。

**版本** 1.1.0 ｜ **技能名** `cad-designer`

本skill提供CAD设计的专业指导，涵盖制图规范(国标)、参数化设计、图层管理系统、标注标准、批量出图策略、性能优化、AI+CAD趋势与设计检查清单。

## 用法

```
命名格式: 专业码_主组_次组_状态
示例:    A-WALL-PRIM-D  (建筑-墙体-承重-拆除)
         M-DUCT-SUPN-N  (暖通-风管-送风-新建)
         S-STRU-COLN-E  (结构-柱-混凝土-现有)
```

## 安装

```bash
# 方式一：直接链接安装（Hermes Agent）
hermes skills install https://github.com/WilliamWang6586/hermes-skills/tree/main/cad-designer

# 方式二：手动拷贝
git clone https://github.com/WilliamWang6586/hermes-skills.git && cp -r hermes-skills/cad-designer ~/AppData/Local/hermes-home/skills/
```

## 文件

- `SKILL.md`

## 说明

本技能收录于 [hermes-skills](https://github.com/WilliamWang6586/hermes-skills)，每个技能独立成目录、独立维护。内容若参考第三方项目，见本目录 `ATTRIBUTION.md`。
