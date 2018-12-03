## Task
1. Use Python/BeautifulSoup to set up a lawsuit database [here](https://legalref.judiciary.hk/lrs/common/ju/judgment.jsp?L1=FA#H1).
2. Each court has subcategories.
3. Each subcategory contains different result of lawsuit, which each case documented by date and case number.
4. Each category and the corresponding content in it shall be recorded.
5. Output in CSV or sqlite.

## Additinal Tasks (not required)
1. Use NER to extract name of person/company in each document.
2. Based on the summary result, what insights can you get?
3. Neglecting the deduplication step, who (person/company) are the most frequently involved in lawsuit?

# Solution
The notebook file [here](https://github.com/Zhitaow/Gekko_Webcrawler_Project/blob/master/dev/webcrawler.ipynb) consists of two parts: webcrawling and data analysis.
