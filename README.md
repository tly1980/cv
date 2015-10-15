##About me

```yaml
	Using python:
		Implemented a pixel server tracks 40+ millions pageviews/day across all newscorp digital properties (news.com.au, dailytelegraph, taste.com.au, ... etc.).

		Implemented Audience API supports enables newscrop to target customer on second pageview.

		Pixel server + Audience API is a core part of our user-data / event realtime pipeline is the foundation of targeting advertisement business and user customization.

		Implemented S3 clean up scripts using multi-process. Early version of awscli hangs when you have too many files in S3 bucket.

	Using GO:
		Maintain and enhance the user id Graph modeling tool to group all the related ID mappings.

		Implemented a dynamodb ingestion tool ships segment attributes at 9000TPS with a ec2 t2.small instance.

		Implemented a dynamodb table clone tool tops at 3500 TPS on a single EC2 m3.medium instance (tested with table with 50 millions records ), whereares the AWS offical data pipeline (beta version) failed to clone the tables in a EMR cluster.

	Using Spark:
		Generate a couple daily reports that tracks accruacy of 3rd party data partner.

BTW:
	Probably the first one to use AWS Kinesis for project, as he found a blocking bug in BOTO (AWS official python sdk) and fix it and created pull-request to BOTO (PR was accepted.) on github.

	What is mentioned above are implemented by himself alone, and all running on AWS and he implemented more than half of the build-plan (using AWS cloudformation stacks) for those projects. They all run on AWS ec2 and heavly use AWS service ( SQS / Kinesis / DynamoDB / S3 / EC2-ELB / EC2-Autoscalegroup ) and some of the project run on docker container on top of EC2


His github projects:
	A devops PoC:
		CFN generation:
			https://github.com/tly1980/agile_conf
		Server provisioning using S3 / GSUtils:
			https://github.com/tly1980/provisioner

	DynamoDB talble clone tool:
		https://github.com/tly1980/dynoclone

	Load enverion variables from Mac's key chain
		https://github.com/tly1980/senv
```
