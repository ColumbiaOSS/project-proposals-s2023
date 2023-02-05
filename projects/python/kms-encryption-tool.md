# KET (KMS Encryption Tool)

### Description

KET (KMS Encryption Tool) uses AWS KMS Key to encrypt and decrypt files/contents based on user provided keys and push them to a datastore backend (S3, RDS or DynamoDB).

Primary Goals/Requirments:
1. Use KMS Boto3 to encrypt and decrypt string/files with user provided or default key.

2. Allow user to decrypt the file or content using the key

3. Push ecrypted file to S3, RDS (optional) or DynamoDB Table (Optional).

4. Choose the key you want to use to encrypt (searchable by name or tag)