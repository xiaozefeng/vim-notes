# 关于vim中的let关键字
我们经常在vimrc文件中看到
```vimrc
let	g:variable
let b:variable
let l:variable 
```
 
```
# 在vim中执行
:help internal-variables
```

`
(nothing) In a function: local to a function; otherwise: global  
|buffer-variable|    b:	  Local to the current buffer.  
|window-variable|    w:	  Local to the current window. 
|tabpage-variable|   t:	  Local to the current tab page.  
|global-variable|    g:	  Global.  
|local-variable|     l:	  Local to a function.  
|script-variable|    s:	  Local to a |:source|'ed Vim script.  
|function-argument|  a:	  Function argument (only inside a function).  
|vim-variable|       v:	  Global, predefined by Vim.  
`
