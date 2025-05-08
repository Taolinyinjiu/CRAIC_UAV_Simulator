# Abstract
Hello, this Github repository is 2025 CRAIC micro UAV Competition GAZEBO simulator environment and designed by Taolinyinjiu from XUPT

# How To Use It
first, you should clone this repositoty to your ros workspace like catkin_ws, and then compileted ,and finally try to use it .
by the way.this repository only world and not have UAV ,also not have PX4,QGC and so on,just a basic and perfect environment to mapping or try some thinks.

# TODO
1. add UAV models
2. link PX4 launch 
3. add some great launch that add UAV in world,and the UAV linked PX4 sitl 


# 介绍
你好，这个仓库用于存放2025年中国机器人及人工智能大赛微型无人机赛项Gazebo仿真环境，由西安邮电大学的桃林饮酒设计，

# 如何使用
这个仓库由于最开始的设计理念是希望拿到手的同学开箱即用，因此将整个的工作空间进行了打包上传，在使用时，首先将该仓库克隆到自己的电脑上，由于在后续的更新中会上传有关ros软件包的部分，因此最好操作系统使用Ubuntu20
```
# 克隆
git clone https://github.com/Taolinyinjiu/CRAIC_UAV_Simulator.git
# 进入仓库(其实也是个工作空间)
cd CRAIC_UAV_Simulator
catkin_make
# 关键的一步，设置模型路径
export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:/your_path/CRAIC_UAV_Simulator/src/CRAIC/models
# 查看环境
source devel/setup.bash
cd src/CRAIC/worlds
gazebo CRAIC_Simulator.world
```

# 如果对你有帮助的话可以给我点个star吗
