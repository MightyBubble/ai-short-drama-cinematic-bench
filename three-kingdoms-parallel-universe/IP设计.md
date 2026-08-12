# 三国：平行宇宙 — IP / 游戏视觉概念设计

## 1. 概述

《三国：平行宇宙》是一套「平行宇宙乱世」原创 IP 的视觉概念合集。  
画面语法锚定 Sony Animation《Spider-Verse》三部曲：**印刷感、网点、套印错位、一宇宙一材质、冲击帧与残影**。

**生图铁律：** 提示词只写 Spider-Verse 画面语言（halftone / CMYK offset / smear / mixed 2D-3D 等）。  
题材名、阵营名、古装/水墨/书法等词不进提示词，避免模型被拉进古风参数；IP 命名只放在展示层与文案层。

## 2. 结构

| 层 | 内容 | 玩家感知 |
|---|---|---|
| 品牌层 | 展示页标题「三国：平行宇宙」 | 这是我们的 IP 名 |
| 主视觉 | 跃出画面的平行宇宙英雄海报 | 第一眼就是 Spider-Verse 电影气质 |
| 分宇宙 | 冷马克笔城 / 情绪水彩城 / 油印拼贴城 | 换世界 = 换画风 |
| 角色 | 竖幅近景英雄、水彩情绪角色 | 剪影与印刷细节 |
| 冲突 | 跨宇宙对撞、分格战场 | 动作像能动的漫画 |
| 终局 | 未完成线稿反派 + 负空间裂隙 | 世界正在被撕开 |

本合集 8 张图覆盖以上层次。

## 3. 详情

### 3.1 画面语法（提示词可用）

- Ben-Day / halftone  
- CMYK misregistration / chromatic print offset  
- bold comic ink outlines, cross-hatching  
- smear frames + speed lines（禁用镜头运动模糊）  
- mixed 2D/3D, unfinished pencil construction lines  
- xerox collage / marker rendering / mood-ring watercolor（分宇宙材质）  

### 3.2 提示词禁入（会激活古风偏置）

- 三国、武将、关羽、赤壁、城阙、水墨、书法、印章、古装、汉服、兵器名等  
- 这些只出现在展示文案，不出现在生图 prompt  

### 3.3 分宇宙材质（展示层命名）

| 展示名 | 画面材质 | 对应图 |
|---|---|---|
| 魏维 | 冷马克笔未来城 | 02 左 |
| 蜀维 | 情绪水彩城 | 02 中 / 07 |
| 吴维 | 高对比网点/拼贴城 | 02 右 / 06 |
| 裂隙 | 未完成线稿 + 负空间 | 05 |

### 3.4 清单

1. `tk-verse-01-key-art` — 品牌主视觉  
2. `tk-verse-02-triptych-worlds` — 三宇宙三联  
3. `tk-verse-03-hero-guan` — 竖幅英雄近景  
4. `tk-verse-04-cross-universe-clash` — 跨宇宙对撞  
5. `tk-verse-05-rift-boss` — 裂隙反派概念  
6. `tk-verse-06-rebel-collage` — 叛军拼贴宇宙  
7. `tk-verse-07-strategist-watercolor` — 情绪水彩角色  
8. `tk-verse-08-panel-battle` — 分格战场  

## 4. 场景

| 玩家会看到 | 对应图 | 要传达的感觉 |
|---|---|---|
| 宣传第一帧 | 01 | 这就是会动的漫画宇宙 |
| 选世界 | 02 | 三个世界三种画法 |
| 角色图鉴 | 03 / 07 | 近景印刷细节 + 情绪材质 |
| 对决预告 | 04 | 红青材质对撞 |
| 支线入口 | 06 | 粗糙油印叛军感 |
| 终局威胁 | 05 | 未画完的存在在撕世界 |
| 过场风格板 | 08 | 分格叙事战斗 |

## 5. 边界

**做：** Spider-Verse 印刷语言、分宇宙材质、原创英雄剪影。  
**不做：** 水墨山水、书法标题、古装史诗剧照、照搬现成超级英雄造型与标志。

## 6. UAT（Cucumber BDD · 玩家视角）

```gherkin
Feature: 概念图一眼就是 Spider-Verse 气质的平行宇宙 IP
  作为第一次打开合集的玩家
  我希望先被漫画印刷动画气质抓住
  而不是看到古风水墨海报

  Scenario: 主视觉风格正确
    Given 我打开概念图合集
    When 我看第一张主视觉
    Then 我应看到网点、套印错位或粗漫画线
    And 我不应感觉这是水墨或书法海报

  Scenario: 三联宇宙是画风差不是换皮
    Given 我查看三宇宙三联图
    When 我对比三幅画面
    Then 三幅应是明显不同的绘画介质
    And 整体仍统一在漫画动画印刷气质里

  Scenario: 对决与分格像电影分镜
    Given 我查看对决图和分格战场
    When 我观察动作表现
    Then 我应看到残影、速度线或冲击帧
    And 我不觉得这是写实历史战争剧照
```
