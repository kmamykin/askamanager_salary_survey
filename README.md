# askamanager Salary Survey

Cleaned up dataset of self-reported salaries


## Getting the raw original data

Download in CSV https://docs.google.com/spreadsheets/d/1rGCKXIKt-7l5gX06NAwO3pjqEHh-oPXtB8ihkp0vGWo/export?format=csv

Download OpenRefine https://github.com/OpenRefine/OpenRefine


## Assumptions and calculations

Hourly rate to annual base salary conversion: assumes 1650 billable hours per year.
https://www.trinityp3.com/calculators/

Google API Key: AIzaSyCmmdNgylHYkAa4hlB3B-cIV0Q_rFd__gU
AIzaSyCqd-BAzUsp6a2ICBETWebYYwoA3d3EeWk

Industry codes: https://developer.linkedin.com/docs/reference/industry-codes#
https://www.webspidermount.com/features/generic-job-taxonomy/
https://en.wikipedia.org/wiki/Global_Industry_Classification_Standard
https://en.wikipedia.org/wiki/Industry_Classification_Benchmark


"https://maps.googleapis.com/maps/api/place/findplacefromtext/json?input=" + escape(value.strip(), "url") + "&inputtype=textquery&fields=formatted_address,name&type=locality&key=AIzaSyCqd-BAzUsp6a2ICBETWebYYwoA3d3EeWk"

## Job Title normalization

Links

* http://dataatwork.org/data/
* http://dataatwork.org/skills-ml/SkillsMLWhitepaper.pdf
* https://github.com/workforce-data-initiative/skills-api
* https://github.com/workforce-data-initiative/skills-api/wiki/API-Overview - not working very well
* https://www.levels.fyi/
* https://github.com/careerbuilder/DataScienceAPIDocumentation/blob/master/JobTitle.md
* https://towardsdatascience.com/job-title-analysis-in-python-and-nltk-8c7ba4fe4ec6
* https://towardsdatascience.com/document-embedding-techniques-fed3e7a6a25d#bbe8 - Document Embedding Techniques


Job ocupation taxonomies:

* https://www.onetcenter.org/taxonomy/2010/list.html - O*NET-SOC 2010 occupations
* https://www.bls.gov/soc/2018/home.htm - Standard Occupational Classification
* https://en.wikipedia.org/wiki/International_Standard_Classification_of_Occupations

Datasets:

* https://docs.peopledatalabs.com/docs/free-related-title-dataset
* http://dataatwork.org/data/research/?prefix=cleaned_title_count/ - link to datasets of titles to O*NET occupation taxonomy

Research papers:

* https://cs224d.stanford.edu/reports/BoucherEric.pdf
* https://www.aclweb.org/anthology/W16-1617.pdf - Learning Text Similarity with Siamese Recurrent Networks
* https://arxiv.org/pdf/1606.00917.pdf - Towards a Job Title Classification System (Careerbuilder)
* https://www.aaai.org/ocs/index.php/FLAIRS/FLAIRS17/paper/download/15470/14933 - Document Embedding Strategies for Job Title Classification - best paper

