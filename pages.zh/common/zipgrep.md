# zipgrep

> 在 Zip 压缩档案中的文件中使用扩展正则表达式查找模式（支持 `?`、`+`、`{}`、`()` 和 `|`）。
> 更多信息：<https://manned.org/zipgrep>.

- 在 Zip 压缩档案中搜索一个模式：

`zipgrep "{{搜索模式}}" {{路径/到/文件.zip}}`

- 打印匹配的文件名和行号：

`zipgrep -H -n "{{搜索模式}}" {{路径/到/文件.zip}}`

- 搜索与模式不匹配的行：

`zipgrep -v "{{搜索模式}}" {{路径/到/文件.zip}}`

- 指定在 Zip 压缩档案中要搜索的文件：

`zipgrep "{{搜索模式}}" {{路径/到/文件.zip}} {{要搜索的文件1}} {{要搜索的文件2}}`

- 排除在 Zip 压缩档案中要搜索的文件：

`zipgrep "{{搜索模式}}" {{路径/到/文件.zip}} -x {{要排除的文件1}} {{要排除的文件2}}`
