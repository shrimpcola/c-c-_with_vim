# c-c-_with_vim
通过原始的vim进行c/c++开发
f1上下分屏幕,查看vim客户端的具体信息
f4进行头文件和源文件之间的相互跳转
f6调出目录结构
Ctrl+o返回原来代码位置
nmap gd <Plug>(coc-definition)    " 跳定义（进头文件核心）
nmap gr <Plug>(coc-references)    " 查所有引用
nmap gi <Plug>(coc-implementation)" 跳实现
nmap gT <Plug>(coc-type-definition)" 跳结构体类型
nmap K  <Plug>(coc-hover)         " 悬停看函数文档

