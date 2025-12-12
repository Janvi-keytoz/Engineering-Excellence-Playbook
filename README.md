## Engineering Excellence Playbook

This playbook organizes engineering standards, guidelines, and best practices across domains.

### Quick navigation
- [Database](db/README.md)
- [Docs hub](docs/README.md)

### Table of contents
- [Overview](#overview)
- [How to use this playbook](#how-to-use-this-playbook)
- [Section structure](#section-structure)
- [Contributing](#contributing)
- [License](#license)


### Overview
This repository centralizes standards so teams can move fast with consistency. Each domain has a checklist for quick adoption and deeper guidance with rationale, risks, and exceptions.

### How to use this playbook
- Start with the domain checklist to get the baseline.
- Read the detailed guidance when making or reviewing changes.
- Link to relevant sections from PRs, design docs, and runbooks.
- Propose improvements via PRs when gaps are discovered.

### Section structure
Each section contains:
- A quick checklist
- Detailed guidance with rationale, risks, and exceptions
- AI editing rules to keep documents consistent

### Contributing
- Open an issue for discussion, or submit a PR directly when changes are small and scoped.
- Keep language concise and action-oriented. Prefer checklists and examples.
- Maintain consistent naming and formatting across sections.
 - See [Documentation guidelines](docs/writing-guidelines.md) for writing and updating section READMEs.

### License
Unless otherwise noted, content is provided under the MIT License.

---

_Last updated: 2025-01-17_

# MASTER GUIDE: SEO + GEO + CONTENT SIGNALS + BLOG STRUCTURE + AI SAFETY

---

## SECTION 1 — FOUNDATION

**Purpose:** Define core concepts to create a common vocabulary across SEO, GEO, content signals, and AI safety.

### What SEO Is and Why It Matters
**Definition:**  
Search Engine Optimization (SEO) is the practice of organizing and optimizing website content, metadata, and structure to improve visibility and relevance in search engines.

**Key Guidelines:**
- Primary keyword inclusion in title, H1, first paragraph, meta description.  
- Keyword density: 0.8–1.5% for primary keywords, 2–4% for secondary.  
- Word count for standard pages: 800–1,500 words; long-form: 2,000–2,500 words.

### What GEO (Generative Engine Optimization) Is
**Definition:**  
GEO optimizes content for AI-driven search engines and LLMs, ensuring content is interpretable, trustworthy, and surfaced accurately in generative answers.

**Key Guidelines:**
- Include structured headings and clear definitions of key terms.  
- Use examples relevant to the target region.  
- Ensure factual and verifiable content; signals like E-E-A-T must be present.

### What Content Signals Are
**Definition:**  
Content signals are markers (structural, semantic, factual, experiential) that indicate content quality, trustworthiness, and relevance for both traditional search engines and AI-driven engines.

**Numeric Recommendations:**
- Include at least 1 H1, 3–6 H2, and 0–4 H3 per standard page.  
- Bullet points and numbered lists: 3–7 items for scan-friendly reading.  
- Visuals with alt text: 1 per 400–600 words.

### How SEO, GEO, and Content Signals Work Together
**Definition:**  
These three layers combine to ensure content ranks, is AI-interpretable, and builds trust.  
Example: well-structured headings (SEO) + factual examples (Content Signals) + region-specific references (GEO) improve AI visibility and user trust.

### Current Search Trends & Engine Landscape
**Definition:** Overview of Google Search, Google SGE, Bing Copilot, Perplexity AI, and LLM-driven search consumption patterns.

**Recommendations:**
- Ensure content answers specific user intents: informational, transactional, commercial, navigational.  
- Include structured data/schema to support rich results in AI snippets.

---

## SECTION 2 — ENTERPRISE SEO GUIDELINES

**Purpose:** Tactical and strategic rules to run SEO at an enterprise level.

### Keyword Strategy
- **Intent Models:** Informational, navigational, transactional, commercial.  
- **Semantic Clusters:** Group 10–20 related keywords per topic cluster.  
- **Primary/Secondary/Contextual Keywords:**  
  - Primary: H1, first paragraph, 1–2 H2s, last paragraph.  
  - Secondary: 3–5 per page naturally.  
  - Contextual/LSI: 5–8 per page.  
- **Long-tail Keywords:** Target niche and voice search queries.

### On-Page SEO
- Title: 50–60 characters, primary keyword first.  
- Meta Description: 130–155 characters, clear value proposition.  
- Headings: One H1 per page, 3–6 H2s, optional H3s.  
- Paragraphs: 2–4 lines; sentences: 12–20 words on average.  
- Image SEO: filenames 3–5 words, alt text with primary/secondary keywords, 1 image per 400–600 words.  
- URL Structure: 2–5 words, hyphenated, lowercase, include keyword.  
- Internal Linking: 2–5 links per page to relevant pillar or cluster pages.

### Technical SEO
- Core Web Vitals: LCP < 2.5s, CLS < 0.1, FID/INP < 100ms.  
- Indexability: Correct robots.txt, XML sitemaps, canonical URLs.  
- Schema: Article, Product, FAQ, HowTo, Breadcrumbs.  
- Internationalization: Hreflang for multi-language pages.

### Off-Page SEO & Authority
- E-E-A-T signals in author bios, citations.  
- Backlinks: High-quality, relevant sources, anchor variation.  
- Social signals: Engagement on social platforms, press mentions.

### On-Site Analytics & Logging
- Track SEO KPIs: impressions, CTR, ranking position, conversions.  
- Monitor crawl logs, bot behavior, and index coverage.  
- Event tracking: scroll depth, downloads, CTA clicks.

---

## SECTION 3 — ADVANCED GEO GUIDELINES

**Purpose:** Region-aware SEO and GEO rules, including AI-optimized content.

### GEO Principles & LLM Interpretation
**Definition:** GEO ensures content is relevant and interpreted correctly by regional audiences and AI-driven search.  
**Signals:** entity clarity, verified facts, region-specific examples.

### Regional GEO Rules (Examples)
- **United States:** Tone: Direct, value-focused; Examples: Renewable energy, infrastructure projects; Keywords: “infrastructure intelligence,” “workflow automation.”  
- **European Union:** Tone: Quality, regulation-focused; Examples: Offshore wind, sustainable energy; Keywords: “GDPR-compliant workflows,” “sustainability reporting.”  
- **India:** Tone: Practical, cost-conscious; Examples: Solar EPC projects, metro rail; Keywords: “project execution,” “document workflows.”  
- **Middle East (UAE, KSA, Qatar):** Tone: Innovation-first; Examples: Smart city projects, mega infrastructure; Keywords: “digital transformation,” “AI for megaprojects.”  
- **APAC (Singapore, Japan, Korea, Australia):** Tone: Precision, reliability; Examples: Grid modernization, energy digitalization; Keywords: “high-tech infrastructure,” “project compliance.”

### Localization vs Translation
- **Localization:** Full cultural and regulatory adaptation of content.  
- **Translation:** Maintain accuracy; use human review for nuance.  
- **Metadata:** Localized meta titles, descriptions, and URLs.

### GEO for Different Page Types
- Adjust terminology, CTAs, examples per region.  
- Include region-specific schema and contact details.

### Regional Keyword Research Methodology
- Tools: SEMrush, Ahrefs, Google Keyword Planner.  
- Normalize data across languages and regions.  
- Map user intent and funnel stage per region.

### Numeric Recommendations (Sections 1–3)
- Page word count: 800–1,500 words; long-form: 2,000–2,500.  
- Paragraph length: 2–4 lines; sentence length: 12–20 words.  
- Heading counts: 1 H1, 3–6 H2, 0–4 H3.  
- Image ratio: 1 image per 400–600 words.  
- Keyword density: primary 0.8–1.5%, secondary 2–4%.

---

## SECTION 4 — CONTENT SIGNAL SYSTEM

**Purpose:** Generate content signals trusted by AI and search engines.

### What Content Signals Are
**Definition:** Structural, semantic, factual, and trust-based markers indicating content quality.  
**Numeric Guidance:** 5–10 distinct content signals per page.

### Why Content Signals Matter for AI & SGE
AI relies on clarity, evidence, and structured content for accurate answers and snippets.

### 25 Types of Strong Content Signals
- **Structural:** H1-H3, bullet lists, tables.  
- **Semantic:** LSI keywords, named entities, synonyms.  
- **Attribution:** Citations, references to authoritative sources.  
- **Experience:** Case studies, first-hand insights.  
- **Data:** Figures, graphs, charts, datasets.  
- **Interaction:** FAQ, polls, calculators.  
- **Technical:** Schema markup, alt tags.  
- **Freshness:** Updated dates, versioning.  
- **Consistency:** Naming, entity linking, internal cross-references.  

**Implementation:** 3–5 per page for standard pages; 7–10 for blogs/long-form.

### How to Build Content That AI Trusts
- Include evidence blocks, citations, verified data workflows.  
- Maintain update cadence: every 6–12 months.

### Entity-First SEO
- Build entity maps for brands, products, processes.  
- Canonicalize entity names across content assets.

### Experience Evidence Blocks & Templates
- Include case studies, methodology callouts, first-hand reports.  
- Numeric: 1–2 evidence blocks per major H2 section in blogs/pillars.

### Structured Content Patterns by Vertical
- Customize signals per industry: B2B SaaS, Finance, Healthcare, Energy/Infrastructure, eCommerce.

### Content Depth & Unique Value Framework
- Use depth scoring: 1–2 levels of H2/H3 subtopics.  
- Ensure unique value: avoid duplication across pages or clusters.

---

## SECTION 5 — BLOG GUIDELINES

**Purpose:** Blueprint for high-ranking, AI-friendly, GEO-aware blogs.

### Blog Strategy & Purpose
- Objectives: Awareness, thought leadership, lead generation, support.  
- Identify personas and user intent.

### Word Count & Character Rules
- Standard: 1,200–1,500 words (~8,000–12,000 chars).  
- Minimum: 800–1,000 words (~6,000–8,000 chars).  
- Long-form: 2,000–2,300 words (~14,000–18,000 chars).

### Full Blog Structure
- Title/H1: 50–70 characters, primary keyword.  
- Deck/Subtitle: 20–30 words, contextual hook.  
- First Paragraph: 40–80 words, include primary keyword.  
- H2 Sections: 3–6 per post.  
- H3 Sections: Optional.  
- Visuals: 1 per 400–600 words, alt text with keywords.  
- CTA/FAQ/Further Reading: Encourage engagement, internal linking.

### SEO Rules for Blogs
- Meta title: 50–60 chars, primary keyword early.  
- Meta description: 130–155 chars, include primary + 1–2 secondary keywords.  
- Image alt text: descriptive, 3–5 words, include keyword.  
- URL slug: 3–6 words, hyphenated, lowercase.  
- Keyword placement: Title, first paragraph, 2 H2s, last paragraph, meta description, images.  
- Keyword density: 0.8–1.5% primary, 2–4% secondary.  
- Internal linking: 2–4 links to related blogs, pillar pages, or products.

### GEO Rules for Blogs
- US: Direct, value-focused.  
- EU: Formal, regulation-aware, GDPR references.  
- India: Practical, cost-conscious, Indian English variants.  
- Middle East: Innovation-first, infrastructure examples.  
- APAC: Precision-focused, technical examples, formal tone.

### Content Signals in Blogs
- Evidence blocks, inline citations, tables, FAQ sections.  
- Numeric: 1 evidence block per H2, 1 FAQ per 800–1,000 words, 1 table/chart per 1,000 words.

### Writing Style Manual
- Tone: Human, clear, straightforward.  
- Sentence length: mix 12–20 words; occasional short sentences for emphasis.  
- Avoid: marketing fluff, repeated filler words.

### Formatting & Visuals
- Use bullet points, numbered lists, tables, charts, screenshots.  
- Captions: 10–15 words.  
- Code snippets (technical): syntax-highlighted, max 20–30 lines.

### Templates for Blog Types
- How-to, listicles, deep dives, interviews, case studies, product announcements.  
- Numeric: 3–5 H2s, 1–3 H3s per H2 if needed.

### Blog Quality Scoring System
- Scoring rubric: 0–100 across SEO, GEO, Content Signals, E-E-A-T, uniqueness.  
- Minimum target: 80/100.


## SECTION 6 — CONTENT ARCHITECTURE FOR ENTERPRISE SEO

**Purpose:** Build long-term topical authority via structured content, linking, and publishing cadence.

### Topic Clusters & Pillar Strategy
- Pillar Page: Authoritative hub covering a broad topic.
- Cluster Pages: Supporting pages targeting subtopics, internally linking to the pillar.
- Numeric: 1 pillar per 5–10 cluster pages.

### Internal Linking Maturity Model
- Hub & Spoke: Links from cluster → pillar → related clusters.
- Anchor Text: Mix exact match, partial match, and generic terms.
- Numeric: 2–5 internal links per cluster page; 5–10 per pillar.

### Content Mapping & User Journey Alignment
- Match pages to funnel stages: Awareness, Consideration, Decision.
- Map keywords and questions to personas.

### Content Calendar & Cadence Framework
- Prioritize evergreen vs. topical content.
- Numeric: Publish 1–2 pillar pages/month; 2–4 cluster posts/month depending on team size.

### Authority Building Roadmap
- PR, research studies, partnerships, content assets to earn backlinks.

### Governance for Evergreen Content
- Update cycle: every 6–12 months.
- Versioning, canonicalization, and content retirement policies.

### Numeric Recommendations Summary
- Evidence blocks per page: 5–10 minimum.
- H2 count per blog: 3–6, H3: 0–4.
- FAQ: 1 per 800–1,000 words.
- Internal links per cluster: 2–5; per pillar: 5–10.
- Publishing cadence: 1–2 pillar pages/month; 2–4 clusters/month.

---

## SECTION 7 — WRITER & EDITOR PLAYBOOKS

**Purpose:** Day-to-day rules for producing, reviewing, and publishing content at scale.

### Writer Guidelines & Brief Templates
- Define objectives, target persona, user intent, keyword set, angle, and tone.
- Numeric Guidance: 3–5 primary/secondary keywords per brief; 1–2 H2 ideas per page.

### Editor Checklists
- Verify SEO compliance, factual accuracy, E-E-A-T, GEO adaptation, readability.
- Numeric: 90–100% of keywords properly placed, 1–2 content signal checks per section.

### SEO QA Checklists
- Check metadata, schema, internal links, alt text, page speed (<2.5 sec).
- Numeric: H1 unique per page, meta title 50–60 chars, meta description 130–155 chars.

### GEO QA Checklists
- Check localization, spelling variants, regulatory mentions, region-specific CTAs.
- Numeric: At least 2 region-specific examples per major H2, 1 regional CTA per page.

### Content Signal Checklists
- Confirm evidence blocks, citations, structured formatting, entity consistency.
- Numeric: 5–10 signals per page; 1–2 evidence blocks per H2 in blogs.

### Pre-publish QA Workflow & Sign-offs
- Assign writer, editor, SEO specialist, GEO reviewer, compliance.
- Numeric: Minimum 2 review rounds before publishing.

### Post-publish Review Process
- Monitor organic traffic, CTR, ranking, AI citations.
- Refresh content every 6–12 months based on metrics.

---

## SECTION 8 — METADATA, STRUCTURED DATA & TAGGING RULES

**Purpose:** Exact standards for metadata, schema, and tagging for SEO and AI discoverability.

### Meta Titles & Description Standards
- Titles: 50–60 characters, primary keyword first, unique.
- Descriptions: 130–155 characters, primary + secondary keywords naturally.
- Numeric Guidance: CTR-focused.

### Open Graph & Social Meta Rules
- OG Title: 60 characters max.
- OG Description: 100–150 characters.
- OG Image: 1200×630 px, relevant.

### Schema & Structured Data Guidelines
- Use JSON-LD format.
- Recommended schemas: Article, BlogPosting, FAQ, HowTo, Product, Organization, Breadcrumb.
- Numeric: Minimum 1 schema type per page; multiple allowed.

### URL & Slug Conventions
- Lowercase, hyphenated, no stop words.
- 3–6 words per slug.
- Example: /project-management-software

### Tagging & Taxonomy Governance
- Use 3–5 tags per page, consistent across clusters.
- Categories: Broad topics (pillar), subcategories (cluster).
- Numeric: 1–2 taxonomies per site hierarchy level.

---

## SECTION 9 — PAGE-TYPE SPECIFIC GUIDELINES

**Purpose:** Precise, copy-ready rules for each page type.

### Home Page
- Word Count: 800–1,200 words
- H1: Unique, primary keyword
- Content Signals: Hero, benefits, social proof, CTAs
- GEO: National/region-specific examples

### Solution / Use Case Pages
- Word Count: 1,000–1,500 words
- H2s: Features, benefits, workflows
- Schema: Product, FAQ, HowTo
- GEO: Localized terminology, compliance mentions

### Feature Pages
- Word Count: 600–1,200 words
- H2s: Capabilities, benefits, technical details
- CTAs: Demo, trial, download
- Content Signals: Diagrams, screenshots, examples

### Industry Pages
- Word Count: 800–1,500 words
- H2s: Pain points, solutions, outcomes
- GEO: Industry-specific regulations, case studies
- Schema: Organization, FAQ, Article

### Landing Pages (campaign)
- Word Count: 500–1,000 words
- Focused CTA
- Keyword density: 1–2%
- Content Signals: Testimonials, benefits

### Blog / Article Pages
- Word Count: 1,200–1,500 words
- H2s: 3–6, H3 optional
- Content Signals: Evidence blocks, tables, FAQs
- GEO: Regional examples

### Case Studies
- Word Count: 1,000–2,000 words
- H2s: Challenge, solution, outcome
- Content Signals: Data charts, testimonials
- GEO: Regional context

### Documentation / Knowledge Base
- Word Count: 500–1,500 words
- H2s/H3s: Steps, instructions, troubleshooting
- Content Signals: Screenshots, tables, inline code

### Pricing Page
- Word Count: 300–600 words
- H2s: Plan comparison, benefits, FAQs
- Content Signals: Tables, CTA buttons
- GEO: Currency, region-specific pricing

### About Page
- Word Count: 400–800 words
- H2s: Mission, team, history
- Content Signals: Team bios, milestones

### Careers Page
- Word Count: 400–800 words
- H2s: Roles, culture, benefits
- GEO: Office location, region-specific benefits

### Contact / Local Pages
- Word Count: 200–400 words
- H2s: Contact info, map, form
- GEO: Local office details

### Legal / Compliance Pages
- Word Count: 500–1,000 words
- H2s: Policies, disclaimers, terms
- Content Signals: Structured lists, citations

### Numeric Recommendations Summary
- Meta title: 50–60 characters
- Meta description: 130–155 characters
- H1: 1 per page; H2: 3–6 (blogs), 2–4 (other pages)
- Keyword density: 0.8–1.5% primary, 2–4% secondary
- Internal links per page: 2–5 for standard pages, 5–10 for pillars/clusters
- Evidence blocks: 1–2 per H2 in blogs/case studies

---

## SECTION 10 — MEASUREMENT, TESTING & SCORING

**Purpose:** Quantify content quality, SEO performance, GEO optimization, and AI visibility.

### KPI Framework for SEO & Content
- Track: organic traffic, CTR, impressions, ranking positions, bounce rate, scroll depth, conversions.
- Numeric: Target CTR > 3–5%, bounce < 50%, avg. session duration 2–3 minutes for blogs.

### Content Quality Scoring Model (0–100)
- Inputs: content signals, E-E-A-T, technical SEO, GEO relevance, readability, uniqueness.
- Recommended: Minimum quality score 80/100.
- Weighting example: 30% content signals, 25% E-E-A-T, 20% SEO, 15% GEO, 10% readability.

### GEO Score & AI Visibility Metrics
- Measure: region-specific search performance, citations in AI answers/snippets.
- Numeric: Track at least 3 GEO KPIs per target region (SERP rank, CTR, AI mentions).

### A/B & Multivariate Testing
- Framework: Test headline, subheadline, CTA, image variations.
- Numeric: Run tests on 20–30% of page traffic for 2–4 weeks.

### Reporting Cadence & Dashboards
- Frequency: weekly (traffic/SEO), monthly (content signals/GEO), quarterly (strategy review).
- Tools: Google Search Console, GA4, Screaming Frog, Ahrefs, SEMrush dashboards.

---

## SECTION 11 — AI CONTENT SAFETY & HALLUCINATION PREVENTION

**Purpose:** Prevent AI-generated falsehoods, ensure factual correctness, maintain trust.

### Definition & Risks of Hallucination
- AI hallucination: plausible but factually incorrect content.
- Risks: loss of credibility, legal exposure, misinformation.

### Source Validation & Citation Policy
- Cite primary sources; secondary only if reputable.
- Numeric: Minimum 1 citation per H2 for blogs, 2–3 for research-heavy articles.

### Fact-Checking Workflow
- Steps: verify numbers, names, standards, regulations.
- Assign editor or SME for final verification.
- Numeric: 100% claims in sensitive content must be verified.

### Content Guardrails for Sensitive Verticals
- Extra review layers for healthcare, finance, legal, security, energy/infrastructure.
- Numeric: 2-step verification for AI-generated drafts.

### Automated Tools & Human Oversight
- AI for initial verification, plagiarism check.  
- Human sign-off required.  
- Numeric: No AI content goes live without 1 human reviewer.

### Rewrite & Retraction Policies
- Immediate update if errors detected.  
- Numeric: Track all retractions/updates for audit.

### Attribution & Quotation Rules
- Attribute expert quotes, data sources, third-party content.  
- Numeric: 100% of external data references with in-line citations or footnotes.

### Versioning & Audit Trails
- Keep logs of all AI-generated and human-edited versions.  
- Numeric: Maintain history for at least 24 months.

---

## SECTION 12 — APPENDIX, GLOSSARY, TEMPLATES & REFERENCES

**Purpose:** Ready references and reusable assets to standardize content operations.

### Glossary of Terms
- Short definitions for SEO, GEO, content signals, schema, AI content safety.
- Example: E-E-A-T = Expertise, Experience, Authoritativeness, Trustworthiness.

### Reusable Templates
- Content brief templates, blog templates, pillar/cluster templates, meta templates, schema snippets.
- Numeric: Include at least 1 template per page type.

### Checklists & Quick QA Sheets
- For writers, editors, SEO, GEO, AI content reviewers.
- Numeric: Minimum 5–10 QA points per checklist.

### Reference Bibliography & Official Sources
- Google Search Central, HubSpot GEO resources, Yoast, Ahrefs, SEMrush, Moz, research papers.
- Numeric: Maintain at least 5–10 authoritative sources per topic cluster.

### Tooling Recommendations
- Google Search Console, GA4, Screaming Frog, Ahrefs/SEMrush, Notion/Contentful, translation memory tools.
- Numeric: Implement minimum 3–4 tools for tracking, SEO, GEO compliance.

### Numeric Recommendations Summary
- KPI thresholds: CTR > 3–5%, bounce < 50%, avg. session duration 2–3 min.  
- Quality score: Minimum 80/100.  
- Citation requirements: 1–3 per H2 for blogs/research-heavy content.  
- AI verification: 100% human review for sensitive verticals.  
- Templates/checklists: At least 1 per page type or workflow.

---

**References:**
1. [Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
2. [Meta Description Guidelines — Google](https://developers.google.com/search/docs/appearance/meta-descriptions)
3. [Core Web Vitals & Page Experience — Google](https://developers.google.com/search/docs/appearance/page-experience)
4. [HubSpot GEO Guide](https://blog.hubspot.com/marketing/generative-engine-optimization)
5. [Yoast SEO Copywriting & Readability](https://yoast.com/seo-copywriting/)
6. [SEMrush SEO Best Practices](https://www.semrush.com/blog/seo-best-practices/)
7. [Ahrefs SEO Guide](https://ahrefs.com/blog/seo/)
8. [Moz Beginner’s Guide to SEO](https://moz.com/beginners-guide-to-seo)
9. [NN/g UX Writing Guidelines](https://www.nngroup.com/articles/ux-writing-guidelines/)


