qpack
### NAME
qpack - a tools used to pack Qt project on Linux.
### SYNOPSIS
**qpack** \<binary file\> [options] [args]...
### DESCRIPTION
Pack the Qt project to whom the binary file(sepcified by you) belongs.

- **-o \<output dir\>**
	Specify the package dir.
	 The default dir is "__XXX_pack".
- **-t**
	tar the package automatically.
- **-v**
	Print the version(the last time modified the script).
- **--help**
	  Print the help info.
	  
### WARNINGS
1. Currently, option -o can only specify output path in current path or its child($PWD or $PWD/*).
2. The script will overwrite files wihthout warnings. Make sure there are no files needed. 
### AUTHOR

       Written by QingYang.
	   
### COPYRIGHT
       Copyright © 2022 Free Software Foundation, Inc.   License  GPLv3+:  GNU
       GPL version 3 or later <https://gnu.org/licenses/gpl.html>.
       This  is  free  software:  you  are free to change and redistribute it.
       There is NO WARRANTY, to the extent permitted by law.
	   
### EXAMPLE

![2022-05-30 10-38-55 的屏幕截图.png](../_resources/2022-05-30 10-38-55 的屏幕截图.png)



![2022-05-30 10-40-15 的屏幕截图.png](../_resources/2022-05-30 10-40-15 的屏幕截图.png)



![2022-05-30 10-41-16 的屏幕截图.png](../_resources/2022-05-30 10-41-16 的屏幕截图.png)



![2022-05-30 10-41-58 的屏幕截图.png](../_resources/2022-05-30 10-41-58 的屏幕截图.png)

