#Everett Github：https://everetthuang.github.io
#swaywm README：https://everetthuang.github.io/Depository/Config/sway/README.md
#swaywm  配置地址：https://everetthuang.github.io/Depository/Config/sway/config
#i3status配置地址：https://everetthuang.github.io/Depository/Config/sway/i3status.conf

# ===================================================
#Everett
# ==========该配置快捷键说明==========
# =====Mod+=====
# Mod+  Return      : 打开终端（该配置终端为sakura）
# Mod+  d           : 打开程序菜单（该配置程序菜单为dmenu）
# Mod+  number      : 切换到数字对应的工作区
# Mod+  h,j,k,l     : 移动焦点到(左h)(下j)(上k)(右l)窗口
# Mod+  g,c,v,s     : 打开(g:chromex)(c:vscode)(c:vlc)(s:spotify)程序,可自行设置
# Mod+  right,down  : 下一个打开窗口相对于当前焦点窗口打开的位置(right:右;down:下)
# Mod+  -           : 显示暂存器中的窗口 
# =====Mod+Shift+=====
# Mod+Shift+ q      : 退出当前窗口
# Mod+Shift+ f      : 将当前窗口更改为浮动模式
# Mod+Shift+ space  : 将当前窗口更改为全屏
# Mod+Shift+ h,j,k,l: 将当前窗口移动到左h下j右k上l位置
# Mod+Shift+ number : 将当前窗口移动到对应数字工作区
# Mod+Shift+ -      : 将当前窗口移动到暂存器
# =====Mod+Ctrl+=====
# Mod+Ctrl+  e      : 退出sway窗口管理器
# Mod+Ctrl+  r      : 重启系统
# Mod+Ctrl+  p      : 关机
# Mod+Ctrl+  l      : 锁屏
# Mod+Ctrl+  c      : 重载swaywm配置
# 5秒自动隐藏光标，600秒自动锁屏，610秒自动黑屏
# 快捷键音量增加减少静音，快捷键亮度增加减少
# ==================================================
# =====使用该配置需要安装的程序=====
# 必须安装：sakura swaylock i3status swayidle
# 建议安装：network-manager blueman fcitx fcitx-libpinyin chrome vlc spotify vscode pavucontrol
# 命令行网络管理nmtui
# 蓝牙管理blueman
# =================================================


# 显示器
# 通过运行 `swaymsg -t get_outputs` 可以获得显示器名称
# 笔记本自带显示器
#output eDP-1 pos 0,0 res 1920x1080
# 外置显示器
#output DP-1 pos 1920,0 res 1440x900
#### 输入配置
#
# 通过运行 `swaymsg -t get_inputs` 可以获得输入名称
# 阅读 `man 5 sway-input` 了解详情
#
