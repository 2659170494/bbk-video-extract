bbk-video-extract
=================

步步高视频破解.

几年前的,还能用.有些bug,有问题看代码.

来源于对步步高某ROM的逆向.

编译命令为:gcc blmkey.c bmdkey.c main.c -o <输出的可执行文件(如main_get)>

Win编译需要下载libiconv Developer files

编译命令为:gcc blmkey.c bmdkey.c main.c -I <libiconv Include目录> -L <libiconv Lib目录> -liconv -o <输出的可执行文件(如main_get.exe)>

执行命令为:./main_get <完整的文件路径（不能使用相对路径！！！）>

如果你想直接运行，直接使用项目文件夹的main_get程序就可以了

源代码在Github中原fork就可以看到



GreenYoshi

2023.05.03 01:07
