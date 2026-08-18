# ThePromptProtocol 设计规范

## 1. 品牌 Logo

- 品牌名称：ThePromptProtocol
- 图形符号：一条斜杠"/"与字母"P"组合而成的图形标记（可读作 "/P"），置于圆形色块背景中
- 文字部分（Wordmark）由两部分组成：顶部小号"THE"上标文字 + 主体"PromptProtocol"文字
- 资产文件：
  - **完整标志（Logo）**：`assets/img-brand-logo/` —— 图标 + 文字组合，含 4 种配色变体（main / black / white / green）
  - **图形标记（Logomark）**：`assets/img-brand-logomark/` —— 仅图标，不含文字，含相同的 4 种配色变体（main / black / white / green）

### 1.1 配色变体

| 变体 | 完整 Logo 预览 | Logomark 预览 | 圆形背景色 | 图标"P"颜色 | "PromptProtocol"颜色 | "THE"颜色 |
|---|---|---|---|---|---|---|
| 浅色背景版 | ![Logo-浅色](assets/img-brand-logo/main.svg) | ![Logomark-浅色](assets/img-brand-logomark/main.svg) | 渐变 White → #E3E3E3 | Brand/100 #47EA81 | Brand/100 #47EA81 | Black #000000 |
| 黑底版 | ![Logo-黑底](assets/img-brand-logo/black.svg) | ![Logomark-黑底](assets/img-brand-logomark/black.svg) | Black #000000 | Brand/100 #47EA81 | Black #000000 | Black #000000 |
| 纯图标版（无背景） | ![Logo-白色](assets/img-brand-logo/white.svg) | ![Logomark-白色](assets/img-brand-logomark/white.svg) | White #FFFFFF（在浅色画布上视觉无背景） | Brand/100 #47EA81 | Brand/100 #47EA81 | Black #000000 |
| 纯绿色背景版 | ![Logo-绿色](assets/img-brand-logo/green.svg) | ![Logomark-绿色](assets/img-brand-logomark/green.svg) | Brand/100 #47EA81 | White #FFFFFF | Black #000000 | Black #000000 |

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

### 4.1 Base icons-Line（线性基础图标库）
线性风格基础图标库，用于导航、操作、箭头等通用场景，共 130 个：

