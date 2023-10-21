# Task-Web-Scraping-for-NLP
web data scraping

Problem Statement: A website is typically design in such a way that the information is provided in a hierarchical manner. The landing page is considered the top of the information hierarchy. Understanding this hierarchy for a given website is the critical first step in extracting the relevant information from that site.

This notebook provides detailed code highlighting information extraction techinques at various levels from the website named PoetryState : https://banglarkobita.com/. This site contains obout 73,442 poems which are categorized into 11 different groups written by various Bangali poets in the past 100 years. Your task will be to extract information from the website and create a dataframe in the following format:

poet name, poem name, poem url, poem genre Your final dataframe is expected to have ~73000 rows (assuming some poems are missing) and 4 columns.

Note 1 : The steps provided in this notebook are deliberately disjoined. You will need to find the way to combine these together using a loop. To do so, understanding the code provided below is important.

Note 2 : We expect you to be creative in addressing the challenge. Therefore, use our code as a guideline but do not use it as something that is written on the stone. For example, if you are comfortable using other web scraping libraries, such as urllib2 or selenium, please feel free to use it. if you know better method to extracts data from the html tags, use it by all means.

Extra Credit 1:
Add a new column name poem content in the dataframe. For a given poet, this column will contain the entire poem as a string.

Extra Credit 2:
1- Remove comma, bangla dari (,|) if they appear in the text or extracted data.
2- Remove semi-colon, exclamatory mark(;!) if they appear in the extracted data.
3- Remove dash of various types (-) if they appear in the extracted data.
4- Remove unicode characters if they appear in the extracted data.
