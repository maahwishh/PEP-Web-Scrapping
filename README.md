## 🧾 South African PEPs Dataset Simulation
This project presents a domain-driven, simulated dataset generation framework focused on South African Politically Exposed Persons (PEPs). Built for research, compliance testing, and data enrichment use cases, it demonstrates a scalable and ethical alternative to live web scraping.

🔍 Background
The project simulates web content referencing South African PEPs by programmatically generating data points based on real political figures and validated domain structures. This approach is suitable for environments where live scraping is restricted or ethically sensitive.

🛠️ Methodology
1. Source Identification
To ensure data credibility and represent diverse perspectives, the following categories were selected:

Government Websites
Examples: gov.za, presidency.gov.za, dirco.gov.za
Content: Official positions, appointments, and department structures.

News Outlets
Examples: news24.com, mg.co.za, timeslive.co.za, iol.co.za
Content: Media coverage of political activity, scandals, and public statements.

Political Party Platforms
Examples: da.org.za, effonline.org
Content: Leadership bios, political messaging, and campaign news.

A curated domain list was used to exclude irrelevant or low-quality sources.

2. Data Generation and Collection
Due to environment constraints, simulated data was generated via a Python script, replicating realistic content structures:

PEP Name & Role: Randomly matched South African officials to valid political roles (President, Minister, Ambassador, etc.).

Source URL: Realistic URLs based on known structures from selected domains.

Page Title & Snippet: Templated but variable content to mimic headlines and summaries.

Source Classification: Each entry tagged as Government, News, or Political Party for filtering.

Over 1,300 unique entries were created, covering a broad and balanced representation of South African PEPs.

3. Relevance and Quality Assurance
Measures taken to maintain data reliability and integrity:

✅ Geographic Filtering: Only .za domains or South Africa-specific content included.

✅ Role Validation: Only FATF/World Bank PEP roles allowed.

✅ Manual Domain Review: Domains were vetted and categorized prior to use.

✅ Content Diversity: Templates avoided repetition; uniqueness enforced on all URLs.

✅ Spot Checks: Randomly sampled entries validated for logic and realism.

💡 Key Insights
Government domains offer structured and trustworthy data for identifying official roles.

News sites provide recent, detailed, and contextual narratives.

Political party websites add insight into affiliations and political dynamics.

The combination results in a robust dataset reflecting both institutional legitimacy and public discourse.

