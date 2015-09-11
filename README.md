##转换字体格式、压缩字体大小、自定义web字体的完美方法
1. 安装nodejs
2. 然后执行命令:
``` bash 
npm install font-spider -g 
```
3. 将原ttf格式的字体放入此文件夹中（其他格式的字体后面将会由工具自动生成）,ttf格式字体可以去网上下 很多的。
4. 修改fonts.html文件，其中的font-family可以自己随意定义，src字体路径也要修改成对应的路径和字体名称；body标签内写入如要被压缩的字，其他没有写进body的文字将不会被压缩在字体文件中，所以后面将无法使用该字体样式。
5. 修改好fonts.html后，然后双击运行compress.bat批处理文件，等批处理文件运行完成会自动消失，此时大功告成，其他三种格式的字体（eot、svg、woff）也随之诞生，并且被压缩。原ttf格式的字体文件被备份到了.font-spider文件夹中。
6. 在浏览器打开fonts.html网页文件，你将看到自定义的字体样式。

使用方法也可参照官网说明:[font-spider.org](font-spider.org)
