# 平行宇宙乱世 — 渲染管线圣经（生图用 · 文案-only）

> 本文件服务下一轮生图。只写概念与完整英文 prompt，不附成品图。  
> 展示层可用势力色名；**英文 prompt 禁止**古人名、古装、水墨、书法，以及会把模型拽成廉价街头偶像的词。

---

## 1. 概述

上一轮失败不是「不够当代」，而是把空词当成了画法：

- 「当代身份」被模型翻译成舞台偶像、耳麦、时尚编辑照。
- 「Spider-Verse」被翻译成**全员同一套 Ben-Day 半调贴纸**，界面像贴了网点装饰的通用 HUD。
- 真正的 Spider-Verse 方法是：**同一帧里多套渲染管线撞车**，并在接触带发生材质感染（Miles 网点漫画 vs Gwen 水彩 vs Miguel 三维 vs Punk 复印拼贴）。它不是给所有人套同一张半调滤镜。

本版把「平行宇宙」定义成三套**可点名作者语法**的世界渲染管线。势力换的不是衣服，是**画世界的引擎**。跨势力镜头必须同框至少两套引擎，并写清接触带如何互相污染。

### 1.1 美学锚点（必须写进 prompt 的作者名）

| 锚点 | 作者 / 作品 | 可执行语法（禁止空词） |
|------|-------------|------------------------|
| 超尺度巨构 | 弐瓶勉 Tsutomu Nihei《BLAME!》 | 无限层 Megastructure、排线密度当体积、人在建筑里像尘埃、Safeguard 角面、纵深消失在结构重复里 |
| 几何机体 / 有机侵染 | 《Knights of Sidonia》Tsutomu Nihei | 切面几何 Gardes、种子船走廊的模块肋骨、Gauna 半透明脂膜与不规则内脏光 |
| 银眼巨兵 | 八木教広 Norihiro Yagi《大剑 / Claymore》 | 银虹膜、比人更高的剑、高对比黑白块、斗篷剪影、妖气 youki 轮廓（薄热畸变，不是霓虹描边） |
| 90s 赛璐珞都市 | 《Ghost in the Shell》1995 背景 **Hiromasa Ogura**；**Katsuhiro Otomo**《Akira》；**Patlabor 2** | 2–3 阶赛璐珞阴影、胶片颗粒、钠灯雨、湿沥青、Ogura 水粉城市块、Otomo 高架与破坏透视、Patlabor 2 雨幕政治都市 |

Spider-Verse 在本 IP 里**只负责合成法**：同帧多介质 + 接触带感染。它不负责统一皮肤。

### 1.2 配色 7:2:1（区域面积，不是衣服品牌）

| 势力管线 | 主 70% | 辅 20% | 点 10% |
|----------|--------|--------|--------|
| 魏 · 巨构管线 | 黑 `#0D0D10` | 金 `#D4B35A` | 红 `#C41E2A` |
| 蜀 · 银眼赛璐珞管线 | 红 `#E11D2E` | 白 `#F7F4EF` | 蓝 `#2F6BFF` |
| 吴 · 膜雨管线 | 青蓝 `#1A8F9C` | 深蓝 `#1D4E89` | 橘 `#F07A2A` |

跨管线镜头：7:2:1 跟**画面里面积更大的那套管线**；第二管线以接触带与武器感染出现，不要两套主色对半平分导致发灰。

### 1.3 生图铁律

1. 每个主体/区域必须点名作者 + 介质（排线 / 赛璐珞 2-3 阶 / Gauna 膜 / Ogura 水粉……）。
2. 跨势力镜头必须有一句 **CONTACT BELT**（接触带材质如何爬过边界）。
3. 禁止全局半调、禁止把 UI 画成贴纸层。
4. 角色是管线里的操作员、骑士、机体驾驶员、结构体，不是娱乐业身份。
5. Hydro Skater 的「Skater」= 在 Gauna 膜上掠行的几何水翼足具，**不是滑板**。

---

## 2. 结构

### A. 三势力「世界渲染管线」

