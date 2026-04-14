# ICDFA Internship Programme -- Instructor Guide & Delivery Notes

**Version:** 1.0  
**Effective Date:** April 2026  
**Audience:** ICDFA Instructors and Facilitators

---

## Overview

This guide provides instructors with comprehensive delivery notes, pacing recommendations, common student challenges, lab setup instructions, and assessment rubrics for the ICDFA Cybersecurity Internship Programme (CIP).

---

## Part 1: Course Delivery Framework

### General Principles

1. **Lab-Centric Learning:** The programme is 70% hands-on labs and 30% theoretical instruction. Prioritize lab time.
2. **Scaffolded Difficulty:** Courses progress from foundational (Linux) to advanced (Cloud Security, Digital Forensics).
3. **Peer Learning:** Encourage interns to work in pairs on labs and share findings.
4. **Real-World Context:** Connect each lab to actual security incidents or industry use cases.

### Weekly Structure

Each week should follow this pattern:

- **Monday:** Course introduction, learning objectives, and theoretical overview (2 hours)
- **Tuesday-Thursday:** Hands-on labs with instructor support (6 hours per day)
- **Friday:** Lab review, Q&A, and assessment preparation (2 hours)

---

## Part 2: Track A -- Ethical Hacking Delivery Notes

### CIP-A101 & CIP-A102: Linux Systems Fundamentals I & II (Weeks 1-6)

**Pacing Recommendations:**
- Week 1-3 (A101): Focus on shell fundamentals, file management, and basic system administration
- Week 4-6 (A102): Advance to user management, networking, and security concepts
- Allocate 1 hour per lab for completion

**Common Student Challenges:**
- Struggling with command-line syntax and permissions
- Confusion between absolute and relative file paths
- Difficulty understanding shell scripting logic

**Mitigation Strategies:**
- Provide a "Linux Command Cheat Sheet" on day one
- Use visual diagrams for file system hierarchy
- Pair struggling interns with advanced peers for lab support

**Lab Setup Notes:**
- Ensure all interns have access to NDG NETLAB+ accounts before Week 1
- Test lab connectivity on Day 1 to avoid delays
- Provide backup lab access via local VirtualBox if NETLAB+ is unavailable

**Assessment Rubric:**
- Chapter Exams (40%): Test conceptual understanding
- Lab Completion (40%): All 21/18 labs must be completed
- Midterm/Final Exams (20%): Comprehensive assessment

---

### CIP-A103: Network Defence & Traffic Analysis (Weeks 7-8)

**Pacing Recommendations:**
- Week 7: Introduce DHCP, certificates, and packet capture concepts
- Week 8: Focus on analyzing captures and understanding encryption
- Allocate 2 hours per lab for hands-on practice

**Common Student Challenges:**
- Difficulty interpreting packet capture data
- Confusion about SSL/TLS decryption and certificate management
- Limited understanding of network protocols

**Mitigation Strategies:**
- Use Wireshark demonstrations before labs
- Provide pre-configured packet captures for analysis
- Explain OSI model layers and protocol relationships

**Lab Setup Notes:**
- Pre-configure Palo Alto Networks environment with sample traffic
- Ensure interns understand packet capture limitations and legal implications
- Provide network topology diagrams for reference

**Assessment Rubric:**
- Lab Completion (50%): All 8 labs with passing scores
- Packet Analysis Report (30%): Ability to identify threats in captures
- Final Exam (20%): Conceptual understanding of network security

---

### CIP-A104 & CIP-A105: Offensive Security Operations I & II (Weeks 9-13)

**Pacing Recommendations:**
- Week 9-11 (A104): Reconnaissance, scanning, enumeration, exploitation
- Week 12-13 (A105): Advanced exploitation, post-exploitation, covering tracks
- Allocate 3-4 hours per lab due to complexity

**Common Student Challenges:**
- Ethical concerns about hacking techniques
- Difficulty understanding exploitation chains
- Confusion about Metasploit framework usage
- Overwhelm from the breadth of tools and techniques

