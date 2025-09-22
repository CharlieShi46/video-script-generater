# video-script-generater
# 🎬 Video Script Generator | 视频脚本生成器

This project is a **Streamlit app** that helps you generate engaging short video scripts using OpenAI’s API and Wikipedia knowledge.  
本项目是一个基于 **Streamlit** 的应用，利用 **OpenAI API** 和维基百科信息，帮助你快速生成有趣的短视频脚本。

---

## 🚀 Features | 功能介绍

- Generate **catchy video titles** with AI  
  使用 AI 自动生成 **吸引人的视频标题**  
- Create **structured video scripts** (Opening, Middle, Ending)  
  生成包含 **开头、中间、结尾** 的完整视频脚本  
- Integrate **Wikipedia search results** as background reference  
  自动结合 **维基百科搜索结果** 作为参考信息  
- Simple and interactive **Streamlit UI**  
  提供简洁易用的 **Streamlit 界面**

---

## 🛠️ Installation | 安装步骤

1. Clone the repository  
   克隆项目代码：
   ```bash
   git clone https://github.com/your-repo/video-script-generator.git
   cd video-script-generator

2. Install dependencies
   pip install -r requirements.txt

3. Run the Streamlit app
   streamlit run main.py

## How to use

🔑 How to Use | 使用方法
	1.	Open the app in your browser (default: http://localhost:8501)
在浏览器中打开应用（默认地址：http://localhost:8501）
	2.	Enter your OpenAI API Key in the sidebar
在侧边栏输入你的 OpenAI API 密钥
	3.	Input the video subject (主题), select video length (时长), and adjust creativity (创造力参数)
输入 视频主题，选择 视频时长，并调整 创造力滑块
	4.	Click Generate Script to get your title and script
点击 生成脚本 按钮，即可得到 标题和脚本

## Structure 
  📦 video-script-generator
 ┣ 📜 main.py              # Streamlit app entry point | Streamlit 应用入口
 ┣ 📜 utils.py             # Script generation logic with OpenAI + Wikipedia | 脚本生成逻辑
 ┣ 📜 requirements.txt     # Dependencies | 依赖列表
 ┗ 📜 README.md            # Project documentation | 项目说明

## Notes
⚠️ Notes | 注意事项
	•	You must have a valid OpenAI API Key
需要一个有效的 OpenAI API 密钥
	•	Wikipedia content is only used as reference, not copied directly
维基百科搜索内容仅作为 参考信息，不会被直接照搬
	•	Video script length roughly follows your input duration
脚本长度会大致遵循你输入的视频时长
