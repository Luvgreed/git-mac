# git-mac

## quick start

Setup an SSH key

    ssh-keygen
    cat ~/.ssh/id_rsa.pub | pbcopy

Small sample to get you started

    alias ga='git add'
    alias gc='git commit -v'
    alias gcmsg='git commit -m'
    alias gd='git diff'
    alias gds='git diff --staged'
    alias gst='git status'

    alias gco='git checkout'
    alias gcm='git checkout master'

    alias gb='git branch'
    # view remote branches
    alias gbr='git branch --remote'

    alias gup='git pull --rebase'
    alias gp='git push'
    # push a newly created local branch to origin
    alias gpsup='git push --set-upstream origin $(git_current_branch)'

Source `~/.zshrc`

    source ~/.zshrc

Create a `~/.gitexcludes` file and paste in this:

    .DS_Store

## Reference

https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/git/git.plugin.zsh