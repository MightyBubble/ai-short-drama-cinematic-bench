# 三国：平行宇宙 — 蜀势力 · 游戏内界面概念

> 仅概念文案 / 生图 prompt，不附成品图。  
> 风格锚点：**Spider-Verse 印刷感** + **Expedition 33 / Persona 4 Reload** 游戏内 UI 气质。  
> 配色铁律 **7:2:1** —— 主色红(~70%) / 辅色白(~20%) / 点缀蓝(~10%)。

---

## 1. 概述

蜀线界面不是「古战场 HUD」，而是一张会呼吸的**偶像正义海报**：大色块红底、干净白字、少量电光蓝作为技能与焦点点缀。信息密度向 Persona 式菜单靠拢（清晰层级、大字号、留白），冲击帧与网点错位则借用 Spider-Verse；Expedition 33 贡献「叙事 UI 可入画」——控件像印在海报上的墨层，而不是浮在玻璃上的通用面板。

**蜀气质关键词：** 热血义气 · 偶像正义 · 海报印刷 · 留白呼吸感  
**生图禁入（展示文案可用）：** 三国人名、古装史诗、水墨书法，以及任何会把模型拽进古风参数的词。

---

## 2. 结构

| 层 | 界面 | 玩家感知 | 红/白/蓝角色 |
|---|---|---|---|
| 冲突层 | 战斗 HUD | 热血对决，像跃出海报的连招板 | 红=血条/大底；白=可读字与缺口；蓝=技能就绪/弱点 |
| 成长层 | 养成/构筑 | 「正义编队」像专辑内页点歌单 | 红=区块与节点；白=卡片纸面；蓝=已激活连线 |
| 品牌层 | 主菜单 | 势力选择即偶像海报封面 | 红=全幅海报场；白=标题与 CTA；蓝=光标/选中 |
| 探索层 | 城市冒险 | 情绪城街道上的轻量导航叠层 | 红=任务标记/危险；白=路牌信息；蓝=互动高亮 |

四类界面共用同一套印刷语法与配色比例，仅改信息密度与动效节奏。

---

## 3. 详情

### 3.0 共用视觉语法（四类界面通用）

- **印刷：** Ben-Day / halftone、CMYK 轻微套印错位、粗漫画外轮廓、海报级色块裁切  
- **UI 气质：** 大字号、少描边、模块之间有「海报出血」留白；菜单像 Persona 的舞台感，读条/提示像 Expedition 的叙事叠字  
- **配色：** `#E11D2E` 系主红 ~70% 画面面积；`#F7F4EF` 系白纸字面 ~20%；`#2F6BFF` 系电光蓝 ~10% 仅用于焦点、就绪、互动  
- **禁止材质：** 水墨晕染、书法标题、青铜纹样、古装甲胄道具堆砌（展示层叙事可以说，prompt 不写）

---

### 3.1 战斗 HUD

**Mood**  
偶像正义上场：画面像一张被撕开的红底宣传海报，伤害数字带着网点飞溅；玩家读到的是「气势与连招」，不是军令状。

**布局**  
- 上沿：极薄白字状态条（队伍名 / 回合节拍），两侧留空，不放密密麻麻小图标  
- 左下：主角圆形头像印戳 + 红色生命块（粗印刷色带，非写实血槽）；蓝点仅标「爆发就绪」  
- 右下：3–4 个大正方形技能键，白底红描边，选中键蓝光描边膨胀一圈  
- 中央偏上：弱点/连携提示用短句白色叠字（Expedition 式），不遮挡角色全身剪影  
- 敌方血条贴右上短柱，红底白缺口，避免对称「竞技场 HUD」

**材质**  
粗网纹红纸、丝网印刷边缘毛刺、轻微 CMYK 错位、技能图标为扁平海报 pictogram（星、盾、跃、冲），纸纤维噪点，无玻璃模糊。

**动效**  
1. 受击：红半调闪帧 + 套印错位一帧后回正（非镜头运动模糊）  
2. 技能就绪：蓝描边脉冲两下，像海报油墨未干发亮  
3. 连携成功：白字砸入画面中央，带速度线与 smear frame，随后碎成网点消散  

