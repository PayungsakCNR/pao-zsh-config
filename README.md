## pao-zsh config

How to use
1. vim ~/.zshrc
2. Add or modify this line

```
export PROMPT_EOL_MARK=''
PROMPT='$FG[154]%n%{$reset_color%}$FG[136]@%{$reset_color%}$FG[081]%m%{$reset_color%}:%{$reset_color%}$FG[161]%~%{$reset_color%} $ '
autoload -U promptinit; promptinit prompt pure
```
