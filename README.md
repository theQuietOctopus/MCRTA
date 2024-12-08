# MCRTA

## Introduction
This repository contains my review and some study notes for the **MCRTA** course by CWL. It is designed to help others preparing for this course by providing a structured summary of the key concepts, tips, and resources.

## Table of Contents
1. [About the Certification](#about-the-certification)
2. [Topics Covered](#topics-covered)
3. [Resources](#resources)
4. [Exam Tips](#tips)
5. [Acknowledgments](#acknowledgments)

## About the Certification
- **Name**: MCRTA - Multi-Cloud Red Team Analyst
- **Issuer**: CWL - CyberWarfareLabs
- **Prerequisites**: Familiarity with Command Line Interface
- **Target Audience**: Red Teamers, Penetration Testers, Security Enginners
- **Format**: Life-time access to MCRTA lab and 30 Flags to submit

## Topics Covered
Mainly transversal to all domains AWS, Microsoft Azure and GCP
### Domains: AWS, Microsoft Azure and GCP
- Architecture
- IAM
- Authentication (GUI and CLI)
- CLI Enumeration
- Red Team Operations (Manual and Automated)
### My Takeaway
The MCRTA certification course is an excellent entry point for anyone new to cloud red teaming, offering hands-on labs across AWS, Azure, and GCP environments. It’s particularly appealing due to its affordability—available for just $5 during promotions like Black Friday.
The course excels in providing a structured overview of each cloud provider, from their architecture to IAM. However, the lab environments are mostly focused on enumeration, lacking aspects like lateral movement or privilege escalation, which are covered in the videos but not hands-on. Despite these limitations, the course delivers a beginner-friendly introduction to key cloud red teaming activities such as enumeration, escalation, exfiltration, and persistence.
The AWS section provides valuable insights, but tools like Pacu require troubleshooting if you're working from RedCloudOS and the course could dive a bit into OSINT techniques and tools. Azure’s material requires a deeper understanding and independent research to capture flags, encouraging learners to think critically. Finally, The GCP content touches on automation but could expand further on showing the use of these tools with practical scenarios.

Overall, the course offers a solid starting point, especially considering its price, but could benefit from more polished materials and clearer guidance on next steps after completing the documentation and videos and before initiating the labs and capturing the flags.

## Resources
- [CyberWarFare Labs](https://cyberwarfare.live/)
- [Course](https://cyberwarfare.live/product/multi-cloud-red-team-analyst-mcrta/)
- [RhinoSecurityLabs](https://github.com/RhinoSecurityLabs)
- [RedCloudOS](https://github.com/RedTeamOperations/RedCloud-OS?tab=readme-ov-file)
- [Verify](https://labs.cyberwarfare.live/badge/image/6755fc24f6d2b394d978185d)

## Tips
1. Setup Recommendations: If you're facing issues with outdated/broken tools like Pacu in RedCloudOS, consider setting up a clean environment on Kali Linux or Parrot OS. This ensures smoother operation and minimizes errors.
2. Course Material Insights: The study material is essentially the slides from the video lessons, so focus on the videos for in-depth understanding.
3. Flags and Hints: The lack of OSINT guidance might require you to rely on provided hints, so if you are feeling a bit lost, don't skip those.

## Acknowledgments
Thanks to [CyberWarFare Labs](https://cyberwarfare.live/) for providing this awesome course for such a cheap price.