**完整英文生图 Prompt**

```text
In-game combat HUD concept art for a modern hero action RPG, Spider-Verse print language mixed with Persona 4 Reload menu clarity and Expedition 33 narrative overlay typography, 7:2:1 color balance: dominant vivid crimson red poster field about 70 percent, clean off-white paper typography and gaps about 20 percent, electric cobalt blue accents only about 10 percent for ready skills and focus rings. Bold Ben-Day halftone, CMYK misregistration, thick comic ink outlines, screen-print grit, poster crop marks. Layout: thin white status line at top with breathing negative space; circular stamped portrait and chunky red health bar bottom-left; large square skill buttons bottom-right with white faces and red borders, selected button outlined in blue; short white narrative combat cue text floating mid-upper; compact enemy meter top-right. Hot-blooded idol-justice energy, passionate loyalty vibe, large whitespace, readable game UI mockup, mixed 2D/3D, no photoreal HUD glass. Strictly avoid historical epic costumes, ink-wash painting, calligraphy brushes, ancient armor props, real-world trademark logos.
```

---

### 3.2 养成 / 构筑

**Mood**  
「正义编队」像限量专辑内页：点亮节点像盖章应援，构筑连线是蓝色应援棒轨迹，冷静但不冷血。

**布局**  
- 左 40%：竖幅角色立绘区（大留白，角色偏下，头顶呼吸空间）  
- 右 60%：白纸构筑板——六边形或唱片纹节点网，默认灰红未点亮，激活节点红芯 + 蓝连线  
- 底栏：构筑槽位 5 格，白卡片红标题字，选中卡蓝角标  
- 顶：单一页面标题（大白字或反白红条），副句一行，无多余 Tab 丛林  

**材质**  
丝网印刷节点、贴纸感技能卡、轻度 xerox 纹理、纸张齿孔与打孔器圆点（Persona 菜单亲和感）、节点内部细半调。

**动效**  
1. 点亮节点：红墨从中心洇开成半调圆，再弹出白字数值  
2. 连线：蓝轨迹沿路径「印刷」出来，像油墨被刮板推过  
3. 确认构筑：整板轻微 CMYK 三色分离后咬合，发出「封面合上」的静止冲击帧  

**完整英文生图 Prompt**

```text
Character growth and loadout build UI concept for a stylish turn-based action game, Spider-Verse halftone print meets Persona 4 Reload album-insert menu staging and Expedition 33 elegant readable panels, strict 7:2:1 palette: mostly saturated crimson red panels and node cores ~70%, off-white paper board and card faces ~20%, cobalt blue only for active link lines and selected corner marks ~10%. Left side tall character portrait zone with generous negative space; right side white paper skill constellation board with stamped circular nodes, inactive nodes muted red, active nodes bright red cores connected by blue ink trails; bottom row of five white loadout cards with red titles. Screen-print texture, Ben-Day dots, light xerox grit, sticker-like icons, bold comic outlines, idol-justice passionate loyalty mood, poster breathing whitespace, clean hierarchy, game UI mockup. Avoid historical epic costumes, ink-wash aesthetics, calligraphy lettering, ancient weapon catalogs, cluttered MMO grids.
```

---

### 3.3 主菜单

**Mood**  
势力封面页：一打开就是红底偶像海报，标题是白印刷大字，光标是蓝色「应援焦点」。像把游戏碟封面直接做成可点的舞台。

**布局**  
- 全屏红海报场为绝对主体（角色剪影或抽象英雄姿态可入画，但不抢过标题层级）  
- 品牌名 / 势力线标题：超大白字偏左下或中左，符合「品牌即英雄」——标题不压过势力标识字重  
- 菜单列表垂直左对齐，字距疏朗：CONTINUE / FORMATION / CITY / OPTIONS（示例英文 UI 字）  
- 选中项：白字放大 + 左侧蓝竖条或蓝半调三角指针  
- 右下极小版本号与印刷准星装饰，不抢第一眼  

