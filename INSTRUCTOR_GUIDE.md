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

### CIP-B101, B102, B103: Linux, Network Security (Weeks 1-8)

**Delivery Notes:**
- Same as Track A (CIP-A101, A102, A103)
- Emphasize forensic implications of Linux and network concepts
- Connect to digital evidence preservation and chain of custody

---

### CIP-B104: Applied Security Engineering (Weeks 9-12)

**Delivery Notes:**
- Same as Track A (CIP-A108) but with forensic focus
- Emphasize logging and audit trail requirements
- Discuss forensic readiness and evidence preservation

---

### CIP-B105: Digital Forensics & Evidence Analysis (Weeks 13-16)

**Pacing Recommendations:**
- Week 13-14: File system forensics and data recovery
- Week 15-16: Advanced forensic analysis and case studies
- Allocate 3 hours per lab

**Common Student Challenges:**
- Difficulty understanding file system structures
- Ethical concerns about data privacy
- Overwhelm from complex forensic scenarios

**Mitigation Strategies:**
- Provide file system fundamentals overview
- Use anonymized real-world forensic images
- Emphasize legal and ethical requirements
- Break complex investigations into phases

**Lab Setup Notes:**
- Pre-configure Autopsy or similar forensic tools
- Provide forensic images with known artifacts
- Document chain of custody procedures
- Create realistic forensic scenarios

**Assessment Rubric:**
- Lab Completion (50%): All 21 labs with passing scores
- Forensic Analysis Report (30%): Professional documentation of findings
- Final Exam (20%): Forensic methodologies and evidence handling

---

### CIP-B106: Security Operations Centre (SOC) Essentials (Weeks 17-18)

**Delivery Notes:**
- Same as Track A (CIP-A107) but with forensic focus
- Emphasize incident investigation and evidence collection
- Discuss forensic readiness in SOC environments

---

### CIP-B107: Advanced Forensic Investigations (Weeks 19-25)

**Pacing Recommendations:**
- Week 19-21: Case study analysis and evidence correlation
- Week 22-23: Advanced investigation techniques
- Week 24-25: Capstone investigation and expert report preparation
- Allocate 4 hours per unit for research and analysis

**Common Student Challenges:**
- Difficulty synthesizing evidence from multiple sources
- Overwhelm from real-world case complexity
- Uncertainty about expert witness requirements

**Mitigation Strategies:**
- Provide case study templates and frameworks
- Use guided investigations with increasing complexity
- Invite guest lecturer (practicing forensic expert)
- Emphasize report writing and presentation skills

**Lab Setup Notes:**
- Provide comprehensive forensic case packages
- Include multiple evidence types (disk, memory, network, logs)
- Document case background and investigation objectives
- Create realistic multi-source investigation scenarios

**Assessment Rubric:**
- Case Analysis (40%): Thorough investigation of each case
- Forensic Report (40%): Professional documentation and findings
- Capstone Presentation (20%): Clear communication of investigation results

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
