## 同步与备份
第一种是使用插件，譬如说Remotely safe插件，配合第三方存储，譬如说onedrive或者坚果云什么的。
第二种使用第三方文件夹同步软件，譬如说FolderSync或者Syncthing，配合第三方存储，同上。
第三种呢？

备份可以用Github或者Gitee

## DataView
~~~dataview
Table file.ctime as 创建日期,file.mtime As 修改日期
from #trello
sort file.day desc
~~~

可以使用list table 
from
group by
faltten

~~~dataview
Table status,flag,file.ctime
From #project-todo
~~~

