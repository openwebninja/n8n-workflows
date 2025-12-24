# Google Maps Business Scraper – n8n Workflow

Automate Google Maps business data extraction using n8n and the OpenWebNinja API.

---

## Overview

This repository provides a ready-to-use **n8n workflow** that extracts **local business data from Google Maps**
based on a location and keyword.

The workflow returns:
- Business name  
- Phone number  
- Email address (when available)

Instead of using browser scraping or the official Google Maps API, this workflow relies on the
**OpenWebNinja Local Business Data API**, making it faster, simpler, and more automation-friendly.

This project is designed for **developers, builders, and marketers** who want scalable
**lead generation and business data enrichment**.

---

## What This Workflow Does

1. Accepts a **location / address** and a **search keyword**
2. Queries Google Maps business listings via OpenWebNinja API
3. Extracts structured business contact data
4. Outputs clean results ready for automation (CRM, Sheets, outreach tools)

---

## Common Use Cases

- Local lead generation
- Sales prospecting
- Marketing automation
- CRM enrichment
- Agency workflows
- Market research
- No-code / low-code scraping projects

---

## Google Maps API – Important Note

Many users search for **Google Maps API** solutions to extract business data.

This workflow provides a **practical alternative to the official Google Maps API**.

Instead of dealing with Google Maps API quotas, billing complexity, and setup limitations,
this n8n workflow retrieves **Google Maps business data via the OpenWebNinja API**.

It is especially useful for:
- Google Maps API alternatives
- Google Maps API–style business data extraction
- Lead generation without official API limitations

---

## Powered by OpenWebNinja API

This workflow uses the **OpenWebNinja Local Business Data API** to retrieve Google Maps business data.

Why OpenWebNinja:
- API-first (no browser scraping)
- Clean, structured results
- Built for automation tools like n8n
- Easy to scale

API documentation:
👉 https://www.openwebninja.com/api/local-business-data

---

## Requirements

- n8n (self-hosted or cloud)
- OpenWebNinja API key

No headless browsers. No proxies. No scraping scripts.

---

## How to Use

1. Import the workflow JSON into n8n
2. Add your OpenWebNinja API key to the HTTP Request node
3. Set the following inputs:
   - Location / address
   - Search keyword (e.g. "dentist", "restaurant", "real estate")
4. Run the workflow
5. Use the output in your next automation step

---

## Example Input

**Location:**  
Lisbon, Portugal  

**Keyword:**  
Real estate agency  

---

## Example Output

- Business Name: ABC Realty  
- Phone: +351 21 000 0000  
- Email: info@abcrealty.pt  

---

## Who This Workflow Is For

- Developers building automation pipelines
- No-code / low-code builders
- Growth marketers
- Sales teams
- Agencies
- Anyone using n8n for business data automation

---

## Keywords

n8n workflow, Google Maps scraper, Google Maps API alternative, Google Maps business data,
local business leads, lead generation automation, OpenWebNinja API,
marketing automation, no-code scraping, low-code workflows

---

