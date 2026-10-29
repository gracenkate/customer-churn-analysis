# Data source

This project uses the 21-column IBM Telco Customer Churn CSV (7,043 customer records). The local file's original acquisition date is unknown.

- [IBM reference CSV](https://github.com/IBM/telco-customer-churn-on-icp4d/blob/master/data/Telco-Customer-Churn.csv)
- [Direct download](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)
- [IBM description and churn definition](https://community.ibm.com/community/user/blogs/steven-macko/2018/11/26/new-base-samples-for-ibm-cognos-analytics-1111)
- [Upstream license](https://github.com/IBM/telco-customer-churn-on-icp4d/blob/master/LICENSE)

Download the CSV and save it here as **`telco_customer_churn.csv`**. Preserve it unchanged. From the repository root, PowerShell users can run:

```powershell
Invoke-WebRequest -Uri 'https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv' -OutFile 'data/telco_customer_churn.csv'
```

The CSV is not included in the publication archive and is excluded from Git. Consult the upstream license and notices for its terms. The notebook contains the variable dictionary and documents all cleaning decisions. The source describes a fictional company; no real customer population is inferred.
