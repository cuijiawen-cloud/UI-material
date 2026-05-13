# Game UI Style Knowledge Entries: 原神 / 梦幻西游 / 大话西游 / 英雄联盟

last_updated: 2026-05-13
research_method: text-first; avoids screenshots, key art, PV frames, activity banners and fan art as primary style evidence.
intended_use: GitHub knowledge base for AI / Maker tool UI style transfer.

---

# Game UI Style Knowledge Entry: 原神

## 1. Text Research Summary
- sources_checked:
  - HoYoverse / miHoYo 官方站：开放世界冒险 RPG、提瓦特、七国、寻找血亲、与伙伴共同战斗
  - Google Play / PlayStation 商店文案：元素能量、探索每一寸世界、与不同角色同行
- source_urls:
  - https://genshin.hoyoverse.com/zh-cn
  - https://genshin.hoyoverse.com/en/company/about
  - https://play.google.com/store/apps/details?id=com.miHoYo.GenshinImpact
  - https://www.playstation.com/en-sg/games/genshin-impact/
- game_type: 开放世界冒险 / 动作 RPG
- core_gameplay: 探索提瓦特、队伍角色切换、元素战斗、解谜、挑战敌人和秘境、推进主线与区域故事。
- world_setting: 名为提瓦特的幻想世界，由七国、七元素、神明与古文明谜团构成，长期基调是明亮、生机、冒险与神秘并存。
- player_role: 旅行者：寻找失散血亲，在提瓦特游历七国，结识伙伴并揭开世界谜题。
- emotional_experience: 自由探索、清澈幻想、轻史诗感、好奇、治愈、明亮但带有古代谜团。
- key_visual_keywords:
  - 开放世界
  - 高幻想
  - 元素
  - 七国
  - 旅途
  - 清澈天空
  - 古文明纹样
  - 精致轻奢
- confidence: high

## 2. Game Style Understanding
### recognized_visual_identity
- 明亮高幻想开放世界冒险 RPG：清澈自然、元素魔法、古文明纹样与精致轻奢 UI 的结合。

### genre_presentation
- RPG 被视觉化为“旅途式幻想冒险”：不是暗黑地下城，也不是重金属战斗 HUD，而是把地图、元素、遗迹、神殿、天空与风作为主视觉语义。

### primary_mood
- 明亮
- 清澈
- 幻想
- 好奇
- 轻史诗
- 治愈
- 神秘

### world_semantics
- 提瓦特
- 七元素
- 神之眼
- 遗迹纹样
- 星空
- 风场
- 传送锚点
- 神殿石柱
- 自然地貌
- 旅行者笔记

### common_ui_material_language
- 暖白羊皮纸
- 浅金属细边
- 半透明磨砂玻璃
- 柔和石材
- 星尘粒子
- 元素徽记
- 薄光晕

### shape_language
- 圆角矩形
- 细金边
- 对称徽章
- 轻浮雕
- 柔和内阴影
- 菱形/星形节点
- 低对比纹样底

### palette_tendency
- 暖白/象牙色用于主面板底，制造干净、明亮、非压迫感。
- 浅金/香槟金用于边框、分割线、等级感和选中高光。
- 天空蓝/青绿用于辅助层次、探索与元素清澈感。
- 深靛蓝/夜空紫仅用于深层背景或神秘区域，不应覆盖普通面板。
- 元素色可以作状态点缀，但不应让整套工具 UI 变成彩虹主题。

### accent_semantics
- 元素徽记
- 星尘
- 羽毛
- 风纹
- 传送锚点轮廓
- 古文明线纹
- 小晶石
- 地图标记
- 卷轴角花

### background_language
- 适合浅金蓝或晨雾绿的开阔幻想背景。背景应像远处的提瓦特地貌/遗迹边缘，而不是完整角色海报；中心保留 45%–60% 低纹理安全区，边缘放柔化石柱、浮岛轮廓、云层、星尘或元素光点。

### misclassification_risks
- 误判为通用蓝紫二次元手游渐变。
- 误判为冷色赛博 HUD。
- 过度堆角色立绘、抽卡金光、版本活动图。
- 把七元素做成高饱和彩虹 UI，削弱原神的清澈轻奢感。

## 3. Auto Game Style Brief
### style_keywords
- 明亮高幻想
- 开放世界冒险
- 元素魔法
- 精致轻奢
- 提瓦特旅途

### mood
- 明亮
- 清澈
- 治愈
- 好奇
- 轻史诗

### world_semantics
- 七元素
- 神之眼
- 传送锚点
- 古文明遗迹
- 星尘
- 云层
- 旅行者地图

### material_language
- 暖白羊皮纸
- 香槟金细边
- 半透明磨砂玻璃
- 柔和石材纹
- 轻粒子光晕

### shape_language
- 圆角矩形
- 细边框
- 菱形节点
- 对称徽章
- 轻浮雕
- 低纹理底

