# Phishing-Email-Analysis-Task-2

Overview

This task focuses on analyzing a sample phishing email to identify common indicators of email-based attacks. The objective is to understand how attackers use spoofing, social engineering, malicious links, and header manipulation to trick users into revealing sensitive information. The analysis was performed using a publicly available phishing email sample and free online header analysis tools.

Email Examination Process

The first step was examining the sender’s email address. Although the display name appeared legitimate, the actual email domain was suspicious and did not match the organization it claimed to represent. This mismatch is a common phishing tactic known as email spoofing.
Next, the email headers were analyzed using an online header analyzer. During the inspection, inconsistencies were observed in authentication results such as SPF, DKIM, and DMARC checks. The originating IP address also did not align with the claimed sender domain, which further indicated possible spoofing.
The body of the email contained urgent and threatening language designed to pressure the recipient into taking immediate action. Phrases such as “Your account will be suspended” and “Immediate action required” were used to create panic. This is a classic social engineering technique used in phishing campaigns.
Embedded links in the email were carefully inspected by hovering over them to reveal their true destination. The visible link text suggested a trusted website, but the actual URL redirected to an unrelated or suspicious domain. This URL mismatch is a strong phishing indicator.
Additionally, minor spelling and grammatical errors were identified in the email content. While not always present, such errors often indicate fraudulent communication.

Phishing Indicators Identified

The analysis revealed multiple phishing characteristics, including sender domain mismatch, suspicious originating IP address, authentication failures in email headers, misleading hyperlinks, urgent language, and minor grammar inconsistencies. The combination of these indicators confirms that the email is likely malicious.

Key Concepts Covered

This task involved practical understanding of phishing attacks, email spoofing techniques, header authentication mechanisms (SPF, DKIM, DMARC), URL inspection, and social engineering tactics.

Conclusion

Through this analysis, I developed a structured approach to identifying phishing emails by systematically examining sender information, header data, email content, and embedded links. This task strengthened my ability to detect potential threats and improved my awareness of common phishing tactics used in real-world cyber attacks.
