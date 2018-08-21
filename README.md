目录结构


lib64

py编译成so文件后所依赖的库,运行前需将该目录加入LD_LIBRARY_PATH


traffic_core

交通相关的核心逻辑，注意这部分代码必须以so的方式发布，不得发布py文件


utils

一些常用的功能函数


case

违法行为检测的测试用例


set_env.sh

用于设置系统环境
