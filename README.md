# 🕸️ GitHub Topics Web Scraper

A Python-based web scraping project that extracts the top repositories from [GitHub Topics](https://github.com/topics). For each topic (like `machine-learning`, `web-development`, `blockchain`, etc.), we collect the top 25 repositories along with details like repo name, owner, star count, and repository URL. The scraped data is saved in CSV format for easy analysis and visualization.

---

## 📌 Project Summary

This project demonstrates how to:

- Navigate a complex web structure (GitHub’s Topics page)
- Extract structured information using BeautifulSoup
- Modularize code for reusability
- Store real-world data into CSV files for further analytics

---

## 🧠 Why This Project?

GitHub is one of the largest repositories of open-source projects. Its Topics page offers a curated list of trending domains like AI, web development, and data science. This scraper helps you:

✅ Explore the most-starred projects by topic  
✅ Identify leading developers and tools in each space  
✅ Build datasets for GitHub trend analysis  
✅ Gain hands-on experience in real-world web scraping

---

## 📚 Learning Outcomes

By working on this project, you’ll learn:

- HTML parsing and traversal with BeautifulSoup
- Best practices for web scraping and response handling
- How to clean, transform, and structure scraped data
- Saving outputs using `pandas` into reliable CSVs
- Reusability and function encapsulation

---

## 🛠️ Tech Stack & Libraries

| Tool / Library     | Purpose                                |
|--------------------|----------------------------------------|
| `requests`         | To make HTTP requests to GitHub        |
| `BeautifulSoup`    | To parse and navigate HTML structure   |
| `pandas`           | To create structured data and CSVs     |
| `os` (optional)    | For folder handling and saving files   |
| `Jupyter Notebook` | Development and visualization          |

---

## 🧩 Workflow

### 🔍 Step 1: Scrape GitHub Topics Page
- URL: `https://github.com/topics`
- Extract:
  - ✅ Topic Title
  - ✅ Topic Description
  - ✅ Topic Page URL

### 🔍 Step 2: Scrape Top Repositories Per Topic
- Navigate to each topic’s page (e.g. `https://github.com/topics/machine-learning`)
- Extract for each repository:
  - ⭐ Repo Name
  - 👤 Owner / Username
  - 🌟 Number of Stars
  - 🔗 Repo URL

### 📥 Step 3: Save Output to CSV
- One CSV per topic
- Columns: `Repo Name`, `Username`, `Stars`, `Repo URL`
- Example row:
