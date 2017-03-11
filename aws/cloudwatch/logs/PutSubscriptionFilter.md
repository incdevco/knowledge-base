# AWS CloudWatch Logs PutSubscriptionFilter

If you receive the following error:

`[InvalidParameterException: Could not deliver test message to specified Firehose stream. Check if the given Firehose stream is in ACTIVE state.]
message: 'Could not deliver test message to specified Firehose stream. Check if the given Firehose stream is in ACTIVE state.`

Check the permissions, the service principal must be logs.{region}.amazonaws.com, with the region the log group is in.
