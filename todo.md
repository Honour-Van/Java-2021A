增加其他几个接口。直接调用相关数据库接口即可
1. modify：增加id输入框，调用function中给出的api即可
2. add：需要增添一个针对前端的增加记录的api
3. remove：类似modify的思路，delete相关api已经实现完成

增加一个刷新接口，重新读取整体数据，进行渲染。
1. 将全部数据查询传输
2. 重新调用接口进行绘图

增加Cookies功能

javascript 脚本加载是有顺序的。
尽量还是打分号比较好