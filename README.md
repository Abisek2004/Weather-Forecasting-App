
# 🌦 Weather Forecast with AI

An interactive, dark-themed weather forecasting app built using **Streamlit**. It provides real-time weather updates, a 5-day forecast, AI-generated weather summaries via Hugging Face, forecast charts, and downloadable PDF reports — all styled with custom visuals.

![App Screenshot](https://user-images.githubusercontent.com/your-app-screenshot.png)

---

## 🔍 Features

- 🌤 Real-time **current weather** and **5-day forecast**
- 💬 **AI weather summary** powered by Hugging Face (Zephyr)
- 📊 **Matplotlib temperature chart** for easy understanding
- 📄 **Forecast PDF download** option
- 🌙 **Dark-themed UI** for modern aesthetics
- 🎯 Fully responsive layout for all screen sizes

---

## 🚀 Live Demo

🔗 Coming soon: Deployed via [Streamlit Cloud](https://streamlit.io/cloud)

---

## 🧰 Tech Stack

- **Python 3.10+**
- **Streamlit**
- **OpenWeatherMap API**
- **Hugging Face Inference API**
- **Matplotlib**
- **FPDF**

---

## 🔐 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Abisek2004/Weather-Forecasting-App.git
cd Weather-Forecasting-App
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Add Your API Keys Securely

Create a `.streamlit/secrets.toml` file with the following content:

```toml
OPENWEATHER_API_KEY = "your_openweathermap_api_key"
HUGGINGFACE_API_KEY = "your_huggingface_api_key"
```

> ✅ If deploying to [Streamlit Cloud](https://streamlit.io/cloud), add these keys under **Settings → Secrets**

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## ☁️ Deployment Instructions

1. Push the project to your GitHub repository
2. Visit [Streamlit Cloud](https://streamlit.io/cloud)
3. Click **New App**
4. Select your repo and branch
5. Under **Settings > Secrets**, add your API keys
6. Click **Deploy** 🚀

---

## 📸 Screenshots

| Weather UI | Forecast Chart | AI Summary |
|------------|----------------|------------|
| ![weather](https://via.placeholder.com/250) | ![chart](https://via.placeholder.com/250) | ![ai](https://via.placeholder.com/250) |

---

## 🪪 License

Licensed under the [MIT License](LICENSE)

---

## 👨‍💻 Developed By

**Abishek**  
📫 [GitHub](https://github.com/Abisek2004)  
🎓 B.Tech (Information Technology), DMI College of Engineering  
💡 Passionate about Python, AI/ML, and Full-Stack Development

---

## 🙌 Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/)
- [Hugging Face](https://huggingface.co/)
- [Streamlit](https://streamlit.io/)
- [Matplotlib](https://matplotlib.org/)
