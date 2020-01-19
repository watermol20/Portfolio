---
name: "City of Somerville, MA: Budgeting and Performance Evaluation Project"
tools: [Cost Accounting, Pivot Tables]
image: /assets/budgeting.jpg
description:  This project was to test our ability to take extensive data set unfamiliar to us and to report significant insights.
---

## City of Somerville, MA: Budgeting and Performance Evaluation Project

---
  
Cost Accounting provides detailed cost information for management in planning and control. This course exposes students to not only the fundamental knowledge of cost terms and concepts, various systems to estimate costs but also to recent advances in cost accounting and data analytics skills. Working knowledge of cost accounting is essential for accounting student's education due to the importance of cost accounting in every organizational setting. The information presented in the course is also vital for the successful completion of professional examinations such as CPA and CMA.

<p class="text-center">{% include elements/button.html link="/download/city_sommerville.xlsx" text="Download Spreadsheet" %} </p>

{%- capture list_items -%}
The Report
Summary
{%- endcapture -%}

{% include elements/list.html title="Table of Contents" type="toc" %}

<br>

#### The Report

---

| Years        | Sum of   Amount   |
|--------------|-------------------|
| 2013         |  $157,158,458.62  |
| 2014         |  $141,432,243.16  |
| 2015         |  $190,121,361.06  |
| 2016         |  $188,302,773.79  |
| **Total Result** |  **$677,014,836.63**  |
  
- There is an overall increase to spending from 2013 to 2016.
  
| Category of Gov    | 2013              | 2014              | 2015              | 2016              | **Total Result**      |
|--------------------|-------------------|-------------------|-------------------|-------------------|-------------------|
| General Government |  $103,035,030.05  |  $84,464,671.28   |  $120,518,950.97  |  $128,668,856.21  |  **$436,687,508.51**  |
| Public Works       |  $41,224,909.62   |  $43,654,715.31   |  $55,211,386.56   |  $45,170,727.47   |  **$185,261,738.96**  |
| Education          |  $12,898,518.95   |  $13,312,856.57   |  $14,391,023.53   |  $14,463,190.11   |  **$55,065,589.16**   |
| **Total Result**       |  **$157,158,458.62**  |  **$141,432,243.16**  |  **$190,121,361.06**  |  **$188,302,773.79**  |  **$677,014,836.63**  |
  
- The general government spends the most money year over year  
- The amount of money spent for education has increased every year in increments of  
- The amount of money spent by public works has a general trend of decreasing expeditures  

| Item Class                          | 2013              | 2014             | 2015              | 2016              | **Total Result**      |
|-------------------------------------|-------------------|------------------|-------------------|-------------------|-------------------|
| Advertising                         |  $49,573.14       |  $51,871.36      |  $62,377.48       |  $67,369.14       |  **$231,191.12**      |
| Athletics expense                   |  $17,514.65       |  $22,469.09      |  $18,657.55       |  $37,856.50       |  **$96,497.79**       |
| Bonds and debt-related expenditures |  $33,854,232.07   |  $21,685,664.46  |  $47,558,823.83   |  $62,957,496.94   |  **$166,056,217.30**  |
| Books                               |  $24,033.08       |  $20,560.83      |  $21,208.49       |  $22,653.80       |  **$88,456.20**       |
| Dues and subscriptions              |  $166,507.50      |  $193,114.47     |  $132,350.34      |  $183,334.47      |  **$675,306.78**      |
| Education-related                   |  $556,702.19      |  $660,333.76     |  $291,316.50      |  $329,576.54      |  **$1,837,928.99**    |
| Miscellaneous line item             |  $41,038,439.59   |  $43,601,152.41  |  $45,962,436.57   |  $45,551,444.08   |  **$176,153,472.65**  |
| Professional services expense       |  $4,064,556.79    |  $5,022,525.75   |  $7,270,359.50    |  $9,174,273.01    |  **$25,531,715.05**   |
| Property, plant and equipment       |  $20,145,609.46   |  $9,864,127.47   |  $15,634,074.75   |  $6,042,134.21    |  **$51,685,945.89**   |
| Rental expense                      |  $316,881.62      |  $339,747.89     |  $366,313.35      |  $390,800.75      |  **$1,413,743.61**    |
| Repairs and maintenance expense     |  $1,931,344.07    |  $2,154,967.24   |  $2,156,617.82    |  $2,978,075.98    |  **$9,221,005.11**    |
| Supplies expense                    |  $17,992.35       |  $18,511.75      |  $24,855.15       |  $22,642.83       |  **$84,002.08**       |
| Technology expense                  |  $434,909.75      |  $445,896.47     |  $735,375.01      |  $606,263.80      |  **$2,222,445.03**    |
| Utilities expense                   |  $416,733.79      |  $383,728.33     |  $284,184.63      |  $304,934.16      |  **$1,389,580.91**    |
| **Total Result**                        |  **$103,035,030.05**  |  **$84,464,671.28**  |  **$120,518,950.97**  |  **$128,668,856.21**  |  **$436,687,508.51**  |

