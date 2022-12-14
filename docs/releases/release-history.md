# Release history

## [v1.0.1 <small>November 2, 2022</small>](https://github.com/ZachChristensen28/SA-AwsAssets/releases/tag/v1.0.1)

### Compatibility

Product | Version
--------- | -------
Splunk platform versions | 9.x, 8.x
Splunk Enterprise Security version | [7.x, 6.x](https://splunkbase.splunk.com/app/263)
Splunk Add-on for AWS | [6.x](https://splunkbase.splunk.com/app/1876)

### What's Changed

- Fixed duplicate `nt_host` field - [#5](https://github.com/ZachChristensen28/SA-AwsAssets/issues/5)

### Known issues

Issue | Description | Solution | GitHub issue reference
----- | ----------- | -------- | ----------------------
Lookup file error | You may see the error `status="Lookup file error, unknown path or update time" name=sa_aws_assets` | This error exists since the KVstore is being used opposed to a csv file and does not interfere with the functionality of lookup creation. | Issue [#1](https://github.com/ZachChristensen28/SA-AwsAssets/issues/1)

## [v1.0.0 <small>October 28, 2022</small>](https://github.com/ZachChristensen28/SA-AwsAssets/releases/tag/v1.0.0)

### Compatibility

Product | Version
--------- | -------
Splunk platform versions | 9.x, 8.x
Splunk Enterprise Security version | [7.x, 6.x](https://splunkbase.splunk.com/app/263)
Splunk Add-on for AWS | [6.x](https://splunkbase.splunk.com/app/1876)

### New

- Initial release

### Known issues

Issue | Description | Solution | GitHub issue reference
----- | ----------- | -------- | ----------------------
Lookup file error | You may see the error `status="Lookup file error, unknown path or update time" name=sa_aws_assets` | This error exists since the KVstore is being used opposed to a csv file and does not interfere with the functionality of lookup creation. | Issue [#1](https://github.com/ZachChristensen28/SA-AwsAssets/issues/1)
