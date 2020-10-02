安装以后，可以使用以下两种方式执行 Hexo：

npx hexo <command>

将 Hexo 所在的目录下的 node_modules 添加到环境变量之中即可直接使用 hexo <command>：

echo 'PATH="$PATH:./node_modules/.bin"' >> ~/.profile


运行下列命令启动hexo-admin ：

hexo server -d
打开 http://localhost:4000/admin/ 就可以访问到hexo-admin管理页面了。