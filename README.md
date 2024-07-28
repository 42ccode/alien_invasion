README
飞船游戏 (Spaceship Game)
简介 (Introduction)
这是一个使用 Pygame 开发的简单飞船游戏。玩家可以通过键盘控制飞船的移动，并向外星人射击。游戏包含计分系统和多个关卡。

This is a simple spaceship game developed using Pygame. Players can control the spaceship's movement using the keyboard and shoot at aliens. The game includes a scoring system and multiple levels.

安装 (Installation)
确保你已安装 Python 3.x 和 Pygame。

克隆或下载此仓库到本地。

Ensure you have Python 3.x and Pygame installed.

Clone or download this repository to your local machine.

sh
复制代码
git clone https://github.com/yourusername/spaceship-game.git
cd spaceship-game
安装依赖：

Install dependencies:

sh
复制代码
pip install pygame
运行游戏 (Running the Game)
在终端或命令提示符中运行以下命令：

Run the following command in your terminal or command prompt:

sh
复制代码
python main.py
控制 (Controls)
右箭头键：向右移动

左箭头键：向左移动

上箭头键：向上移动

下箭头键：向下移动

空格键：射击

Q 键：退出游戏

Right Arrow Key: Move right

Left Arrow Key: Move left

Up Arrow Key: Move up

Down Arrow Key: Move down

Spacebar: Shoot

Q Key: Quit the game

文件结构 (File Structure)
bash
复制代码
spaceship-game/
│
├── images/                     # 游戏所需的图片
│   └── ship.bmp
│
├── main.py                     # 主程序
├── settings.py                 # 游戏设置
├── game_functions.py           # 游戏功能
├── ship.py                     # 飞船类
├── bullet.py                   # 子弹类
├── alien.py                    # 外星人类
├── scoreboard.py               # 记分板类
├── game_stats.py               # 游戏统计
├── button.py                   # 按钮类
└── README.md                   # 说明文件
主要功能 (Main Features)
飞船移动：玩家可以使用箭头键上下左右移动飞船。

射击功能：玩家可以使用空格键射击子弹。

外星人：游戏生成外星人，玩家需要射击它们。

记分系统：根据玩家击中的外星人数量进行计分。

多关卡：每次击败所有外星人后，进入下一关卡，游戏难度增加。

Spaceship Movement: Players can move the spaceship up, down, left, and right using arrow keys.

Shooting Function: Players can shoot bullets using the spacebar.

Aliens: The game generates aliens that players need to shoot.

Scoring System: Players score points based on the number of aliens hit.

Multiple Levels: After defeating all aliens, players advance to the next level, increasing the game's difficulty.

修改记录 (Changelog)
增加了飞船的上下移动功能。

完善了 README 文件。

Added vertical movement for the spaceship.

Improved the README file.

贡献 (Contributing)
欢迎提交问题和合并请求。

Feel free to submit issues and pull requests.

许可 (License)
本项目基于 MIT 许可。

This project is licensed under the MIT License.