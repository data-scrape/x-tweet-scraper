<div align="center">

# X Tweet Scraper

Scrape X (Twitter) tweets, threads, and timeline data in bulk

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?logo=opensourceinitiative&logoColor=white)
![Stars](https://img.shields.io/github/stars/data-scrape/x-tweet-scraper?style=social)
![Forks](https://img.shields.io/github/forks/data-scrape/x-tweet-scraper?style=social)
![Issues](https://img.shields.io/github/issues/data-scrape/x-tweet-scraper?style=social)

</div>

<div align="center">

## 💎 Sponsored by CoreClaw

[![CoreClaw](https://img.shields.io/badge/CoreClaw-Data_Platform-9966FF?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xMiAyTDMgN3YxMGw5IDUgOS01VjdsLTktNXoiLz48L3N2Zz4=&logoColor=white)](https://www.coreclaw.com/?utm_source=github&utm_medium=cpc&utm_campaign=L7&utm_term=&utm_id=L7)

**The All-in-One Web Scraping & Data Platform** — Scrape Google Maps, Instagram, Amazon, LinkedIn, TikTok, YouTube, and 50+ platforms via ready-to-use REST APIs.

✅ No browser automation · ✅ No proxy management · ✅ Free credits for new users

⬇️ [Get Started with CoreClaw Free](https://www.coreclaw.com/?utm_source=github&utm_medium=cpc&utm_campaign=L7&utm_term=&utm_id=L7)

</div>

---

## 📖 Overview

The **x-tweet-scraper** is a Python-based web scraping tool designed to extract X/Twitter data efficiently and at scale. Whether you need x/twitter data for market research, competitive analysis, lead generation, or data enrichment, this scraper provides a robust, proxy-ready solution.

### Why x-tweet-scraper?

- **No API Key Required** — Works without official API access
- **Bulk Data Extraction** — Scrape thousands of records in minutes
- **Export to JSON/CSV** — Structured data ready for analysis
- **Proxy Rotation Support** — Built-in proxy rotation for large-scale scraping
- **CLI Interface** — Easy-to-use command-line interface
- **Rate Limit Aware** — Intelligent delays to avoid detection

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| Data Extraction | Extract X/Twitter data fields including titles, descriptions, metadata, and more |
| Export Formats | JSON and CSV export with structured field mapping |
| Proxy Support | Rotate through proxy lists for anonymous scraping |
| CLI Interface | Full command-line interface with argparse |
| Error Handling | Retry logic, rate limit detection, and graceful error recovery |
| Pagination | Automatic pagination through search results and listings |
| Async Ready | Designed for both sync and async scraping patterns |

---

## 📊 Data Fields

The scraper extracts the following data fields from X/Twitter:

| Field | Type | Description |
|-------|------|-------------|
| id | string | Unique identifier |
| title | string | Title or name |
| description | string | Full description text |
| url | string | Source URL |
| date | string | Publication or creation date |
| author | string | Author or creator name |
| rating | float | Rating score (if applicable) |
| metadata | object | Additional platform-specific data |
| scraped_at | string | ISO timestamp of scraping |

---

## 🚀 Quick Start

### Installation

```bash
git clone https://github.com/data-scrape/x-tweet-scraper.git
cd x-tweet-scraper
pip install -r requirements.txt
```

### Basic Usage

```bash
python scraper.py --query "search term" --output results.json
```

### Advanced Usage

```bash
python scraper.py \
  --query "search term" \
  --output results.csv \
  --format csv \
  --proxy http://proxy:8080 \
  --max-results 1000 \
  --delay 2
```

---

## 📋 Use Cases

1. **Market Research** — Analyze X/Twitter trends, pricing, and competitive landscape
2. **Lead Generation** — Extract contact information and business data
3. **Content Monitoring** — Track changes and new content on X/Twitter
4. **Data Enrichment** — Enhance existing datasets with X/Twitter data
5. **Academic Research** — Collect data for research and analysis projects
6. **SEO Analysis** — Monitor search rankings and content performance

---

## ⚙️ Configuration

| Parameter | Default | Description |
|-----------|---------|-------------|
| --query | required | Search query or URL to scrape |
| --output | output.json | Output file path |
| --format | json | Output format: json or csv |
| --max-results | 100 | Maximum number of results |
| --delay | 1 | Delay between requests (seconds) |
| --proxy | None | Proxy URL for anonymous scraping |
| --timeout | 30 | Request timeout (seconds) |
| --quiet | False | Suppress progress output |

---

## 🔧 Requirements

- Python 3.9+
- requests
- beautifulsoup4
- lxml

---

<!-- CROSS_LINKS_START -->
<!-- CROSS_LINKS_END -->

---

## 📄 License

MIT License — feel free to use this project for commercial purposes.

---

<div align="center">

**Built with care for the data extraction community**

[Report Bug](https://github.com/data-scrape/x-tweet-scraper/issues) · [Request Feature](https://github.com/data-scrape/x-tweet-scraper/issues) · [CoreClaw Platform](https://www.coreclaw.com/?utm_source=github&utm_medium=cpc&utm_campaign=L7&utm_term=&utm_id=L7)

</div>