| 势力 | 世界渲染管线（作者语法） | 人在世界里的尺度 | 点缀色的物质含义 |
|------|--------------------------|------------------|------------------|
| **魏** | **Nihei《BLAME!》Megastructure 排线**为主世界；**Sidonia 几何装甲 / 种子船肋骨**为可动结构。城市不是街道，是无限层结构腔。 | 人 = 尘埃。镜头要有至少一处「人体 vs 结构柱」的尺度对照。 | 金 = 结构光 / 铆钉许可；红 = Gauna 撞击脏器或杀伤狭缝，从不铺底。 |
| **蜀** | **Yagi《Claymore》人物语法**（银眼、巨兵器、斗篷剪影、youki）叠在 **90s 赛璐珞都市**上：Ogura 1995 水粉城、Otomo 高架、Patlabor 2 雨。人物是赛璐珞 2–3 阶，背景是 Ogura 层。 | 人是前景剪影英雄，但城市仍比人巨大；youki 是唯一「非赛璐珞」的薄轮廓。 | 白 = 虹膜 / 刃 / 斗篷里衬；蓝 = youki，面积必须最少。 |
| **吴** | **Sidonia 种子船走廊 + Gauna 有机膜**作为水域与雾的物质；**Patlabor 2 / Ogura** 作为雨、玻璃、钠灯、湿混凝土。水不是特效，是活膜。 | 人被雨和膜吞到半身；舰桥玻璃大于人脸。 | 深蓝 = 种子船阴影体积；橘 = 警告灯 / 危险纹，从不铺天。 |

**管线碰撞时的感染方向（写进 CONTACT BELT）：**

- 魏→蜀：Nihei 排线爬上赛璐珞斗篷，把 3 阶色块咬成刻线体积。
- 蜀→魏：Claymore 赛璐珞红漆从刃口溅进 Megastructure，排线缝里渗出 2 阶平涂。
- 吴→魏：Gauna 脂膜沿排线生长，金结构光在膜里变成浑浊生物光。
- 魏→吴：Megastructure 肋骨刺穿种子船走廊，排线把雨画成工程剖面。
- 蜀→吴：youki 蓝轮廓在 Gauna 膜上烙出赛璐珞硬边；钠灯把红斗篷印进湿玻璃。
- 吴→蜀：Ogura 雨和水粉块溶解 Claymore 高对比，斗篷下摆变成半透明膜。

Spider-Verse 在此只做一件事：让上述感染发生在**同一帧的接触带**，而不是切分屏各画各的。

### 信息架构（给 UI 用）

| 层 | 来源 | 本 IP 里变成什么 |
|----|------|------------------|
| 信息层级 | *Expedition 33* 入画字 / *Persona 4 Reload* 大字号、疏菜单、一屏一焦点 | 控件少、字大、留白是构图不是空 |
| 控件材质 | 三套作者管线 | 血条可以是排线密度计；技能槽可以是赛璐珞色块；锁定可以是 Sidonia 几何；提示可以是写在墙上的 Ogura 水粉字 |
| 合成 | Spider-Verse 接触带 | HUD 压到角色/建筑上的地方必须发生材质感染，禁止悬浮玻璃贴纸 |

---

## 3. 详情

### 3.0 共用 Negative（所有英文 prompt 末尾可拼接）

```text
Strictly avoid: streetwear, fashion editorial, pop-stage costume, headset microphone, skateboard, sports jersey, cheap global Ben-Day halftone filter, sticker HUD overlay, uniform print skin on all characters, ancient Chinese armor, historical epic costumes, ink-wash painting, calligraphy, palace gates, generic neon cyberpunk, photoreal glass UI, motion blur, identical rendering medium across the whole frame.
```

---

### B. 六个 crossover 镜头

每个镜头同框至少两套管线。构图写死，避免模型画成左右分屏贴纸。

#### B1 · OATH-CUT MEGASTRUCTURE

**管线：** 蜀 Claymore 赛璐珞 × 魏 Nihei/Sidonia 巨构  
**接触带：** 刃口 youki 把排线缝撑开，红赛璐珞漆渗进金结构光；锤头 Gauna 红脏器反噬斗篷，把 3 阶阴影咬成刻线。

```text
Cinematic widescreen concept still, Spider-Verse mixed-media collision in ONE frame (not a split-screen, not a global halftone). LEFT-TO-CENTER SUBJECT: a Claymore-grammar oath warrior by Norihiro Yagi — silver irises, oversized two-handed blade taller than the body, high-contrast cloak silhouette, thin blue youki heat-haze outline, 1990s 2-3 tone cel shading, film grain. BACKGROUND AND ENEMY MASS: Tsutomu Nihei BLAME! megastructure filling the sky, humans as dust specks on distant ledges, dense cross-hatching as volume, Knights of Sidonia geometric siege-frame opponent with faceted Gardes limbs. Palette: Shu red #E11D2E / off-white #F7F4EF / youki blue #2F6BFF on the warrior; Wei black #0D0D10 / gold #D4B35A structural light / Gauna impact-red #C41E2A on the megastructure and hammer. CONTACT BELT at the blade impact: cel paint bleeds into Nihei hatch-lines; hatch-lines crawl onto the red cloak and convert flat cel shades into engraved volume; gold rivet-light refracts through blue youki then curdles into Gauna membrane. Hiromasa Ogura 1995 sodium-rain reflections only in a puddle at their feet. Mixed media, same-frame pipeline crash. No stickers, no street fashion, no idol staging.
```

