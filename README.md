# Scriptfiles

A list of handy command-line tools

## Available tools

### copy-lines

Copies a range of lines from any file to your clipboard.

```
copy-lines 100,200 my-file.txt
```

### git-remove-deleted

Removes all git files that have been deleted.

```
#
# Changes not staged for commit:
#   (use "git add/rm <file>..." to update what will be committed)
#   (use "git checkout -- <file>..." to discard changes in working directory)
#
#       deleted:    scripts/Root.js
#       deleted:    scripts/app.js
#       deleted:    stylesheets/style.sass
#
ddyba@70KY0:~/Code/react-tutorial|master⚡
⇒  git-remove-deleted
rm 'scripts/Root.js'
rm 'scripts/app.js'
rm 'stylesheets/style.sass'
ddyba@70KY0:~/Code/react-tutorial|master⚡
⇒
```
