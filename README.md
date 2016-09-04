# my_oh-my-zsh_theme
my oh-my-zsh theme

###关于右边的命令提示符显示时间
需要在`~/.oh-my-zsh/themes`目录下的`bira.zsh-theme`中引入一个`$RPROMPT`变量。
```sh
# Time on the right %* stands for the 24-hour time ,with seconds included
RPROMPT="%{$fg[green]%}[%*]%{$reset_color%}"
```
参考：
http://superuser.com/questions/943844/add-timestamp-to-oh-my-zsh-robbyrussell-theme
