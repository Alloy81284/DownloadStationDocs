# 学习版安装MOD

## 在启动器中上传MOD

1. 打开P社启动器，新建MOD文件夹。

![新建MOD文件夹](https://img.alloy.eu.org/1751550896-fad4f7ab2af0f1f5-530b3415-cf6a-430c-a494-5b962062dd79.png)

2. 将MOD文件放入该文件夹。

![放入MOD文件](https://img.alloy.eu.org/1751550918-c8472d386c2e5987-17442a95-b4ea-4706-aab2-c7a1d493da53.png)

## MOD出现感叹号怎么办?

- **黄色感叹号**：通常可忽略，若无法使用请联系支持。
- **红色感叹号**：MOD与游戏版本不匹配，需更换MOD或游戏版本。

## 安装步骤后MOD不生效怎么办？

1. 先找到你创建MOD的目录，然后返回上一级，来到有很多.mod文件的地方，如下图所示。找到你新建MOD（你起什么名它就是什么名字）的文件名的.mod文件，以CPF_TEST为例。

![找到.mod文件](https://img.alloy.eu.org/1751550930-e99dfcef521c32ba-aed4839c-95d3-4fdb-bf69-40534f6b589d.png)

2. 复制MOD文件路径。

3. 回到MOD文件夹里面，以记事本打开descriptor.mod文件

![打开descriptor.mod文件](https://img.alloy.eu.org/1751550945-848b8e77fceb88b3-c3c20352-594f-4cff-8e93-00fccf73a292.png)

4. 把你刚才复制的path=XXXX，也就是文件路径粘贴进去。

![修改路径](https://img.alloy.eu.org/1751551070-327776c50f955213-c9a38807-d5f2-4181-acc7-5b37b5b4ed84.png)

---

## 常见MOD安装问题

### MOD无法启用

**可能原因：**
- 路径设置错误
- 文件权限问题
- MOD版本不兼容

**解决方案：**
1. 检查descriptor.mod文件中的路径是否正确
2. 确保MOD文件夹有读写权限
3. 验证MOD是否支持当前游戏版本

### MOD冲突

**症状：**
- 游戏崩溃
- 功能异常
- 界面显示错误

**解决方案：**
1. 逐个禁用MOD来定位冲突源
2. 查看MOD说明了解兼容性
3. 使用MOD管理工具检查冲突

### 性能问题

**症状：**
- 游戏运行缓慢
- 内存占用过高
- 频繁卡顿

**解决方案：**
1. 减少同时启用的MOD数量
2. 关闭不必要的MOD功能
3. 升级硬件配置

## 相关链接

- [快速开始指南](../getting-started/quick-start.md)
- [其他常见问题](../troubleshooting/)