#### B2 · LANCE IN THE RIB CORRIDOR

**管线：** 蜀 Claymore 白兵 + Sidonia 几何长枪 × 魏 Nihei Safeguard 夜袭体  
**接触带：** 枪脊几何切面把排线走廊剖开；狐盔排线感染白赛璐珞肩甲。

```text
Low-angle corridor battle still inside a Knights of Sidonia seed-ship rib corridor drawn with Tsutomu Nihei BLAME! hatching, vanishing repetition of structural ribs, human figures tiny against the tunnel. Subject A: White Lance Ace as Norihiro Yagi Claymore grammar — pale high-contrast face, silver irises, white cloak silhouette, 2-3 tone 1990s cel shading — driving a Sidonia faceted geometric lance that is a different medium from the body. Subject B: Night Raid Fox as Nihei Safeguard hunter — angular helm whose fox-ear shape is negative-space geometry not fur, gold visor slits, black hatch-work cloak, red kill-slit at the throat. CONTACT BELT: where the lance pierces, Sidonia planar geometry cuts Nihei hatch volume into clean facets; black hatch-lines infect the white cel shoulder plates and engrave them; a strip of Hiromasa Ogura 1995 gouache city-light leaks through a hull puncture, sodium-lamp orange-not-as-Wu, wet film grain. Palettes collide: Shu red-white-blue on the lancer (red lining 70 of their mass, white armor, blue youki along the lance spine); Wei black-gold-red on the hunter. Spider-Verse contact-infection, not global Ben-Day. No esports gear, no streetwear, no split-screen.
```

#### B3 · ORACLE AS DUST

**管线：** 蜀 Claymore 银眼人物（赛璐珞）× 魏 BLAME! 巨构尺度 × Ogura 背景被 youki 改写成剖面  
**接触带：** 蓝 youki 蓝图把排线建筑「翻译」成 Ogura 水粉块，再被巨构重新吞回排线。

```text
Extreme scale concept shot in the grammar of Tsutomu Nihei BLAME!: a cathedral-sized megastructure atrium, endless floors, the human body the size of a dust mote on a gantry. The dust-mote person is Oracle Architect rendered in Norihiro Yagi Claymore language — silver irises readable even at scale via a held close-cut inset, high-contrast cloak silhouette, 1990s 2-3 tone cel shading, red cloak #E11D2E, off-white inner geometry, blue youki #2F6BFF drawing architectural sections in the air. The youki drawing is the CONTACT BELT: it infects the Nihei hatch-city and temporarily translates walls into Hiromasa Ogura Ghost in the Shell 1995 gouache city-blocks and Patlabor 2 wet-concrete planes; then the megastructure re-hatches those painted blocks back into engraved volume. Gold #D4B35A structural lights recede for miles. Film grain. Spider-Verse mixed-media collision of cel figure, Nihei architecture, and Ogura painted city, infection only along the youki blueprint, not a uniform print filter. No fashion architect look, no headset, no sticker UI.
```

#### B4 · DOCKING COLLISION

**管线：** 吴 Sidonia 种子船 / Gauna 潮 × 魏 Iron Bastion Megastructure  
**接触带：** 膜长满排线；金结构光在膜里变成浑浊生物光；Patlabor 2 雨在两种体积上反射不同介质。

```text
Docking-collision establishing shot: a Knights of Sidonia seed-ship hull and ribbed corridor mouth, cyan-teal #1A8F9C wet plating, deep blue #1D4E89 interior volume, orange #F07A2A warning beacons only as 10 percent accents, Gauna organic tide-membrane filling the sea between. Colliding into it: Iron Bastion as a walking slice of Tsutomu Nihei BLAME! megastructure, black #0D0D10 slabs, gold #D4B35A rivet-light, red #C41E2A kill-slits, Sidonia faceted tower-shield, a tiny human visible in a chest viewport like dust. Rain in Mamoru Oshii / Patlabor 2 language and Hiromasa Ogura 1995 wet glass. CONTACT BELT along the docking ring: Gauna membrane grows across Nihei hatch-lines and turns engraved metal into translucent fat; gold structural light enters the membrane and becomes cloudy biological glow; megastructure ribs puncture the seed-ship and convert rain streaks into engineering sections. Spider-Verse same-frame pipeline crash, material infection at the ring, not xerox stickers, not a harbor postcard. No captain fashion coat, no neon cyberpunk.
```

#### B5 · MEMBRANE MIRROR

**管线：** 吴 Gauna 水面掠行体 × 蜀 Claymore 赛璐珞倒影  
**接触带：** 倒影是另一套引擎；膜把红斗篷变成半透明脂，youki 在水上烙出硬赛璐珞边。

