---
title: "Mallox Ransomware Exploits Weak MS-SQL Servers to Breach Networks"
description: "Mallox ransomware activities in 2023 have witnessed a 174% increase when compared to the previous year, new findings from Palo Alto Networks Unit 42 reveal."
pubDate: "Jul 20 2023"
heroImage: "/test.jpg"
---

New research from Palo Alto Networks Unit 42 has revealed a staggering 174% surge in Mallox ransomware activities in 2023 compared to the previous year.

According to security researchers Lior Rochberger and Shimi Cohen, Mallox ransomware follows the double extortion trend, where data is stolen before encrypting an organization's files. The threat actors then leverage this stolen data by threatening to publish it on a leak site, coercing victims to pay the ransom fee. Mallox has been linked to a threat actor associated with other ransomware strains like TargetCompany, Tohnichi, Fargo, and the recent Xollam, making its debut in June 2021.

The manufacturing, professional and legal services, and wholesale and retail sectors have been prominent targets for Mallox. One striking characteristic of this group is its exploitation of poorly secured MS-SQL servers through dictionary attacks as a penetration vector to breach victims' networks. Xollam, on the other hand, deviates from this pattern, having been observed employing malicious OneNote file attachments for initial access.

Once Mallox gains a foothold on the infected host, it executes a PowerShell command to retrieve the ransomware payload from a remote server. The binary takes further action by attempting to stop and remove SQL-related services, deleting volume shadow copies, clearing system event logs, terminating security-related processes, and bypassing Raccine, an open-source tool designed to counter ransomware attacks. After the encryption process is completed, a ransom note is dropped in every directory.

While TargetCompany remains a closed, small group, it has been seen recruiting affiliates for the Mallox ransomware-as-a-service (RaaS) program on the RAMP cybercrime forum.

The rise in Mallox's activities coincides with the ongoing lucrative financial success of ransomware, which netted cybercriminals a staggering $449.1 million in the first half of 2023, according to Chainalysis.

The researchers caution that the increased activity and recent recruiting efforts of the Mallox ransomware group could lead to more attacks on organizations if their recruitment drive proves successful. As ransomware continues to evolve and wreak havoc, it remains crucial for cybersecurity professionals to remain vigilant and adopt proactive security measures to safeguard against such threats.
