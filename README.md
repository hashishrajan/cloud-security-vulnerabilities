# Goal:
List of all the Publicly disclosed vulnerabilities of Public Cloud Provider like Amazon Web Services (AWS), Microsoft Azure, Google Cloud, Oracle Cloud, IBM Cloud etc

NOTE: This list will not cover any data breaches caused by misconfiguration

Table of contents
=================

<!--ts-->

* [Contribute](#Contribute)
* [Cloud Security Provider Vulnerabilites](#cloud-service-provider-vulnerabilites)
  * [Amazon Web Services (AWS)](#amazon-web-services-aws)
  * [Microsoft Azure](#microsoft-azure)
  * [Google Cloud ](#google-cloud )
  * [Oracle Cloud](#oracle-cloud)
  * [IBM Cloud](#ibm-cloud)
  * [All Cloud](#all-cloud)
* [Useful Links](#useful-links)
  * [Security Bulletin](#security-bulletin)
  * [Vulnerability Disclosure](#vulnerability-disclosure)
<!--te-->


# Contribute
Do you want to contribute to this list? Feel free to send a PR.

# Cloud Service Provider Vulnerabilites

### Amazon Web Services (AWS) 
- [AWS: Execution in CloudFormation service account](https://onecloudplease.com/blog/security-september-cataclysms-in-the-cloud-formations) - Published: 26 August,2020 - Status: RESOLVED
- [AWS IAM Cross Account](https://www.wiz.io/blog/black-hat-2021-aws-cross-account-vulnerabilities-how-isolated-is-your-cloud-environment/) - Published: 4 August,2021 - Status: RESOLVED
- [AWS SageMaker Notebook](https://blog.lightspin.io/aws-sagemaker-notebook-takeover-vulnerability) - Published: 7 December,2021 - Status: RESOLVED
- [Breaking Formation: AWS Cloudformation](https://orca.security/resources/blog/aws-cloudformation-vulnerability/) - Published: 13 Jan,2022 - Status: RESOLVED
- [SuperGlue: AWS Glue](https://orca.security/resources/blog/aws-glue-vulnerability/) - Published: 13 Jan,2022 - Status: RESOLVED
- [AWS EKS Authentication Vulnerabilty](https://blog.lightspin.io/exploiting-eks-authentication-vulnerability-in-aws-iam-authenticator) - Published: 11 Jul,2022 - Status: RESOLVED (requires User Intervention in certain scenarios to fix)
- [AWS S3 Replication Service - Only logs first destination bucket](https://www.vectra.ai/blogpost/abusing-the-replicator-silently-exfiltrating-data-with-the-aws-s3-replication-service) - Published: 20 Jul,2022 - Status: NO FIX PROVIDED
- [AWS CodeArtifact - Depedency Confusion](https://zego.engineering/dependency-confusion-in-aws-codeartifact-86b9ff68963d) - Published: 28 Jul,2022 - Status: RESOLVED
- [AWS CloudTrail - iamadmin CloudTrail Bypass](https://securitylabs.datadoghq.com/articles/iamadmin-cloudtrail-bypass/) - Published: 17 January,2023 - Status: RESOLVED
- [AWS App Runner Cross Tenant](https://frichetten.com/blog/minor-cross-tenant-vulns-app-runner/)- Published:3 April,2023 - Status: RESOLVED

### Microsoft Azure 
- [ChaosDB:Azure Cosmos DB](https://www.wiz.io/blog/how-we-broke-the-cloud-with-two-lines-of-code-the-full-story-of-chaosdb/) - Published: 7 August,2021 - Status: RESOLVED
- [Azure: Azurescape](https://unit42.paloaltonetworks.com/azure-container-instances/) - Published: 9 September,2021 - Status: RESOLVED
- [OMIGOD:Microsoft Open Management Infrastructure (OMI)](https://www.wiz.io/blog/secret-agent-exposes-azure-customers-to-unauthorized-code-execution/) - Published: 14 September,2021 - Status: RESOLVED
- [NotLegit: Azure App Service](https://www.wiz.io/blog/azure-app-service-source-code-leak/) - Published: 21 December,2021 - Status: RESOLVED
- [ExtraReplica:Azure PostgreSQL](https://www.wiz.io/blog/wiz-research-discovers-extrareplica-cross-account-database-vulnerability-in-azure-postgresql/) - Published: 28 April,2022 - Status: RESOLVED
- [AutoWrap: Azure Automation](https://orca.security/resources/blog/autowarp-microsoft-azure-automation-service-vulnerability/) - Published: 7 March,2021 - Status: RESOLVED
- [Synapse: Azure Synapse Analytics](https://orca.security/resources/blog/azure-synapse-analytics-security-advisory/) - Published: 9 May,2021 - Status: PARTIAL(requires User Caution)
- [FabricSCape: Microsoft Service Fabric - commonly used with many Azure offerings](https://unit42.paloaltonetworks.com/fabricscape-cve-2022-30137/) - Published: 14 June,2022 - Status: RESOLVED (requires User Intervention in certain scenarios to fix)
- [Azure WAF - Pattern bypass with OWASP 3.2 managed rule set](https://twitter.com/justm0rph3u5/status/1542943538857799680) - Published: 2 July,2022 - Status: RESOLVED
- [Azure Site Recovery service susceptible to DLL Hijacking flaw](https://medium.com/tenable-techblog/microsoft-azure-site-recovery-dll-hijacking-cd8cc34ef80c) - Published: 13 July,2022 - Status: RESOLVED
- [Azure Database for PostgreSQL - escape to host](https://www.wiz.io/blog/the-cloud-has-an-isolation-problem-postgresql-vulnerabilities) - Published 12 August,2022 - STATUS: RESOLVED
- [Azure Synapse Analytics](https://orca.security/resources/blog/synapse-local-privilege-escalation-vulnerability-spark/) - Published: 1 September,2022 - Status: RESOLVED
- [Azure Cloud Shell Command Injection Stealing User’s Access Tokens](https://blog.lightspin.io/azure-cloud-shell-command-injection-stealing-users-access-tokens) - Published: 20 September,2022 - Status: RESOLVED
- [Authenticated SSRF Vulnerability on Azure API Management Service](https://orca.security/resources/blog/ssrf-vulnerabilities-azure-api-management/) - Published: 17 January,2023 - Status: RESOLVED
- [Authenticated SSRF Vulnerability on Azure Machine Learning Service](https://orca.security/resources/blog/ssrf-vulnerabilities-azure-machine-learning/) - Published: 17 January,2023 - Status: RESOLVED
- [Unauthenticated SSRF Vulnerability on Azure Digital Twins Explorer](https://orca.security/resources/blog/ssrf-vulnerabilities-azure-digital-twins/) - Published: 17 January,2023 - Status: RESOLVED
- [Unauthenticated SSRF Vulnerability on Azure Functions](https://orca.security/resources/blog/ssrf-vulnerabilities-azure-functions-app/) - Published: 17 January,2023 - Status: RESOLVED
- [Azure Active Directory B2C service – Crypto Misuse and Account Compromise](https://www.praetorian.com/blog/azure-b2c-crypto-misuse-and-account-compromise/) - Published: 15 February,2023 - Status: RESOLVED
 - [Super FabriXss: From XSS to an RCE in Azure Service Fabric Explorer](https://orca.security/resources/blog/super-fabrixss-azure-vulnerability/) - Published: 30 March,2023 - Status: RESOLVED
 
### Google Cloud 
- [Cloud SQL's PostgreSQL engine - escape to host](https://www.wiz.io/blog/the-cloud-has-an-isolation-problem-postgresql-vulnerabilities) - Published 12 August,2022 - STATUS: RESOLVED
- [Asset Key Thief - Google Cloud privilege escalation vulnerability that enabled principals with the "Cloud Asset Viewer" role](https://engineering.sada.com/asset-key-thief-disclosure-cfae4f1778b6) - Published 19 April,2023 - STATUS: RESOLVED


### Oracle Cloud 
- [AttachMe: critical OCI vulnerability allows unauthorized access to customer cloud storage volumes](https://www.wiz.io/blog/attachme-oracle-cloud-vulnerability-allows-unauthorized-cross-tenant-volume-access) - Published 21 September,2022 - STATUS: RESOLVED

### IBM Cloud 

### Alibaba Cloud
- [BrokenSesame](https://www.wiz.io/blog/brokensesame-accidental-write-permissions-to-private-registry-allowed-potential-r)  - Published 19 April,2023 - STATUS: RESOLVED

### All Cloud
- [sudo vulnerability](https://www.wiz.io/blog/recent-linux-sudo-vulnerability-affects-a-major-percent-of-cloud-workloads/) - Published 6 August,2021 - Status: PARTIAL (requires User Caution)
- [Dynamic DNS](https://www.wiz.io/blog/is-your-organization-leaking-sensitive-dynamic-dns-data-heres-how-to-find-out/) - Published 6 August,2021 - Status: PARTIAL (requires User Caution)
- [Log4Shell](https://snyk.io/blog/log4j-vulnerability-software-supply-chain-security-log4shell/) - Published 13 December,2021 - Status: Resolved
- [Spring4Shell](https://security.snyk.io/vuln/SNYK-JAVA-ORGSPRINGFRAMEWORKCLOUD-2436645) - Published 13 March,2022 - Status: Resolved

# Useful Links

## Security Bulletin
* Amazon Web Services (AWS) - ([link](https://aws.amazon.com/security/security-bulletins/))
* Microsoft - ([link](https://docs.microsoft.com/en-us/security-updates/))
* Google Cloud -  ([link](https://cloud.google.com/support/bulletins))

## Vulnerability Disclosure
All identified vulnerabilities should be disclosed to the vendors/maintainers of affected software or hardware systems directly. All major cloud providers have published disclosure addresses
* AWS - ([link](https://aws.amazon.com/security/vulnerability-reporting/))
* Azure - ([link](https://www.microsoft.com/en-us/msrc/bounty))
* Google GCP - ([link](https://www.google.com/appserve/security-bugs/m2/new))
* Oracle OCI - ([link](https://www.oracle.com/corporate/security-practices/assurance/vulnerability/reporting.html)).

## Other Community Links - you may find helpful for Cloud Security
* Toni De La Fuente - [My-Arsenal-of-aws-security-tools](https://github.com/toniblyx/my-arsenal-of-aws-security-tools)
* Wiz - [Cloud Vulnerability Database] [cloudvulndb](https://www.cloudvulndb.org/)
* Orca Security - [Cloud Risk Encyclopedia](https://orca.security/resources/cloud-risk-encyclopedia/)
* LightSpin - [Attack Path for Domains](https://recon.cloud/)
* Snyk - [Open Source Vulnerability Database](https://security.snyk.io/)
* JupiterOne - [Starbase - a Graph-based security analysis](https://github.com/JupiterOne/starbase)

For more Cloud Security Resources, Training, Interviews and more check out Cloud Security Podcast 
[Website](www.cloudsecuritypodcast.tv) | [YouTube](https://www.youtube.com/c/CloudSecurityPodcast?sub_confirmation=1) | [Linkedin](https://www.linkedin.com/company/cloud-security-podcast/) | [Apple](https://podcasts.apple.com/us/podcast/cloud-security-podcast/id1489678590) | [Spotify](https://open.spotify.com/show/6LZgeh4GecRYPc0WrwMB4I) | [Twitter](https://twitter.com/CloudSecPod)
