# pdfjs-backup
去除了对pdf和viewer同源的限制。

在react项目中的用法：
将所用版本放到public文件夹下，使用iframe引用viewer.html文件
```
 <iframe src={`pdfjs-2.2.228-dist/web/viewer.html?file=${fileUrl}`} width={800} height={1000} />
```
其中```pdfjs-2.2.228-dist/web/viewer.html```是viewer文件的路径，```${fileUrl}```是pdf的文件路径。宽度和高度可以自行定义。