### palette_intent
- 象牙白主面板
- 香槟金层级与选中
- 青蓝/青绿辅助
- 深靛蓝仅作远景神秘层
- 元素色只作小面积状态或分类

### state_language
- normal：暖白底 + 浅金细边
- selected：浅金外发光 + 小元素徽记/星尘，不使用红色
- disabled：降低透明度 + 冷灰蓝雾化，不压灰装饰语义
- locked：小锁/封印纹 + 低饱和蓝灰
- warning/error：橙黄用于注意，红色只用于真实错误

### accent_semantics
- 元素徽记
- 星尘
- 羽毛
- 风纹
- 传送锚点
- 古文明线纹
- 晶石

### background_language
- 浅金蓝晨雾
- 远景遗迹/云层/浮岛
- 中心干净
- 边缘低饱和装饰
- 无角色海报化

### forbidden_directions
- 赛博霓虹
- 暗黑哥特
- 高饱和彩虹元素
- 抽卡金光满屏
- 中央大角色
- 复杂传送门

### maker_safe_assets
- 九宫格浅金边框
- 元素小图标 atlas
- 低透明星尘纹理
- 圆角磨砂卡片
- 云纹背景片
- 小菱形选中角标

## 4. UI Translation Recommendations
### panel_design
普通面板使用象牙白或暖灰白底，边框为 1–2px 香槟金，内高光轻而薄。大卡可加轻微石材/羊皮纸纹理，小卡必须简化为干净圆角卡 + 小徽记。阴影应柔和偏蓝灰，避免厚重黑影。状态栏可使用半透明磨砂蓝灰底配浅金分割线。

### state_design
normal 保持白金清爽；selected 用金色描边、轻外发光、星尘/元素角标表达“被祝福/被激活”；disabled 用低饱和蓝灰蒙层，但保留边框和功能图标；locked 使用封印纹或小锁，不能和禁用混为一体；warning 用琥珀黄提示，error 才用低面积红色，且不作为普通选中色。

### text_design
主标题可用较优雅的衬线感或高对比标题字，配少量浅金描边；分区标题使用深蓝灰或深棕灰；卡片主文字深灰蓝，副文字降低透明度；状态栏文字用深蓝灰或白字视底色而定。正文不依赖描边，小字号要清晰。

### accent_design
角标优先用元素徽记、星尘、小晶石、传送锚点轮廓和风纹。装饰应承担分类、选中、稀有度、引导等功能，不要每张卡都堆元素标志。装饰层级放在普通 overlay 之上，不被 disabled 蒙层完全压灰。

### background_design
生成工具背景时保留 45%–60% 中央安全区，安全区用低纹理晨雾/云层。边缘可放柔化遗迹石柱、浮岛、远山、星尘和轻元素光点。背景比 UI 弱，不能像登录页、抽卡页、角色海报或战斗截图；不要中央大光源、传送门、巨大角色、清晰文字或假按钮。

### maker_feasibility
目标 4–5。用纯色块、borderRadius、细 border、boxShadow、半透明遮罩、静态纹理贴图、九宫格边框、少量元素 icon 和简单 scale/opacity tween 即可。避免复杂 shader、动态粒子瀑布、真实材质光照和大量不可复用插画。

## 5. Tool Background Prompt
明亮高幻想开放世界工具 UI 背景，浅金蓝晨雾色调，中心 45%–60% 保留干净低纹理 UI 安全区，边缘有柔化的古代遗迹石柱、远山、云层、少量星尘和元素光点，低对比、低饱和、无强视觉中心、无清晰文字、无假按钮、无假输入框、无角色海报、无战斗场景、不过暗不过亮，背景弱于前景 UI，适合叠加面板和卡片。

## 6. Quality Gate
- 是否只是机械套用了代表色: 否；重点提炼清澈高幻想、元素与遗迹语义，而不是只套蓝金。
- 是否误判了具名游戏风格: 未见明显误判；核心是开放世界幻想冒险。
- 是否把具名游戏拆成了错误关键词: 否；避免拆成通用二次元/抽卡/蓝紫渐变。
- brief 是否来自 Game Style Understanding: 是。
- 背景是否服务 UI，而不是完整插画: 是；强调中心安全区和边缘远景。
- 背景是否过暗或过亮: 不应；保持晨雾中明度。
- UI 安全区是否足够干净: 是，45%–60%。
- 普通态、选中态、警示态是否混淆: 否；选中用金/星尘，警示用琥珀/红。
- 选中态是否像错误态: 否。
- 装饰语义是否符合游戏世界: 是。
- 装饰是否被蒙层压灰: 提醒不要完全压灰。
- 文字是否清晰: 是，正文深色字优先。
- 小卡片是否过度复杂: 已要求简化。
- Maker 成本是否过高: 否，建议 4–5 可行。
- 是否有硬编码游戏名映射: 无；以风格原则输出。
- 是否需要补充新的风格原型: 建议新增“明亮高幻想开放世界轻奢 UI”原型。

