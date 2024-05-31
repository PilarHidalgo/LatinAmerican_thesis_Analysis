# LatinAmerican_thesis_Analysis
This repository contains documentation about the paper: Social and scientific relevance of Undergraduate Theses in Latin America

## Process in obtaining and processing data: We used scraping and crawling techniques to obtain data. These procedures have limitations. Legality and ethics of using these tools are often overlooked. In order not to incur legal faults [24], we followed the following rules:

- Use the free access API2 to collect information from Google Scholar, through the Serapi3 tool.
- Avoid pages that contain blocking codes CAPTCHA4.
- The use of the mentioned data is for the exclusive purpose of scientific dissemination and teaching, not for commercial purposes.

To obtain metrics, the procedure was:

- For social relevance: compliance with the items of social relevance that must contain at least one thesis work is evaluated. To avoid manual reading, we used the technique of natural language processing (NLP) Word2Vec [26], which automatically identifies the terms and stores them in registers to determine if the thesis under study mentions terms of social relevance defined by the theoretical framework [27].
- For scientific relevance: These data are obtained from the statistics available on the website of each DSpace repository5. Additionally, we grouped other indicators (such as author and thesis citation statistics) that were available in a scattered way in Google Scholar to build the database. The purpose was to find out if a thesis work complied with the indicators of scientific relevance and if it was justified within the process of statistical description.

## Data analysis:

In this phase, we carried out an expert validation (Appendix B) for the assessment of the instrument to measure the social and scientific relevance presented in this work.

## Metrics description:

We organized the description and visualization of the results for each indicator through the development of a dashboard, which is a graphical interface that shows the metrics and fundamental data to monitor their evolution. It can be accessed from an [Application Programming Interface](https://serpapi.com/search-api) (API) that allows extracting metadata from Google searches. CAPTCHA stands for the Completely Automated Public Turing test to tell Computers and Humans Apart. They are machine-controlled challenge-response tests that are used to determine whether the user is a human or an automated program [25]. DSpace repository is the most popular software used by the universities to organize publishing academic data online [28]. One of its advantages is that it allows the interaction of the users with the dashboard. Besides, visits are registered, according to the search requirement. There are several free access platforms to connect a set of data to a dashboard.
