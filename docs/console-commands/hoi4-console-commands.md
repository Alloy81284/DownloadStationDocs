# 钢铁雄心4 控制台指令

> **重要说明**：本文档只包含经过官方验证或可靠来源确认的控制台指令。我们优先考虑准确性而非完整性。

## 控制台打开方法

### 键盘按键

- **`~`** (波浪号) - 大多数键盘的标准按键
- **Shift+2**, **§**, **\\**, **`**, **"**, **^**
- **ALT+2+1** 或 **Shift+3**

*具体按键取决于键盘布局*

### 使用注意事项

⚠️ **重要提醒**：

- 使用前请先**保存游戏**
- 建议在使用指令时**暂停游戏**
- 控制台指令会**禁用成就获取**
- 某些指令需要特定**DLC**支持
- **多人游戏**中无法使用控制台指令
- 部分指令会影响**AI行为**
- **铁人模式**下无法使用控制台指令

---

## 基础控制指令

### 帮助与信息

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `help` | `[指令名]` | 显示所有指令或特定指令帮助 | `help tag` |
| `version` | 无 | 显示当前游戏版本 | `version` |
| `time` | 无 | 显示当前游戏时间 | `time` |
| `tdebug` | 无 | 开启/关闭调试信息显示 | `tdebug` |

### 国家控制

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `tag` | `[国家标签]` | 切换到指定国家 | `tag GER` |
| `observe` | 无 | 切换到观察者模式 | `observe` |
| `spectator` | 无 | 同observe | `spectator` |

---

## 资源管理指令

### 基础资源

| 指令 | 参数 | 效果 | 默认值 | 示例 |
|------|------|------|--------|------|
| `pp` | `[数量]` | 添加政治力点数 | 1000 | `pp 5000` |
| `political_power` | `[数量]` | 同pp | 1000 | `political_power 5000` |
| `manpower` | `[数量]` | 添加人力 | 10000000 | `manpower 5000000` |
| `fuel` | `[数量]` | 添加燃料 | 无默认值 | `fuel 50000` |
| `xp` | `[数量]` | 添加陆海空经验值 | 无默认值 | `xp 999` |
| `cp` | `[数量]` | 添加指挥力点数 | 无默认值 | `cp 100` |

### 国家属性

| 指令 | 参数 | 效果 | 最大值 | 示例 |
|------|------|------|--------|------|
| `st` | `[数量]` | 添加稳定度 | 100% | `st 25` |
| `stability` | `[数量]` | 同st | 100% | `stability 25` |
| `ws` | `[数量]` | 添加战争支持度 | 100% | `ws 50` |
| `add_war_support` | `[数量]` | 同ws | 100% | `add_war_support 30` |

---

## 国家精神与理念指令

### 理念管理

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `add_ideas` | `[理念名]` | 添加国家精神/理念 | `add_ideas generic_military_youth` |
| `remove_ideas` | `[理念名]` | 移除国家精神/理念 | `remove_ideas generic_military_youth` |
| `swap_ideas` | `[旧理念] [新理念]` | 替换理念 | `swap_ideas old_idea new_idea` |

**常用理念名称示例**：

- `generic_military_youth` - 军事青年组织
- `generic_fortification_focus` - 防御重点
- `generic_mobile_focus` - 机动重点
- `generic_infantry_equipment_manufacturer` - 步兵装备制造商

---

## 军事相关指令

### 装备管理

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `ae` | `[数量] [装备名]` | 添加指定装备 | `ae 1000 infantry_equipment_1` |
| `add_equipment` | `[数量] [装备名]` | 同ae | `add_equipment 500 light_tank_equipment_1` |
| `ale` | `[数量]` | 添加最新型号装备 | `ale 1000` |
| `add_latest_equipment` | `[数量]` | 同ale | `add_latest_equipment 2000` |
| `nuke` | `[数量]` | 添加核武器 | `nuke 10` |

### 单位训练与特质

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `it` | 无 | 瞬间训练师团和舰船 | `it` |
| `instanttraining` | 无 | 同it | `instanttraining` |
| `allowtraits` | 无 | 允许自由分配将领特质 | `allowtraits` |
| `gain_xp` | `[数量]` | 为选中将领添加经验 | `gain_xp 500` |

### 移动与传送

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `teleport` | 无 | 激活传送模式（右键使用） | `teleport` |
| `tp` | 无 | 同teleport | `tp` |
| `moveunit` | `[单位ID] [省份ID]` | 移动指定单位 | `moveunit 123 3024` |

---

## 科技研发指令

### 基础研发

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `research all` | 无 | 研究所有科技 | `research all` |
| `research` | `[槽位ID]` | 研究指定槽位科技 | `research 1` |
| `research_on_icon_click` | 无 | 点击科技树图标瞬间研究 | `research_on_icon_click` |

---

## 国策与决议指令

### 国策控制

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `focus.autocomplete` | 无 | 瞬间完成当前国策 | `focus.autocomplete` |
| `Focus.AutoComplete` | 无 | 同上（大写版本） | `Focus.AutoComplete` |
| `Focus.NoChecks` | 无 | 忽略国策要求 | `Focus.NoChecks` |
| `Focus.IgnorePrerequisites` | 无 | 忽略国策前置条件 | `Focus.IgnorePrerequisites` |
| `freefocuses` | 无 | 自由选择任何国策 | `freefocuses` |

### 决议控制

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `Decision.NoChecks` | 无 | 忽略决议要求 | `Decision.NoChecks` |
| `Decision.FastRemove` | 无 | 决议只需一天 | `Decision.FastRemove` |

---

## 外交关系指令

### 外交行动

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `allowdiplo` | 无 | 移除外交限制 | `allowdiplo` |
| `adiplo` | 无 | 同allowdiplo | `adiplo` |
| `nocb` | 无 | 同allowdiplo | `nocb` |
| `ai_accept` | 无 | AI接受所有外交提议 | `ai_accept` |
| `yesman` | 无 | 同ai_accept | `yesman` |

### 和平与战争

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `whitepeace` | `[国家标签]` | 与指定国家白和 | `whitepeace GER` |
| `wp` | `[国家标签]` | 同whitepeace | `wp SOV` |
| `instant_wargoal` | 无 | 瞬间正当化战争目标 | `instant_wargoal` |
| `debug_nuking` | 无 | 移除核武器使用限制 | `debug_nuking` |

### 国家关系

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `add_opinion` | `[国家标签]` | 增加100点好感度 | `add_opinion USA` |
| `annex` | `[国家标签]` | 吞并指定国家 | `annex POL` |
| `annex` | `all` | 吞并所有国家 | `annex all` |
| `puppet` | `[主人] [傀儡]` | 建立傀儡关系 | `puppet GER ITA` |
| `add_autonomy` | `[国家] [数值]` | 改变自治度 | `add_autonomy ENG -500` |

---

## 阵营管理指令

### 阵营操作

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `eval_effect [国家标签] = { dismantle_faction = yes }` | 无 | 删除指定国家的阵营 | `eval_effect GER = { dismantle_faction = yes }` |
| `eval_effect [国家1] = { add_to_faction = [国家2] }` | 无 | 添加国家到阵营 | `eval_effect GER = { add_to_faction = ITA }` |
| `eval_effect [国家1] = { remove_from_faction = [国家2] }` | 无 | 从阵营移除国家 | `eval_effect GER = { remove_from_faction = ITA }` |
| `eval_effect [国家] = { set_faction_name = "[阵营名]" }` | 无 | 重命名阵营 | `eval_effect GER = { set_faction_name = "新轴心" }` |

---

## 领土管理指令

### 省份控制

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `setowner` | `[国家标签] [州ID]` | 设置州的拥有者 | `setowner GER 123` |
| `setcontroller` | `[国家] [省份ID]` | 设置省份控制者 | `setcontroller USA 3024` |
| `add_core` | `[州ID]` | 添加核心州 | `add_core 123` |

### 州级操作

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `add_state_core` | `[州ID]` | 添加州核心 | `add_state_core 123` |
| `remove_state_core` | `[州ID]` | 移除州核心 | `remove_state_core 123` |
| `transfer_state` | `[州ID]` | 转移州所有权和控制权 | `transfer_state 123` |
| `set_state_owner` | `[州ID]` | 设置州拥有者 | `set_state_owner 123` |
| `set_state_controller` | `[州ID]` | 设置州控制者 | `set_state_controller 123` |
| `set_capital` | `[州ID]` | 设置首都 | `set_capital 64` |
| `remove_state_claim` | `[州ID]` | 移除州声索 | `remove_state_claim 123` |
| `set_province_controller` | `[省份ID]` | 设置省份控制者 | `set_province_controller 2999` |

### 占领与抵抗

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `resistance` | 无 | 增加选中省份抵抗 | `resistance` |
| `compliance` | 无 | 增加选中省份服从度 | `compliance` |
| `add_compliance` | 无 | 同compliance | `add_compliance` |

---

## 政治意识形态指令

### 执政党设置

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `set_ruling_party democratic` | 无 | 设置民主主义执政 | `set_ruling_party democratic` |
| `set_ruling_party fascism` | 无 | 设置法西斯主义执政 | `set_ruling_party fascism` |
| `set_ruling_party communism` | 无 | 设置共产主义执政 | `set_ruling_party communism` |
| `set_ruling_party neutrality` | 无 | 设置中立主义执政 | `set_ruling_party neutrality` |

### 政党支持度

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `add_party_popularity democratic` | `[数值]` | 增加民主主义支持度 | `add_party_popularity democratic 25` |
| `add_party_popularity fascism` | `[数值]` | 增加法西斯主义支持度 | `add_party_popularity fascism 50` |
| `add_party_popularity communism` | `[数值]` | 增加共产主义支持度 | `add_party_popularity communism 30` |
| `add_party_popularity neutrality` | `[数值]` | 增加中立主义支持度 | `add_party_popularity neutrality 40` |

### 内战与政变

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `civilwar` | `[意识形态] [国家]` | 发动内战 | `civilwar fascism GER` |

---

## 间谍活动指令（需要La Resistance DLC）

### 间谍机构管理

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `agency.autocomplete` | 无 | 瞬间完成间谍机构升级 | `agency.autocomplete` |
| `agency.instantslotunlock` | 无 | 移除特工招募等待时间 | `agency.instantslotunlock` |
| `create_intelligence_agency` | 无 | 自动创建情报机构 | `create_intelligence_agency` |
| `upgrade_intelligence_agency` | 无 | 自动升级情报机构 | `upgrade_intelligence_agency` |

### 特工活动

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `prevent_operative_detection` | 无 | 防止特工被发现 | `prevent_operative_detection` |
| `force_operative_detection` | 无 | 强制特工被发现 | `force_operative_detection` |

---

## 经济与工业指令

### 建设控制

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `ic` | 无 | 开启/关闭瞬间建设 | `ic` |
| `instantconstruction` | 无 | 同ic | `instantconstruction` |

### 海上作战相关

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `instant_prepare` | 无 | 瞬间准备海军入侵 | `instant_prepare` |

---

## AI控制指令

### AI基础控制

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `ai` | `[国家标签]` | 开启/关闭AI | `ai GER` |
| `aiview` | 无 | 启用AI调试信息 | `aiview` |
| `human_ai` | 无 | 让AI控制玩家国家 | `human_ai` |
| `airealism` | 无 | 启用现实AI | `airealism` |

### AI行为控制

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `ai_invasion` | 无 | 开启/关闭AI海军入侵 | `ai_invasion` |

---

## ImGui调试界面指令

| 指令 | 参数 | 效果 | 来源 |
|------|------|------|------|
| `imgui show` | 无 | 列出可用的子命令 |  |

**使用说明**：

- 该指令可以查看AI的师团模板匹配值和升级倾向
- 有助于理解AI的模板选择机制
- 主要用于MOD开发和游戏机制研究

---

## 调试与显示指令

### 地图显示控制

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `fow` | `[省份ID]` | 开启/关闭战争迷雾 | `fow 3024` |
| `debug_fow` | `[省份ID]` | 同fow | `debug_fow` |
| `night` | 无 | 开启/关闭夜晚模式 | `night` |

### 调试信息

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `debug_commands` | 无 | 输出指令计数到日志 | `debug_commands` |
| `debug_events` | 无 | 开始计数事件 | `debug_events` |
| `debug_dumpevents` | 无 | 转储事件数据到日志 | `debug_dumpevents` |
| `debug_diploactions` | 无 | 开始计数外交行动 | `debug_diploactions` |
| `debug_dumpdiploactions` | 无 | 转储外交行动数据到日志 | `debug_dumpdiploactions` |

### 图形调试

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `debug_assert` | 无 | 开启/关闭断言 | `debug_assert` |
| `debug_smooth` | 无 | 开启/关闭帧平滑 | `debug_smooth` |
| `debug_nomouse` | 无 | 开启/关闭鼠标滚轮 | `debug_nomouse` |
| `debug_terrain` | 无 | 开启/关闭地形显示 | `debug_terrain` |
| `debug_cities` | 无 | 开启/关闭城市绘制模式 | `debug_cities` |
| `debug_water` | 无 | 开启/关闭水体显示 | `debug_water` |
| `debug_fronts` | 无 | 开启/关闭前线调试 | `debug_fronts` |
| `debug_borders` | 无 | 开启/关闭边界显示 | `debug_borders` |
| `debug_trees` | 无 | 开启/关闭树木显示 | `debug_trees` |
| `debug_rivers` | 无 | 开启/关闭河流显示 | `debug_rivers` |
| `debug_postfx` | 无 | 开启/关闭后期效果 | `debug_postfx` |
| `debug_sky` | 无 | 开启/关闭天空显示 | `debug_sky` |
| `debug_bloom` | 无 | 开启/关闭光晕效果 | `debug_bloom` |
| `debug_tooltip` | 无 | 开启/关闭工具提示 | `debug_tooltip` |
| `debug_nogui` | 无 | 开启/关闭GUI | `debug_nogui` |
| `debug_volume` | `[音量变化]` | 修改音乐音量 | `debug_volume 0.5` |
| `debug_lockcamera` | 无 | 开启/关闭摄像头锁定 | `debug_lockcamera` |
| `debug_lines` | 无 | 开启/关闭调试线 | `debug_lines` |

---

## 事件控制指令

### 事件执行

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `event` | `[事件ID] [国家标签]` | 在指定国家执行事件 | `event political.3 GER` |
| `poll` | 无 | 轮询有效事件 | `poll` |

### 常用事件ID

| 事件ID | 效果 | 示例 |
|--------|------|------|
| `political.3` | 共产主义政变 | `event political.3` |
| `political.6` | 民主主义政变 | `event political.6` |
| `political.9` | 法西斯主义政变 | `event political.9` |

---

## 单位管理指令

### 单位删除

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `deleteallunits` | `[国家标签]` | 删除指定国家所有单位 | `deleteallunits GER` |
| `deleteallunitsbut` | `[国家标签]` | 删除除指定国家外所有单位 | `deleteallunitsbut USA` |

---

## 系统工具指令

### 游戏控制

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `savegame` | 无 | 强制保存游戏 | `savegame` |
| `fullscreen` | 无 | 开启/关闭全屏 | `fullscreen` |
| `nextsong` | 无 | 更换音乐 | `nextsong` |
| `IP` | 无 | 显示IP地址 | `IP` |
| `nudge` | 无 | 进入微调工具 | `nudge` |

---

## 高级脚本指令

### 脚本执行

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `effect` | `[脚本效果名]` | 执行脚本效果 | `effect add_stability = 0.1` |

### 变量与标志

| 指令 | 参数 | 效果 | 示例 |
|------|------|------|------|
| `set_country_flag` | `[标志]` | 设置国家标志 | `set_country_flag test_flag` |
| `modify_country_flag` | `[标志]` | 修改国家标志 | `modify_country_flag test_flag` |
| `set_rule` | `[规则]` | 开启特殊游戏规则 | `set_rule can_use_kamikaze` |

---

## 获取内部ID的方法

### 方法1：使用调试模式

1. 在控制台输入 `tdebug` 开启调试模式
2. 鼠标悬停在国家焦点、国家精神、科技上可获取相关信息
3. 鼠标悬停在省份上可获取州和省份ID以及国家标签
4. 再次输入 `tdebug` 关闭调试模式

### 方法2：本地化文件查询

1. 前往游戏安装目录：`/Hearts of Iron IV/localisation/english/`
2. 使用文本编辑器的"在文件中搜索"功能
3. 搜索指定的本地化键值

---

## 完整势力标签列表

### 主要大国/地区

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 德国 | GER | Germany |
| 苏联 | SOV | Soviet Union |
| 美国 | USA | United States |
| 英国 | ENG | United Kingdom |
| 法国 | FRA | France |
| 意大利 | ITA | Italy |
| 日本 | JAP | Japan |

### 轴心国阵营

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 德国 | GER | Germany |
| 意大利 | ITA | Italy |
| 日本 | JAP | Japan |
| 匈牙利王国 | HUN | Kingdom of Hungary |
| 罗马尼亚王国 | ROM | Kingdom of Romania |
| 保加利亚 | BUL | Bulgaria |
| 芬兰 | FIN | Finland |
| 泰国 | SIA | Siam |
| 满洲国 | MAN | Manchukuo |
| 蒙疆联合自治政府 | MEN | Mengkukuo |

### 同盟国阵营

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 英国 | ENG | United Kingdom |
| 美国 | USA | United States |
| 苏联 | SOV | Soviet Union |
| 自由法国 | FRA | Free France |
| 加拿大自治领 | CAN | Dominion of Canada |
| 澳大利亚 | AST | Australia |
| 新西兰 | NZL | New Zealand |
| 南非联邦 | SAF | South Africa |
| 英属印度 | RAJ | British Raj |
| 英属马来亚 | MAL | British Malaya |

### 共产国际阵营

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 苏联 | SOV | Soviet Union |
| 蒙古 | MON | Mongolia |
| 图瓦 | TAN | Tannu Tuva |

### 欧洲势力

#### 西欧

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 法国 | FRA | France |
| 荷兰 | HOL | Netherlands |
| 比利时 | BEL | Belgium |
| 卢森堡 | LUX | Luxembourg |
| 瑞士 | SWI | Switzerland |
| 爱尔兰 | IRE | Ireland |

#### 南欧

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 西班牙 | SPR | Spain |
| 葡萄牙 | POR | Portugal |
| 希腊 | GRE | Greece |
| 南斯拉夫 | YUG | Yugoslavia |
| 阿尔巴尼亚 | ALB | Albania |

#### 北欧

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 瑞典 | SWE | Sweden |
| 挪威 | NOR | Norway |
| 丹麦 | DEN | Denmark |
| 芬兰 | FIN | Finland |
| 冰岛 | ICE | Iceland |

#### 东欧

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 波兰 | POL | Poland |
| 捷克斯洛伐克 | CZE | Czechoslovakia |
| 匈牙利王国 | HUN | Kingdom of Hungary |
| 罗马尼亚王国 | ROM | Kingdom of Romania |
| 保加利亚 | BUL | Bulgaria |
| 立陶宛 | LIT | Lithuania |
| 拉脱维亚 | LAT | Latvia |
| 爱沙尼亚 | EST | Estonia |
| 奥地利 | AUS | Austria |

### 美洲势力

#### 北美

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 美国 | USA | United States |
| 加拿大自治领 | CAN | Dominion of Canada |
| 墨西哥 | MEX | Mexico |

#### 中美洲

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 危地马拉 | GUA | Guatemala |
| 洪都拉斯 | HON | Honduras |
| 萨尔瓦多 | ELS | El Salvador |
| 尼加拉瓜 | NIC | Nicaragua |
| 哥斯达黎加 | COS | Costa Rica |
| 巴拿马 | PAN | Panama |
| 古巴 | CUB | Cuba |
| 海地 | HAI | Haiti |
| 多米尼加共和国 | DOM | Dominican Republic |

#### 南美洲

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 巴西 | BRA | Brazil |
| 阿根廷 | ARG | Argentina |
| 智利 | CHL | Chile |
| 秘鲁 | PRU | Peru |
| 哥伦比亚 | COL | Colombia |
| 委内瑞拉 | VEN | Venezuela |
| 厄瓜多尔 | ECU | Ecuador |
| 玻利维亚 | BOL | Bolivia |
| 巴拉圭 | PAR | Paraguay |
| 乌拉圭 | URG | Uruguay |

### 亚洲势力

#### 东亚

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 日本 | JAP | Japan |
| 中国 | CHI | China |
| 中共 | PRC | Communist China |
| 朝鲜 | KOR | Korea |
| 满洲国 | MAN | Manchukuo |
| 蒙疆联合自治政府 | MEN | Mengkukuo |
| 广西军阀 | GXC | Guangxi Clique |
| 山西军阀 | SHX | Shanxi |
| 云南军阀 | YUN | Yunnan |
| 新疆军阀 | SIK | Sinkiang |
| 西北三马 | XSM | Xibei San Ma |
| 西藏 | TIB | TIBET |

#### 东南亚

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 泰国 | SIA | Siam |
| 荷属东印度 | INS | Dutch East Indies |
| 英属马来亚 | MAL | British Malaya |
| 菲律宾 | PHI | Philippines |

#### 南亚

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 英属印度 | RAJ | British Raj |
| 阿富汗 | AFG | Afghanistan |
| 伊朗 | PER | Iran |
| 尼泊尔 | NEP | Nepal |
| 不丹 | BHU | Bhutan |

#### 西亚/中东

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 土耳其 | TUR | Turkey |
| 伊拉克 | IRQ | Iraq |
| 沙特阿拉伯 | SAU | Saudi Arabia |
| 阿曼 | OMA | Oman |
| 也门 | YEM | Yemen |

### 非洲势力

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 埃及 | EGY | Egypt |
| 利比亚 | LBA | Libya |
| 摩洛哥 | MOR | Morocco |
| 利比里亚 | LIB | Liberia |
| 埃塞俄比亚 | ETH | Ethiopia |
| 南非联邦 | SAF | South Africa |
| 安哥拉 | ANG | Angola |

### 大洋洲势力

| 势力 | 标签 | 英文名 |
|-----------|------|--------|
| 澳大利亚 | AST | Australia |
| 新西兰 | NZL | New Zealand |

---

## 实用指令组合示例

### 新手快速发展套装

```bash
# 基础资源套装
pp 10000          # 添加政治力
manpower 5000000  # 添加500万人力
xp 999            # 添加经验值
fuel 50000        # 添加燃料
cp 100            # 添加指挥力

