<!-- Project Header -->
<h1 align="center">🚀 Pinak Demo Task — Web Scraping + Django REST API</h1>

<p align="center">
  <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="120px">
</p>

<p align="center">
  <b>Completed by:</b> Himanshu Anand  
  <br>
  <b>Under Guidance of:</b> Bhaskar Sir (Recruiter, Pinak Venture)  
  <br>
  <b>Technologies:</b> Python | Django REST Framework | Web Scraping | Pandas | BeautifulSoup  
</p>

---

## 📋 Project Overview
This project was developed as part of the **Pinak Venture Demo Task** under the guidance of **Bhaskar Sir**.  
It demonstrates both **web scraping** and **API development** using Django REST Framework.

### ✅ Includes:
- Web Scraper that fetches **IBPS job listings**
- Extracts:  
  🔹 Job Title  
  🔹 Location  
  🔹 Publish Date  
  🔹 Detail Page Link  
- Saves the extracted data into a **CSV file** using Pandas.

---

## ⚙️ Django REST API
Implements a **login authentication system** using Django REST Framework.

### API Endpoint:
**POST →** `/api/login/`  
**Request Body:**
```json
{
  "username": "testuser",
  "password": "Test@1234"
}
