# ROS-
catkin_ws是空文件夹，上传错了
# 任务内容

利用松灵小车上录制的`bag包`数据（链接见后文），编写软件，展示ROS系统中的各类数据，具体包括：

1. 用命令行窗口显示小车的IMU和里程计（odometry）数据；
2. 用图形界面显示颜色相机和深度相机的数据（利用OpenCV库）；
3. 用图形界面显示激光雷达的点云数据（利用PCL库）；
4. 自行选择一种高级算法（例如语义分割、三维重建、导航定位（SLAM）等），实现该算法（可以直接利用第三方库），将其集成到系统中。

# 代码要求

1. 所有程序代码采用C++编写，使用git进行源代码管理；
2. 类名、变量名、函数名应符合C++的命名规范，并在代码中前后保持一致；
3. 涉及面向对象的程序，例如自定义的类，应符合面向对象的设计原则；
4. 正确使用头文件和源文件，自定义的头文件应符合头文件的编写原则，例如用条件宏定义确保头文件不被多次引用、不在头文件中进行类和函数的实现（模板除外）；
5. 项目必须是ROS项目，符合ROS的项目的规范，正确编写CmakeLists.txt等文件；

# 提交资料

1. 程序源代码，需要包含git仓库（.git文件夹），源代码需上传到公网上的git仓库，并提供仓库的URL地址
2. 录制程序的演示视频，视频可以传到B站，上传视频播放的URL地址；
3. 提交一份报告，描述程序实现的关键步骤、算法和结果。

# 成绩构成

1. 代码规范性占10分；
2. git的使用占10分；
3. 报告和视频占20分；
4. 任务1-3占50分；
5. 任务4占10分。

Rosbag包下载地址，若地址过期，请联系老师
链接: https://pan.baidu.com/s/1kA6MYzvprQJxv2L45U7K6w 提取码: ov15 
--来自百度网盘超级会员v6的分享
