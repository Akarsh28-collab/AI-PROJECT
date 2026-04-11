# 💼 Fake Jobs Scraper (Web Scraping Project)

This is a beginner-friendly web scraping project built using Python.
It extracts job listings from a demo job portal and stores them in a structured format.

---

## 🚀 Project Overview

The script scrapes job data from:

👉 https://realpython.github.io/fake-jobs/

It collects important details like:

* 🧑‍💻 Job Title
* 🏢 Company Name
* 📍 Location
* 📅 Date Posted

---

## 🛠️ Tech Stack

* Python
* Requests
* BeautifulSoup (bs4)
* Pandas

---

## 📂 Output

The scraped data is stored in a CSV file:

```bash
jobs_data.csv
```

---

## ⚙️ How It Works

1. Sends a request to the website using `requests`
2. Parses HTML using `BeautifulSoup`
3. Extracts job data using HTML tags and classes
4. Stores data in lists
5. Converts data into a Pandas DataFrame
6. Exports the data as a CSV file

---

## 📸 Sample Output

| Role             | Company  | Location | Date       |
| ---------------- | -------- | -------- | ---------- |
| Python Developer | XYZ Corp | Remote   | 2024-01-01 |

---

## 📚 Learning Outcomes

* Understanding HTML structure
* Using `find()` and `find_all()`
* Working with real-world webpage layouts
* Data cleaning and structuring
* Creating DataFrames using Pandas

---

## ⚠️ Note

This project is for learning purposes only.
The website used is a demo site created specifically for web scraping practice.

---

## 👨‍💻 Author

**Akarsh Pratap Singh**

---

✨ This project is part of my AI & Data Science learning journey.