## 7. GitHub Metadata
```yaml
game_or_style_name: 原神
aliases:
  - Genshin Impact
  - Genshin
category: open_world_fantasy_action_rpg
visual_identity: 明亮高幻想开放世界冒险 RPG
source_confidence: high
last_updated: 2026-05-13
recommended_archetypes:
  - bright_high_fantasy_open_world
  - elemental_adventure_luxury_ui
misclassification_risks:
  - generic_anime_gradient
  - cyber_hud
  - dark_gothic
  - gacha_poster_ui
maker_feasibility_target: '4-5'
tags:
  - fantasy
  - elemental
  - open-world
  - light-luxury
  - adventure
  - blue-gold
  - soft-panel
```

---

# Game UI Style Knowledge Entry: 梦幻西游

## 1. Text Research Summary
- sources_checked:
  - TapTap 商店页：西游记世界观、仙人魔三族、十三门派、国民级回合制手游、亲密社交、经典回合、画风精美
- source_urls:
  - https://www.taptap.cn/app/2315/all-info
  - https://my.163.com/
- game_type: 西游题材国风回合制 MMORPG / 手游 RPG
- core_gameplay: 回合制战斗、门派养成、召唤灵/炼妖、装备打造、师门捉鬼、押镖、副本、社交组队。
- world_setting: 基于西游记与贞观年间的三界世界，仙、人、魔、多门派与召唤灵构成轻松热闹的国风幻想社会。
- player_role: 天命之人 / 三界修行者：拜入门派、组队冒险、养成召唤灵、参与社交与日常活动。
- emotional_experience: 热闹、亲切、Q 版、社交、节庆、轻松、国民化。
- key_visual_keywords:
  - Q版国风
  - 西游
  - 三界
  - 门派
  - 召唤灵
  - 热闹社交
  - 节庆
  - 圆润
- confidence: high

## 2. Game Style Understanding
### recognized_visual_identity
- 明亮 Q 版国风西游回合制 MMORPG：可爱人物、热闹三界、门派社交、节庆市集感。

### genre_presentation
- 回合制 MMORPG 被视觉化为“轻松热闹的西游三界社区”：不是冷蓝仙侠，也不是严肃写实唐风，而是圆润、彩色、可爱、社交化的国风幻想。

### primary_mood
- 明亮
- 热闹
- 亲切
- 童趣
- 喜庆
- 社交
- 轻松

### world_semantics
- 长安
- 门派
- 召唤灵
- 祥云
- 灯笼
- 锦旗
- 铜钱
- 葫芦
- 符纸
- 师门
- 帮派
- 摆摊

### common_ui_material_language
- 宣纸
- 卷轴
- 木牌
- 浅金边
- 红绳
- 玉佩
- 布纹
- 糖果感高光

### shape_language
- 圆润厚块面
- 卷轴角
- 木牌吊牌
- 轻浮雕
- 软阴影
- 饱满按钮
- 小动物/召唤灵角标

### palette_tendency
- 暖米黄/浅杏色用于面板底，表达亲切和可读性。
- 朱红/橙红用于喜庆、重要活动和提醒，但不能作为错误态的唯一识别。
- 金黄用于奖励、等级、选中和强强调。
- 青绿/天蓝用于辅助信息、清爽层级和门派差异。
- 深棕用于文字、边框和木牌结构，避免大面积冷黑。

### accent_semantics
- 祥云
- 灯笼
- 铜钱
- 葫芦
- 玉佩
- 红绳
- 卷轴
- 门派令牌
- 召唤灵小脸
- 锦旗

### background_language
- 适合暖米黄到浅天蓝的三界市集/长安远景氛围。中心留干净面板区，边缘可有灯笼、屋檐、祥云、远山、摊位轮廓；避免复杂街景和满屏节庆装饰。

### misclassification_risks
- 误判成冷蓝水墨仙侠。
- 误判成写实唐风宫廷。
- 过度使用红金导致变成春节活动页。
- 把 Q 版国风做成幼儿卡通，失去 MMORPG 门派和社交厚度。

## 3. Auto Game Style Brief
### style_keywords
- 明亮 Q 版国风
- 西游三界
- 回合制 MMORPG
- 热闹社交
- 门派养成

### mood
- 明亮
- 热闹
- 亲切
- 童趣
- 喜庆
- 轻松

### world_semantics
- 长安
- 门派
- 召唤灵
- 祥云
- 灯笼
- 铜钱
- 葫芦
- 卷轴
- 帮派

### material_language
- 宣纸
- 卷轴
- 木牌
- 浅金边
- 红绳
- 玉佩
- 布纹

### shape_language
- 圆润厚块面
- 卷轴角
- 软阴影
- 饱满按钮
- 木牌吊牌
- 轻浮雕

### palette_intent
- 米黄主面板
- 深棕文字/边框
- 朱红活动提醒
- 金黄选中/奖励
- 青绿天蓝辅助层次

