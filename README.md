<p align="center">
  <img src="https://dummyimage.com/600x180/0b1220/ffffff&text=FusionProxy+Mini+Scraper" alt="FusionProxy Mini Scraper">
</p>

<h1 align="center" style="border-bottom: none;">
  FusionProxy Mini Scraper
</h1>

<p align="center">
  <em>A lightweight Python scraper that turns any webpage into clean, AI-ready data formats: JSON, Markdown, or HTML.</em>
</p>

<div align="center">

[![Python](https://img.shields.io/badge/python-3.9%2B-3776AB.svg)](#)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Tests](https://img.shields.io/badge/tests-pytest-brightgreen.svg)](#)
[![Style](https://img.shields.io/badge/style-PEP8-black.svg)](#)

</div>

---

## 📖 Overview

**FusionProxy Mini Scraper** is a simple but powerful tool for quickly scraping and cleaning content.  
It focuses on being **minimal, readable, and extendable**, making it perfect for learning, prototyping, or building your own scraping toolkit.

With just a few lines of code, you can:

- Fetch and parse **any webpage**  
- Extract **title**, **meta description**, and **main text**  
- Convert results into **JSON**, **Markdown**, or return raw **HTML**  
- Run it via **CLI** or as a **Python module**

---

## ✨ Key Features

<details>
<summary><strong> Minimal API & CLI</strong></summary>
<br>

- One main class: `MiniScraper`
- CLI for quick use:  
  ```bash
  python -m src.fusionproxy_scraper https://example.com --mode json
