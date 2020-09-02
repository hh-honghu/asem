请自行下载dosbox
压缩包包含MASM5、LINK、DEBUG
         配置
目录结构:C:\asem里包含汇编程序文件夹ASM 汇编环境文件夹MASM

双击打开dosbox xxxx option.bat

在末尾添加
  mount C:C:\asem (C:\asem是被挂载的目录)
  set PATH=%PATH%;C:\MASM (将c:\asem\MASM添加到系统变量)
  C:  (切换到挂载的C盘)
  cd C:\ASM (进入到C:\asem\ASM)



 汇编步骤
masm a.asm
link a.obj
debug a.exe