### state_language
- normal：米黄纸底 + 深棕/浅金边
- selected：金色描边 + 小祥云/铜钱/门派令牌
- disabled：低饱和灰褐 + 纸纹保留
- locked：符纸封条/小锁
- warning/error：橙红用于警示，深红仅用于错误或危险

### accent_semantics
- 祥云
- 灯笼
- 铜钱
- 葫芦
- 玉佩
- 红绳
- 门派令
- 召唤灵

### background_language
- 暖米黄/浅天蓝
- 长安远景
- 屋檐和灯笼放边缘
- 中心低纹理
- 低饱和节庆感

### forbidden_directions
- 冷蓝水墨仙侠
- 写实宫廷唐风
- 春节红金满屏
- 幼儿卡通
- 黑金传奇页

### maker_safe_assets
- 九宫格卷轴边框
- 祥云角花
- 铜钱 icon
- 灯笼贴片
- 木牌按钮
- 召唤灵小圆标
- 红绳分割线

## 4. UI Translation Recommendations
### panel_design
普通面板使用米黄宣纸底，轻纸纹即可；边框可用浅金/深棕双线或卷轴角。大卡可做木牌/卷轴混合，小卡必须减少角花，只保留圆角、浅金边和一个功能图标。状态栏可用木牌或浅棕横条，但文字区域要干净。

### state_design
normal 亲切浅色；selected 用金黄描边、祥云角标、铜钱/门派令小标，不要用大红整块覆盖；disabled 降低饱和并保留纸纹层次；locked 用符纸封条或小锁；warning 用橙红，error 用更深红并配叹号，红色不能同时承担喜庆、选中和错误。

### text_design
主标题可用圆润国风标题字，配轻浅金边；分区标题深棕或朱砂小印章；卡片主文字深棕，副文字棕灰；状态栏文字用深棕或米白。正文绝不依赖重描边，小字号要放在低纹理底上。

### accent_design
装饰应服务功能：祥云用于分区/流动感，铜钱用于奖励，灯笼用于活动，符纸用于锁定/限制，门派令用于分类。不要每张卡都挂灯笼；小装饰放在 overlay 上层，避免被 disabled 灰层压没。

### background_design
背景是工具背景，不是长安完整街景。中心 45%–60% 保留米黄/浅天蓝低纹理区；边缘放低细节屋檐、灯笼、祥云、远山和摊位轮廓。避免高饱和红金、满屏铜钱、节日烟花、多人角色、假按钮和清晰招牌文字。

### maker_feasibility
目标 4–5。使用纯色底、borderRadius、borderWidth、boxShadow、九宫格卷轴边、少量祥云/铜钱/灯笼贴图和简单 bounce/scale tween。避免大量角色插画、复杂街景、粒子烟花和高精度金边。

## 5. Tool Background Prompt
明亮 Q 版国风西游工具 UI 背景，暖米黄与浅天蓝统一色调，中心 45%–60% 干净低纹理安全区，边缘有柔化长安屋檐、祥云、灯笼、远山和少量铜钱/红绳点缀，低对比、低饱和、轻松热闹但不拥挤，无清晰文字、无假按钮、无角色群像、无复杂街景、无满屏节庆烟花，背景弱于前景 UI，适合叠加面板卡片。

## 6. Quality Gate
- 是否只是机械套用了代表色: 否；强调 Q 版国风西游、社交与门派语义。
- 是否误判了具名游戏风格: 否；避免冷蓝水墨仙侠。
- 是否把具名游戏拆成了错误关键词: 否。
- brief 是否来自 Game Style Understanding: 是。
- 背景是否服务 UI，而不是完整插画: 是。
- 背景是否过暗或过亮: 应保持中高明度。
- UI 安全区是否足够干净: 是。
- 普通态、选中态、警示态是否混淆: 已区分金黄选中、橙红警示、深红错误。
- 选中态是否像错误态: 否。
- 装饰语义是否符合游戏世界: 是。
- 装饰是否被蒙层压灰: 提醒保留上层语义。
- 文字是否清晰: 是，深棕字优先。
- 小卡片是否过度复杂: 已要求简化。
- Maker 成本是否过高: 否。
- 是否有硬编码游戏名映射: 无。
- 是否需要补充新的风格原型: 建议新增“明亮 Q 版国风回合制”原型。

## 7. GitHub Metadata
```yaml
game_or_style_name: 梦幻西游
aliases:
  - Fantasy Westward Journey
  - 梦幻西游手游
  - 梦幻西游电脑版
category: turn_based_chinese_fantasy_mmorpg
visual_identity: 明亮 Q 版国风西游回合制 MMORPG
source_confidence: high
last_updated: 2026-05-13
recommended_archetypes:
  - bright_q_chinese_fantasy
  - westward_social_turn_based_ui
misclassification_risks:
  - cold_blue_xianxia
  - realistic_tang_court
  - spring_festival_red_gold
  - childish_cartoon
maker_feasibility_target: '4-5'
tags:
  - q-style
  - chinese-fantasy
  - westward-journey
  - turn-based
  - social
  - paper
  - wood
  - lantern
```

