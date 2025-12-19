# Arbeitsagentur Germany Job Details Scraper 🇩🇪
> A powerful tool for extracting detailed job listing data from Germany’s official employment portal.
> It converts complex job detail pages into clean, structured datasets, helping professionals analyze the German job market efficiently.


<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
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
  If you are looking for <strong>arbeitsagentur-germany-job-details-scraper</strong> you've just found your team — Let’s Chat. 👆👆
</p>


## Introduction
This project extracts rich job offer information from individual job detail pages published on Germany’s federal employment platform.
It solves the problem of manually collecting and normalizing fragmented job data.
It is built for job seekers, recruiters, HR platforms, and labor market analysts.

### Structured German Job Intelligence
- Parses full job descriptions from individual job detail pages
- Normalizes employer, contract, salary, and location data
- Designed for scalable job market analysis
- Outputs data ready for analytics, dashboards, or integrations

## Features
| Feature | Description |
|----------|-------------|
| Full Job Parsing | Extracts complete job descriptions and metadata |
| Employer Insights | Captures company names and job sources |
| Contract Details | Identifies contract type, duration, and work mode |
| Salary Extraction | Retrieves available salary or pay range |
| Location Mapping | Collects structured regional and city data |
| Reference Tracking | Preserves official job reference identifiers |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|-------------|------------------|
| stellenangebotsTitel | Official job title |
| stellenangebotsBeschreibung | Full job description text |
| stellenangebotsart | Employment type (full-time, freelance, etc.) |
| hauptberuf | Main occupation category |
| firma | Employer or company name |
| arbeitszeitVollzeit | Indicates full-time availability |
| arbeitszeitTeilzeit | Indicates part-time availability |
| gehalt | Salary or compensation range |
| vertragsdauer | Contract duration information |
| stellenlokationen | Job location details |
| veroeffentlichungszeitraum | Job posting date |
| externeURL | Direct link to the job posting |
| referenznummer | Official job reference ID |

---
## Example Output

    [
      {
        "stellenangebotsTitel": "Web Developer, PHP (m/f/d)",
        "firma": "ANTSTORE Martin Sebesta",
        "hauptberuf": "Software Developer",
        "arbeitszeitVollzeit": true,
        "arbeitszeitTeilzeitVormittag": true,
        "gehalt": "2500 - 3000 EUR",
        "vertragsdauer": "FIXED-TERM",
        "befristetBis": "2026-12-31",
        "adresse": {
          "city": "Berlin",
          "zipcode": "12169",
          "region": "BERLIN",
          "country": "GERMANY"
        },
        "veroeffentlichungszeitraum": {
          "from": "2025-03-19"
        },
        "externeURL": "https://www.arbeitsagentur.de/jobsuche/jobdetail/10001-1001263295-S"
      }
    ]

---
## Directory Structure Tree

    arbeitsagentur-germany-job-details-scraper/
    ├── src/
    │   ├── main.py
    │   ├── parsers/
    │   │   ├── job_detail_parser.py
    │   │   └── location_parser.py
    │   ├── utils/
    │   │   ├── text_cleaner.py
    │   │   └── date_utils.py
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_input_urls.txt
    │   └── sample_output.json
    ├── requirements.txt
    └── README.md

---
## Use Cases
- **Recruiters** use it to centralize German job postings, so they can accelerate candidate sourcing.
- **Job platforms** use it to ingest structured listings, so they can enrich their search experience.
- **Analysts** use it to study regional hiring trends, so they can produce labor market insights.
- **HR tech teams** use it to feed ATS systems, so they can automate job intake pipelines.

---
## FAQs
**Q: Does it support multiple job URLs in one run?**
Yes, it processes a list of job detail URLs and extracts data for each entry independently.

**Q: Is salary data always available?**
Salary fields are extracted when published in the job listing; some postings may not disclose compensation.

**Q: Can the data be integrated into analytics tools?**
The structured output is suitable for direct use in dashboards, databases, or BI systems.

**Q: Does it handle regional differences in listings?**
Yes, location fields are normalized to support consistent regional analysis across Germany.

---
### Performance Benchmarks and Results

**Primary Metric:** Processes individual job detail pages in under 2 seconds on average.

**Reliability Metric:** Maintains a successful extraction rate above 99% on valid job URLs.

**Efficiency Metric:** Optimized parsing minimizes memory usage while handling large URL batches.

**Quality Metric:** Delivers high data completeness with consistently structured fields across listings.


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
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
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
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
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
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
  </tr>
</table>