| | | | | | | | |
|---|---|---|---|---|---|---|---|
| ![AddCircle-1](assets/icons/base-line/AddCircle-1.svg) | ![AddCircle](assets/icons/base-line/AddCircle.svg) | ![Add_Tags](assets/icons/base-line/Add_Tags.svg) | ![Back](assets/icons/base-line/Back.svg) | ![Brand](assets/icons/base-line/Brand.svg) | ![Calendar](assets/icons/base-line/Calendar.svg) | ![Camera-1](assets/icons/base-line/Camera-1.svg) | ![Camera](assets/icons/base-line/Camera.svg) |
| AddCircle-1 | AddCircle | Add_Tags | Back | Brand | Calendar | Camera-1 | Camera |
| ![Card](assets/icons/base-line/Card.svg) | ![Categories](assets/icons/base-line/Categories.svg) | ![Chart-pie](assets/icons/base-line/Chart-pie.svg) | ![Chart](assets/icons/base-line/Chart.svg) | ![Check](assets/icons/base-line/Check.svg) | ![CheckCircle](assets/icons/base-line/CheckCircle.svg) | ![Clock](assets/icons/base-line/Clock.svg) | ![CloseCircle-1](assets/icons/base-line/CloseCircle-1.svg) |
| Card | Categories | Chart-pie | Chart | Check | CheckCircle | Clock | CloseCircle-1 |
| ![CloseCircle](assets/icons/base-line/CloseCircle.svg) | ![Contact](assets/icons/base-line/Contact.svg) | ![ContactWithUS](assets/icons/base-line/ContactWithUS.svg) | ![Copy](assets/icons/base-line/Copy.svg) | ![Delete](assets/icons/base-line/Delete.svg) | ![Discount](assets/icons/base-line/Discount.svg) | ![Dislike](assets/icons/base-line/Dislike.svg) | ![Down](assets/icons/base-line/Down.svg) |
| CloseCircle | Contact | ContactWithUS | Copy | Delete | Discount | Dislike | Down |
| ![DownFill](assets/icons/base-line/DownFill.svg) | ![DownLine](assets/icons/base-line/DownLine.svg) | ![DownkCircle](assets/icons/base-line/DownkCircle.svg) | ![Downlosd](assets/icons/base-line/Downlosd.svg) | ![Edit](assets/icons/base-line/Edit.svg) | ![Edit_Complete](assets/icons/base-line/Edit_Complete.svg) | ![Email](assets/icons/base-line/Email.svg) | ![ErrorCircle](assets/icons/base-line/ErrorCircle.svg) |
| DownFill | DownLine | DownkCircle | Downlosd | Edit | Edit_Complete | Email | ErrorCircle |
| ![Expand](assets/icons/base-line/Expand.svg) | ![Explore](assets/icons/base-line/Explore.svg) | ![Eye-1](assets/icons/base-line/Eye-1.svg) | ![Eye](assets/icons/base-line/Eye.svg) | ![Feedback](assets/icons/base-line/Feedback.svg) | ![Filter](assets/icons/base-line/Filter.svg) | ![FingerPrint](assets/icons/base-line/FingerPrint.svg) | ![GPS](assets/icons/base-line/GPS.svg) |
| Expand | Explore | Eye-1 | Eye | Feedback | Filter | FingerPrint | GPS |
| ![Global](assets/icons/base-line/Global.svg) | ![Hand](assets/icons/base-line/Hand.svg) | ![Home](assets/icons/base-line/Home.svg) | ![Inbox](assets/icons/base-line/Inbox.svg) | ![InfoCircle](assets/icons/base-line/InfoCircle.svg) | ![LanguageSwitching](assets/icons/base-line/LanguageSwitching.svg) | ![Left](assets/icons/base-line/Left.svg) | ![LeftCircle](assets/icons/base-line/LeftCircle.svg) |
| Global | Hand | Home | Inbox | InfoCircle | LanguageSwitching | Left | LeftCircle |
| ![LeftLine](assets/icons/base-line/LeftLine.svg) | ![Like](assets/icons/base-line/Like.svg) | ![Link](assets/icons/base-line/Link.svg) | ![Loading](assets/icons/base-line/Loading.svg) | ![Location-1](assets/icons/base-line/Location-1.svg) | ![Location](assets/icons/base-line/Location.svg) | ![Lock](assets/icons/base-line/Lock.svg) | ![Love](assets/icons/base-line/Love.svg) |
| LeftLine | Like | Link | Loading | Location-1 | Location | Lock | Love |
| ![Mark](assets/icons/base-line/Mark.svg) | ![Marketplace](assets/icons/base-line/Marketplace.svg) | ![Menu](assets/icons/base-line/Menu.svg) | ![MenuDraw](assets/icons/base-line/MenuDraw.svg) | ![MenuPush](assets/icons/base-line/MenuPush.svg) | ![Message](assets/icons/base-line/Message.svg) | ![Microphone-slash](assets/icons/base-line/Microphone-slash.svg) | ![Microphone](assets/icons/base-line/Microphone.svg) |
| Mark | Marketplace | Menu | MenuDraw | MenuPush | Message | Microphone-slash | Microphone |
| ![Mobile](assets/icons/base-line/Mobile.svg) | ![More](assets/icons/base-line/More.svg) | ![MoreCircle-1](assets/icons/base-line/MoreCircle-1.svg) | ![MoreCircle](assets/icons/base-line/MoreCircle.svg) | ![Mute](assets/icons/base-line/Mute.svg) | ![Notification](assets/icons/base-line/Notification.svg) | ![Package](assets/icons/base-line/Package.svg) | ![Picture](assets/icons/base-line/Picture.svg) |
| Mobile | More | MoreCircle-1 | MoreCircle | Mute | Notification | Package | Picture |
| ![PlayCircle](assets/icons/base-line/PlayCircle.svg) | ![PoliceTerm](assets/icons/base-line/PoliceTerm.svg) | ![Profile](assets/icons/base-line/Profile.svg) | ![QR](assets/icons/base-line/QR.svg) | ![Quantity](assets/icons/base-line/Quantity.svg) | ![QuestionCircle](assets/icons/base-line/QuestionCircle.svg) | ![Record](assets/icons/base-line/Record.svg) | ![Recovery](assets/icons/base-line/Recovery.svg) |
| PlayCircle | PoliceTerm | Profile | QR | Quantity | QuestionCircle | Record | Recovery |
| ![Reffer](assets/icons/base-line/Reffer.svg) | ![Refresh-circle](assets/icons/base-line/Refresh-circle.svg) | ![Reminder](assets/icons/base-line/Reminder.svg) | ![Right](assets/icons/base-line/Right.svg) | ![RightCircle](assets/icons/base-line/RightCircle.svg) | ![RightLine](assets/icons/base-line/RightLine.svg) | ![Rotate](assets/icons/base-line/Rotate.svg) | ![Ruler](assets/icons/base-line/Ruler.svg) |
| Reffer | Refresh-circle | Reminder | Right | RightCircle | RightLine | Rotate | Ruler |
| ![Save](assets/icons/base-line/Save.svg) | ![Scan](assets/icons/base-line/Scan.svg) | ![Scan_QR](assets/icons/base-line/Scan_QR.svg) | ![Search](assets/icons/base-line/Search.svg) | ![Send](assets/icons/base-line/Send.svg) | ![Setting](assets/icons/base-line/Setting.svg) | ![Share-1](assets/icons/base-line/Share-1.svg) | ![Share](assets/icons/base-line/Share.svg) |
| Save | Scan | Scan_QR | Search | Send | Setting | Share-1 | Share |
| ![Shield](assets/icons/base-line/Shield.svg) | ![SignIn](assets/icons/base-line/SignIn.svg) | ![SignOut](assets/icons/base-line/SignOut.svg) | ![Sliders](assets/icons/base-line/Sliders.svg) | ![Sound](assets/icons/base-line/Sound.svg) | ![Star](assets/icons/base-line/Star.svg) | ![Tag](assets/icons/base-line/Tag.svg) | ![Theme](assets/icons/base-line/Theme.svg) |
| Shield | SignIn | SignOut | Sliders | Sound | Star | Tag | Theme |
| ![Ticket](assets/icons/base-line/Ticket.svg) | ![Timer](assets/icons/base-line/Timer.svg) | ![Types](assets/icons/base-line/Types.svg) | ![Unlock-1](assets/icons/base-line/Unlock-1.svg) | ![Unlock](assets/icons/base-line/Unlock.svg) | ![Up](assets/icons/base-line/Up.svg) | ![UpCircle](assets/icons/base-line/UpCircle.svg) | ![UpFill](assets/icons/base-line/UpFill.svg) |
| Ticket | Timer | Types | Unlock-1 | Unlock | Up | UpCircle | UpFill |
| ![UpLine](assets/icons/base-line/UpLine.svg) | ![User-1](assets/icons/base-line/User-1.svg) | ![User-2](assets/icons/base-line/User-2.svg) | ![User](assets/icons/base-line/User.svg) | ![UserAdd](assets/icons/base-line/UserAdd.svg) | ![UserSwitch](assets/icons/base-line/UserSwitch.svg) | ![Video-slash](assets/icons/base-line/Video-slash.svg) | ![Video](assets/icons/base-line/Video.svg) |
| UpLine | User-1 | User-2 | User | UserAdd | UserSwitch | Video-slash | Video |
| ![Zoom_In](assets/icons/base-line/Zoom_In.svg) | ![Zoom_Out](assets/icons/base-line/Zoom_Out.svg) | ![data-1](assets/icons/base-line/data-1.svg) | ![data](assets/icons/base-line/data.svg) | ![list](assets/icons/base-line/list.svg) | ![minimizeCircle-1](assets/icons/base-line/minimizeCircle-1.svg) | ![minimizeCircle](assets/icons/base-line/minimizeCircle.svg) | ![note](assets/icons/base-line/note.svg) |
| Zoom_In | Zoom_Out | data-1 | data | list | minimizeCircle-1 | minimizeCircle | note |
| ![receipt](assets/icons/base-line/receipt.svg) | ![wallet-3](assets/icons/base-line/wallet-3.svg) | | | | | | |
| receipt | wallet-3 | | | | | | |

