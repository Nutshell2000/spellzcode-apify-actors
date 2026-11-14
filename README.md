# SpellzCode Apify Actors

Ready-made data tools that run on [Apify](https://apify.com/spellzcode). Each one takes a list of inputs (links, domains, company numbers, keywords) and returns clean rows you can download as CSV, Excel or JSON, or call from code, Make, Zapier, n8n or an AI agent through Apify's API and MCP server.

All of them are **pay per result**: you pay only for rows returned, failed or unavailable inputs are free, and Apify's free plan includes $5 of monthly credit, which covers thousands of results on most of these tools.

Made and maintained by SpellzCode. Not affiliated with LinkedIn, Google, TikTok, Meta or any other site named here.

## Lead generation and company data

| Actor | What it does | Price |
|---|---|---|
| [LinkedIn Profile Scraper: Full Profiles, No Login](https://apify.com/spellzcode/linkedin-profile-data) | Full public LinkedIn profiles from links: current job, every position with title and dates, education, skills, certifications. No login or cookies. | $2 per 1,000 (per profile found) |
| [Google Ads Transparency Scraper API: Ads by Domain](https://apify.com/spellzcode/google-ads-transparency-scraper) | Get every ad a company runs on Google Search, YouTube, Display and Maps from the Google Ads Transparency Center: format, first and last shown dates, image and preview... | $1 per 1,000 (per ad returned) |
| [Tech Stack Detector API: CMS, Ecommerce, Analytics](https://apify.com/spellzcode/website-tech-stack-detector) | Find out what any website is built with. Checks a list of websites for their CMS, ecommerce platform, JavaScript framework, analytics, ad pixels, chat, payments, hosti... | $3 per 1,000 (per website analyzed) |
| [Email Validator API: Bulk Email List Cleaner](https://apify.com/spellzcode/bulk-email-list-cleaner) | Clean an email list before you send: catches malformed addresses, dead domains, domains that accept no mail, disposable addresses and typos like gmial.com, with a sugg... | $0.5 per 1,000 (per email checked) |
| [Contact Details Scraper API: Emails, Phones, Socials](https://apify.com/spellzcode/website-contact-extractor) | Get the public emails, phone numbers and social profiles from any list of company websites. Emails are checked against the domain's mail server. You pay only for websi... | $4 per 1,000 (per website with contacts) |
| [Companies Hiring Now API: B2B Leads from Jobs](https://apify.com/spellzcode/companies-hiring-now) | Find companies actively hiring for any role, as B2B sales leads: open roles that match, total open roles, locations, departments, newest posting and careers page. From... | $10 per 1,000 (per hiring company returned) |
| [Funding Rounds Tracker API: SEC Form D](https://apify.com/spellzcode/sec-funding-rounds-tracker) | Find US companies that just raised money, from SEC Form D filings: amount raised, offering size, investors, industry, founding year, address and company phone. Funds,... | $20 per 1,000 (per funded company returned) |
| [Swedish Company Register Lookup: Bolagsverket Org.nr & VAT](https://apify.com/spellzcode/sweden-company-register-lookup) | Look up Swedish companies in bulk by organisationsnummer, VAT number or name, from Bolagsverket and SCB official open data: name, legal form, status, bankruptcy or liq... | $3 per 1,000 (per company found) |
| [Nordic Company Register Lookup: Sweden, Norway, Finland](https://apify.com/spellzcode/nordic-company-register-lookup) | One lookup for three official registers: Swedish (Bolagsverket), Norwegian (Brønnøysund) and Finnish (PRH) companies by company number, VAT number or name. Same fields... | $4 per 1,000 (per company found) |
| [Sweden New Companies & Company Lists: B2B Leads by Industry](https://apify.com/spellzcode/sweden-new-companies-leads) | Build lists of Swedish companies from official Bolagsverket and SCB data: newly registered companies from the last days or weeks, or any segment by industry (SNI), cit... | $3 per 1,000 (per company listed) |

## Developer tools and checks

| Actor | What it does | Price |
|---|---|---|
| [Google Play Reviews Scraper API: Country & Rating](https://apify.com/spellzcode/google-play-reviews) | Get reviews of any Android app on Google Play: star rating, text, date, likes, app version and the developer's reply. Choose countries and language, sort by newest, mo... | $0.1 per 1,000 (per review returned) |
| [WHOIS Lookup API: Domain Age, Expiry, DNS & DMARC](https://apify.com/spellzcode/domain-whois-dns-lookup) | Look up a list of domains in one run: registrar, registration and expiry dates, domain age, nameservers, IP addresses, mail servers and provider, and SPF and DMARC ema... | $2 per 1,000 (per domain looked up) |
| [App Store Reviews Scraper API: Country & Rating](https://apify.com/spellzcode/app-store-reviews-by-country) | Get the latest App Store reviews for any iOS or macOS app in any country: rating, title, text, author, app version, date and helpful votes. Filter by star rating, date... | $0.2 per 1,000 (per review returned) |
| [Website Screenshot API: Bulk Full-Page Captures](https://apify.com/spellzcode/website-screenshots-bulk) | Take screenshots of any list of websites: desktop, tablet or mobile, full page or first screen, PNG or JPEG, with a link to each image. Failed pages are reported and n... | $1 per 1,000 (per screenshot taken) |
| [Bulk HTTP Requests API: Call Any API from URL List](https://apify.com/spellzcode/bulk-http-requests-api) | Send many HTTP requests from one run: any method, headers and JSON body, with concurrency, retries and parsed JSON answers. Works with Make, n8n, Zapier and Clay. Requ... | $1 per 1,000 (per request completed) |
| [EU VAT Number Validator: Bulk VIES Check, Name & Address](https://apify.com/spellzcode/eu-vat-number-validator-vies) | Validate EU VAT numbers in bulk against the official VIES service: valid or not, the registered name and address where the member state shares them, and the check time... | $4 per 1,000 (per vat number checked) |
| [EU Company KYB Check: Register, VAT (VIES), Sanctions, LEI](https://apify.com/spellzcode/eu-company-kyb-check) | One row per company with four checks: official register status (Sweden, Norway, Finland), live EU VAT validation in VIES, OFAC sanctions name screening and the GLEIF L... | $20 per 1,000 (per company checked) |

## SEO

| Actor | What it does | Price |
|---|---|---|
| [Google Trends Scraper API: Interest & Related Queries](https://apify.com/spellzcode/google-trends) | Get Google Trends data for any keyword: interest over time, interest by country or region, and top and rising related queries and topics. Compare up to 5 keywords, any... | $2 per 1,000 (per keyword report) |
| [SEO Audit Tool API: On-Page Scores & Issues](https://apify.com/spellzcode/website-seo-audit) | Audit any website's on-page SEO. Every page gets a 0-100 score and a plain-language list of issues: titles, meta descriptions, headings, canonicals, indexability, alt... | $10 per 1,000 (per page audited) |
| [Sitemap URL Extractor API: All Pages of a Site](https://apify.com/spellzcode/sitemap-url-extractor) | List every page a website declares in its sitemaps. Finds the sitemaps automatically from robots.txt, follows sitemap indexes and gzipped files, and returns each addre... | $0.3 per 1,000 (per page address returned) |
| [PageSpeed Insights API: Bulk Core Web Vitals Audit 💰$3/1K](https://apify.com/spellzcode/pagespeed-insights-bulk-audit) | Bulk Google PageSpeed Insights (Lighthouse) audit for any list of URLs: performance, SEO, accessibility and best-practices scores, Core Web Vitals field data (LCP, INP... | $3 per 1,000 (per audit completed) |

## Social media

| Actor | What it does | Price |
|---|---|---|
| [Telegram Channel Scraper API: Posts & Views](https://apify.com/spellzcode/telegram-channel-scraper) | Get posts from any public Telegram channel without a phone number, bot token or login: text, date, views, reactions, links, hashtags, photos and forwards, plus the cha... | $0.5 per 1,000 (per post returned) |
| [Substack Scraper API: Posts, Full Text & Comments](https://apify.com/spellzcode/substack-posts-scraper) | Get the posts of any Substack newsletter: title, subtitle, date, authors, full text of free posts, likes, comment and restack counts, tags and links. Filter by date an... | $2 per 1,000 (per post returned) |
| [TikTok Profile Scraper: Exact Followers & Likes](https://apify.com/spellzcode/tiktok-profile-data) | TikTok profiles by username with exact counts: followers, likes, videos, avg likes per video, bio link, business and TikTok Shop seller flags. No login. | $2 per 1,000 (per profile found) |
| [Threads Profile Scraper: Posts & Engagement](https://apify.com/spellzcode/threads-profile-data) | Threads profiles by username: followers, bio, links, recent posts with likes, replies, reposts and quotes, engagement rate. No login. | $2 per 1,000 (per profile found) |

## Jobs

| Actor | What it does | Price |
|---|---|---|
| [Greenhouse, Lever & Ashby Jobs API: Career Boards](https://apify.com/spellzcode/greenhouse-lever-ashby-jobs) | Get every open job from company career boards on Greenhouse, Lever and Ashby in one clean format: title, location, remote flag, department, salary where published, dat... | $1 per 1,000 (per job returned) |
| [Greenhouse Jobs Scraper API: All Open Jobs, No Login](https://apify.com/spellzcode/greenhouse-jobs-scraper) | Get every open job from any company's Greenhouse job board: title, location, remote flag, department, salary where published, dates, links and full description. Filter... | $1 per 1,000 (per job returned) |
| [Career Site Jobs API: Job Postings from Company Sites](https://apify.com/spellzcode/career-site-jobs-search) | Search open jobs across company career sites on Greenhouse, Ashby, SmartRecruiters and Lever by title, location, department and date. Direct from employers, with no jo... | $2 per 1,000 (per job returned) |

## AI and documents

| Actor | What it does | Price |
|---|---|---|
| [PDF to Text API: Extractor & OCR for Scanned PDFs](https://apify.com/spellzcode/pdf-to-text-extractor) | Turn PDFs into clean text for search, analysis and AI pipelines. Give it PDF links and get each document's full text, page-by-page text, word and page counts and metad... | $5 per 1,000 (per pdf extracted) |
| [Nano Banana AI Image Generator API: Text to Image, No Key](https://apify.com/spellzcode/nano-banana-ai-image-generator) | Generate and edit images with Google's Nano Banana (Gemini 2.5 Flash Image) from text prompts, in bulk: any aspect ratio, optional reference images for editing, a down... | $5 per 1,000 (per image generated) |

## Automation

| Actor | What it does | Price |
|---|---|---|
| [Bulk Image Downloader API: Images from URLs & Pages](https://apify.com/spellzcode/bulk-image-downloader-cheap) | Download images in bulk from a list of image links or from web pages. Each image is checked to be a real image and saved with a download link. Failed links are reporte... | $1 per 1,000 (per image saved) |
| [Bulk File Downloader API: PDFs, Docs, Media, No Login](https://apify.com/spellzcode/bulk-file-downloader-api) | Download files in bulk from a list of links or from web pages: PDFs, Word and Excel files, CSV, presentations, images, audio, video and archives. Each file is checked... | $1 per 1,000 (per file saved) |

## E-commerce

| Actor | What it does | Price |
|---|---|---|
| [Shopify Scraper API: Products, Prices, Variants, Stock](https://apify.com/spellzcode/shopify-store-products) | Export the full product catalog of any Shopify store: titles, prices, sale prices and discount, stock status, variants with SKUs, images, tags and descriptions. Filter... | $1 per 1,000 (per product returned) |

## News

| Actor | What it does | Price |
|---|---|---|
| [Google News Scraper API: Real Publisher URLs](https://apify.com/spellzcode/google-news-scraper) | Search Google News by keyword or topic in 36 editions and get each article's title, publisher, date and its real publisher URL (not the news.google.com redirect). Time... | $2 per 1,000 (per article returned) |

## Working examples (Node.js and Python)

| Example repo | Actor |
|---|---|
| [linkedin-profile-scraper-no-login](https://github.com/Nutshell2000/linkedin-profile-scraper-no-login) | LinkedIn profiles by link, no login |
| [tiktok-profile-scraper](https://github.com/Nutshell2000/tiktok-profile-scraper) | TikTok followers, likes, bio |
| [threads-profile-scraper](https://github.com/Nutshell2000/threads-profile-scraper) | Threads followers, bio, recent posts |
| [website-email-extractor](https://github.com/Nutshell2000/website-email-extractor) | Emails, phones, socials from websites |
| [bulk-email-list-cleaner](https://github.com/Nutshell2000/bulk-email-list-cleaner) | Email list validation |
| [sweden-new-companies-list](https://github.com/Nutshell2000/sweden-new-companies-list) | New Swedish companies from Bolagsverket |
| [pdf-to-text-ocr-api](https://github.com/Nutshell2000/pdf-to-text-ocr-api) | PDF to text with OCR |

## Guides

- [Keep your CRM's job titles current from LinkedIn profile links](https://dev.to/spellzcode/keep-your-crms-job-titles-current-from-linkedin-profile-links-without-logging-in-or-using-cookies-3pkk)
- [Every new Swedish company from the last 30 days as a spreadsheet](https://dev.to/spellzcode/every-new-swedish-company-from-the-last-30-days-as-a-spreadsheet-from-bolagsverkets-open-data-49ee)
- [Getting the contact email from 500 company websites](https://dev.to/spellzcode/getting-the-contact-email-from-500-company-websites-hidden-addresses-junk-matches-and-dead-domains-3ehn)
- [Detecting scanned PDFs and when OCR is worth it](https://dev.to/spellzcode/your-pdf-to-text-pipeline-is-silently-returning-empty-pages-detecting-scanned-pdfs-and-when-ocr-is-40d4)
## Calling one from code

```js
// npm i apify-client
import { ApifyClient } from 'apify-client';
const client = new ApifyClient({ token: process.env.APIFY_TOKEN });
const run = await client.actor('spellzcode/linkedin-profile-data').call({
  profiles: ['https://www.linkedin.com/in/williamhgates'],
});
const { items } = await client.dataset(run.defaultDatasetId).listItems();
console.log(items);
```

Every actor's input fields are listed on its Store page under **Input**.

## Personal data

Some of these tools return personal data (public profiles, contact details on company websites). You are the controller of what you collect: you need a lawful basis under GDPR and similar laws and must respect each site's terms.

## Requests

Missing a field or a source? Open an issue here or use the Issues tab on the actor's Store page.

## License

This catalogue and the example code are MIT licensed. The actors themselves run on Apify.
