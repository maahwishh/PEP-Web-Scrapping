## 🧾 South African PEPs Dataset – Real Data Collection Project
This project involved the live extraction and structuring of data related to South African Politically Exposed Persons (PEPs). Designed for use in compliance, research, and data enrichment, it provides a high-quality dataset built through ethical web scraping practices.

### 🔍 Background
The objective was to collect real-time, publicly available data on South African PEPs from trusted online sources. Data was extracted directly from official government websites, credible news portals, and political party platforms, ensuring the dataset reflects both formal positions and media narratives.

### 🛠️ Methodology
1. Source Identification
   Only verified and high-quality .za domains were included. Low-authority or irrelevant sources were excluded through manual vetting.
   To ensure accuracy and diverse coverage, sources were selected from three key categories:

- Government Websites
Examples: gov.za, presidency.gov.za, dirco.gov.za
Content: Official roles, appointments, department structures.

- News Outlets
Examples: news24.com, mg.co.za, timeslive.co.za, iol.co.za
Content: Reports on political activity, controversies, public appearances.

- Political Party Platforms
Examples: da.org.za, effonline.org
Content: Party leadership bios, policies, statements, and campaigns.

2. Data Scraping and Structuring
   A total of 1,300+ real entries were collected, offering a comprehensive, diverse dataset of South African PEPs.
Python-based scraping scripts were used to extract structured information from the selected domains:

- PEP Name & Role: Extracted from page content and headings, with context on their political designation (e.g., President, Minister, Mayor).
- Source URL: Direct page links were captured and logged.
- Page Title & Snippet: Actual metadata and content snippets were scraped for context.
- Source Type Classification: Each source was categorized (Government, News, Political Party).

3. Relevance and Quality Assurance\
Spot Checks: Random manual reviews ensured accuracy and logical consistency.
To maintain high data quality and compliance alignment:

- Geographic Filtering: Only South African (.za) domains were scraped.
- Role Validation: PEPs matched FATF and World Bank role criteria.
- Domain Vetting: All domains manually reviewed before scraping.
- Content Verification: Duplicate entries were removed; varied templates ensured content diversity.

💡 Key Insights
- Government domains provided reliable, up-to-date info on official roles.
- News outlets enriched the dataset with narratives, context, and controversy tracking.
- Party websites helped identify political alignment, speeches, and campaign information.
- The result is a well-balanced dataset suitable for AML systems, academic research, and compliance pipelines.
