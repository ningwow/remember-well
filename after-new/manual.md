# pulseaudio声卡正常
    使用kmix开启声音即可

# oh-my-zsh
    mv /home/rjn/.oh-my-zsh /usr/share/oh-my-zsh
    .zshrc 文件中的 export ZSH=/usr/share/oh-my-zsh/
    mv /home/rjn/.oh-my-zsh /root/.zshrc

# yay编译手动
    cd /home/rjn/yay
    makepkg -si
    y

# alacritty配置
    vim .config/i3/config   配置terminal为alacritty

# 配置图形   手动优先
    #xrandr --output HDMI-1 --mode 1920x1080 --rate 60
    #echo "xrandr --output HDMI-1 --mode 1920x1080 --rate 60" >> /etc/profile