**材质**  
巨型半调渐变红、海报折痕、套印错位边缘、轻微纸纤维、菜单字像丝网印上去而非 UI 字体引擎默认态。

**动效**  
1. 入场：红海报从网点颗粒「显影」成实色，白字后到  
2. 光标移动：蓝指针拖出短 smear，上一选项网点淡出  
3. 确认：选中行白底闪一下再切场，像翻开专辑内页  

**完整英文生图 Prompt**

```text
Main menu title screen UI concept art, full-bleed crimson poster field as the hero plane, Spider-Verse cinematic print language with Persona 4 Reload stage-like menu list and Expedition 33 artful typography, color ratio 7:2:1: about 70 percent vivid red poster background, 20 percent off-white title and menu type, 10 percent electric blue selection marker only. Oversized white printed title on the left, vertical sparse menu items with generous leading, selected line marked by a blue halftone chevron, huge breathing negative space, idol-justice passionate loyalty atmosphere, Ben-Day dots, CMYK offset fringes, screen-print grit, bold comic contour on optional hero silhouette in the poster, mixed 2D/3D, no inset cards, no dashboard widgets. Avoid historical epic costume framing, ink-wash backgrounds, calligraphy titles, ancient fortress silhouettes, generic sci-fi glass UI.
```

---

### 3.4 城市冒险

**Mood**  
情绪红城街道上的轻量叠层：任务是海报贴纸，路牌是白印刷条，可互动物是蓝光「应援点」。探索感像在漫画页里走路，而不是开放世界雷达战争。

**布局**  
- 世界场景占满（街道 / 巷口 / 高架下广场等现代平行城意象）  
- 左上：迷你目标条——白底短句 + 红左边条，最多两行  
- 右上：非圆形小地图，而是撕边海报角标式方位块，红底白街名  
- 场景内：可互动物头顶蓝半调感叹/对话点，远处危险用暗红斜向印刷条暗示  
- 底中：上下文操作提示一行白字，平时隐藏，靠近时淡入  

**材质**  
场景可用情绪水彩+印刷叠层（与蜀维世界材质衔接），但 UI 叠层必须是清晰丝网印刷贴纸；半调阴影落在墙上，控件不使用厚重卡片框。

**动效**  
1. 走近互动点：蓝点从网点聚合成实心，轻脉冲  
2. 接任务：白目标条从左侧「印刷滑入」，红边条后盖章到位  
3. 进入危险区：画面边缘短暂红半调暗角 + 一次套印抖动，随即恢复呼吸留白  

**完整英文生图 Prompt**

```text
City exploration adventure UI overlay concept on a stylized parallel-universe street scene, Spider-Verse print overlays with Expedition 33 diegetic readability and Persona 4 Reload clean objective strips, palette locked 7:2:1: dominant crimson environmental and UI accents ~70%, off-white objective paper strips and labels ~20%, cobalt blue interaction markers ~10%. Full-bleed city backdrop with mood-wash atmosphere under comic ink and Ben-Day shadows; top-left white objective ticker with red side bar; top-right torn-poster mini locator block in red with white street type; blue halftone talk/interact dots above nearby props; bottom contextual white prompt text fading in. Hot-blooded idol-justice tone, passionate loyalty vibe, breathing whitespace, light screen-print stickers instead of heavy cards, CMYK misregistration on UI edges, mixed 2D/3D game screenshot mockup. Avoid historical epic city gates, ink-wash landscapes, calligraphy signage, ancient costume NPCs, cluttered radar-heavy open-world HUD.
```

---

### 3.5 额外：蜀线角色立绘共用背景 / 角标 Prompt 片段

可拼接到任意蜀线角色立绘 prompt 末尾（角色描述自行替换，**勿写入三国人名 / 古装史诗 / 水墨书法**）：

**共用背景片段**

