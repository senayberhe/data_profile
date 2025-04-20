# 📊 Streamlit Data Profiler App

Welcome to the **Streamlit Data Profiler** — a powerful, interactive web app built with **Streamlit** and **YData Profiling** to help you **quickly explore and understand your datasets**.

---

## 🚀 Features

✅ Upload `.csv` or `.xlsx` files (up to 10 MB)
✅ Choose sheets from Excel files
✅ Generate **automated profiling reports** with beautiful statistics
✅ Toggle between minimal and full reports
✅ Use different display modes: Default, Dark, or Orange
✅ Fully interactive and browser-based — no setup needed by end users

---

## 📸 Screenshots

![App Screenshot](https://streamlit.io/images/brand/streamlit-logo-primary-colormark-darktext.png)
*Live screenshot or deploy your own for a preview!*

---

## 🧠 How It Works

1. Upload your dataset (`.csv` or `.xlsx`) using the left sidebar
2. Choose minimal or full profiling mode
3. Select Excel sheets if applicable
4. Let the app generate an in-depth report using **ydata-profiling**
5. Scroll, explore, and download insights!

---

## 📂 Folder Structure


---

## 💻 Run Locally

```bash
# Create a new environment
conda create -n data_profiler_env python=3.11
conda activate data_profiler_env

# Install required packages
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py