---

# Game UI Style Knowledge Entry: 大话西游

## 1. Text Research Summary
- sources_checked:
  - 网易大话西游2官方论坛/官网入口：大话西游2是回合制网游经典之作，强调西游杂谈、江湖客栈、比武大会等社区语义
  - App Store《大话西游：归来》：正版大话、情义归来、怀旧国风红木界面、原版长安城/东海渔村、人魔仙鬼、五人组队、回合策略
- source_urls:
  - https://xy2.netease.com/
  - https://apps.apple.com/cn/app/%E5%A4%A7%E8%AF%9D%E8%A5%BF%E6%B8%B8-%E5%BD%92%E6%9D%A5/id6444670359
- game_type: 经典西游 IP 回合制 RPG / 回合制网游 / 放置类回合制衍生作
- core_gameplay: 五人组队、回合制策略、种族职业搭配、召唤兽、帮战/比武/副本、经典地图探索与社交情义。
- world_setting: 西游三界、长安城、东海渔村、帮派江湖与情义社交，整体更偏怀旧、江湖、市井与红木国风。
- player_role: 少侠/天命之人/三界行者：在经典大话世界中组队、修行、比武、养成召唤兽并重温情义。
- emotional_experience: 怀旧、江湖、情义、市井、热闹、经典、略成熟。
- key_visual_keywords:
  - 怀旧国风
  - 红木界面
  - 西游三界
  - 长安城
  - 东海渔村
  - 情义
  - 回合策略
  - 江湖客栈
- confidence: medium_high

## 2. Game Style Understanding
### recognized_visual_identity
- 怀旧红木国风西游回合制 RPG：比梦幻西游更成熟、更江湖、更有红木/客栈/情义记忆点。

### genre_presentation
- 回合制 RPG 被视觉化为“老朋友重聚的西游江湖”：重点不是童趣可爱，而是怀旧红木、旧卷轴、客栈、市井长安、五人组队和策略情义。

### primary_mood
- 怀旧
- 情义
- 江湖
- 市井
- 热闹
- 稳重
- 经典

### world_semantics
- 长安城
- 东海渔村
- 江湖客栈
- 红木界面
- 召唤兽
- 神兵
- 帮派
- 比武大会
- 五人组队
- 西游妖魔

### common_ui_material_language
- 红木
- 旧宣纸
- 铜扣
- 雕花木框
- 卷轴
- 酒肆木牌
- 玉佩
- 布纹
- 暗金边

### shape_language
- 较厚木框
- 圆角但更稳重
- 雕花角
- 牌匾形标题
- 暗金细边
- 卷轴压边
- 分栏结构

### palette_tendency
- 红木棕/深栗色用于框架、标题栏和强结构，传达怀旧与经典。
- 旧纸米黄用于内容底，保证工具 UI 可读。
- 暗金/铜金用于边框、奖励、选中和品质感。
- 朱红用于情义/活动/重要提示，但不应满屏高饱和。
- 青玉绿/墨蓝可作为辅助，缓和红木色的厚重。

### accent_semantics
- 铜扣
- 木牌
- 酒旗
- 玉佩
- 卷轴轴头
- 祥云
- 神兵纹
- 召唤兽小印
- 客栈灯笼
- 帮派令牌

### background_language
- 适合红木暖棕 + 旧纸米黄的客栈/长安边缘氛围。中心需低纹理安全区；边缘可以有客栈木梁、灯笼、卷轴、远景街巷或东海渔村轮廓，但不可做成复杂街景。

### misclassification_risks
- 被误判成梦幻西游式过度 Q 萌。
- 被误判成冷蓝仙侠或写实水墨武侠。
- 红木与暗金过重导致变成传奇/页游黑金。
- 只记住西游，不记住大话的怀旧情义和市井江湖。

## 3. Auto Game Style Brief
### style_keywords
- 怀旧红木国风
- 西游江湖
- 情义社交
- 回合制经典
- 客栈市井

### mood
- 怀旧
- 情义
- 江湖
- 市井
- 热闹
- 稳重

### world_semantics
- 长安城
- 东海渔村
- 江湖客栈
- 召唤兽
- 神兵
- 帮派
- 比武大会
- 五人组队

### material_language
- 红木
- 旧宣纸
- 铜扣
- 雕花木框
- 酒肆木牌
- 玉佩
- 暗金边

### shape_language
- 厚木框
- 牌匾标题
- 雕花角
- 暗金细边
- 卷轴压边
- 稳重圆角

### palette_intent
- 旧纸米黄内容底
- 红木棕框架
- 铜金选中/奖励
- 朱红重要提示
- 青玉绿/墨蓝辅助

### state_language
- normal：旧纸底 + 红木框
- selected：铜金边 + 玉佩/帮派令角标
- disabled：褪色木纹 + 灰褐遮罩
- locked：铜锁/符纸封条
- warning/error：朱红或暗红只用于真实风险，普通选中不用红底