```text
Surface-skimming action still. Foreground: Hydro Skater as a Knights of Sidonia geometric hydrofoil combatant — faceted water-wing greaves, NO skateboard, NO streetwear — skimming a Gauna organic membrane sea, Patlabor 2 wet-armor sheen, cyan-teal body #1A8F9C, deep blue shadowed planes #1D4E89, orange #F07A2A hazard chevrons only at the ankles. The water is living Sidonia Gauna fat-film, not normal ocean. Reflected in the membrane: Scarlet Oathblade in Norihiro Yagi Claymore grammar, silver eyes, giant sword, red cloak, 1990s cel 2-3 shading, blue youki. CONTACT BELT is the reflection plane: cel red cloak becomes translucent Gauna fat where it touches the surface; blue youki burns hard cel edges into the membrane; orange ankle chevrons print onto the reflected cloak as infected marks; Hiromasa Ogura 1995 sodium lamps smear in the film-grain rain. Spider-Verse mixed-media collision via mirror infection, not halftone stickers. No idol posing, no sports photography.
```

#### B6 · FOG EATS TWO CITIES

**管线：** 吴 Ogura+Gauna 雾 × 魏 Megastructure × 蜀 Akira/Claymore 赛璐珞街  
**接触带：** 雾是感染介质本身，三种画法在雾的浓度梯度里互相改写。

```text
Wide city-eating weather shot. The fog is the third renderer: Hiromasa Ogura Ghost in the Shell 1995 gouache mist plus Knights of Sidonia Gauna organic vapor, sodium lamps as Patlabor 2 rain-city lights, orange #F07A2A only in isolated warning bulbs. LEFT STRUCTURE: Tsutomu Nihei BLAME! megastructure rising through the block, dense hatching, black-gold-red, humans as dust on balconies. RIGHT STREET: Katsuhiro Otomo Akira elevated highway and 1990s cel-painted pavement, a Claymore-grammar cloak silhouette (Norihiro Yagi) walking in Shu red-white-blue, silver eye glint, 2-3 tone cel. CENTER: Mist Tactician as a long cloak cutout inside the Gauna fog, Sidonia geometric tactical traces floating like seed-ship HUD planes made of membrane. CONTACT BELT is the fog density gradient: where fog is thin, media stay distinct; where fog thickens, Nihei hatch-lines dissolve into Ogura wet planes, cel red cloaks turn to translucent fat, and gold rivet-lights become sodium smears. Spider-Verse same-frame multi-pipeline crash, weather as infection, NOT a global halftone, NOT collage stickers. Film grain. No calligraphy fog, no ink-wash, no historical gates.
```

---

### C. 九个角色（作者语法立绘 · 全身）

立绘默认：全身、无偶像pose、无时尚编辑布光。光源跟管线走（钠灯 / 结构光 / 种子船廊灯）。武器是身体比例的一部分，不是道具配件。

#### C1 · Scarlet Oathblade（蜀）

**一句话：** 八木教広的银眼与巨剑斗篷剪影，用 2–3 阶 90s 赛璐珞画在 Hiromasa Ogura 钠灯雨城里，蓝 youki 只箍在刃缘。

**外观 5 条：**
1. 银虹膜、高对比面（Yagi，不是化妆高光）。
2. 剑长过身，双手握，剑身有赛璐珞硬边缺口。
3. 重斗篷剪影，下摆破，红占身体面积七成。
4. 蓝 youki 为薄热畸变轮廓，仅刃与肩，面积约一成。
5. 背景 Ogura 1995 湿城与钠灯，胶片粒；脚下人与楼的尺度仍成立。

```text
Full-body character concept, Norihiro Yagi Claymore grammar: silver irises, giant two-handed blade taller than the figure, high-contrast cloak silhouette, thin blue youki heat-haze on the edge of the sword, 1990s 2-3 tone cel shading, film grain. Standing on Hiromasa Ogura Ghost in the Shell 1995 wet asphalt under sodium-lamp rain, distant Otomo Akira highway as graphic blocks. Palette 7:2:1 Shu — crimson cloak and blade-wrap #E11D2E about 70 percent of the figure mass, off-white #F7F4EF eyes, inner lining and blade chips 20 percent, youki blue #2F6BFF 10 percent only. Mixed 2D cel figure against Ogura painted city, not a fashion pose, not a stage spotlight. No streetwear, no headset, no global halftone.
```

#### C2 · White Lance Ace（蜀）

**一句话：** Yagi 白兵高对比剪影，兵器是 Sidonia 切面几何长枪（接触感染从握柄开始），背景 Otomo 高架与 Ogura 雨。

**外观 5 条：**
1. 苍白高对比面、银虹膜、无耳麦。
2. 白斗篷与切面肩甲，里衬红。
3. 长枪为 Knights of Sidonia 平面几何，与身体赛璐珞介质不同。
4. 蓝 youki 只沿枪脊。
5. 风把斗篷吹成 Claymore 剪影，不是飞行斗篷超级英雄布。

