# AzurLanePaintingAnalysis_SavePathModified
 
在大佬Deficuet的ALPA基础上修改了保存路径，不过这个功能只能说见仁见智吧，有些人就刚好需要存放在任务目录下，像我就喜欢堆一起（笑）。故在这此存个档，供有单一保存路径需要的人使用。   

具体功能：输出的目录固定为alpa.yml中path的值，检测到同名文件后在末尾添加序号后保存。（注意：打开保存文件夹失效，问就是懒）  

## 使用方法
1.前往https://github.com/Deficuet/AzurLanePaintingAnalysis-Kt 获取Release下最新文件，解压所有文件放入你指定的文件夹记作"A"  
2.下载我在Release下准备的替换jar包，放入"A"文件夹中替换  
3.编辑alpa.yml文件，在最后一行后换行加上 path:'YourTargetDirectory' 例如 path:'D:\Test',如果已有path:''则直接填入即可  
4.运行"A"文件夹中的launch.bat  
5.前往https://github.com/Deficuet/AzurLanePaintingAnalysis-Kt/blob/main/README.md 查阅具体的使用教程  

PS:Release下只会有替换用的jar包，以防有人不知道原作者  
PPS:有需要者可以查阅代码，应该只在function和configuration上做了修改，有能力者拿本仓库的src替换原作者的代码自己编译也是可以的  
