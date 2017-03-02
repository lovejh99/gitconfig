# gitconfig
[user]                                                                                                                                                                                   
        email = hailei.zhao@ushow.media
        name = hailei.zhao
[alias]
    st=status 
    s=status --short
    co=checkout
    tr=checkout
    br=branch
    ci=commit
    lg=log --color --graph --decorate
    last=log -1 HEAD
    l=log --color --graph --decorate --pretty=oneline --abbrev-commit
    la=log --color --graph --decorate --pretty=oneline --abbrev-commit --all
    lb=log --color --graph --decorate --pretty=oneline --abbrev-commit --all --simplify-by-decoration
    l0=log --color --graph --decorate --pretty=oneline --abbrev-commit -U0 
    dl=log --date-order --color --graph --decorate --pretty=oneline --abbrev-commit
    dla=log --date-order --color --graph --decorate --pretty=oneline --abbrev-commit --all
    dlb=log --date-order --color --graph --decorate --pretty=oneline --abbrev-commit --all --simplify-by-decoration
    dlg=log --date-order --color --graph --decorate
[push]
        default = matching
[color]
        ui = auto
[core]
        excludesfile = /Users/hailei/.gitignore_global
[difftool "sourcetree"]
        cmd = opendiff \"$LOCAL\" \"$REMOTE\"
        path = 
[mergetool "sourcetree"]
        cmd = /Applications/SourceTree.app/Contents/Resources/opendiff-w.sh \"$LOCAL\" \"$REMOTE\" -ancestor \"$BASE\" -merge \"$MERGED\"
        trustExitCode = true
