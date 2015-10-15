##About Tom Tang


###Using python:

1. Implemented a pixel server tracks 40+ millions pageviews/day across all newscorp digital properties (news.com.au, dailytelegraph, taste.com.au, ... etc.).

2. 
Implemented Audience API supports enables newscrop to target customer on second pageview.

3. Pixel server + Audience API is a core part of our user-data / event realtime pipeline is the foundation of targeting advertisement business and user customization.

4. Implemented S3 clean up scripts using multi-process. Early version of awscli hangs when you have too many files in S3 bucket.

### Using GO:

1. Maintain and enhance the user id Graph modeling tool to group all the related ID mappings.

2. Implemented a dynamodb ingestion tool ships segment attributes at 900 TPS with a ec2 t2.small instance.

3. Implemented a dynamodb table clone tool tops at 3500 TPS on a single EC2 m3.medium instance (tested with table with 50 millions records ), whereares the AWS offical data pipeline (beta version) failed to clone the tables in a EMR cluster.

### Using Spark / BigQuery:

1. Generate a couple daily reports that tracks accruacy of 3rd party data partner.

2. Adlog reporting, including identifing DFP feq-cap issues and internal identifier issues.

### BTW:

1. Probably the first one to use AWS Kinesis for project, as he found a blocking bug in [boto (AWS official python sdk)](https://github.com/boto/boto) and fix it and created [pull-request](https://github.com/boto/boto/pull/2434) to [boto](https://github.com/boto/boto) on github, and it was [accepted](https://github.com/boto/boto/pull/2434).

2. They all run on AWS ec2 and heavly use AWS service ( SQS / Kinesis / DynamoDB / S3 / EC2-ELB / EC2-Autoscalegroup / SNS / RDS ) and some of the project run on docker container on top of EC2

3. What is mentioned above mostly implemented by himself.


### Github projects:

| domain | Projects | Comments  |
|------|:----|:---|
| devops |   [agile_conf](https://github.com/tly1980/agile_conf) |  CFN generation using [Ninja2](http://jinja.pocoo.org) templates |
| devops | [provisioner](https://github.com/tly1980/provisioner)  | Server continus provisioning Using S3 / Gsutils  |
| tools | [dynoclone](https://github.com/tly1980/dynoclone)  | DynamoDB clone tool |
| tools | [senv](https://github.com/tly1980/dynoclone)  | Secure your enviornment variables using Mac keychain |

Here is my other [github projects](http://github.com/tly1980/) or my [slides](https://slides.com/liyingtang).