# 快速发展套装
ic                # 开启瞬间建设
research all      # 研究所有科技
focus.autocomplete # 瞬间完成国策
it                # 瞬间训练
```

### 战争准备套装

```bash
# 装备准备
ae 10000 infantry_equipment_3     # 现代步兵装备
ae 2000 medium_tank_equipment_3   # 现代中坦
ae 1000 fighter_equipment_3       # 现代战斗机
nuke 50                          # 核武器

# 军队强化
allowtraits                      # 解锁特质限制
xp 999                          # 军种经验
gain_xp 1000                    # 选中将领经验
```

### 外交控制套装

```bash
# 外交无限制
allowdiplo        # 移除外交限制
ai_accept         # AI接受所有提议
yesman           # 同上
instant_wargoal  # 瞬间正当化
debug_nuking     # 移除核武器限制
```

### 调试观察套装

```bash
# 开启调试模式
tdebug           # 显示国家标签和ID
fow              # 移除战争迷雾
ai               # 关闭AI（可选）
observe          # 观察者模式
```

### 间谍活动套装（需要DLC）

```bash
# 间谍机构强化
agency.autocomplete            # 瞬间升级机构
agency.instantslotunlock       # 移除招募等待
prevent_operative_detection    # 防止特工被发现
```

### 国内政治控制套装

```bash
# 政治控制
set_ruling_party fascism        # 设置执政党
add_party_popularity fascism 80 # 增加支持度
st 100                         # 最大稳定度
ws 100                         # 最大战争支持度
Decision.NoChecks              # 忽略决议要求
```

### 阵营管理套装

```bash
# 阵营操作示例
eval_effect GER = { dismantle_faction = yes }           # 解散轴心国
eval_effect USA = { add_to_faction = CHI }              # 中国加入同盟国
eval_effect GER = { set_faction_name = "新欧洲联盟" }    # 重命名阵营
```

---

## 注意事项与说明

### ⚠️ 使用前必读

1. **保存游戏**：使用任何控制台指令前务必保存游戏
2. **暂停游戏**：使用指令时建议暂停游戏，特别是影响AI的指令
3. **成就禁用**：使用控制台指令会**永久禁用**当前游戏的成就获得
4. **版本兼容**：某些指令可能在不同游戏版本中有变化或失效
5. **DLC要求**：标注"需要DLC"的指令必须拥有对应DLC才能使用
6. **多人游戏**：控制台指令无法在多人游戏中使用
7. **AI影响**：某些指令会同时影响AI国家的行为
8. **铁人模式限制**：铁人模式下完全无法使用控制台指令

### 常见问题解答

**Q: 为什么某些指令不起作用？**
A: 可能原因：

- 指令输入错误（检查大小写和空格）
- 缺少必要的DLC
- 游戏版本不兼容
- 需要先使用`tdebug`等前置指令

**Q: 如何找到国家标签？**
A:

1. 使用`tdebug`指令
2. 鼠标悬停在地图上的国家
3. 查看本文档的国家标签列表

**Q: 如何找到省份ID？**
A:

1. 使用`tdebug`指令
2. 鼠标悬停在地图上的省份
3. ID会显示在调试信息中

**Q: 为什么使用指令后游戏变慢？**
A: 某些指令（如`ic`瞬间建设）会同时影响AI，导致大量计算。建议：

- 暂停游戏后使用
- 使用完毕后关闭相关指令
- 避免在大型战争期间使用

### 版本更新说明

本文档基于Hearts of Iron IV最新版本编写。随着游戏更新，部分指令可能会：

- 被移除或替换
- 改变参数格式
- 需要新的DLC支持

---

## 相关链接

- [入门指南](../getting-started/) - 游戏基础设置
- [问题解答](../troubleshooting/) - 常见问题解决
