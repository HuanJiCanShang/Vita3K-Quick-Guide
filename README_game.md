# 游戏安装教程
分为三种格式：
- PKG（加密）
- ZIP
- VPK（解密）= ZIP格式

# Mai VPK游戏的安装
分为两种加载方式：
- 加载方式0
- 加载方式5

mai游戏为加载方式0的安装流程：

分两种方式安装，推荐第1种安装方式，因为带补丁的游戏在Vita3K模拟器安装会放到ux0/patch里面。
- 打开Vita3K模拟器，在菜单栏点击文件—>打开存放路径选项，将vpk改zip解压放到ux0/app文件夹里，并将文件夹名字更改为游戏ID（如PCSX00000），再去Vita3K模拟器运行游戏。

- 直接拖到Vita3K模拟器图标安装，或者打开Vita3K模拟器，在菜单栏点击文件—>安装zip、vpk选项，点击Select File（选择），选择vpk文件，等待安装完成后需要在菜单栏文件打开存放路径文件夹，在ux0/patch文件夹找到该游戏移动到ux0/app，点击Refresh刷新应用显示游戏运行即可。

mai游戏为加载方式5的安装流程：

不能在Vita3K上直接安装的缺点是因为eboot是修改过的，只适用于实机，不能直接安装，直接安装会崩溃闪退，需要解压，或者使用MaiDumpTool来切换加载方式，并设置为加载方式0，之后重新启动Vita3K模拟器运行游戏即可。

切换原版eboot流程：
1. 在菜单栏点击文件—>打开存放路径选项；
2. 在ux0/app文件夹中，将游戏vpk改为zip解压到此目录，并将游戏文件夹名字改成游戏ID（如PCSX00000）；
3. 打开游戏文件夹，把在mai_moe/eboot_origin.bin原版eboot替换掉，并改名为eboot.bin；同时将dlc文件夹命名为同游戏ID文件夹，并移动ux0/addcont里，之后点击Refresh刷新显示应用程序，运行游戏即可。

# ZIP游戏的安装
相比pkg安装方式省略了需要输入密钥或者导入work.bin这一步，Vita3K会检测到nonpdrm zip里的sce_sys/package/work.bin文件后解压解密安装。nonpdrm zip不能直接解压到ux0/app里。

安装流程：
- 可以在nps下载游戏后打包zip，nonpdrm zip打包方式与vpk打包方式一致，之后拖入到Vita3K图标安装，或者打开Vita3K模拟器，在菜单栏点击文件—>安装zip、vpk选项，点击Select File（选择），选择zip文件，等待安装完成后运行即可。

# PKG游戏的安装
打开Vita3K模拟器，在菜单栏点击文件—>安装pkg选项，选择pkg文件，输入zrif密钥或者导入work.bin文件，等待安装完成后运行即可。