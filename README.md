# 1、将两个文件dll和lib文件放置在java全局环境的jdk/jre/bin文件下
然后，在 Run Configurations -> Agruments -> VM Agruments 下填入 -XX:+UnlockDiagnosticVMOptions -XX:+PrintAssembly 即可

//# 2、设置运行命令追加以下命令
//-server -Xcomp -XX:+ UnlockDiagnosticVMOptions -XX:+ PrintAssembly 一XX:CompileCommand=compileonly,*VolatileDemo.changeData