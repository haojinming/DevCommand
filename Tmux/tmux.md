tmux 常用命令  
[参考](http://www.ruanyifeng.com/blog/2019/10/tmux.html)  
1. tmux 进入一个新窗口
2. exit 退出 tmux 窗口
3. tmux new -s \<session-name\>
4. tmux detach 分离会话
5. tmux ls 查看已有会话
6. tmux attach -t \<session-name\> 接入已有会话
7. tmux kill-session -t |<session-name\> 杀死会话
8. ctrl + b 进入命令模式，翻页上移 下移都需要在命令模式下进行
9. 