**Mitigation Strategies:**
- Begin with ethical hacking principles and legal frameworks
- Use isolated lab environments (no real-world targets)
- Provide step-by-step Metasploit tutorials
- Break complex labs into sub-tasks
- Emphasize responsible disclosure practices

**Lab Setup Notes:**
- Create isolated lab networks with intentionally vulnerable systems
- Pre-configure Metasploit with common exploit modules
- Provide target machine credentials and documentation
- Document all lab scenarios with learning objectives

**Assessment Rubric:**
- Lab Completion (50%): All 18+8 labs with passing scores
- Penetration Test Report (30%): Professional documentation of findings
- Final Exam (20%): Understanding of hacking methodologies and ethics

---

### CIP-A106: Critical Infrastructure & ICS Security (Weeks 14-16)

**Pacing Recommendations:**
- Week 14: Introduction to PLCs, SCADA, and ICS protocols
- Week 15: Hands-on PLC programming and SCADA simulation
- Week 16: ICS penetration testing and defensive measures
- Allocate 2-3 hours per lab

**Common Student Challenges:**
- Limited prior experience with industrial systems
- Difficulty understanding real-time control systems
- Concern about causing physical damage in simulations

**Mitigation Strategies:**
- Provide ICS fundamentals overview before labs
- Use safe simulation environments (no physical equipment)
- Invite guest lecturer from energy/utilities sector
- Emphasize safety-first approach to ICS testing

**Lab Setup Notes:**
- Configure simulated SCADA environments (e.g., HMI simulators)
- Provide PLC programming IDE and sample code
- Document ICS protocols and communication patterns
- Create realistic industrial network topologies

**Assessment Rubric:**
- Lab Completion (50%): All 14 labs with passing scores
- ICS Security Assessment Report (30%): Identification of vulnerabilities
- Final Exam (20%): Understanding of ICS threats and defenses

---

### CIP-A107: Security Operations Centre (SOC) Essentials (Weeks 17-18)

**Pacing Recommendations:**
- Week 17: Log analysis, threat detection, and SIEM usage
- Week 18: Incident response procedures and threat intelligence
- Allocate 2 hours per lab

**Common Student Challenges:**
- Difficulty correlating events across multiple logs
- Overwhelm from alert fatigue in SIEM environments
- Limited understanding of threat intelligence sources

**Mitigation Strategies:**
- Provide pre-configured SIEM with sample logs
- Use real-world incident scenarios
- Teach alert tuning and false positive reduction
- Provide threat intelligence feeds and resources

**Lab Setup Notes:**
- Configure Palo Alto Networks ACC or similar SIEM
- Pre-load sample logs from real incidents (anonymized)
- Document alert signatures and tuning procedures
- Provide threat intelligence API access

**Assessment Rubric:**
- Lab Completion (50%): All 8 labs with passing scores
- Incident Detection Report (30%): Ability to identify threats in logs
- Final Exam (20%): SOC operations and incident response procedures

---

### CIP-A108: Applied Security Engineering (Weeks 19-21)

**Pacing Recommendations:**
- Week 19-20: Security controls, cryptography, and system hardening
- Week 21: Incident response and forensics
- Allocate 2-3 hours per lab

**Common Student Challenges:**
- Complexity of cryptography concepts
- Difficulty understanding firewall rule logic
- Limited experience with security tools

**Mitigation Strategies:**
- Use visual representations of encryption processes
- Provide firewall rule templates and examples
- Demonstrate each tool before lab assignment
- Encourage experimentation in safe environments

**Lab Setup Notes:**
- Pre-configure firewalls, VPNs, and encryption tools
- Provide sample configurations and best practices
- Document security policy requirements
- Create realistic network scenarios

**Assessment Rubric:**
- Lab Completion (50%): All 25 labs with passing scores
- Security Implementation Report (30%): Design and deployment of controls
- Final Exam (20%): Security engineering principles and practices

---

### CIP-A109 & CIP-A110: Cloud Security (Weeks 22-25)

**Pacing Recommendations:**
- Week 22-23 (A109): Cloud fundamentals, Docker, container security
- Week 24-25 (A110): Kubernetes, DevSecOps, and cloud-native security
- Allocate 2 hours per lab

