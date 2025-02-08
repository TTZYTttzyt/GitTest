# Git Cmd

## 创建（）

<code> git init -b main</code>  # 1. 初始化一个新的 Git 仓库的命令，其中 -b main 指定了要创建的默认分支名称为 main


<code> echo "# InspireJaka" >> REDEME.md</code>  # 2. 在当前目录下创建一个名为 README.md 的文件，并将文本 # InspireJaka 写入该文件。 # 在 Markdown 中表示标题，因此这里生成的内容将是一个一级标题


<code> git add .</code>  # 3. 将当前目录下面所有文件添加到暂存区，准备好进行下一次提交


<code> git commit -m "first commit"</code>  # 4. 提交暂存区中的文件，并附加一条说明信息 "first commit"


<code> git branch -M main</code>  # 5. 创建一个名为 main 的新分支，并将当前分支重命名为 main。-M 选项表示强制重命名，如果 main 分支已存在，将会被覆盖


<code> git remote add origin git@github.com:TTZYTttzyt/InspireJaka.git </code>  # 6. origin 是远程仓库的一个常用名称，通常指向你所克隆或要推送的默认远程仓库


<code>  git push -u origin main </code>  # 7. 将本地的 main 分支推送到名为 origin 的远程仓库中。-u 选项用于设置上游跟踪，这样以后在使用 git push 时可以直接使用 git push 而不需要指定远程仓库和分支


## 本地推送

<code>git add .</code> # 1. 把所有改动之后的文件需要加到git缓存下面才可以继续git push


<code>git commit -m 'xxx'</code>  # 2. 必须还要执行commit操作


<code>git push origin main</code> # 3. push!



## 远程拉取

<code> git fetch </code>  # 1. 检查远程更新


<code> git pull origin main </code>   # 2. 命令同步远程更改。
