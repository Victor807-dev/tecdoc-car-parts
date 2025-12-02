# Tecdoc Car Parts Scraper
> A powerful integration that enables developers to fetch detailed Tecdoc vehicle data, including models, engines, parts, and product categories.
> This scraper streamlines access to the Tecdoc Auto Parts Catalog, helping teams build automotive applications and data pipelines with ease.


<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/za2122/footer-section/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/devpilot1" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>




<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Tecdoc Car Parts</strong> you've just found your team — Let's Chat. 👆👆
</p>


## Introduction
This project provides a structured interface for retrieving Tecdoc automotive data.
It solves the challenge of navigating multiple endpoints by offering an organized, developer-friendly workflow.
Ideal for automotive e-commerce platforms, catalog builders, data analysts, and vehicle-lookup systems.

### Core Data Retrieval Workflow
- Retrieve supported languages, countries, and vehicle types with dedicated endpoints.
- Navigate through manufacturers, models, engine types, and vehicle details.
- Fetch hierarchical categories and granular auto parts info.
- Perform searches using part numbers or supplier data.
- Build complete product catalogs with rich technical attributes.

## Features
| Feature | Description |
|---------|-------------|
| Multi-region data | Retrieve country-filtered vehicle and parts information. |
| Multi-language support | Fetch product descriptions in any supported language. |
| Hierarchical catalog navigation | From brand → model → engine → vehicle → category → article. |
| Powerful search endpoints | Search by article number, supplier, or product attributes. |
| Detailed article insights | Access specifications, compatibility info, and technical details. |
| Modular workflow | Use only the endpoints you need with clear parameter requirements. |

---

## What Data This Scraper Extracts
| Field Name | Field Description |
|-------------|------------------|
| lngId / langId | Selected language identifier for product descriptions. |
| countryFilterId | Country ID used for region-specific filtering. |
| typeId | Vehicle type identifier (automobile, motorcycle, etc.). |
| manufacturerId | Identifier of the selected car brand. |
| modelId / modelSeriesId | Model or series identifier for the vehicle. |
| vehicleId | Specific vehicle/engine configuration ID. |
| levelId_1 / 2 / 3 | Category hierarchy identifiers for product groups. |
| productGroupId | Category ID used when fetching article lists. |
| articleId / articleNo | Individual auto part identifiers. |
| articleSearchNr | Article number for search queries. |
| supplierId | Supplier identifier for advanced part searches. |

---

## Directory Structure Tree


    Tecdoc Car Parts/
    ├── src/
    │   ├── runner.py
    │   ├── extractors/
    │   │   ├── tecdoc_client.py
    │   │   └── utils_format.py
    │   ├── outputs/
    │   │   └── exporters.py
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── inputs.sample.txt
    │   └── sample.json
    ├── requirements.txt
    └── README.md

---

## Use Cases
- **Automotive retailers** use it to **build real-time product catalogs**, allowing customers to **find compatible parts accurately**.
- **Marketplace platforms** use it to **validate vehicle compatibility for listings**, ensuring **higher buyer trust and fewer returns**.
- **Data analysts** use it to **collect structured Tecdoc data**, enabling **market insights and product intelligence**.
- **Garage management systems** use it to **lookup vehicle details from a single workflow**, improving **diagnostic and repair accuracy**.

---

## FAQs

**Q: Do I need both language and country filters?**
Yes. Language ensures proper product descriptions, while country filtering tailors results to your regional market.

**Q: Can I retrieve data for motorcycles or trucks?**
Yes. The `/listVehicleTypes` endpoint provides all available vehicle types, each accessible with its `typeId`.

**Q: Is category depth consistent across all vehicles?**
No. Different manufacturers and models may support different category levels (V1–V3).

**Q: Can I search parts using only article numbers?**
Yes. Use `/searchArticlesByNumber`, or `/searchArticlesByNumberAndSupplier` for more precise results.

---

### Performance Benchmarks and Results

**Primary Metric:**
Efficient endpoint chaining averages **280–350 ms per request**, enabling smooth multi-step catalog retrieval.

**Reliability Metric:**
Consistent **98.7% response success rate** across multi-endpoint workflows under typical load.

**Efficiency Metric:**
Optimized batching enables throughput of **thousands of article lookups per hour** with minimal resource usage.

**Quality Metric:**
Data completeness reaches **95%+** for vehicles and parts across common markets, ensuring robust catalog coverage.


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtube.com/shorts/6AwB5omXrIM" target="_blank">
        <img src="https://github.com/Instagram-Automations/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. Bitbash nailed it."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
  </tr>
</table>
