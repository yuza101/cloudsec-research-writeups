# cloudsec-research-writeups
Publicly available CloudSec research writeups from great researchers on AWS, GCP, Azure, OCI and more.

This repository was inspired by [xdavidhu](https://github.com/xdavidhu/awesome-google-vrp-writeups)’s Google VRP writeups repository. While his repository covers Google VRP writeups in general, this one is focused specifically on cloud-related writeups on any cloud providers. Be sure to check out his repository as well.

## Google Cloud
1. [GatewayToHeaven: Finding a Critical Cross-Tenant Exploit in GCP's Apigee](https://omeramiad.com/posts/gatewaytoheaven-gcp-cross-tenant-vulnerability) (**@omer_asfu**)
2. [Kicking the Bucket: Critical RCE and Cross-Tenant Exploits in 3 Different GCP Products](https://focalsecurity.io/blog/kicking-the-bucket-gcp-cross-tenant/) (**@omer_asfu**)
3. [Privilege Escalation via a service account impersonation chain](https://jdsec.cloud/posts/2026-01-17-privilege-escalation-via-a-service-account-impersonation-chain/) (**@j_domeracki**)
4. [Hunting for Bucket Traversals in Google's Client Libraries](https://jdomeracki.github.io/2025/05/04/hunting_for_bucket_traversals/) (**@j_domeracki**)
5. [Cross-tenant compromise of Application Design Center spaces via bucket squatting](https://bughunters.google.com/reports/vrp/HRDqQWSLs) (**@j_domeracki**)
6. [ConfusedComposer: A Privilege Escalation Vulnerability Impacting GCP Composer](https://www.tenable.com/blog/confusedcomposer-a-privilege-escalation-vulnerability-impacting-gcp-composer) (**@terminatorLM**)
7. [LeakyLooker: Hacking Google Cloud’s Data via Dangerous Looker Studio Vulnerabilities](https://www.tenable.com/blog/leakylooker-google-cloud-looker-studio-vulnerabilities) (**@terminatorLM**)
8. [StubZero: $148,337 RCE in Google Cloud Production](https://brutecat.com/articles/google-cloud-rce/) (**@brutecat**)
9. [How Attackers Can Exploit GCP's Multicloud Workload Solution](https://www.tenable.com/blog/how-attackers-can-exploit-gcps-multicloud-workload-solution) (**@terminatorLM & @NoamDahan**)
10. [ConfusedFunction: A Privilege Escalation Vulnerability Impacting GCP Cloud Functions](https://www.tenable.com/blog/confusedfunction-a-privilege-escalation-vulnerability-impacting-gcp-cloud-functions) (**@terminatorLM**)
11. [CloudImposer: Executing Code on Millions of Google Servers with a Single Malicious Package](https://www.tenable.com/blog/cloudimposer-executing-code-on-millions-of-google-servers-with-a-single-malicious-package) (**@terminatorLM**)
12. [ImageRunner: A Privilege Escalation Vulnerability Impacting GCP Cloud Run](https://www.tenable.com/blog/imagerunner-a-privilege-escalation-vulnerability-impacting-gcp-cloud-run) (**@terminatorLM**)
13. [Two RCEs in Google Cloud products and Nike Air Max 90s](https://stazot.com/?article=dataprep-actifio-jar-swapping-rce) (**@sivaneshashok, @kl_sree & @asterfiester**)
14. [LookOut: Discovering RCE and Internal Access on Looker (Google Cloud & On-Prem)](https://www.tenable.com/blog/google-looker-vulnerabilities-rce-internal-access-lookout) (**@terminatorLM**)
15. [Tutorial on privilege escalation and post exploitation tactics in Google Cloud Platform environments](https://about.gitlab.com/blog/plundering-gcp-escalating-privileges-in-google-cloud-platform/#service-account-impersonation) (**Chris Moberly**)
16. [Privilege escalation via GKE Metadata protection downgrade attack scenario](https://bughunters.google.com/reports/vrp/BrQZ18W5k) (**@j_domeracki**)
17. [$36k Google App Engine RCE](https://www.ezequiel.tech/p/36k-google-app-engine-rce.html) (**Ezequiel Pereira**)
18. [RCE in Google Cloud Deployment Manager](https://www.ezequiel.tech/2020/05/rce-in-cloud-dm.html) (**Ezequiel Pereira**)
19. [$7.5k Google Cloud Platform organization issue](https://www.ezequiel.tech/2019/01/75k-google-cloud-platform-organization.html) (**Ezequiel Pereira**)
20. [$7.5k Google services mix-up](https://www.ezequiel.tech/p/75k-google-services-mix-up.html) (**Ezequiel Pereira**)
21. [Remote Command Execution in Google Cloud with Single Directory Deletion](https://flatt.tech/research/posts/remote-command-execution-in-google-cloud-with-single-directory-deletion/) (**@ryotkak**)
22. [The Trifecta: How Three New Gemini Vulnerabilities in Cloud Assist, Search Model, and Browsing Allowed Private Data Exfiltration](https://www.tenable.com/blog/the-trifecta-how-three-new-gemini-vulnerabilities-in-cloud-assist-search-model-and-browsing) (**@terminatorLM**)
23. [My first bug in Google Cloud: Command injection in Vertex AI](https://buganizer.cc/bug_vertex_ai/) (**@valent1nee**)
24. [Google Cloud Account Takeover via URL Parsing Confusion](https://infosecwriteups.com/google-cloud-account-takeover-via-url-parsing-confusion-c5e47389b7c7) (**Mohamed Benchikh**)
25. [Sketchy Cheat Sheet - Story of a Cloud Architecture Diagramming Tool gone wrong](https://jdomeracki.github.io/2024/11/09/sketchy_cheat_sheet/) (**@j_domeracki**)
26. [Escalating Privileges in Google Cloud via Open Groups](https://www.netspi.com/blog/technical-blog/cloud-pentesting/escalating-privileges-in-google-cloud-via-open-groups/) (**Thomas E.**)
27. [Unveiling TE.0 HTTP Request Smuggling: Discovering a Critical Vulnerability in Thousands of Google Cloud Websites](https://www.bugcrowd.com/blog/unveiling-te-0-http-request-smuggling-discovering-a-critical-vulnerability-in-thousands-of-google-cloud-websites/) (**@sw33tLie**)
28. [Google Cloud Vertex AI - Data Exfiltration Vulnerability Fixed in Generative AI Studio](https://embracethered.com/blog/posts/2023/google-gcp-generative-ai-studio-data-exfiltration-fixed/) (**@wunderwuzzi23**)
29. [GCP CloudSQL Vulnerability Leads to Internal Container Access and Data Exposure](https://web.archive.org/web/20230525144859/https://www.dig.security/post/gcp-cloudsql-vulnerability-leads-to-internal-container-access-and-data-exposure) (**@ofir_balassiano**)
30. [Hijacking Cloud CI/CD Systems for Fun and Profit](https://seg-fault.gitbook.io/researchs/hijacking-cloud-ci-cd-systems-for-fun-and-profit) (**Divyanshu**)
31. [Exploring Eclipse IDE Attack Vectors: Unveiling Google Cloud Tools Plugin Vulnerabilities](https://medium.com/@moh.abo.sakr/exploring-eclipse-ide-attack-vectors-unveiling-google-cloud-tools-plugin-vulnerabilities-ff334a56a44c) (**Mo Sakr**)
32. [Unveiling a Critical Authentication Bypass Vulnerability in Google Cloud API Gateway](https://securingbits.com/bypassing-google-cloud-api-gateway) (**Securing Bits**)
33. [Identity-Aware Proxy Misconfiguration- Google Cloud Vulnerability](https://medium.com/@LogicalHunter/identity-aware-proxy-misconfiguration-google-cloud-vulnerability-813d2a07a4ed) (**Borna Nematzadeh**)
34. [XSS using postMessage in Google Cloud Theia notebooks [Google VRP]](https://blog.geekycat.in/xss-using-postmessage-in-google-cloud-theia-notebooks/) (**Sreeram KL**)
35. [Bypassing authorization in Google Cloud Workstations [Google VRP]](https://blog.stazot.com/ssh-key-injection-google-cloud/) (**Sivanesh Ashok**)
36. [SSH key injection in Google Cloud Compute Engine [Google VRP]](https://blog.stazot.com/auth-bypass-in-google-cloud-workstations/) (**Sivanesh Ashok**)
37. [Client-Side SSRF to Google Cloud Project Takeover [Google VRP]](https://blog.geekycat.in/client-side-ssrf-to-google-cloud-project-takeover/) (**Sreeram KL**)
38. [Few bugs in the google cloud shell](https://obmiblog.blogspot.com/2022/12/gcp-2022-few-bugs-in-google-cloud-shell.html) (**Obmi**)
39. [ApatchMe - Authenticated Stored XSS Vulnerability in AWS and GCP Apache Airflow Services](https://www.tenable.com/blog/apatchme-authenticated-stored-xss-vulnerability-in-aws-and-gcp-apache-airflow-services) (**@terminatorLM**)

## AWS
1. [FlowFixation: AWS Apache Airflow Service Takeover Vulnerability and Why Neglecting Guardrails Puts Major CSPs at Risk](https://www.tenable.com/blog/flowfixation-aws-apache-airflow-service-takeover-vulnerability-and-why-neglecting-guardrails) (**@terminatorLM**)

## Azure
1. [Uncovering 3 Azure API Management Vulnerabilities – When Good APIs Go Bad](https://www.tenable.com/blog/uncovering-3-azure-api-management-vulnerabilities-when-good-apis-go-bad) (**@terminatorLM**)
2. [These Services Shall Not Pass: Abusing Service Tags to Bypass Azure Firewall Rules (Customer Action Required)](https://www.tenable.com/blog/these-services-shall-not-pass-abusing-service-tags-to-bypass-azure-firewall-rules-customer) (**@terminatorLM**)

## Microsoft Entra ID (formerly Azure AD)
1. [One Token to rule them all - obtaining Global Admin in every Entra ID tenant via Actor tokens](https://dirkjanm.io/obtaining-global-admin-in-every-entra-id-tenant-with-actor-tokens/) (**Dirk-jan Mollema**)

## Oracle Cloud Infrastructure (OCI)
1. [OCI, Oh My: Remote Code Execution on Oracle Cloud Shell and Code Editor Integrated Services](https://www.tenable.com/blog/remote-code-execution-on-oracle-cloud-shell-and-code-editor-integrated-services) (**@terminatorLM**)
