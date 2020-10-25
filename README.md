## Analysis of the CFPB Consumer Complaint Database Data

### Date created
08/24/2020

### About the Project  
Utilizing data from the CFPB's Consumer Complaint Database, the business objective of this analysis is to determine key attributes of consumer complaints for the top 25 depository institutions regulated by the CFPB.  

Data provided by the [Consumer Finance Protection Bureau](https://www.consumerfinance.gov/). 

Per the CFPB:

>**About the database**  
The Consumer Complaint Database is a collection of complaints about consumer financial products and services that we sent to companies for response. Complaints are published after the company responds, confirming a commercial relationship with the consumer, or after 15 days, whichever comes first. Complaints referred to other regulators, such as complaints about depository institutions with less than $10 billion in assets, are not published in the Consumer Complaint Database. The database generally updates daily.

Questions answered are:

1. How many complaints has the CFPB handled for the top 25 depository institutions?  
2. What is the average amount of complaints recieved per 30 days and how does that compare to the most recent 30 days?  
3. What are the most common issues reported by consumers?  
4. What are the most common products that complaints are recieved for?  
4. How does the complaint volume compare from year to year?  
5. Given that these top 25 depository institution's total assets are wide ranging, does an adjustment to asset size reveal that some companies have more complaints per $100 billion in total assets?  

The top 25 depository institutions by total assets are:

| **Company Name** | **Total Assets** |
| :---: | ---: |
| JPMORGAN CHASE BANK, NATIONAL ASSOCIATION | &#0036;2,690,959,000,000 |
| BANK OF AMERICA, NATIONAL ASSOCIATION | &#0036;2,031,940,000,000 |
| WELLS FARGO BANK, NATIONAL ASSOCIATION | &#0036;1,763,696,000,000 |
| CITIBANK, N.A. | &#0036;1,632,405,000,000 |
| U.S. BANK NATIONAL ASSOCIATION | &#0036;533,129,091,000 |
| TRUIST BANK | &#0036;495,079,000,000 |
| PNC BANK, NATIONAL ASSOCIATION | &#0036;433,803,038,000 |
| BANK OF NEW YORK MELLON, THE | &#0036;387,037,000,000 |
| STATE STREET BANK AND TRUST COMPANY | &#0036;359,196,000,000 |
| TD BANK, N.A. | &#0036;355,767,822,000 |
| CAPITAL ONE, NATIONAL ASSOCIATION | &#0036;339,215,513,000 |
| CHARLES SCHWAB BANK, SSB | &#0036;270,245,000,000 |
| GOLDMAN SACHS BANK USA | &#0036;254,668,000,000 |
| HSBC BANK USA, NATIONAL ASSOCIATION | &#0036;201,885,682,000 |
| FIFTH THIRD BANK, NATIONAL ASSOCIATION | &#0036;183,723,698,000 |
| MORGAN STANLEY BANK, N.A. | &#0036;178,664,000,000 |
| CITIZENS BANK, NATIONAL ASSOCIATION | &#0036;176,632,580,000 |
| ALLY BANK | &#0036;170,655,000,000 |
| NORTHERN TRUST COMPANY, THE | &#0036;161,163,529,000 |
| KEYBANK NATIONAL ASSOCIATION | &#0036;154,993,507,000 |
| BMO HARRIS BANK NATIONAL ASSOCIATION | &#0036;145,168,865,000 |
| MUFG UNION BANK, NATIONAL ASSOCIATION | &#0036;135,037,826,000 |
| REGIONS BANK | &#0036;132,707,000,000 |
| AMERICAN EXPRESS NATIONAL BANK | &#0036;130,004,248,000 |
| NAVY FEDERAL CREDIT UNION | &#0036;125,580,859,000 |

### Files used
* CFPB-Consumer_Comp_DB.ipynb  
* complaints.csv - CFPB's Consumer Complaint Database dataset located [here](https://www.consumerfinance.gov/data-research/consumer-complaints/).  
* Top25_Companies.xlsx - List of the top 25 depository institutions, by total assets, created from the CFPB's list of Depository Institutions subject to CFPB supervisory authority located [here](https://www.consumerfinance.gov/policy-compliance/guidance/supervision-examinations/institutions/).  
