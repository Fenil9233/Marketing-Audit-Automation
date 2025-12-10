# 📘 Property Management Marketing Audit & Reporting Automation System

This project is an end-to-end automated marketing audit system built using **n8n**, **Apify**, **Google APIs**, and **Gemini AI**. It analyzes any property management business website and automatically generates a detailed audit report with performance scores, strengths, weaknesses, and actionable recommendations.

The workflow eliminates manual research by integrating multiple scraping, analytics, and AI components—delivering a ready-to-share audit report directly into Google Sheets and Google Docs.

---

## 🚀 Key Capabilities

### ✅ 1. Automated Data Collection
The system gathers required marketing and business data from multiple sources:

- **Website HTML Scraping** (tech stack, metadata, content signals)
- **Google PageSpeed API** (performance metrics, Core Web Vitals)
- **Apify Actors** for:
  - Company research (business details, contacts, social links)
  - Google Maps reviews (ratings, reviews, reply rate)
- **HTML extraction** for address, email, phone, hours, website
- **SEO keyword visibility** via Apify datasets
- **Tech detection** (GTM, GA4, FB Pixel, chat widgets, Ads pixels)

---

## ⚙️ 2. Comprehensive Data Aggregation

All raw data from APIs and scrapers is merged and normalized using:

- Combine Nodes  
- Custom Code Nodes  
- Structured parsing logic  

This ensures full, consistent audit data even with partial or missing sources.

---

## 🧮 3. Automated Category Scoring Engine

A dynamic scoring algorithm evaluates performance across **six critical categories**:

1. Business Details Completeness  
2. Tech Stack & Tracking Infrastructure  
3. Google Business Profile Quality  
4. Online Reputation & Reviews  
5. Website Performance & Speed  
6. SEO Visibility & Keyword Rankings  

Each category receives a **0–100 score**, followed by a weighted **Overall Marketing Health Score**.

---

## 🤖 4. AI-Powered Audit Report Generation (Gemini)

The aggregated data is passed to **Gemini AI**, which:

- Generates a full **executive summary**  
- Highlights **strengths & weaknesses**  
- Identifies **critical alerts**  
- Creates **specific, actionable recommendations**  
- Classifies performance levels (Excellent → Worse)  
- Returns structured results in JSON  

This ensures every audit report is clean, accurate, and formatted professionally.

---

## 📄 5. Automated Report Publishing

Final audit results are automatically written to:

- **Google Sheets** — raw data, extracted fields, scores  
- **Google Docs** — formatted audit report with summaries & insights  

Perfect for sharing with clients, teams, or marketing analysts.

---

## 🧩 6. Modular Workflow Architecture

The workflow uses fully modular components:

- Chat Trigger  
- Domain Extractor  
- Workflow Configuration  
- Website Scraper  
- Performance Fetcher  
- Review Scrapers  
- SEO Analyzer  
- Audit Data Merger  
- Scoring Engine  
- Gemini AI Report Generator  
- Google Sheets/Docs Writers  

Each module can be updated or replaced independently.

---

## 🔄 7. Fully Automated Execution Pipeline

Once a user submits a website URL:

1. Domain is extracted  
2. Scrapers and APIs run automatically  
3. Data is normalized and aggregated  
4. Scores are calculated  
5. Gemini generates the full audit  
6. Google Docs & Sheets are updated  

Zero manual input required.

---

## 🎯 Project Purpose

Ideal for:

- Digital Marketing Agencies  
- Property Management Marketing Teams  
- SEO Analysts & Performance Consultants  
- Audit Automation Platforms  
- Sales & Lead Generation Tools  
