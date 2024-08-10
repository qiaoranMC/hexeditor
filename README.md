一个使用c语言制作的控制台版十六进制编辑器，拥有图灵完备的宏功能/A use c language build hexeditor, script mode Toling full support
历时两周打造，拥有着较为出色的功能/Use 14 day time make, have very good the mode
下面是使用方法：/Down is usage:
运行程序/Run program
输入路径/文件名称，按下换行
Enter path/file name, press enter
你会看到以下界面/You will see this interface
0 _0__1__2__3__4__5__6__7__8__9__a__b__c__d__e__f_   0-f
   0|2d 31 20 31 20 66 66 20 31 20 30 20 30 20 30 20    0>>>
可以使用以下命令编辑十六进制文件/can use down command edit hex file
-1：修改指定的数组元素值，可用于修改以下内容/-1:edit local sub class value, can use the mode edit for
 -1 0 （值）：修改光标位置，可用于跳转指定地址/-1 0 (value):edit lock address, can use the command goto to you hope address value
 -1 a （值）：修改开始打印地址的位置/-1 a (value):edit start print address the value
 -1 b （值）：修改结束打印地址的位置/-1 b (value):edit end print address the value
 -1 c （值）：选择显示格式，编辑为0显示成十六进制，编辑为1显示成十进制/-1 c (value):select show format, edit for zero show hex, edit for 1 show dec
 -1 d （值）：是否显示ascii字符在右侧，编辑为0表示不用，编辑为1表示是的/-1 d (value):Enable show ascii word, edit for 0 no show, edit for 1 show
-2：使用宏模式，默认版本为hexeditor_mod.h，编辑导入头文件名称以切换为hexeditor_mod_v1.h/-2:use script mode, default version for hexeditor_mod.h, edit import head file name to select hexeditor_v1.h
具体用法见include/README.md
How to use see with include/README.md
-3：保存文件/-3:save file