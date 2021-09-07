# Corpora-for-Conflict-Study

Examples for crawling and preprocessing corpora for conflict study.

**./Crawlers**: example crawlers for two types of sources. We combined [Newspaper3k](https://newspaper.readthedocs.io/en/latest/) and manually designed patterns with [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/).
- News wires 
- Organizations: 
    - UN: &emsp; UN News, UNHCR, UNODC, OHCHR
    - Refword: &emsp; Amnesty, USCRI, Immigration and Refugee Board of Canada (IRB)
    - NGO: &emsp; Amnesty, HRW.org, New Humanitarian, Rescue.org,  PHR.org
    - Others: &emsp; CFR.org, FRUS
    
**./Preprocess**: Preprocessing pipelines for five different types of sources. Cleaning and filtering stories in conflicts domain.
- News wires
- Organizations         
- [Gigaword](https://catalog.ldc.upenn.edu/LDC2011T07)
- Phoenix Real-Time from [the paper](https://ieeexplore.ieee.org/abstract/document/8910051)
- [Wikipedia](https://dumps.wikimedia.org/)

**./Patterns**: statistically summarized the most frequent keywords’ regular expressions to filter conflicts domain.
- wiki_relevant: &emsp; patterns for filtering relevant news wires
- irelevant_keywords: &emsp; patterns for filtering out not relevant news wires
- wiki_relevant_exclude: &emsp; additional patterns for filtering out not relevant wikipedia documents by categories

        