```text
Full-body character concept, Norihiro Yagi Claymore white-warrior grammar: pale high-contrast face, silver irises, cloak silhouette in wind, 1990s 2-3 tone cel shading. The lance is a Knights of Sidonia faceted geometric weapon, a different render pipeline from the cel body; CONTACT at the grip: hatch-like engraved planes infect the cel gloves. Background: Katsuhiro Otomo Akira elevated highway plus Hiromasa Ogura 1995 sodium rain, film grain. Palette 7:2:1 Shu — red inner cloak and wrapping #E11D2E as the largest color mass, off-white armor and cloak face #F7F4EF, blue youki #2F6BFF only along the lance spine. No esports jersey, no headset, no skate fashion, no global Ben-Day.
```

#### C3 · Oracle Architect（蜀）

**一句话：** Claymore 银眼读结构的人，身体是赛璐珞斗篷剪影，但尺度按 Nihei 规则缩成巨构里的尘埃；蓝 youki 是建筑剖面。

**外观 5 条：**
1. 银虹膜直视结构，不是看镜头卖萌。
2. 长斗篷剪影，红外白内，边缘被排线微微咬蚀（微量魏感染）。
3. 双手展开的 youki 蓝线是剖面/肋骨图，不是全息玻璃屏。
4. 身后 Megastructure 重复柱列，人极小。
5. 面为 2–3 阶赛璐珞，背景为 Nihei 排线。

```text
Full-body character concept with extreme architectural scale: Oracle Architect as Norihiro Yagi Claymore grammar — silver irises, high-contrast cloak silhouette, 1990s 2-3 tone cel shading — standing as a dust-speck human in a Tsutomu Nihei BLAME! megastructure nave. Blue youki #2F6BFF draws seed-ship / megastructure cross-sections in the air (Knights of Sidonia rib logic), and those lines slightly infect nearby hatch-work. Palette 7:2:1 Shu on the figure: crimson cloak #E11D2E dominant, off-white #F7F4EF inner planes and eyes, blue youki 10 percent. Gold megastructure lights recede for kilometers. Film grain, Hiromasa Ogura wet-air depth in the far haze only. No trendy architect glasses-as-fashion, no tablet product shot, no sticker diagrams, no global halftone.
```

#### C4 · Siege Hammer（魏）

**一句话：** 弐瓶勉排线把驾驶员焊进 Sidonia 几何攻城架，锤头是一截 Megastructure，红是 Gauna 撞击脏器。

**外观 5 条：**
1. 人脸只在盔的窄窗，人体量相对锤头像尘埃。
2. 四肢为 Sidonia Gardes 切面几何。
3. 全身 Nihei 排线当体积，无光滑潮牌装甲。
4. 金为结构许可光，沿接缝。
5. 锤头内部有半透明 Gauna 红脂，撞击时才可见。

```text
Full-body heavy operator concept in Tsutomu Nihei grammar: Siege Hammer as a Knights of Sidonia geometric siege-frame, faceted Gardes limbs, BLAME! dense cross-hatching as armor volume, the human pilot visible only as a dust-scale face in a visor slit. The hammer head is a broken megastructure column. Palette 7:2:1 Wei — black #0D0D10 about 70 percent, gold #D4B35A structural light 20 percent, Gauna impact-organ red #C41E2A 10 percent inside the hammer. Seed-ship corridor or megastructure cavity background, humans as dust on distant pipes. Film grain. No construction-worker fashion, no street destroyer look, no sticker warning labels as graphic design, no global halftone.
```

#### C5 · Night Raid Fox（魏）

**一句话：** BLAME! Safeguard 角面猎手，狐耳是头盔负空间几何，排线斗篷在种子船走廊里像移动的结构阴影。

**外观 5 条：**
1. 盔为角面，狐耳是镂空几何，无毛皮、无兽耳发饰。
2. 金缝视窗，极窄。
3. 斗篷是排线体积，剪影长，Claymore 式的「可读剪影」但介质是 Nihei。
4. 红只在喉部杀伤狭缝或爪尖。
5. 姿态贴结构行走，人比走廊肋骨小。

```text
Full-body stealth hunter concept, Tsutomu Nihei Safeguard language inside a Knights of Sidonia rib corridor: Night Raid Fox helm is angular negative-space geometry that reads as fox ears without fur, gold #D4B35A visor slits, black #0D0D10 hatch-work cloak silhouette, red #C41E2A only as a throat kill-slit. Dense BLAME! cross-hatching, human scale tiny in the corridor. Palette 7:2:1 Wei. Optional CONTACT: a scrap of 1990s cel light from a hull crack (Ogura sodium) infecting the cloak hem into a few flat cel planes. Film grain. No cute fox mascot, no fur hood, no spy-fashion leather editorial, no global Ben-Day.
```

