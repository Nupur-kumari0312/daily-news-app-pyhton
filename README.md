# 📰 Daily News App (Python)

A simple desktop application built using Python that fetches and displays the latest news headlines using the NewsAPI. The app provides an interactive GUI to browse news articles with images and links.

---

## 🚀 Features

* Fetches real-time news using NewsAPI
* User-friendly GUI built with Tkinter
* Displays news title, description, and image
* Navigation buttons (Next / Previous)
* Option to read full article in browser
* Secure API key handling using `.env`

---

## 🛠️ Tech Stack

* Python
* Tkinter (GUI)
* Requests (API calls)
* Pillow (Image handling)
* python-dotenv (Environment variables)

---

## 📂 Project Structure

```
daily-news-app-python/
│── News_GUI.py
│── README.md
│── .gitignore
│── .env (not uploaded to GitHub)
```

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/daily-news-app-python.git
cd daily-news-app-python
```

### 2. Install dependencies

```bash
pip install requests pillow python-dotenv
```

### 3. Get API Key

* Sign up at https://newsapi.org
* Copy your API key

### 4. Create `.env` file

Create a file named `.env` and add:

```
API_KEY=your_api_key_here
```

---

## ▶️ Run the Application

```bash
python News_GUI.py
```

---

## 🔐 Security Note

* API keys are stored in `.env`
* `.env` is added to `.gitignore` to prevent exposure

---

## 📸 Screenshots

(will be addded soon)

---

## 💡 Future Improvements

* Add category selection (sports, tech, etc.)
* Add search functionality
* Improve UI design
* Add dark/light mode

---

## 👩‍💻 Author

**Nupur Kumari**

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!

