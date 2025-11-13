# git.fzf

Fzf wrapper arround git commands.

## install

```
git clone github.com/llynch/git.fzf
cd git.fzf
gitfzf_dir="$(readlink -f .)"
echo "export PATH=\"\$PATH:$gitfzf_dir\"" >> ~/.bashrc
```

## dependecies

- gum: a tool for glamorous shell scripts.
- fzf: a general-purpose command-line fuzzy finder.

## git-branch

- See logs in preview.
- Checkout the branch using `enter`.
    To auto track remote branch:
   `git config --global --type bool push.autoSetupRemote true`
- Track the branch using `ctrl+t`.
- Diff branch using `ctrl+d`.
- Remove local branch using `ctrl+r`.
- Delete remote branch using `ctrl+x`.
- Call git-log using `ctrl+l`

## git-log

- show a branch latest commits.
- show unified diff in preview.
- show diff in terminal when pressing enter.

# git-stash

- show stashes.
- show unified diff in preview.
- apply stash using `ctrl+a`.
- pop stash using `ctrl+p`.
- delete stash using `ctrl+x`.

## confirm

- Simple confirm script to say yes or no.