#### C6 · Iron Bastion（魏）

**一句话：** 会行走的 BLAME! Megastructure 切片，Sidonia 切面塔盾，胸窗里的操作员小得像尘埃。

**外观 5 条：**
1. 竖直板块装甲，像一段被锯下的城。
2. 塔盾为 Sidonia 平面几何，边缘锋利。
3. 胸窗小人体，明确尺度对照。
4. 金铆钉光成列，像许可刻度。
5. 红杀伤狭缝在盾缝，面积最小。

```text
Full-body walking-fortress concept: Iron Bastion is a vertical slice of Tsutomu Nihei BLAME! megastructure given Sidonia faceted tower-shield geometry. A tiny human operator is visible in a chest viewport, dust-scale. Dense hatching, black slabs #0D0D10, gold rivet-light #D4B35A in columns, red kill-seams #C41E2A at 10 percent. Background continues the City as infinite architecture. Film grain. No riot-police costume, no security-guard uniform, no fashion coat over armor, no sticker emblems, no global halftone.
```

#### C7 · Tide Captain（吴）

**一句话：** Sidonia 种子船舰桥船长：身体是束具与切面肩肋，不是时装大衣；Patlabor 2 雨打在 Ogura 玻璃上，潮汐图是活的 Gauna 膜。

**外观 5 条：**
1. 种子船安全束具 + 几何肩肋，无时装大衣、无舞台麦。
2. 青蓝湿板为主，深蓝为腔体阴影。
3. 橘仅在仪器警告灯与一条危险纹。
4. 面前 Gauna 膜潮汐图，半透明脂，内有不规则光。
5. 玻璃外是 Ogura/Patlabor 2 雨港，人脸小于舰桥窗。

```text
Full-body seed-ship captain concept, Knights of Sidonia interior grammar: Tide Captain wears geometric harness and faceted shoulder ribs, wet cyan-teal plating #1A8F9C, deep blue cavity shadows #1D4E89, orange #F07A2A only as instrument warnings. A living Gauna membrane tide-chart floats before the hands. Behind rain-glass: Hiromasa Ogura 1995 / Patlabor 2 harbor sodium lamps, film grain. Palette 7:2:1 Wu. Scale: the bridge window is larger than the face. No fashion peacoat, no pop-captain hat as costume, no microphone, no sticker badges, no global halftone.
```

#### C8 · Hydro Skater（吴）

**一句话：** 「Skater」= Sidonia 几何水翼足在 Gauna 膜上掠行；Patlabor 2 湿装甲；禁止滑板、禁止运动时装。

**外观 5 条：**
1. 足部是切面水翼 / 膜撬，与水面 Gauna 脂膜连续。
2. 身体青蓝赛璐珞湿反射，2–3 阶。
3. 橘危险纹只在踝与小腿，约一成。
4. 深蓝为背侧阴影体积。
5. 姿态是低重心掠行，不是街头技巧动作。

```text
Full-body hydrofoil combatant, Knights of Sidonia geometric water-wing greaves skimming a Gauna organic membrane — Hydro Skater, absolutely no skateboard, no street shoes, no sports fashion. 1990s 2-3 tone cel on the body with Patlabor 2 wet-armor rain, Hiromasa Ogura sodium lamps on the horizon. Palette 7:2:1 Wu: cyan-teal #1A8F9C 70 percent, deep blue #1D4E89 20 percent, orange #F07A2A hazard chevrons 10 percent at the ankles only. CONTACT: membrane fat climbs the greaves and turns cel shading into translucent tissue. Film grain. No trick pose for camera, no idol balance pose, no global Ben-Day.
```

#### C9 · Mist Tactician（吴）

**一句话：** Ogura 1995 雾是 Gauna 有机天气；人是长斗篷剪影；Sidonia 几何标绘浮在钠灯里，橘是孤立警告泡。

**外观 5 条：**
1. 面半没入膜雾，可见的眼偏银青，冷静。
2. 斗篷剪影长，下摆已膜化（半透明脂）。
3. 周围浮着 Sidonia 平面几何标绘，介质是膜不是玻璃 HUD。
4. 钠灯点状，Patlabor 2 雨。
5. 橘仅几盏警告泡，不铺雾。

```text
Full-body tactician in weather: Mist Tactician as a long cloak silhouette standing in Hiromasa Ogura Ghost in the Shell 1995 gouache fog that is also Knights of Sidonia Gauna organic vapor. Sidonia geometric traces float around the figure as membrane planes, not glass holograms. Patlabor 2 rain, sodium lamps, film grain. Palette 7:2:1 Wu: cyan-teal fog-body #1A8F9C dominant, deep blue #1D4E89 in the cloak cavities, orange #F07A2A only as isolated warning bulbs. The cloak hem is infected into translucent fat. No stage-director fashion, no clipboard, no sticker UI, no ink-wash mist, no global halftone.
```

