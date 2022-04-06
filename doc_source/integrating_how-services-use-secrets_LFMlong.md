# How Amazon Lookout for Metrics uses AWS Secrets Manager<a name="integrating_how-services-use-secrets_LFMlong"></a>

Amazon Lookout for Metrics is a service that finds anomalies in your data, determines their root causes, and enables you to quickly take action\. You can use Amazon Redshift or Amazon RDS as a datasource for an Lookout for Metrics detector\. To configure the datasource, you use a secret that contains the database password\. For more information, see [Using Amazon RDS with Lookout for Metrics](https://docs.aws.amazon.com/lookoutmetrics/latest/dev/services-rds.html) and [Using Amazon Redshift with Lookout for Metrics](https://docs.aws.amazon.com/lookoutmetrics/latest/dev/services-redshift.html)\.