**Common Student Challenges:**
- Limited prior cloud experience
- Complexity of container orchestration concepts
- Confusion about cloud-native security models

**Mitigation Strategies:**
- Provide cloud fundamentals overview
- Use hands-on cloud platform access (AWS/Azure free tier)
- Demonstrate Docker and Kubernetes before labs
- Emphasize cloud-native security best practices

**Lab Setup Notes:**
- Provide AWS/Azure/GCP sandbox accounts
- Pre-configure Docker and Kubernetes environments
- Document cloud security tools and services
- Create realistic cloud deployment scenarios

**Assessment Rubric:**
- Lab Completion (50%): All 9+7 labs with passing scores
- Cloud Security Architecture Report (30%): Design of secure cloud environment
- Final Exam (20%): Cloud security concepts and DevSecOps practices

---

## Part 3: Track B -- Digital Forensics Delivery Notes

### CIP-B101: Basic Computer Skills for Digital Forensics (Weeks 1-3)

**Delivery Notes:**
- Begin with number systems and terminology before moving into command-line work
- Demonstrate how foundational computing knowledge supports later forensic interpretation
- Require students to document commands used and what each command reveals

**Lab Setup Notes:**
- Provide a simple Kali Linux VM and a Windows command prompt environment
- Supply short practice datasets for file navigation and hashing exercises

---

### CIP-B102: Foundations of Computer and Digital Forensics (Weeks 4-6)

**Pacing Recommendations:**
- Week 4: Introduction to digital forensics, Sleuth Kit basics, and USB imaging
- Week 5: Evidence search, metadata interpretation, and pattern matching
- Week 6: Data carving, steganography, and introductory reporting

**Common Student Challenges:**
- Confusing acquisition with analysis
- Difficulty understanding artefact provenance and evidential value
- Weak documentation habits during practical exercises

**Mitigation Strategies:**
- Model every lab as acquisition, validation, analysis, and reporting
- Emphasize hash verification and note-taking from the first exercise
- Use worked examples before independent analysis

---

### CIP-B103: Network Forensics Fundamentals (Weeks 7-8)

**Delivery Notes:**
- Teach packet review as evidence interpretation, not only protocol study
- Compare Wireshark GUI workflows with tshark command-line workflows
- Use timeline reconstruction from packet captures as the core assessment skill

**Lab Setup Notes:**
- Pre-stage packet captures for HTTP, SMTP, ARP, DNS, and wireless scenarios
- Provide answer keys for packet-level checkpoints rather than full solutions

---

### CIP-B104: Windows and Endpoint Forensics Casework (Weeks 9-12)

**Pacing Recommendations:**
- Week 9: NIST environment setup, registry, events, browser, and email artefacts
- Week 10: USN, shellbags, cloud/network traces, and NTFS artefacts
- Week 11: Search history, shadow copies, anti-forensics, carving, and password recovery
- Week 12: P2P leakage case, artifact correlation, and final timeline summary

**Common Student Challenges:**
- Overload from the volume of Windows artefacts
- Difficulty correlating user activity across multiple evidence sources
- Weak timeline reasoning when artifacts appear contradictory

**Mitigation Strategies:**
- Use artifact comparison sheets for registry, browser, MFT, USN, and logs
- Require intermediate timeline checkpoints before final conclusions
- Encourage pair discussion on alternative interpretations before grading

**Assessment Rubric:**
- Lab Completion (45%): Accurate processing of all assigned endpoint labs
- Timeline Reconstruction (30%): Clear, evidence-backed reconstruction of events
- Forensic Report (25%): Well-structured case narrative with cited artifacts

---

### CIP-B105: Applied Investigative Case Studies (Weeks 13-16)

**Pacing Recommendations:**
- Week 13: Illegal possession of images case
- Week 14: Email harassment case
- Week 15: Memory forensics case
- Week 16: Hacking case and Morris Worm investigation