### accent_semantics
- 铜扣
- 木牌
- 酒旗
- 玉佩
- 卷轴
- 客栈灯笼
- 帮派令
- 召唤兽印

### background_language
- 红木暖棕
- 旧纸米黄中心
- 客栈/长安边缘
- 低细节街巷
- 怀旧但不黑金

### forbidden_directions
- 过度 Q 萌
- 冷蓝仙侠
- 写实武侠水墨
- 传奇黑金
- 春节红金活动页

### maker_safe_assets
- 红木九宫格边框
- 旧纸纹理
- 铜扣 icon
- 牌匾标题条
- 玉佩角标
- 灯笼贴片
- 帮派令小标

## 4. UI Translation Recommendations
### panel_design
普通面板用旧纸米黄内容底 + 红木棕框架，边框可做九宫格雕花木框。大卡可使用牌匾标题条、铜扣和暗金细线；小卡应去掉复杂雕花，只保留红木描边、圆角和一个语义角标。状态栏适合酒肆木牌或卷轴横条。

### state_design
normal 稳重旧纸；selected 用铜金描边、玉佩/帮派令角标和轻内高光；disabled 用褪色木纹与灰褐遮罩，但保留锁/封条可见；locked 用铜锁或符纸封条；warning 用朱红，error 用暗红 + 图标，不要把红木底误当错误态。

### text_design
主标题可用牌匾式国风标题，暗金或米白字；分区标题用深栗色/暗金；卡片主文字深棕，副文字灰褐；状态栏文字用米白或旧纸深棕。正文必须清晰，避免在木纹上直接放小字。

### accent_design
装饰从客栈、帮派、召唤兽、神兵和卷轴系统中来：铜扣用于结构节点，玉佩用于选中/品质，酒旗/灯笼用于活动，符纸/铜锁用于限制。不要把祥云灯笼铺满所有卡片，装饰要有功能指向。

### background_design
中心 45%–60% 保留旧纸/暖棕低纹理安全区。边缘可放红木梁、客栈灯笼、卷轴轴头、长安远景、东海渔村剪影。避免复杂街景、黑金页游感、满屏红色、多人角色、清晰牌匾文字和假 UI。

### maker_feasibility
目标 4–5。用旧纸底图、红木九宫格边、铜扣小图、牌匾标题、静态灯笼和简单位移/缩放 tween。避免复杂木雕逐帧、高精度写实光照和整屏街景插画。

## 5. Tool Background Prompt
怀旧红木国风西游工具 UI 背景，红木暖棕与旧纸米黄统一色调，中心 45%–60% 保持干净低纹理安全区，边缘有柔化客栈木梁、灯笼、卷轴轴头、长安远景或东海渔村剪影，低对比、低饱和、怀旧情义氛围，无清晰文字、无假按钮、无角色群像、无复杂街景、无黑金页游质感、不过暗不过亮，背景弱于前景面板。

## 6. Quality Gate
- 是否只是机械套用了代表色: 否；红木只是材质入口，核心是怀旧情义与西游江湖。
- 是否误判了具名游戏风格: 基本否；按大话系列基础风格处理。
- 是否把具名游戏拆成了错误关键词: 否；未仅拆成西游/国风。
- brief 是否来自 Game Style Understanding: 是。
- 背景是否服务 UI，而不是完整插画: 是。
- 背景是否过暗或过亮: 需避免黑金过暗。
- UI 安全区是否足够干净: 是。
- 普通态、选中态、警示态是否混淆: 已区分铜金选中与朱红/暗红警示。
- 选中态是否像错误态: 否。
- 装饰语义是否符合游戏世界: 是。
- 装饰是否被蒙层压灰: 提醒保留角标可见。
- 文字是否清晰: 是，避免木纹小字。
- 小卡片是否过度复杂: 已要求简化。
- Maker 成本是否过高: 否。
- 是否有硬编码游戏名映射: 无；但“大话西游”系列分支建议在入库时保留 aliases。
- 是否需要补充新的风格原型: 建议新增“怀旧红木国风西游江湖 UI”原型。

## 7. GitHub Metadata
```yaml
game_or_style_name: 大话西游
aliases:
  - 大话西游2
  - 大话西游：归来
  - Westward Journey Online
category: classic_turn_based_westward_journey_rpg
visual_identity: 怀旧红木国风西游回合制 RPG
source_confidence: medium_high
last_updated: 2026-05-13
recommended_archetypes:
  - nostalgic_redwood_chinese_ui
  - westward_jianghu_turn_based_ui
misclassification_risks:
  - too_q_cute
  - cold_xianxia
  - realistic_wuxia_ink
  - legend_black_gold
maker_feasibility_target: '4-5'
tags:
  - nostalgic
  - redwood
  - westward-journey
  - turn-based
  - jianghu
  - paper
  - bronze
  - inn
```

---

# Game UI Style Knowledge Entry: 英雄联盟

