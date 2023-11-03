# AWS Testing
## Testcases for IAM
| Test case | Access |
|---|---|
| Check for IAM permissions that are too broad | Root |
| Check for open ports and misconfigured security groups | Normal |
| Check for unencrypted data | Normal |
| Check for exposed resources | Normal |
| Check for misconfigured network connections | Normal |
| Check for exposed user credentials | Normal |
| Check for weak passwords and reused passwords | Normal |
| Test for the presence of IAM roles and users with excessive permissions | Root |
| Test for the presence of IAM access keys that are not being rotated regularly | Root |
| Test for the presence of IAM roles and users that are not being used and can be deleted | Root |
| Test for the presence of IAM roles and users that have been compromised | Root |

## Testcases for S3
| Test case | Access |
|---|---|
| Test for S3 buckets that are publicly accessible | Normal |
| Test for S3 buckets that are misconfigured to allow unauthorized write access | Root |
| Test for S3 buckets that are misconfigured to allow unauthorized deletion of objects | Root |
| Test for S3 buckets that contain sensitive data that is not encrypted | Normal |

## Testcases for EC2
| Test case | Access |
|---|---|
| Test for EC2 instances that are publicly accessible | Normal |
| Test for EC2 instances that are misconfigured to allow unauthorized SSH access | Root |
| Test for EC2 instances that are missing the latest security patches | Root |
| Test for EC2 instances that are running vulnerable software | Root |

## Testcases for RDS
| Test case | Access |
|---|---|
| Test for RDS databases that are publicly accessible | Normal |
| Test for RDS databases that are misconfigured to allow unauthorized access | Root |
| Test for RDS databases that are not being backed up regularly | Root |
| Test for RDS databases that are not encrypted | Root |

## Testcases for WAF
| Test case | Access |
|---|---|
| Test for WAF rules that are not configured correctly | Root |
| Test for WAF rules that are not filtering out malicious traffic | Root |
| Test for WAF rules that are causing false positives | Root |

## Testcases for CloudFront
| Test case | Access |
|---|---|
| Test for CloudFront distributions that are misconfigured to allow unauthorized access | Normal |
| Test for CloudFront distributions that are not using HTTPS | Root |
| Test for CloudFront distributions that are not caching static content efficiently | Normal |

## Testcases for Lamda
| Test case | Access |
|---|---|
| Test for Lambda functions that have excessive permissions | Root |
| Test for Lambda functions that are not using least privilege | Root |
| Test for Lambda functions that are not logging their activity | Normal |
| Test for Lambda functions that are vulnerable to injection attacks | Root |

## Testcases for Others
| Test case | Access |
|---|---|
| Test for the presence of unauthorized access to AWS resources from outside of your network | Normal |
| Test for the presence of malicious activity in your AWS environment by monitoring CloudTrail logs and other security logs | Normal |
| Test for the ability to escalate privileges from a normal user account to a root account | Root |
| Test for the ability to exfiltrate data from your AWS environment | Root |
| Test for the ability to launch a denial-of-service attack against your AWS environment | Root |
<br> 

## Tools Used:-
- AWS Security Hub <br>
- AWS Inspector <br>
- AWS CloudTrail <br>
- AWS VPC Flow Logs <br>
- AWS IAM Password Policy Analyzer <br>
- Nmap <br>
- Nessus <br>
- Burp Suite <br>
- Metasploit <br>
- Prowler <br>
- Pacu <br>
- ScoutSuite <br>
- cloudmapper <br>
