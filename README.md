# Important Dev Setup
---

### bash_rc
```bash
alias vbc='vi ~/.bash_rc'
alias ls='ls -GFh'
alias vbp='vi ~/.bash_profile'
alias sbc='source ~/.bash_rc'
alias sbp='source ~/.bash_profile'
alias back='cd $OLDPWD'
alias ..='cd ..'
alias ...='cd ../..'
alias ....='cd ../../..'
alias .....='cd ../../../..'
alias fixup='git add . && git commit -m "Fix" && git rebase -i HEAD~2'

# Bash completion
if [ -f /etc/bash_completion ]; then
  . /etc/bash_completion
fi
```
