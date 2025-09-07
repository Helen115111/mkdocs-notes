应用新主题：
```
theme:
  name: material
```
接上mkdocs serve
端口冲突:mkdocs serve -a 127.0.0.1:8001
执行到一半不动是正常的 直接打开url查看站点 主题已经变了 

部署，托管，优化
- 部署命令：git gh-deploy
- 输出结束后，去github打开actions观察绿色对勾，通过以后打开settings-pages，找到网址打开就是mkdocs个人站点