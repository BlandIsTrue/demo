我的测试样例：本地仓库：D:/code/github-host (意为github托管)
远程连接仓库：起名叫demo, (git remote add demo git@github.com:BlandIsTrue/demo.git该命令已连接)
将修改添到缓冲区：git add -A
加备注：git commit -m "新建了xxx，修改了xxx"
推到远程仓库：向一个空的新仓库中推文件：git push -u 仓库名称如demo 分支如主分支master (首次加上-u，意为将本地master分支和远程master分支关联起来，后续推送不用加)
