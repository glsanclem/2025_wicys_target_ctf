---
layout: default
title: "P2: Hidden Challenges"
---

# P2. Hidden Challenges

**Points:** 30  
**Level:** Simple  
**Category:** Tutorial  

---

## Description
<span style="color: #ffcc00; font-weight: bold;">F</span>ollowing a narrative means some challenges could spoil earlier ones, so most challenges will be hidden at the beginning. <span style="color: #ffcc00; font-weight: bold;">L</span>etting yourself bounce between the offensive and defensive challenges should prevent you from getting stuck. <span style="color: #ffcc00; font-weight: bold;">A</span>s you complete challenges, more will be unlocked — this also helps you get a feel for how an attack would actually unfold!

---

## Objective/Challenge
<span style="color: #ffcc00; font-weight: bold;">G</span>et the flag by finding the hidden message spelled out by combining the first letter in each sentence.

---

## Tools Used
Cognitive tools: CEO of the brain, working memory, selective attention

---

## Methodology + Solution
This was another challenge that required carefully reading instructions, paying close attention to details, and analyzing information. I noticed that the first letter of each sentence was bold and highlighted. I thought that was a bit odd and kept that minor detail in mind.  After reading the instructions, I immediately knew the bold letters was the flag.  **Lesson**: Follow your intuition. If something feels off, take note of it, as it just might be the answer to your flag.  

---

## Flag
`FLAG`  

---

## MITRE ATT&CK
- **Tactics**: Reconnaissance (TA0043); Discovery (TA0007); Collection (TA0009). 
- **Techniques**: For **Reconnaissance**, actively scanning the target’s message to identify any messages that appear a bit off. For **Discovery**, discovering files that may have sensitive data. For **Collection**, capturing and storing the data obtained from the message. 
- **Procedures**: As the defender, I performed analysis to gather intelligence to prevent the attack. My discovery process entailed revealing the artifacts (individual letters) and collecting the evidence to understand its full scope and perform forensics.  
