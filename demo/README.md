
# (null) entry in command string: null chmod 0700
- 拷贝winutils.exe,libwinutils.lib 到%HADOOP_HOME%\bin目录
- 拷贝hadoop.dll到c:\windows\system32目录
# java.io.IOException: Could not locate executable null\bin\winutils.exe in the Hadoop binaries
- 缺少系统变量%HADOOP_HOME%
