# 🩺 Medical Appointment Scheduling Application with REST APIs

This repository contains the implementation of a **medical appointment scheduling application** based on **REST APIs**, with a focus on **patient registration**.

✅ The application architecture consists of **two REST APIs**:  
- One responsible for the **model layer**  
- Another responsible for **data persistence and data retrieval**

👩🏻 The **user** sends **insert** or **list** requests to the model API, which then forwards the request to the corresponding **endpoint** of the data persistence and query API.

📋 The application was developed using the **Python** programming language, and **data persistence and retrieval** are performed using **JSON files**.

---

## ⚙️ Features

- 📋 Insert and list patient records  
- 🔁 Communication between REST APIs to ensure separation of responsibilities  
- 💾 Data persistence using **JSON files**

---

## 🛠️ Technologies Used

- Python 🐍  
- FastAPI for building REST APIs 🚀  
- JSON files for data persistence 📄 
