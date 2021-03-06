![](https://raw.githubusercontent.com/frankietyrine/Tenable.io-Certificate-of-Proficiency-notes/master/b90d76d59285a7d037d2c46ed964d2f4b8b490de.png)
# Tenable.io Certificate of Proficiency Notes
https://university.tenable.com/learn/course/
## [Tenable.io Container Security]()
This course will help users view vulnerability, malware and other security data for all container images, as well as the distribution of vulnerabilities across images by CVSS score and risk level. It explains how to create policies for repositories, conduct a full inventory of image layers and components, and provide a detailed assessment of container image risk by repository.

### Tenable.io for Docker 
- check docker file for vulnerable softwares 
- push image to tenable.io Registry to be scanned and further tested 
  - login ```docker login -u username -p password resigtry.cloud.tenable.com```
  - push container ```docker push registry.cloud.tenable.com/alpine ```
- continuously monitoring of containers activities 
- add policy to block critical vulnerable containers
- integrate with jenkins all images are automatically tested in the registry 
![](jenkins.PNG)
## [Tenable.io Web Application Scanning](#tenableio-container-security-notes)
While organizations build increasingly complex business applications, vulnerabilities in those applications continue to plague the security team tasked with identifying and addressing security risks. Part of the Tenable.io platform, Tenable.io Web Application Scanning delivers safe and automated vulnerability scanning that covers your entire online portfolio. In this series, you will learn how to discover your web applications, safely assess them to avoid downtime, and easily report the findings so you can prioritize remediation.

