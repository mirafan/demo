# demo
- 回退某个文件 、文件夹的修改 （不修改提交历史）

```
git reset commit_id file_name/file_path
git checkout  -- ./
```
- 将HEAD与HEAD^的差异生成patch

```
git format-patch HEAD^
```

git log 显示带分支的提交历史

```
git config --global alias.lg "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative"
```

git log --stat 显示简要的增改行数统计

```
git log --pretty=oneline  # short，full 和 fuller
```

header 1 | header 2
---|---
row 1 col 1 | row 1 col 2
row 2 col 1 | row 2 col 2