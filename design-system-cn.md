# ThePromptProtocol 设计规范

## 1. 品牌 Logo

- 品牌名称：ThePromptProtocol
- 图形符号：一条斜杠"/"与字母"P"组合而成的图形标记（可读作 "/P"），置于圆形色块背景中
- 文字部分（Wordmark）由两部分组成：顶部小号"THE"上标文字 + 主体"PromptProtocol"文字
- 资产文件：
  - **完整标志（Logo）**：`img-brand-logo.svg` —— 图标 + 文字组合，含 4 种配色变体
  - **图形标记（Logomark）**：`img-brand-logomark.svg` —— 仅图标，不含文字，含相同的 4 种配色变体

### 1.1 配色变体

| 变体 | 圆形背景色 | 图标"P"颜色 | "PromptProtocol"颜色 | "THE"颜色 |
|---|---|---|---|---|
| 浅色背景版 | 渐变 White → #E3E3E3 | Brand/100 #47EA81 | Brand/100 #47EA81 | Black #000000 |
| 黑底版 | Black #000000 | Brand/100 #47EA81 | Black #000000 | Black #000000 |
| 纯图标版（无背景） | White #FFFFFF（在浅色画布上视觉无背景） | Brand/100 #47EA81 | Brand/100 #47EA81 | Black #000000 |
| 纯绿色背景版 | Brand/100 #47EA81 | White #FFFFFF | Black #000000 | Black #000000 |

> 注：Logomark（纯图标）文件的 4 种变体背景/图标配色与上表完全一致，只是不含文字部分。

### 1.2 尺寸规范
- 图标直径：24px（圆形色块）
- 图标与文字组合（完整 Logo）参考尺寸：134×24，图标与文字间距约 8–9px
- 完整 Logo 中，"THE"字样与主文字"PromptProtocol"左对齐排列在图标右侧

## 2. 色彩系统 (Color Variables and Styles)

### 2.1 品牌色 Brand Colors
| 名称 | Hex |
|---|---|
| Brand/100 | #47EA81 |
| Brand/120 | #39BB67 |
| Brand/80 | #6CEE9A |
| Brand/70 | #7EF0A7 |
| Brand/50 | #A3F5C0 |
| Brand/30 | #C8F9D9 |
| Brand/20 | #DAFBE6 |
| Brand/10 | #EDFDF2 |

### 2.2 辅助色 Secondary Colors
| 名称 | Hex |
|---|---|
| Secondary/100 | #979FFD |
| Secondary/120 | #797FCA |
| Secondary/80 | #ACB2FD |
| Secondary/70 | #B6BCFE |
| Secondary/50 | #CBCFFE |
| Secondary/30 | #E0E2FE |
| Secondary/20 | #EAECFF |
| Secondary/10 | #F5F5FF |

### 2.3 中性色 Neutral Colors
| 名称 | Hex |
|---|---|
| Black | #000000 |
| Neutral/90 | #242733 |
| Neutral/80 | #3A3E4C |
| Neutral/70 | #606064 |
| Neutral/60 | #6F7075 |
| Neutral/50 | #85878A |
| Neutral/40 | #A9A9A9 |
| Neutral/30 | #C3C3C3 |
| Neutral/20 | #DBDBDB |
| Neutral/10 | #F0F0F0 |
| White | #FFFFFF |

### 2.4 渐变色 Gradient Color
- Gradient/Green-Blue（绿色到蓝色）
- Gradient/Orange-Yellow（橙色到黄色）
- Gradient/Green-Pink（绿色到粉色）

## 3. 字体排版 (Typography — Montserrat)

字体家族：**Montserrat**

### 3.1 Titles
| 样式 | 字号 | 行高 | 字重 |
|---|---|---|---|
| Title 42 Bold | 42px | 58px | Bold |
| Title 32 Bold | 32px | 40px | Bold |
| Title 24 Bold | 24px | 36px | Bold |
| Title 24 Medium | 24px | 36px | Medium |

### 3.2 Subtitles
| 样式 | 字号 | 行高 | 字重 |
|---|---|---|---|
| Subtitle 20 Bold | 20px | 24px | Bold |
| Subtitle 20 Medium | 20px | 24px | Medium |
| Subtitle 18 Bold | 18px | 22px | Bold |
| Subtitle 18 Semi Bold | 18px | 22px | Semibold |
| Subtitle 18 Medium | 18px | 22px | Medium |
| Subtitle 18 Regular | 18px | 22px | Regular |
| Subtitle 16 Semi Bold | 16px | 20px | Semibold |

### 3.3 Body
| 样式 | 字号 | 行高 | 字重 |
|---|---|---|---|
| Body 16 Medium | 16px | 24px | Medium |
| Body 16 Regular | 16px | 24px | Regular |
| Body 14 Medium | 14px | 22px | Medium |
| Body 14 Regular | 14px | 22px | Regular |
| Body 13 Medium | 13px | 18px | Medium |
| Body 13 Regular | 13px | 18px | Regular |

### 3.4 Captions
| 样式 | 字号 | 行高 | 字重 |
|---|---|---|---|
| Caption 12 Medium | 12px | 20px | Semi Bold |
| Caption 12 Regular | 12px | 20px | Regular |