### 4.2 Icon-Menu（菜单图标）
用于菜单/导航的彩色图标，共 7 个：

| | | | | | |
|---|---|---|---|---|---|
| ![DashboardAllData](assets/icons/menu/DashboardAllData.svg) | ![dashboardMyProfile](assets/icons/menu/dashboardMyProfile.svg) | ![dashboardMyRewards](assets/icons/menu/dashboardMyRewards.svg) | ![dataContribution](assets/icons/menu/dataContribution.svg) | ![dataNetworkTiers](assets/icons/menu/dataNetworkTiers.svg) | ![myConnections](assets/icons/menu/myConnections.svg) |
| DashboardAllData | dashboardMyProfile | dashboardMyRewards | dataContribution | dataNetworkTiers | myConnections |
| ![myRewards](assets/icons/menu/myRewards.svg) | | | | | |
| myRewards | | | | | |

### 4.3 Icon-Tasks（任务图标）
任务相关图标，共 10 个：

| | | | | | |
|---|---|---|---|---|---|
| ![AI_Robot_Chat](assets/icons/tasks/AI_Robot_Chat.svg) | ![Branded_Surveys](assets/icons/tasks/Branded_Surveys.svg) | ![HITL_Validation](assets/icons/tasks/HITL_Validation.svg) | ![KYC](assets/icons/tasks/KYC.svg) | ![MBTI](assets/icons/tasks/MBTI.svg) | ![Profile_Surveys](assets/icons/tasks/Profile_Surveys.svg) |
| AI_Robot_Chat | Branded_Surveys | HITL_Validation | KYC | MBTI | Profile_Surveys |
| ![Trivia](assets/icons/tasks/Trivia.svg) | ![Video_Quiz](assets/icons/tasks/Video_Quiz.svg) | ![Wheel](assets/icons/tasks/Wheel.svg) | ![Worded](assets/icons/tasks/Worded.svg) | | |
| Trivia | Video_Quiz | Wheel | Worded | | |

### 4.4 Icons-Assets（资产图标）
资产/资源相关的彩色图标，共 3 个：

| | | | | | |
|---|---|---|---|---|---|
| ![Credit](assets/icons/assets-icons/Credit.svg) | ![PTC](assets/icons/assets-icons/PTC.svg) | ![PTC_Credit](assets/icons/assets-icons/PTC_Credit.svg) | | | |
| Credit | PTC | PTC_Credit | | | |

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

