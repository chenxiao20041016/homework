🚗 MuJoCo汽车仪表盘可视化系统


📖 项目简介
这是一个基于MuJoCo物理引擎的汽车仪表盘可视化系统，能够实时显示车辆的速度、转速、油量等关键数据，提供逼真的物理仿真体验。

🚀 快速开始
1️⃣ 克隆项目
bash
git clone https://github.com/yourname/mujoco-car-dashboard.git
cd mujoco-car-dashboard
2️⃣ 编译运行
bash
# 创建编译目录
mkdir build && cd build

# 配置并编译项目
cmake .. && make -j4

# 运行程序
./bin/mjpc
✨ 主要功能
功能模块	状态	说明
🚗 车辆物理仿真	✅ 已实现	基于MuJoCo的精确物理模拟
📊 速度表显示	✅ 已实现	实时显示车速（0-200 km/h）
⚙️ 转速表显示	✅ 已实现	发动机转速监控（0-8000 RPM）
⛽ 油量显示	🔄 开发中	实时油量消耗模拟
🎮 键盘控制	✅ 已实现	WASD控制车辆运动
🎯 控制说明
按键	功能
W	加速前进
S	减速/后退
A	左转
D	右转
R	重置车辆位置
ESC	退出程序
📁 项目结构
text
mujoco-car-dashboard/
├── 📁 code/              # 源代码目录
│   ├── dashboard/       # 仪表盘相关代码
│   └── tasks/           # 仿真场景定义
├── 📁 scenes/           # 车辆场景文件
├── 📁 assets/           # 资源文件（纹理、字体等）
├── 📁 build/            # 编译输出目录
├── CMakeLists.txt       # 编译配置文件
└── README.md            # 项目说明文档
📋 环境要求
操作系统: Ubuntu 20.04+ / Windows 10+（WSL2推荐）

编译器: GCC 9.0+ 或 Clang 10.0+

依赖库: OpenGL, GLFW, Eigen3, MuJoCo

🛠️ 安装依赖（Ubuntu）
bash
sudo apt update
sudo apt install -y build-essential cmake git
sudo apt install -y libgl1-mesa-dev libglfw3-dev libglew-dev
🔧 进阶配置
如需使用自定义车辆模型或调整物理参数，请修改 scenes/car_config.xml 文件。

🤝 贡献指南
欢迎提交Issue和Pull Request！请确保代码风格一致并通过基础测试。

📄 许可证
本项目基于 MIT 许可证开源 - 查看 LICENSE 文件了解详情。

<div align="center"> ⭐ 如果这个项目对你有帮助，请点个Star支持一下！ </div>

💡 提示: 项目仍在持续开发中，欢迎反馈问题和建议！
