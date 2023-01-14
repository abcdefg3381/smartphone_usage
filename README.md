# Smartphone apps usage time and user cluster sizes
This project holds the datasets and computer codes for paper:

Liu, Xiao Fan and Wang, Zhenzhen and Xu, Xiao-Ke and Wu, Ye and Zhao, Zhidan and Deng, Huarong and Wang, Ping and Chao, Naipeng and Huang, Yi-Hui, The Shock, the Coping, the Resilience: How Smartphone Application Use Reveals Covid-19 Lockdown Effects on Human Behaviour (April 22, 2022). Available at SSRN: https://ssrn.com/abstract=4104602 or http://dx.doi.org/10.2139/ssrn.4104602

## Datasets
* in /app, <strong>the average daily use time of 50 categories of smartphone apps</strong> in nine cities in 2021. Each Excel file contains the data for one city. The file has the structure:

|       | app1 | app2 |
| ----- | ---- | ---- |
| date1 | ... | ... |
| date2 | ... | ... |

_column name translation.txt tells the meaning of the column names.

* in /user clusters, <strong>the daily sizes of 20 user clusters</strong> in nine cities in 2021. Each csv file contains the data for one city. The file has the structure:

|       | cluster1 | cluster2 |
| ----- | ---- | ---- |
| date1 | ... | ... |
| date2 | ... | ... |

_column name translation.txt tells the meaning of the column names.

* NPI policies.xlsx (in Chinese) summarizes <strong>the major lockdown policies</strong> in the five cities that experienced lockdowns.

## Codes

A python function for calculating the difference-in-difference effects are provided in calcDID.txt.
