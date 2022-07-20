# Vita3K使用教程
※注意：首次使用Vita3K前，检查配置情况以及是否安装运行库，请不要放在带有中文文件夹里，否则打开Vita3K会闪退。

## 打开Vita3K，初次为Vita3K进行初始设置
1. 选择语言，选择完成后点Next继续。
2. 选择存放路径（即模拟PSVita的文件路径），修改或不修改路径都可以点击Next继续。
3. 点击下载[系统固件](http://dus01.psv.update.playstation.net/update/psv/image/2022_0209/rel_f2c7b12fe85496ec88a0391b514d6e3b/PSVUPDAT.PUP)和[字体固件](http://dus01.psp2.update.playstation.net/update/psp2/image/2019_0924/sd_8b5f60b56c3da8365b973dba570c53a5/PSP2UPDAT.PUP)选项，并选择下面的Install Firmware，选择PUP格式来安装系统固件，两个固件都已安装且显示 V 就可以点Next继续；不安装固件也不影响使用，部分应用程序需要模块才能正常运行，但建议还是安装系统固件。
4. 设置Vita3K基本设置，例如显示样式、信息栏设置，设置后可以点Next继续。
5. 初始设置完成，点击OK就开始使用Vita3K吧。
6. 创建用户，创建完用户后点击你刚才创建的用户图标继续操作。
7. 进入到锁屏界面再次点击任何地方进入到Vita3K的Livearea主页面，选择顶部选项栏的配置->设置选项，点击GUI勾选Asia Region选项，重启Vita3K模拟器以显示正常文字。

## 系统固件安装流程（若已安装可跳过此步骤）
- 在Vita3K模拟器安装任意版本的系统固件都不会因为系统版本而受到限制。

1. 打开Vita3K；
2. 点击顶部选项栏的文件选项；
3. 选择安装系统固件选项；
4. 选择PUP文件；
5. 安装完固件后可以继续选择安装字体固件，或者确认即可。

## 字体固件安装流程（若已安装可跳过此步骤）
1. 打开Vita3K；
2. 点击顶部选项栏的文件选项；
3. 选择安装系统固件选项；
4. 选择PUP文件；
5. 安装完固件后点击顶部选项栏配置选项；
6. 点击设置选项；
7. 点击GUI选项；
8. 勾选Asia Region选项后重启模拟器即可。

## 设置完成Vita3K相关教程
此流程安装完就可以进行安装游戏、DLC和主题，可以按F11显示全屏。
- [应用程序安装](http://croden1999.github.io/Vita3K-quick-guide/README_APP)
- [更新补丁安装](http://croden1999.github.io/Vita3K-quick-guide/README_PATCH)
- [追加内容安装](http://croden1999.github.io/Vita3K-quick-guide/README_ADDCONT)
- [主题安装](http://croden1999.github.io/Vita3K-quick-guide/README_THEME)

## Vita3K更换语言
在Vita3K的Livearea主页面中选择 【NPXS10015】 设定 应用程序，选择Language语言->System Language系统语言来切换语言。
- Chinese - Simplified 简体中文
- Chinese - Traditional 繁体中文

![](https://user-images.githubusercontent.com/61804715/131735493-7b80ae2e-dfe0-4d83-bcc8-454fb5d0873d.png)


## Vita3K界面介绍
用户管理：
- 新建、编辑、删除用户、名称、头像更换的操作

### Livearea主页面选项
筛选，通过筛选显示的应用程序：
- 所有
- 按地区：美版、欧版、日版、亚版
- 按类型：商业、自制
1. 列表模式（未勾选Grid Mode）：
- 标题ID：以应用程序的标题ID排序
- 版本：以应用程序的版本排序
- 类别（gd：游戏数据、gp：游戏补丁、gda：系统应用）：以应用程序的类别排序
- 最近游玩时间：以应用程序的最近游玩时间排序
- 标题：以应用程序的标题名称排序
- 刷新：刷新应用程序图标
2. 网格模式（勾选Grid Mode）：
- 应用程序排序按：版本/类别/最近游玩时间/标题/标题ID
- 刷新：刷新应用程序图标

应用程序右键选项：
- 运行
- 查看应用程序兼容性
- 复制应用程序信息
- 自定义配置
- 打开文件夹（应用程序、追加内容、许可证、保存数据、着色器缓存、着色器日志）
- 删除（应用程序、追加内容、许可证、保存数据、着色器缓存、着色器日志）
- [此选项仅在取消勾选Live Area应用屏幕选项显示]Live Area（Live Area、搜索、说明书、更新）
- 更新历史记录
- 信息

菜单栏选项：
- 文件：打开存放路径、安装固件/pkg/zip/vpk/许可证
- 模拟：最近使用的应用程序
- Debug（调试）
- 配置：设置、用户管理
- 控制：键盘控制、控制器
- 帮助：关于、Vita3K更新、欢迎

## 配置设置选项介绍
Core 核心：
- Modules Mode（模块模式）：自动选择、自动手动并用或者手动选择模块
- Modules List（模块列表）：Automatic（自动选择）、Auto&Manual（自动&手动并用，也可以手动选择模块）和Manual（手动选择）

CPU 处理器:
- CPU后端：Dynarmic或者Unicorn（已弃用），仅Dynarmic的CPU后端才能启用JIT选项

GPU 显卡：
- 提升分辨率（1x - 8x），选择Reset(重设)会回调到1x（即960x544）分辨率
- 关闭表面同步
- 开启FXAA抗锯齿
- 垂直同步
- 各向异性过滤（1x - 16x），选择重设会回调到1x
- 使用着色器缓存
- 使用Spir-V着色器（已弃用）（不是所有显卡都有这个选项，取决于显卡的支持）
- 清除着色器缓存和着色器日志（如果是自定义配置设置单个游戏就只会清除当前游戏的着色器缓存和日志）

System 系统：
- 切换O / X键为确认键
- 模拟PSVTV / PSTV模式

Emulator 模拟器：
- 运行应用程序时全屏
- 禁用ngs支持
- 日志等级
- 归档日志
- 不和谐丰富的存在
- 性能叠加（显示FPS帧数、平均以及最高帧、帧数线性流动图、调整显示位置）
- 纹理缓存
- 模拟器系统存储文件夹路径（即模拟PSVita分区的路径）

GUI 界面：
- 界面可见：运行应用程序中显示菜单栏
- 显示应用程序的Livearea界面：显示应用程序背景图片、图标、说明书的界面，取消勾选该选项运行应用程序会直接运行
- 网格模式：应用程序图标由列表变为网格显示
- 字体支持：亚洲地区（启用能显示正常文字）
- 主题&背景：还原默认主题、使用主题背景、背景透明度、延时背景切换、延时锁屏的操作

Debug 调试（非开发人员建议忽略此项）：
- 日志导入
- 日志导出
- 着色器日志
- 统一日志
- 保存表面颜色
- 提取纹理
- 提取elfs
- 浏览代码
- 浏览内存
- 浏览导入调用

## 控制
- 键盘控制：可以通过自定义映射按键来达到您舒适的感觉。
- 控制器：连接手柄控制器就可以直接使用，无需按键映射。