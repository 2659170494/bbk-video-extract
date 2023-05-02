bbk-video-extract
=================

步步高视频破解.

几年前的,还能用.有些bug,有问题看代码.

来源于对步步高某ROM的逆向.

### Linux编译命令为:gcc blmkey.c bmdkey.c main.c -o <输出的可执行文件(如main_get)>

Win编译需要下载libiconv,并且编译出来无法解密文件(感觉是缓冲区问题)。目前测试仅能在ubuntu20中的mingw_w64编译，win版msys2依旧无法引用库

libiconv安装教程详情请看:https://gnuwin32.sourceforge.net/packages/libiconv.htm

### Win编译命令为:gcc blmkey.c bmdkey.c main.c -I <libiconv Include目录> -L <libiconv Lib目录> -liconv -o <输出的可执行文件(如main_get.exe)>

Win编译完成后还需要将libiconv中bin文件夹里的文件(dll和exe)拷贝到编译文件的根目录(或许直接使用installer装也行？)才能运行

### 执行命令为:./main_get <完整的文件路径（不能使用相对路径！！！）>

如果你想直接运行，直接使用项目文件夹的main_get程序就可以了

源代码在Github中原fork就可以看到



GreenYoshi

2023.05.03 01:07
