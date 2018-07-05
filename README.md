# Dmx512_Led Specification Guide 
## In windows
### - 使用CMake Gui
1.  使用CMake Gui，在“Where is the source code：”，填写trunk文件夹的绝对目录
2.  在“Where to build the binaries： ”，填写 trunk/build文件夹的绝对目录
3.  点击Configure，点击Generate
4.  在build文件夹下双击生成的xxx.sln打开工程文件。

### - 命令行中调用CMake
1.  添加CMake安装目录到系统环境变量“Path”中。
2.  cd到build目录。
3.  运行 cmake ..
4.  会在build文件夹下生成xxx.sln

## In linux:
    cd build
    cmake ..
----------------------------
You can get in  [github/darboy](https://github.com/darboy) to obtain what you want.

![picture2](http://www.seer-robotics.com/r/default/59af4c66098605169982c793.png)