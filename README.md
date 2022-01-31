# MyDwm
This Is My Dwm
## 1.Install Arch
安装引导
安装输入法
安装字体 nerd-fonts-complete
compton neovim ranger htop
neovim默认教程:<br>
https://blog.csdn.net/weixin_43372529/article/details/112242335?utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-3.control&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-3.control<br>
neovim配置教程:<br>
https://github.com/fgheng/vime<br>
ranger配置：<br>
https://www.zssnp.top/
## 2.Install Dwm
git clone https://github.com/k6k6/MyDwm.git<br>
cd dwm<br>
sudo make clean install
## 3.安装并配置oh-my-zsh
sudo pacman -S zsh<br>
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"<br>
chsh -s /bin/zsh
## 4.USB设置
首先通过安装启用 MTP 支持：

$ sudo pacman -S mtpfs
对于运行的设备 安卓 4+， 这应该可以解决问题。 但是，在以后的版本中，我们需要另一个名为 jmtpfs 从 金子 存储库。 您可以通过以下方式获取它：

$ paru jmtpfs
此时，我们有 中期计划 启用。 但是，它在您的文件管理器中仍然不可见，因为它没有按照我们的需要自动安装。 要自动挂载它，我们需要安装一个包：

$ sudo pacman -S gvfs-mtp
启用 PTP 支持
点对点 代表 “图片传输协议” 事实上是协议 中期计划 基于。 当您通过以下方式与您的 Android 手机通信时 点对点，它在您的 PC 上显示为数码相机。

要启用 PTP，我们需要安装一个包：

$ sudo pacman -Sy gvfs-gphoto2
最后，为了使更改生效，我们需要 重新启动系统 可以通过以下方式完成：

$ reboot

$ yay fat


