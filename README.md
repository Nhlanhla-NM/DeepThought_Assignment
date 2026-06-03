## Methodology
Companies where found using AI tool (Chatgpt) through writing an prompt of required research data needed.
Process of research was done as followed:
- Collecting key words that need to be researched from given information on Githup
- Structure an AI prompt for research
- Structuring excel column headings for information required
- Collecting data from Chatgpt and inputing according to spreadsheet structure
- Calculating score for each company criteria
- Begin filtering companies by Eligibility gate, E1, E2 and auto disqualify instructions provided
- On remining companies we sort score by descending order. The top 25 companies being listed became the chosen companies for this research 

The lesson on this research was learning more about companies different manufacturing processes and products.

## Code 
The following is the ChatGPT prompt created and used:

Hey chat, you are an AI Research Assistant. I require research upon companies in segment of speciality manufacturing from the city of Surat. I require two CSV format tables, On first table i require:

Please collect a list of 100 companies from the city including such information and format column heading by the () names:
- Name of company (Company name)
- Mention website of company (Website)
- Company segment (Segment)
- Identify if company an producer/ service provider or an proprietary specialized service (Producer/Service/Proprietary service)
- Summary of their service/product being offered (Product or Service summary)
- Identify if primarly trader, distributor, or importer (Trade/Distributor/Importer)
- Identify whether company is in an subsidiary of another country (Foreign Subsidy)
- Identify if company is controlled by Private equity or venture capitals (PE/VC Backed)
- Identify company revenue example (Rs.270Cr FY24 (+30% YoY), Rs.900Cr order book) (Revenue/Scale Indicator)
- Identify last active year starting from <2026 (Visible Active years)


Second table:
Based on the 100 companies names being first column, prove the following criteria whether true or false or partial on whether company does have the following  for each criteria provide explaination why true/false/partial: 


Use the CSV table format spreadsheet Book1 to fill in the following information using such structure: 

Example Differentiated has it's own column must be left blank as it shows the data that must be collected for the condition and reason. Condition of differentiated (True/False/Partial) and Reason (Why true/false/partial). Same goes for when starting Decision Making Quality

- Differentiated  - (Makes something niche or technical — not a commodity. Two types of differentiation count: (1) IP-based: patents, R&D centre, regulatory approvals (USFDA, EU-GMP, DSIR-recognized), "first/only/pioneer in India", proprietary products. (2) Capability-based: specialized equipment (German/Japanese/Swiss machines in a market of Chinese), proprietary processes, custom manufacturing competitors can't replicate, market-shaping innovation (e.g., first company to offer 500kg MOQ in an industry that demanded 10 tons). Both are real differentiation.)

- Decision Making Quality- (The founder or MD demonstrates the ability to build structured operations. Two archetypes qualify: (1) Science-founder: PhD, IIT/NIT/BITS/IISc alumni, ex-ISRO/DRDO, engineering pedigree, technical publications. (2) Operator-founder: demonstrated systems thinking — ERP/SAP investment, structured costing models, formal planning processes, contribution-based measurement, evidence of building operational infrastructure over time. Gen-2 leaders with formal education AND operational involvement also count.)

- Growing sector - (Operating in a sector with tailwinds. Look for: PLI scheme eligibility, Make-in-India relevance, China+1 beneficiary, export markets, government support, D2C growth trends.)

- Growth Signals- (Company is expanding, not stagnant. Must meet at least 2 of the 5 thresholds below.)

- Systems Maturity- (Evidence that the company operates through structured systems, not just founder intuition. Look for: ERP/SAP implementation, structured costing models, MIS/dashboard usage, digital infrastructure, IT roles on LinkedIn, job postings mentioning SAP/ERP. A company that invested in operational systems already thinks structurally — they've accepted "we need process." Companies with zero systems infrastructure are significantly harder to work with.)

- Leadership Succession- (Evidence of generational transition or leadership depth beyond the founder. Look for: Gen-2 formally appointed to the board (check MCA filings for appointment date), returned from external education or career before joining, taking an operational role (not just equity holding). Also: non-family professional managers hired into senior roles (COO, CFO, CTO from outside the family), independent directors on the board, multiple V4-level leaders with distinct portfolios (not one person holding every title).)
