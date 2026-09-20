# yeslab
# YES Lab 新成员任务 - cxy2008

## 一、安装环境
- 操作系统：Ubuntu 20.04 LTS
- ROS 版本：ROS Noetic Ninjemys（桌面完整版）

## 二、安装步骤
1. 配置软件源（使用清华/中科大镜像源）
2. 安装 ros-noetic-desktop-full
3. 初始化 rosdep
4. 配置环境变量（source setup.bash 写入 ~/.bashrc）
5. 安装 rosinstall 等辅助工具

## 三、遇到的问题及解决办法
1. **问题**：rosdep init 时报网络错误
   **解决**：手动修改 /etc/hosts 添加 raw.githubusercontent.com 的 IP，或使用国内镜像源

2. **问题**：sudo rosdep init 提示命令不存在
   **解决**：先安装 python3-rosdep2，再执行初始化

3. **问题**：小海龟控制终端无法响应方向键
   **解决**：确保用鼠标点击控制终端窗口使其处于激活状态

## 四、验证结果
- Ubuntu 版本：20.04（截图见仓库）
- ROS 版本：noetic（截图见仓库）
- 小海龟运行录屏：见仓库视频文件
- 