```text
Shared Shu-route portrait backdrop: full-bleed vivid crimson poster wall with soft Ben-Day falloff, generous off-white negative space around the figure for breathing room, faint CMYK misregistration borders, subtle screen-print paper grain, optional distant abstract city blocks as graphic shapes only, idol-justice passionate atmosphere, Spider-Verse print language, no ink-wash, no calligraphy scrolls, no historical palace scenery
```

**共用角标 / 势力章片段**

```text
Corner faction badge sticker: geometric red shield-stamp with off-white bold abstract mark, thin cobalt blue registration tick on one corner only, torn-sticker edge, halftone fill inside badge, screen-print grit, placed top-right like a limited poster seal, 7:2:1 red-white-blue hierarchy, not a historical emblem, not a calligraphy seal
```

**立绘完整拼装示例（结构示意）**

```text
[角色原创外形与姿态，现代英雄剪影，热血正向表情] +
vertical character portrait, generous whitespace, bold comic ink outlines, mixed 2D/3D,
+ [共用背景片段] + [共用角标片段],
color balance crimson ~70 / off-white ~20 / cobalt accent ~10
```

---

## 4. 场景

| 玩家会看到 | 对应界面 | 要传达的感觉 |
|---|---|---|
| 开战第一秒 | 战斗 HUD | 我在红海报里打连招，不是在看军情沙盘 |
| 编队加点 | 养成/构筑 | 像给偶像专辑贴应援轨迹，清晰、仪式、有留白 |
| 开机 / 回标题 | 主菜单 | 势力即封面，光标即蓝色应援焦点 |
| 城里接任务逛点 | 城市冒险 | 漫画页上走路，UI 是贴纸不是仪表盘 |
| 图鉴 / 抽卡立绘 | 共用背景+角标 | 全线角色同一张「红海报墙」家族感 |

---

## 5. 边界

**做**  
- Spider-Verse 印刷语言（halftone / CMYK offset / smear / mixed 2D-3D）  
- Expedition 33 式叙事叠字与 Persona 式大字号菜单呼吸感  
- 严格 7:2:1 红/白/蓝，蓝只做焦点与就绪  
- 热血义气、偶像正义、海报留白  

**不做**  
- 提示词内出现三国人名、古装史诗、水墨书法（及近义古风偏置词）  
- 厚重玻璃拟态、紫霓虹赛博默认皮、仪表盘式密集 HUD  
- 英雄区塞统计条 / 赛程 / 多卡片墙（违反一屏一构图）  
- 把蓝做成第二主色或大面积冷却条底  

---

## 6. UAT（Cucumber BDD · 玩家视角 · 2 条）

```gherkin
Feature: 蜀势力界面一眼是红白蓝偶像正义海报 UI
  作为进入蜀线的玩家
  我希望四类界面都像会呼吸的印刷海报
  而不是古风史诗或通用玻璃 HUD

  Scenario: 战斗 HUD 配色与气质正确
    Given 我进入蜀势力战斗界面概念图
    When 我扫视第一眼的色彩与布局
    Then 我应感觉主色为红、辅色为白、点缀为蓝且蓝面积明显最少
    And 我应读到热血海报连招板而不是古装史诗战场 HUD
    And 我不应看到水墨或书法装饰

  Scenario: 主菜单与养成界面保持留白与印刷感
    Given 我依次查看蜀势力主菜单与养成构筑界面
    When 我对比信息层级与材质
    Then 两屏都应有大面积呼吸留白与丝网/半调印刷材质
    And 选中或激活态应由蓝色焦点提示而不是第二套主色重涂
    And 整体应接近 Persona 式清晰菜单叠加 Spider-Verse 印刷冲击而非密卡片仪表盘
```

---

## 附录：四类界面速查

| ID | 界面 | Prompt 用途 |
|---|---|---|
| `shu-ui-01-combat-hud` | 战斗 HUD | 战斗叠层概念 |
| `shu-ui-02-build` | 养成/构筑 | 节点编队概念 |
| `shu-ui-03-main-menu` | 主菜单 | 势力封面概念 |
| `shu-ui-04-city` | 城市冒险 | 探索叠层概念 |
| `shu-ui-badge-bg` | 立绘共用 | 背景 + 角标片段 |