## 1. Text Research Summary
- sources_checked:
  - Riot 官方 How to Play：两队五名英雄，摧毁敌方基地，防御塔/召唤水晶/野区/男爵和小龙，五个位置，技能与装备成长
  - 英雄联盟繁中官网：团队策略游戏、160+ 英雄、召唤峡谷、5v5 团战、摧毁敌方主堡
  - 腾讯国服官网：风格各异英雄、物品合成、匹配排行竞技、召唤师系统、技能符文天赋
- source_urls:
  - https://www.leagueoflegends.com/zh-tw/
  - https://www.leagueoflegends.com/en-us/how-to-play/
  - https://lol.qq.com/v2/
- game_type: 团队策略 MOBA / 5v5 竞技对战
- core_gameplay: 两队五名英雄分路推进、击杀、推塔、控制野区资源、购买装备、释放技能并摧毁敌方主堡/水晶。
- world_setting: 以符文之地为世界观底层，实际主界面/竞技语义集中在召唤师峡谷、英雄、符文、装备、段位、战术地图和电竞赛事。
- player_role: 召唤师/玩家操控单个英雄，与队友协作占线、团战、争夺资源并赢得比赛。
- emotional_experience: 竞技、紧张、策略、英雄感、胜负、专业、史诗但高可读。
- key_visual_keywords:
  - 5v5
  - MOBA
  - 召唤师峡谷
  - 英雄
  - 符文
  - 装备
  - 防御塔
  - 水晶
  - 电竞
  - 战术地图
- confidence: high

## 2. Game Style Understanding
### recognized_visual_identity
- 史诗竞技幻想 MOBA：深蓝金属/石材 HUD、符文能量、英雄徽章、战术地图与电竞段位感。

### genre_presentation
- MOBA 被视觉化为“竞技战场指挥界面”：强调清晰信息层级、英雄头像/技能/装备/资源状态、防御塔与水晶目标，不是剧情幻想插画或泛二次元卡牌。

### primary_mood
- 竞技
- 紧张
- 专业
- 史诗
- 策略
- 锋利
- 胜负感

### world_semantics
- 召唤师峡谷
- 英雄徽章
- 符文
- 装备
- 防御塔
- 水晶/主堡
- 野区
- 男爵
- 小龙
- 段位徽章
- 战术小地图

### common_ui_material_language
- 深蓝钢铁
- 暗色石材
- 金属镶边
- 符文刻线
- 半透明 HUD
- 宝石光点
- 电竞分割线

### shape_language
- 硬边切角
- 盾牌徽章
- 锐利金属边
- 六边形/菱形节点
- 技能槽圆/方混合
- 高信息密度网格
- 清晰分栏

### palette_tendency
- 深海军蓝/黑蓝用于主背景和 HUD 底，提供竞技沉浸感。
- 古金/亮金用于段位、选中、奖励和高价值层级。
- 冷青/蓝光用于可交互高光、技能冷却和系统强调。
- 红色用于敌方、危险和失败，不应用作普通选中。
- 绿色/青绿用于生命、恢复、可用状态，需和蓝色交互态区分。

### accent_semantics
- 符文刻印
- 盾牌
- 剑刃
- 水晶碎片
- 技能槽
- 装备边框
- 段位徽章
- 小地图网格
- 塔/水晶图标

### background_language
- 适合深蓝灰竞技峡谷/石材 HUD 背景。中心留低纹理暗色安全区；边缘可放模糊战术地图线、符文刻线、金属边框、远景峡谷轮廓。不要做成完整团战场面或英雄宣传图。

### misclassification_risks
- 误判成赛博霓虹电竞。
- 误判成通用西幻 RPG。
- 把符文/段位金边做成页游黑金。
- 用英雄皮肤活动视觉代替长期 MOBA HUD 语义。
- 信息密度过高导致工具 UI 不可读。

## 3. Auto Game Style Brief
### style_keywords
- 史诗竞技幻想 MOBA
- 深蓝金属 HUD
- 符文能量
- 英雄徽章
- 战术地图

### mood
- 竞技
- 紧张
- 专业
- 史诗
- 策略
- 胜负感

### world_semantics
- 召唤师峡谷
- 英雄
- 符文
- 装备
- 防御塔
- 水晶
- 野区
- 男爵
- 小龙
- 段位

### material_language
- 深蓝钢铁
- 暗色石材
- 金属镶边
- 符文刻线
- 半透明 HUD
- 宝石光点

### shape_language
- 硬边切角
- 盾牌徽章
- 锐利金属边
- 菱形节点
- 技能槽
- 网格分栏

### palette_intent
- 深蓝黑 HUD 底
- 古金选中/段位
- 冷蓝交互高光
- 红色敌方/危险
- 绿色生命/可用

### state_language
- normal：深蓝灰底 + 金属细边
- selected：古金描边 + 冷蓝内光/符文激活
- disabled：降低亮度 + 冷灰遮罩
- locked：锁链/封印符文
- warning/error：红色只表示敌方/危险/失败，黄色用于注意或资源不足

