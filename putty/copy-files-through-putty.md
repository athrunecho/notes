# 将文件从Wingdows传入Linux虚拟机

1. 将需要复制的的文件放在PSFTP.EXE相同目录下

2. 运行cmd

3. 进入"PSFTP.EXE"文件目录
   
    * Example:
    
    * `cd C:\`

4. 打开PSFTP.EXE

5. 进入虚拟机
   
    * `psftp> open hostname`

6. 利用put命令将文件复制到Linux系统中
    
    * `psftp> put filename`
