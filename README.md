MuJoCo汽车仪表盘项目
项目简介
这是一个基于MuJoCo物理引擎的汽车仪表盘可视化系统，能够实时显示车辆的速度、转速等数据。

快速开始
1. 克隆项目
bash
git clone https://github.com/yourname/mujoco-car-dashboard.git
cd mujoco-car-dashboard
2. 编译运行
bash
# 创建编译目录
mkdir build && cd build

# 编译项目
cmake .. && make -j4

# 运行程序
./bin/mjpc
主要功能
✅ 车辆物理仿真

✅ 速度表显示

✅ 转速表显示

✅ 键盘控制（WASD）

控制说明
W: 加速

S: 减速

A/D: 转向

ESC: 退出

文件结构
text
mujoco-car-dashboard/
├── code/          # 源代码
├── build/         # 编译目录
├── scenes/        # 场景文件
└── README.md      # 说明文件
作业提交
代码仓库: https://github.com/yourname/mujoco-car-dashboard

运行视频: [视频链接]

PDF报告: [报告链接]