**Common Student Challenges:**
- Jumping to conclusions from single artifacts
- Limited confidence in memory forensics interpretation
- Difficulty distinguishing scenario background from admissible evidence

**Mitigation Strategies:**
- Require students to label each conclusion with supporting artifacts
- Break memory labs into guided sub-questions
- Reinforce the difference between hypothesis, lead, and evidence

---

### CIP-B106: Mobile and IoT Forensics (Weeks 17-21)

**Pacing Recommendations:**
- Week 17: Eufy doorbell workflows and smart-home artifact interpretation
- Week 18: Echo Show acquisition and multimedia/application evidence
- Week 19: Android 10 evidence sources and app investigations
- Week 20: iPhone iOS artifact interpretation
- Week 21: Drone datasets and comparative mobile/IoT review

**Lab Setup Notes:**
- Provide read-only copies of mobile and IoT datasets where possible
- Explain the limits of chip-off and logical extraction evidence
- Use SQLite viewers and timeline templates consistently across device types

**Assessment Rubric:**
- Lab Completion (50%): Completion and accuracy across device-focused labs
- Evidence Interpretation (30%): Quality of artifact explanation and relevance
- Comparative Reflection (20%): Clear discussion of differences across device ecosystems

---

### CIP-B107: AI for Forensics and Capstone Intelligence Analysis (Weeks 22-25)

**Pacing Recommendations:**
- Week 22: AI-assisted forensic analysis foundations and hands-on notebooks
- Week 23: Browser history profiling and email-based insight generation
- Week 24: Forensic intelligence datasets and correlation workflows
- Week 25: Capstone report, presentation, and oral defence preparation

**Common Student Challenges:**
- Over-trusting AI-generated summaries
- Difficulty validating model output against original evidence
- Confusing investigative assistance with automated conclusions

**Mitigation Strategies:**
- Require side-by-side validation of AI output against source artifacts
- Grade transparency of method, not only final answers
- Emphasize disclosure of model limitations and examiner review

**Assessment Rubric:**
- AI/Notebook Exercises (25%): Correct and transparent use of AI-assisted workflows
- Evidence Correlation (35%): Quality of cross-source reasoning and validation
- Capstone Report (25%): Professional documentation and justification of findings
- Oral Defence (15%): Clear communication of methods, limitations, and conclusions

---
## Part 4: General Assessment & Grading

### Grading Scale

| Score Range | Grade | Interpretation |
|-------------|-------|-----------------|
| 90-100 | A | Excellent mastery |
| 80-89 | B | Good understanding |
| 70-79 | C | Satisfactory competency |
| Below 70 | F | Insufficient mastery (Fail) |

### Assessment Components

1. **Lab Completion (50%):** All labs must be completed with passing scores
2. **Exams (30%):** Chapter exams, midterms, and final exams
3. **Projects/Reports (15%):** Capstone projects and professional reports
4. **Participation (5%):** Class engagement, peer collaboration, attendance

### No-Retake Policy

- Interns who fail a course module cannot retake it within the same intake
- Interns must wait for the next intake to re-apply for the failed course
- This policy ensures programme integrity and maintains standards

---

## Part 5: Instructor Resources

### Recommended Tools & Platforms

- **Lab Platform:** NDG NETLAB+
- **Firewall/Security:** Palo Alto Networks
- **Forensics:** Autopsy, EnCase (trial)
- **SIEM:** Splunk (free tier), ELK Stack
- **Cloud:** AWS Academy, Azure Learn, Google Cloud Skills Boost
- **Collaboration:** Slack, Discord, or Teams for intern support

### Professional Development

Instructors are encouraged to:
- Maintain active industry certifications (CEH, GCIH, GCFE, etc.)
- Attend annual cybersecurity conferences
- Participate in threat intelligence communities
- Contribute to open-source security projects

### Feedback & Continuous Improvement

- Collect intern feedback at end of each course
- Review lab completion rates and common challenges
- Update labs based on emerging threats and technologies
- Share best practices with other instructors

---

**International Cybersecurity and Digital Forensics Academy (ICDFA)**  
*Developing Elite Cybersecurity Professionals*