---

### D. 三张游戏界面（UI 也是 crossover）

上一轮把 UI 做成「网点贴纸贴在通用游戏界面上」。本轮 UI 的信息层级学 *Expedition 33*（字入画、控件像画的一部分）与 *Persona 4 Reload*（大字、疏菜单、一屏一个焦点）；**控件的物质**必须来自作者管线，并在压到世界/角色的接触带感染。

#### D1 · 战斗 HUD

**怎么像 crossover：** 世界是蜀赛璐珞骑士砍魏巨构。血条是 Nihei 排线密度计（魏黑金红）；技能槽是 90s 赛璐珞色块（蜀红白蓝）；锁定是 Sidonia 几何环（吴青蓝橘点）。三套控件在角色肩甲与建筑排线上发生感染，而不是浮在玻璃上。

```text
In-game combat HUD concept screenshot, information hierarchy from Expedition 33 painted diegetic captions plus Persona 4 Reload sparse large type and a single selected command. The 3D/2D world is already a Spider-Verse pipeline crash: a Norihiro Yagi Claymore-grammar warrior (silver eyes, giant blade, 1990s 2-3 tone cel, red-white-blue) striking a Tsutomu Nihei BLAME! megastructure enemy (hatching volume, Sidonia geometric mass, black-gold-red). UI MATERIALS ARE THE SAME PIPELINES, NOT STICKERS: bottom-left HP is a Nihei hatch-density meter in Wei black #0D0D10 / gold #D4B35A / red #C41E2A; bottom-right skill slots are cel-paint chips in Shu crimson #E11D2E / off-white #F7F4EF with youki-blue #2F6BFF only on the selected slot; a Sidonia geometric lock-ring in Wu cyan #1A8F9C with orange #F07A2A ticks marks the weak point. CONTACT BELTS: hatch-meter engraves into the cel shoulder where it overlaps the warrior; cel skill chips peel megastructure hatch-lines into flat color; the geometric lock-ring grows a thin Gauna membrane where it touches architecture. Expedition 33 narrative word painted onto a megastructure slab; P4R-scale selected skill name. Readable mockup, film grain. No glass blur HUD, no Ben-Day sticker chrome, no ancient war banner, no dense MMO icon grid.
```

#### D2 · 主菜单

**怎么像 crossover：** 标题画面的建筑本身是三管线撞车：左魏巨构、中蜀斗篷剪影、右吴膜雨港。菜单字是 P4R 疏列；标题字是 E33 式入画——一半刻进排线，一半赛璐珞平涂，一半膜化。无海报网点封面。

```text
Main menu title-screen concept, one composition, not a widget dashboard. Persona 4 Reload sparse vertical commands (CONTINUE / FORMATION / CITY / OPTIONS) with huge leading and a single selected line. Expedition 33 title type is diegetic inside the world, not a logo sticker. The world is a Spider-Verse same-frame crash of three author pipelines: LEFT Tsutomu Nihei BLAME! megastructure, black-gold-red, hatching, humans as dust; CENTER Norihiro Yagi Claymore cloak silhouette, silver eye, 1990s cel 2-3 shading, Shu red-white-blue; RIGHT Hiromasa Ogura 1995 / Patlabor 2 rain harbor plus Sidonia Gauna water, Wu cyan-deep-blue with orange warning lamps only. CONTACT BELTS between the three thirds: hatch-lines crawl onto the cel cloak; Gauna membrane climbs megastructure ribs; Ogura gouache dissolves both edges into wet planes. Selected menu line is youki-blue; title letters are engraved hatching on the left, cel-painted in the middle, membrane-translucent on the right. Film grain. No album-cover idol poster, no global halftone, no floating badges, no statistic cards.
```

#### D3 · 城市冒险

**怎么像 crossover：** 玩家走在 Ogura 赛璐珞街，魏巨构从街区长出，吴运河是 Gauna 膜。目标条是 P4R 清晰短句，但纸面是 Ogura 水粉；小地图是 Sidonia 几何；互动提示是 E33 写在真实墙上的字——写在排线上就变成刻线，写在膜上就变成脂纹。

