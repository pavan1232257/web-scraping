Automated Web Crawler for Domain-Specific Knowledge Bases

# Appian Knowledge Base URL Scanner

This repository contains a Python-based tool designed to scan and crawl URLs listed under Appian's knowledge base. It reads from an input Excel file and multiple domain-specific `.txt` files, then processes each site to extract internal links or downloadable content like PDFs.

---

## 📂 Folder Structure

Appian/
└── knowledge_base/
└── site_mapping/
├── input.xlsx # Contains row-wise metadata or mappings (e.g., domain names)
├── 01_appian_urls.txt # List of URLs for Appian
├── 02_otherdomain_urls.txt # Additional URL sets for other domains
└── ...

yaml
Copy
Edit

---

## 🎯 Features

- Reads metadata from `input.xlsx`
- Parses and processes multiple `*_urls.txt` files
- Crawls listed URLs to extract:
  - Internal HTML links
  - PDF download links
- Writes outputs to `.csv` or `.xlsx` formats
- Logs errors and visited pages
- Can run on **Google Colab** with access to **Google Drive**

---

## ⚙️ Technologies Used

- Python 3.x
- pandas
- openpyxl
- requests
- BeautifulSoup (bs4)
- Google Colab (for remote/cloud use)
- Optional: Google Drive API (if using Drive programmatically)

---

## 🚀 Getting Started

### 1. Clone the Repository

📦 Tech Stack
Google Cloud Platform (GCP)	Cloud and Service Account Management
Google Drive API	Read and write files in Google Drive
Python	Core logic and scripting
BeautifulSoup (bs4)	HTML parsing to extract links
Requests	HTTP requests to websites
Google Colab (optional)	Development and testing environment
📝 Usage
Place your input.xlsx and *_urls.txt files in the site_mapping/ folder.

Open the notebook WS_2_.ipynb in Jupyter or Google Colab.

Run all cells to begin processing the URLs.

Output files (e.g., internal_links.csv, pdf_links.csv) will be saved automatically.

📊 Sample Outputs
internal_links_appian.csv

pdf_links_by_domain.xlsx

crawl_log.txt

🧠 Use Cases
Link validation for documentation teams

Extracting downloadable whitepapers or PDFs

Monitoring changes in Appian knowledge base

Internal crawling for site mapping

📬 Contact
Maintained by: Your Name
📫 Email: your.email@example.com
💼 LinkedIn: your-linkedin-profile

🛡️ License
This project is licensed under the MIT License - see the LICENSE file for details.

yaml
Copy
Edit

---

Would you like me to generate this as an actual `README.md` file and include it in a GitHu
