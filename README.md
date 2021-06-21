# CiCd备忘、学习手册

## 常用命令

  * cat(concatenate) —— 用于连接文件并打印到输出设备上
  * sed(stream editor) —— 用于处理内容，并输出到标准输出上



## 虚拟机连不上网络

  * 使用ping的方式查看是否可以ping通

    * 查看是否开启了网卡

      https://cloud.tencent.com/developer/article/1334254

    * 设置虚拟机交换机管理器

      https://ken.io/note/hyper-v-course-setup-network

## 共享文件夹 & 挂载虚拟硬盘

  * 挂载虚拟硬盘（没有实践完）

    https://www.pcoic.com/system/742.html

  * 共享文件夹

    https://www.jianshu.com/p/b1004a9a4724

    ```sh
    mount -o username=Administrator,password=123456 //172.16.20.60/share share
    ```

  * 常见错误：
    
    https://blog.51cto.com/poollooq/1564203
    
    ***注：注意用户名的填写，是当前windows的账户名，可在C:/Users下查看，除了public，default***

## 系统没有鼠标/光标

  https://blog.csdn.net/zhldt2008/article/details/52621423