# zsh

##安装zsh
####1.如何检测是安装zsh：
zsh --version;
####2.克隆仓库
git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
####3.如果你已存在~/.zshrc文件，则备份现有的~/.zshrc文件
cp ~/.zshrc ~/.zshrc.orig
####4.创建一个新的zsh配置文件
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
####5.改变默认的Shell
chsh -s /bin/zsh
####6.重新启动你的终端
####7.输入zsh，切换到zsh

如果再次打开依然切换不了，可以考虑修改－preferences－profiles－General－command－command设置为:／bin／zsh

注:补充 修改iTerm的透明度:－preferences－profiles－Window-Transparency

##修改zsh－themes
进入github:https://github.com/robbyrussell/oh-my-zsh/wiki/themes 

#### 编辑.zshrc文件
vi .zshrc 
#### 修改主题
ZSH_THEME="alanpeabody" 
#### 退出保存之后 重新打开





