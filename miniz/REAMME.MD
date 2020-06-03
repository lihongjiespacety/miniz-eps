# [编译]

1. windows下: mingw32-make win32-mingw (需要先安装好MinGW并配置好相关路径)
2. linux下: make gcc(可在win10的 linux子系统下编译)


# [使用]

1. windows下
    - 压缩 ./miniz.exe -l10 c .\TY38_EPS_Check.bin bank1app.zip
    - 解压 ./miniz.exe -l10 d bank1app.zip unzip.bin
    - 比对 使用二进制比对工具 010 Editor比对文件TY38_EPS_Check.bin和unzip.bin是否完全一致.


2. linux下
    - 压缩 ./miniz.exe -l10 c TY38_EPS_Check.bin bank1app.zip
    - 解压 ./miniz.exe -l10 d bank1app.zip unzip.bin
    - 比对 使用二进制比对工具 010 Editor比对文件TY38_EPS_Check.bin和unzip.bin是否完全一致.