### 3.5 Action（按钮/链接文字）
| 样式 | 字号 | 行高 | 字重 |
|---|---|---|---|
| Button 14 | 14px | 18px | Medium |
| Link 14 | 14px | 18px | Semibold |
| Button 12 | 12px | 16px | Medium |
| Button 10 | 10px | 13px | Regular |

## 4. 图标 (Icons)
- **Base icons-Line**：线性风格基础图标库（导航、操作、箭头等，数量众多）
- **Menu icons**：用于菜单/导航的彩色图标
- **Tasks icons**：任务相关图标
- **Assets icons**：资产/资源相关的彩色图标

## 5. 按钮 (Buttons)

共 4 种尺寸：Small / Medium / Large / Text，每种均有 fill（实心）与 line（描边）两种样式，以及 default / hover / pressed / disabled 四种状态。

| 尺寸 | 容器大小(示例) | 内边距(水平/垂直) | 圆角 | 字号 |
|---|---|---|---|---|
| Button Small | 82×30px | 16 / 8 | 30（胶囊形） | 14px |
| Button Medium | 105×40px | 24 / 12 | 40（胶囊形） | 16px |
| Button Large | 135×52px | 32 / 16 | 52（胶囊形） | — |
| Button Text | 内容自适应 | 20 / 4 | 0（无背景） | 14px |

**状态颜色（以 fill 样式为例）：**
| 状态 | 填充色 | 文字色 |
|---|---|---|
| Default | Brand/100 | Black |
| Hover | Brand/70 | Black |
| Pressed | Brand/120 | Black |
| Disabled | Neutral/20 | Neutral/50 |

**line（描边）样式**：无填充，描边色 Brand/100，描边宽度 1px（内部对齐）。

## 6. 间距系统 (Space — 4pt Grid)

采用 4pt 网格间距体系，基础间距刻度为：
```
2, 4, 6, 8, 10, 12, 16, 20, 24, 28, 32, 36 (px)
```

## 7. 阴影与模糊 (Shadows and Blur Styles)

阴影分为三档强度 × 四种尺寸，共 12 种样式：
- 强度：subtle（轻）/ regular（常规）/ strong（强）
- 尺寸：sm / md / lg / xl

示例（regular md）：`X:0 Y:2.96 Blur:5.93 Spread:0 颜色:#000000 10%`，实际效果由 3 层投影叠加 + 1 层背景模糊组成，营造由浅到深的层次感。

## 8. 品牌吉祥物 / IP 形象

品牌自带卡通 IP 形象（绿色 "P" 字造型的角色），包含：

### 8.1 Base（基础形象）

![IP Base](assets/img-brand-_IPBase.svg)

基础造型：绿色 "P" 字形身体，搭配黑白椭圆形眼睛，无额外表情或配饰。

### 8.2 Avatar（头像变体）

多种表情/装扮头像变体：

| 默认 | 冬季毛帽+围巾 | 蓝色棒球帽 | 橙色棒球帽 | 遮阳帽 | 牛仔帽 |
|---|---|---|---|---|---|
| ![默认](assets/avatar/avatar-default.png) | ![冬季毛帽+围巾](assets/avatar/avatar-winter-cap-scarf.png) | ![蓝色棒球帽](assets/avatar/avatar-cap-blue.png) | ![橙色棒球帽](assets/avatar/avatar-cap-orange-heart.png) | ![遮阳帽](assets/avatar/avatar-hat-safari.png) | ![牛仔帽](assets/avatar/avatar-hat-fedora.png) |

| 蓝绿条纹围巾 | 睫毛款(默认) | 阔边帽+粉色围巾 | 蝴蝶结+围巾 | 睫毛款+红围巾 | 生气 |
|---|---|---|---|---|---|
| ![蓝绿条纹围巾](assets/avatar/avatar-scarf-teal.png) | ![睫毛款](assets/avatar/avatar-lashes.png) | ![阔边帽+粉色围巾](assets/avatar/avatar-sunhat-scarf-pink.png) | ![蝴蝶结+围巾](assets/avatar/avatar-bow-scarf.png) | ![睫毛款+红围巾](assets/avatar/avatar-lashes-scarf-red.png) | ![生气](assets/avatar/avatar-angry.png) |

| 害羞/眩晕 | 可爱(眯眼笑) | 怀疑 | 爱心眼 | 困倦 | 侧看/眨眼 |
|---|---|---|---|---|---|
| ![害羞眩晕](assets/avatar/avatar-dizzy.png) | ![可爱](assets/avatar/avatar-kawaii.png) | ![怀疑](assets/avatar/avatar-suspicious.png) | ![爱心眼](assets/avatar/avatar-heart-eyes.png) | ![困倦](assets/avatar/avatar-sleepy.png) | ![侧看眨眼](assets/avatar/avatar-wink-side.png) |

### 8.3 Emojis Gif（动态表情包）

动态表情包系列：

| Coming Right Up! | Good Morning! | Heart | Like | Nice |
|---|---|---|---|---|
| ![Coming Right Up](assets/Coming_right_up_.png) | ![Good Morning](assets/Good_Morning_.png) | ![Heart](assets/Heart.png) | ![Like](assets/Like.png) | ![Nice](assets/nice.png) |