```text
City exploration game screenshot with diegetic UI. The street is a pipeline crash: Hiromasa Ogura Ghost in the Shell 1995 gouache blocks and 1990s cel pavement; a Tsutomu Nihei BLAME! megastructure growing through the block (hatching, black-gold, dust-scale pedestrians); a canal of Knights of Sidonia Gauna membrane water under Patlabor 2 rain, orange hazard lamps only on buoys. UI hierarchy from Persona 4 Reload (top-left short objective strip, large type, few elements) and Expedition 33 (interact prompt painted onto the actual wall). UI MATERIALS MATCH WHATEVER SURFACE THEY TOUCH: the objective strip is Ogura gouache paper; the mini-locator is a Sidonia geometric shard; when the painted Expedition 33 prompt sits on megastructure it becomes Nihei engraving; when it sits on canal membrane it becomes Gauna fat-lettering. CONTACT infection only at overlaps, not a sticker layer over the whole shot. Film grain. No radar-heavy open-world HUD, no xerox collage chrome, no historical city gates, no ink-wash signage.
```

---

## 4. 场景

| 玩家会看到 | 对应产出 | 要成立的感觉 |
|------------|----------|--------------|
| 选世界 / 世界观 | A 三管线表 | 换势力 = 换作者引擎，不是换队服 |
| 宣传冲突帧 | B1–B6 | 同一帧里至少两套画法在打架，接缝在互相污染 |
| 图鉴全身 | C1–C9 | 银眼巨剑、尘埃人、种子船束具、水翼掠膜；不是舞台人 |
| 开战 | D1 战斗 | HUD 零件分别是排线计 / 赛璐珞块 / 几何环，压到人身上会感染 |
| 开机 | D2 主菜单 | 标题建筑就是三宇宙撞车，菜单疏、字大 |
| 进城 | D3 城市 | 路是 Ogura，楼从 Nihei 长出，河是 Gauna；UI 写在这些物质上 |

建议下一轮生图顺序：B6（验管线碰撞）→ D2（验 UI 不是贴纸）→ C1/C4/C8（验三角角色不再偶像化）→ 其余。

---

## 5. 边界

**做**
- 点名：Tsutomu Nihei, BLAME!, Knights of Sidonia, Gauna, Norihiro Yagi, Claymore, silver irises, youki, Hiromasa Ogura, Ghost in the Shell 1995, Katsuhiro Otomo Akira, Patlabor 2, 2-3 tone cel, film grain, sodium-lamp rain, megastructure, humans as dust.
- Spider-Verse = 同帧多介质 + CONTACT BELT 感染。
- 7:2:1 面积比；点缀色有物质含义。
- E33 入画字 + P4R 疏层级。

**不做（prompt 与展示文案都禁）**
- 空词当画法；把当代写成娱乐业身份。
- 全员同一套半调 / 贴纸 HUD / 分屏各画各的冒充 crossover。
- 古人名、古装、水墨、书法、宫门城阙。
- 滑板、耳麦、舞台光、时尚大片布光。
- 玻璃拟态通用科幻 UI、紫霓虹默认赛博、运动模糊。

**Hydro Skater 专禁：** skateboard, roller blades as sport, street shoes, trick photography.

---

## 6. UAT（Cucumber BDD · 3 条）

```gherkin
Feature: 平行宇宙是同帧多渲染管线撞车，不是半调贴纸宇宙
  作为下一轮看概念图的制作人
  我希望第一眼能指认作者语法，并看见接触带感染
  而不是看见廉价舞台偶像或全员网点滤镜

  Scenario: 角色是作者语法里的操作体不是舞台人
    Given 打开 Scarlet Oathblade、Siege Hammer、Hydro Skater 三张全身概念
    When 我在前 3 秒摘掉所有特效只看剪影与介质
    Then Scarlet Oathblade 应读作 Claymore 银眼巨剑斗篷剪影加 2-3 阶赛璐珞
    And Siege Hammer 应读作 Nihei 排线巨构攻城架且人像尘埃
    And Hydro Skater 应读作 Sidonia 几何水翼在 Gauna 膜上掠行
    And 三张都不应出现舞台耳麦、时尚编辑姿态或滑板

  Scenario: crossover 镜头同框至少两套管线并有接触带感染
    Given 打开 B1 至 B6 任一冲突帧
    When 我沿两股势力的交界线看材质
    Then 我应能分别指认至少两名作者的画法（例如 Nihei 排线 vs Yagi 赛璐珞 vs Ogura 水粉 vs Gauna 膜）
    And 交界处应发生材质互相污染而不是干净分屏
    And 整帧不应是同一套半调或贴纸拼贴覆盖

  Scenario: 游戏 UI 用作者物质承载 E33/P4R 信息层级
    Given 打开战斗、主菜单、城市三张界面概念
    When 我先看信息再看材质
    Then 我应看到疏的大字层级（P4R）或入画字（E33），而不是密图标玻璃 HUD
    And 控件材质应分别来自排线 / 赛璐珞色块 / Sidonia 几何 / Gauna 膜 / Ogura 水粉
    And 控件与世界重叠处应有感染，而不是一层网点贴纸浮在画面上
```
