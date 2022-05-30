qpack
### NAME
qpack - a tools used to pack Qt project on Linux.
### SYNOPSIS
**qpack** \<binary file\> [options] [args]...
### DESCRIPTION
Pack the Qt project to whom the binary file(sepcified by you) belongs.

- **-o \<output dir\>**
	- Specify the package dir. The default dir is "__XXX_pack".
- **-t**
	- tar the package automatically.
- **-v**
	- Print the version(the last time modified the script).
- **--help**
	- Print the help info.
	  
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

![2022-05-30 10-38-55 的屏幕截图](https://user-images.githubusercontent.com/77574540/170909888-6829bd02-4941-47f3-908a-69a490fbd081.png)
![2022-05-30 10-40-15 的屏幕截图](https://user-images.githubusercontent.com/77574540/170909944-7cca3ed2-3371-43cd-b7cf-0a55561611ba.png)
![2022-05-30 10-41-16 的屏幕截图](https://user-images.githubusercontent.com/77574540/170909968-1ed389c7-1450-4687-a669-2209840a706b.png)
![2022-05-30 10-41-58 的屏幕截图](https://user-images.githubusercontent.com/77574540/170909987-3d0da92a-94c4-4707-b7a0-129ed5b51f37.png)