There is a general increase in expenditure over the years in the general government. This more specifically looks at what item class has the highest expenditures. A problem that can be visible in the pivot table is that the miscellaneous line item group uses almost 50% of the total money spent. This is a red flag for the general government group since there is no simple way for the accountants to see what they money was spent on, which means there could be something that is getting expensed to the group that should not be. 

| Expenditure (Item Class)            | Budget         | Actual         | Variance  $   | Variance  % (as an absolute value) |
|-------------------------------------|----------------|----------------|---------------|------------------------------------|
| Advertising                         |  $66,048       |  $67,369       |  $(1,321)     | 2%                                 |
| Athletics expense                   |  $36,400       |  $37,857       |  $(1,457)     | 4%                                 |
| Bonds and debt-related expenditures |  $62,334,155   |  $62,957,497   |  $(623,342)   | 1%                                 |
| Books                               |  $17,698       |  $22,654       |  $(4,956)     | 28%                                |
| Dues and subscriptions              |  $154,062      |  $183,334      |  $(29,272)    | 19%                                |
| Education-related                   |  $294,264      |  $329,577      |  $(35,313)    | 12%                                |
| Miscellaneous line item             |  $43,799,465   |  $45,551,444   |  $(1,751,979) | 4%                                 |
| Professional services expense       |  $7,339,418    |  $9,174,273    |  $(1,834,855) | 25%                                |
| Property, plant and equipment       |  $5,700,126    |  $6,042,134    |  $(342,008)   | 6%                                 |
| Rental expense                      |  $407,084      |  $390,801      |  $16,283      | 4%                                 |
| Repairs and maintenance expense     |  $2,567,306    |  $2,978,076    |  $(410,770)   | 16%                                |
| Supplies expense                    |  $22,871       |  $22,643       |  $228         | 1%                                 |
| Technology expense                  |  $551,148      |  $606,264      |  $(55,116)    | 10%                                |
| Utilities expense                   |  $260,627      |  $304,934      |  $(44,307)    | 17%                                |
|       Total expenditures            |  $123,550,672  |  $128,668,856  |  $(5,118,184) |  -                                 |

#### Summary

---

There is an overall increase of spending from 2013 to 2016 with the general government spending the most year over year. The trend of an increase in spending specifically looking at item classes under the general government that is a problem is the miscellaneous line item, which uses almost 50% of the total money spent. This is a red flag for the general government group since there is no simple way for the accountants to see what they money was spent on, thus meaning there could be something that is getting expensed to the group that should not be. The variance for the expenditures versus the budgeted amount has a trend of being unfavorable. The largest variance in spending between actual and budgeted was under the professional services expense for $1,834,855. The professional services expense should be looked into as well since it was the second highest unfavorable percent variance at -25%. The variance needs to be investigated since the difference is so high not only in dollars but percentiles as well.