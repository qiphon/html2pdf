# html2pdf

## run

这个项目仅在 Linux 环境下测试没有问题，如果命令无法运行，请删除目录下的 node_modules 文件
执行 `npm i` 然后再运行下面的命令

```bash
# html2pdf <-u|url> 要转成PDF的URL <-o|output> 生成pdf的路径
./html2pdf -u http://qiphon.cc:5500/views -o 123.pdf

```

默认会先删除 要写入的PDF，请保证文件名不冲突