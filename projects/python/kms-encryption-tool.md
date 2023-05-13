# KET (KMS Encryption Tool)

## Description

KET (KMS Encryption Tool) uses AWS KMS Key to encrypt and decrypt files/contents based on user provided keys and push them to a datastore backend (S3).

Primary Goals/Requirments:

1. Use KMS Boto3 library to encrypt and decrypt string/files with user provided kms key.

2. Push ecrypted file to S3.

3. Allow user to download and decrypt the file or content using the key.

4. Exposes library functions that can be used in other tools for quick enryption and decryption.


## Project Link

[AWS KET](https://github.com/sayefiqb/aws-ket)
