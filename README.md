# AWS Account Monitoring

The following details the logging configurations and associated alerts to enable and IL4-capable environment.

## Logging Buckets

The following S3 Buckets are configured to store and archive CloudTrail and CloudWatch logs:

1. Archive Logs Bucket
2. CloudTrailBucket

## Logging Roles

The following roles are creating to facilitate logging:

1. CloudWatchLogsRole
2. CloudTrailRole

## Logging Instance Profile

The following Instance Profile is created to support logging:

1. CloudTrailProfile

## CloudWatch Alarms

The following alarms are created to alert administrators for changes to the environment:

1. Network ACL Changes Alarm
2. Security Group Changes Alarm
3. Root Activity Alarm
4. Unauthorized Attempt Alarm
5. IAM Policy Changes Alarm
6. IAM Create Access Key Alarm
7. CloudTrail Change Alarm