### accent_semantics
- 符文
- 盾牌
- 剑刃
- 水晶
- 技能槽
- 装备框
- 段位徽章
- 小地图线

### background_language
- 深蓝灰
- 暗石材
- 模糊峡谷/战术地图边缘
- 中心暗且干净
- 低饱和符文光

### forbidden_directions
- 赛博霓虹
- 通用西幻背包页
- 页游黑金
- 皮肤活动海报
- 复杂团战场景
- 过高信息密度

### maker_safe_assets
- 切角金属九宫格
- 符文线纹贴图
- 盾牌徽章 icon
- 技能槽框
- 水晶小标
- 小地图网格遮罩
- 段位角标

## 4. UI Translation Recommendations
### panel_design
普通面板用深蓝灰/暗石材底，金属细边和轻内阴影。大卡可用切角金属框、盾牌标题和符文线纹；小卡必须降低材质，只保留切角、细边和一枚功能图标。状态栏适合半透明 HUD 条，边缘用冷蓝或古金分割线。

### state_design
normal 深蓝灰稳定；selected 使用古金外框 + 冷蓝符文内光，不能用红色；disabled 降低亮度并降低饱和，保留图标轮廓；locked 用锁链/封印符文；warning 用黄色/琥珀表示资源不足或注意，error/敌方/失败使用红色，红色不能用于常规装饰。

### text_design
主标题可用锐利电竞/史诗标题字，古金或米白；分区标题用冷蓝小字加金属分割线；卡片主文字白或浅灰蓝，副文字灰蓝；状态栏文字应高对比。正文不使用复杂描边，避免在符文纹理上压小字。

### accent_design
装饰必须围绕战术与竞技语义：符文用于激活/技能，盾牌用于英雄/防御，水晶用于目标/核心，装备框用于资源，段位徽章用于等级。不要把剑、盾、符文无差别堆满卡片；装饰不应压住信息。

### background_design
工具背景中心 45%–60% 保持低纹理深蓝灰安全区。边缘可有模糊召唤师峡谷轮廓、战术小地图线、暗石材、金属边和低饱和符文光。避免清晰团战、巨大英雄、皮肤海报、火焰爆炸、假 UI、清晰文字和高饱和霓虹。

### maker_feasibility
目标 4–5。使用纯色深底、borderWidth、切角 mask、boxShadow、半透明 HUD 层、静态符文线纹、少量徽章/技能槽 icon 与简单 glow/scale tween。避免复杂 3D 金属材质、动态战场、海量粒子和多英雄插画。

## 5. Tool Background Prompt
史诗竞技幻想 MOBA 工具 UI 背景，深蓝灰暗石材与低饱和金属 HUD 色调，中心 45%–60% 保留干净低纹理安全区，边缘有模糊召唤师峡谷轮廓、战术小地图线、符文刻线、金属切角边框和少量冷蓝能量光，低对比、低饱和、无强视觉中心、无清晰文字、无假按钮、无英雄海报、无复杂团战、无赛博霓虹、不过暗不过亮，背景弱于前景 UI。

## 6. Quality Gate
- 是否只是机械套用了代表色: 否；强调 MOBA 目标、符文、英雄徽章和战术 HUD。
- 是否误判了具名游戏风格: 否；未把它当通用西幻 RPG。
- 是否把具名游戏拆成了错误关键词: 否。
- brief 是否来自 Game Style Understanding: 是。
- 背景是否服务 UI，而不是完整插画: 是。
- 背景是否过暗或过亮: 需避免过暗压文字，深底要留可读区。
- UI 安全区是否足够干净: 是。
- 普通态、选中态、警示态是否混淆: 已区分金/蓝选中与红色危险。
- 选中态是否像错误态: 否。
- 装饰语义是否符合游戏世界: 是。
- 装饰是否被蒙层压灰: 提醒保留信息层级。
- 文字是否清晰: 是，浅色字和低纹理底。
- 小卡片是否过度复杂: 已要求简化。
- Maker 成本是否过高: 否。
- 是否有硬编码游戏名映射: 无。
- 是否需要补充新的风格原型: 建议新增“史诗竞技 MOBA 深蓝金属 HUD”原型。

## 7. GitHub Metadata
```yaml
game_or_style_name: 英雄联盟
aliases:
  - League of Legends
  - LoL
  - LOL
category: team_based_strategy_moba
visual_identity: 史诗竞技幻想 MOBA 深蓝金属 HUD
source_confidence: high
last_updated: 2026-05-13
recommended_archetypes:
  - epic_competitive_moba_hud
  - rune_metal_strategy_ui
misclassification_risks:
  - cyber_neon_esports
  - generic_western_fantasy
  - webgame_black_gold
  - skin_poster_ui
maker_feasibility_target: '4-5'
tags:
  - moba
  - competitive
  - rune
  - metal
  - hud
  - strategy
  - blue-gold
  - champion
```

---
