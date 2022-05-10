# OS 系统 Tree 中文说明

## 安装

> Brew

```bash
brew install tree
```

> Mac

```bash
yum install tree
## CentOS/RHEL 8.x and Fedora user try the dnf command ##
dnf install tree
```

> Linux

```bash
sudo apt-get install tree
```

## 语法

```bash
tree
tree /path/to/directory
tree [options]
tree [options] /path/to/directory
```

## 详细参数

```
  -a 列出所有文件。
  -d 仅列出目录。
  -l 跟随目录等符号链接。
  -f 打印每个文件的完整路径前缀。
  -x 仅停留在当前文件系统上。
  -L level 仅下降一级目录。
  -R 达到最大目录级别时重新运行树。
  -P pattern 仅列出与给定模式匹配的那些文件。
  -I 模式 不列出与给定模式匹配的文件。
  --ignore-case 模式匹配时忽略大小写。
  --matchdirs 在 -P 模式匹配中包含目录名称。
  --noreport 在树列表末尾关闭文件/目录计数。
  --charset X 将 charset X 用于终端/HTML 和缩进行输出。
  --filelimit # 不要下降包含超过 # 个文件的目录。
  --timefmt <f> 根据格式<f>打印和格式化时间。
  -o 文件名 输出到文件而不是标准输出。
  -------- 文件选项 ---------
  -q 将不可打印字符打印为“？” .
  -N 按原样打印不可打印的字符。
  -Q 用双引号引用文件名。
  -p 打印每个文件的保护。
  -u 显示文件所有者或 UID 号。
  -g 显示文件组所有者或 GID 号。
  -s 以字节为单位打印每个文件的大小。
  -h 以更易于阅读的方式打印尺寸。
  --si 与 -h 类似，但使用 SI 单位（1000的幂）。
  -D 打印最后修改或( -c )状态更改的日期。
  -F 附加'/' , '=' , '*' , '@' , '|' 或'>'根据 ls -F。
  --inodes 打印每个文件的 inode 编号。
  --device 打印每个文件所属的设备 ID 号。
  ------- 排序选项 -------
  -v 按版本按字母数字排序文件。
  -t 按上次修改时间排序文件。
  -c 按上次状态更改时间对文件进行排序。
  -U 不排序文件。
  -r 反转排序的顺序。
  --dirsfirst 列出文件之前的目录（ -U 禁用）。
  --sort X 选择排序：名称、版本、大小、mtime、ctime。
  ------- 图形选项 ------
  -i不打印缩进线。
  -A 打印 ANSI 线条图形缩进线条。
  -S 使用 CP437（控制台）图形缩进线打印。
  -n 始终关闭着色（-C 覆盖）。
  -C 总是打开着色。
  ------- XML/HTML/JSON 选项 -------
  -X 打印出树的 XML 表示。
  -J 打印出树的 JSON 表示。
  -H baseHREF 以 baseHREF 作为顶层目录打印 HTML 格式。
  -T string 用字符串替换默认的 HTML 标题和 H1 标题。
  --nolinks 关闭 HTML 输出中的超链接。
  ---- 其他选项 ----
  --version 打印版本并退出。
  --help 打印使用情况和此帮助信息并退出。
  -- 选项处理终止符。
```
