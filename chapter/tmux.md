# 12月4日

### tmux的框架结构

*   [__session__](#session)
*   [__window__](#window)
*   [__pane__](#pane)


#### tmux的绑定bind-k

       ctrl + a

####session

  1.   创建session / 列出tmux列表

            tmux  / tmux ls

  2.   链接某个session

            tmux attach-session(a) -t xxx

  2.   关闭某个session

            tmux kill-session(a) -t xxx


####window

  1.  创建window

      bind-k + c

  2.  删除window

      只能一个一个pane的关掉

  3.  重命名window

      bind-k + ,

  4.  切换window

      bind-k + 窗口编号
  
####pane

  1.  创建pane

      bind-k s 横屏开个pane

      bind-k v 竖屏开个pane

  2.  关闭pane

      exit / ctrl + d

  3.  切换pane

      ctrl + hjkl
