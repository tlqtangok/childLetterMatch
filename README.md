# childLetterMatch
一个适合中国5岁儿童学习26个英文字母的互动匹配游戏

A child-friendly letter matching game designed for Chinese 5-year-olds to learn the 26 English letters.

## 功能特点 / Features

- 🎨 **可爱活泼的界面** - 采用柔和渐变背景、卡通风格卡片和星星装饰
- 🔤 **大小写字母匹配** - 左侧显示大写字母，右侧显示打乱顺序的小写字母
- 🎲 **随机选择** - 每轮从26个字母中随机选取3个进行匹配
- 🔊 **发音功能** - 点击卡片播放"大写/小写 + 字母读音"
- ✏️ **连线匹配** - 点击左侧大写字母，再点击右侧对应小写字母进行连线
- ✅ **自动校验** - 连线完成后自动检查，正确显示鼓励语，错误显示红色叉叉
- 🔄 **自动循环** - 成功后依次读出字母发音，3秒后自动开始新游戏
- 📱 **移动端优化** - 禁用Safari双击缩放，防止误操作

## 如何使用 / How to Use

1. 直接在浏览器中打开 `index.html` 文件
2. 点击左侧的大写字母卡片，会播放"大写X"的发音
3. 再点击右侧匹配的小写字母卡片进行连线
4. 完成所有3条连线后，系统自动校验
5. 全部正确则播放鼓励语和字母发音，然后自动开始新游戏
6. 如有错误会显示红色叉叉，可重新尝试

## 技术栈 / Tech Stack

- HTML5
- CSS3 (渐变、动画、Flexbox布局)
- JavaScript (Web Speech API 语音合成)
- Canvas (连线绘制)

## 截图 / Screenshots

![Game Screenshot](https://github.com/user-attachments/assets/97bdd627-1862-4d26-998c-cc5392aed3a3)

## 许可证 / License

MIT License
