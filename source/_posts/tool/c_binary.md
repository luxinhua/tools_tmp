---
title: c binary 相关工具
categories:
- tools
date: 2021/2/8
toc: true # 是否启用内容索引
---

---
### strings 
---
列出bin文件中的字符串
~~~bash
    strings a.out 

    /lib64/ld-linux-x86-64.so.2
    libc.so.6
    puts
    __cxa_finalize
    strcmp
    __libc_start_main
    GLIBC_2.2.5
    _ITM_deregisterTMCloneTable
    __gmon_start__
    _ITM_registerTMCloneTable
    u+UH
    []A\A]A^A_
    cheking passwd!
    ok you got me
    WRONG !
    Usage: <key>
    :*3$"
~~~

---
### 2进制转16进制 
---

1.  vim 中 ：%！xxd   退回二进制： ：%！xxd  -r 
2.  bash shell: xxd a.out > 16.txt

---
### file 
---

~~~bash 
~~~

---
### readelf 
---
查看程序段信息, [参考文档](https://blog.csdn.net/yfldyxl/article/details/81566279)
~~~bash 
readelf -S a.out   #  -S(section headers),sections 
~~~


---
### addr2line
---

~~~bash 
~~~



