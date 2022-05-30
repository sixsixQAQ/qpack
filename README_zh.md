qpack
### 名称
qpack - 一个用于打包linux下QT项目的工具。
### 概述
**qpack** \<binary file\> [options] [args]...
### 描述
用于二进制可执行文件(由你指定)所属的项目打包。

- **-o \<output dir\>**
	指定打包输出路径。
	 默认的文件夹是 "__XXX_pack".
- **-t**
	用tar压缩归档打包后的文件夹。
- **-v**
	打印版本信息(最后一次修改的时间)。
- **--help**
	 打印帮助信息
	  
### 警告
1. 目前，-o选项只能制定当前路径下（$PWD）的文件夹。
2. 脚本会覆盖重名文件夹，请确保没有需要的文件。
### 作者

       Written by QingYang.
	   
### COPYRIGHT
       Copyright © 2022 Free Software Foundation, Inc.   License  GPLv3+:  GNU
       GPL version 3 or later <https://gnu.org/licenses/gpl.html>.
       This  is  free  software:  you  are free to change and redistribute it.
       There is NO WARRANTY, to the extent permitted by law.
	   
### 示例
![2022-05-30 10-38-55 的屏幕截图.png](:/1570944497b2415b80ae9a4bf2005f51)



![2022-05-30 10-40-15 的屏幕截图.png](:/4d5d8723578e471883b7387589f4672f)



![2022-05-30 10-41-16 的屏幕截图.png](:/ec7fd5d06b8f4fb294b16f9875d8ab41)



![2022-05-30 10-41-58 的屏幕截图.png](:/e97fd7bffaaa4b6885fe1d0af17c8c7a)
