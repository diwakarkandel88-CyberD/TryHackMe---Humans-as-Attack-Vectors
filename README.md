# TryHackMe---Humans-as-Attack-Vectors

## Lab Information

* Platform: TryHackMe
* Room: Humans as Attack Vectors
* Category: Security Awareness / SOC Fundamentals
* Status: Completed
* Date: 05-06-2026

## Objective

The objective of this lab was to understand how attackers exploit human behavior through social engineering, phishing, and other human-focused attack techniques. The lab also demonstrated how Security Operations Centers (SOCs) detect, prevent, and respond to these threats.

## Topics Covered

* Social Engineering
* Phishing Attacks
* Human Attack Vectors
* Security Awareness Training
* Access Management
* Endpoint Security
* Incident Response

## Key Learning Outcomes

### 1. Humans Are Often the Weakest Security Layer

Attackers frequently target employees instead of technical systems because convincing a person to perform an action can be easier than exploiting a vulnerability.

Examples include:

* Phishing emails
* Malicious attachments
* Fake software downloads
* Impersonation attacks
* Credential theft

### 2. Security Awareness Is Critical

Organizations should regularly train employees to:

* Identify phishing attempts
* Verify suspicious requests
* Report unusual activity
* Follow security policies

### 3. Importance of Security Controls

The lab demonstrated several controls that help reduce risk:

* Antivirus protection
* Access management policies
* Security awareness programs
* Internet usage restrictions
* Incident reporting procedures

## Scenario Analysis

### Scenario: Suspicious Software Download

A newly hired employee downloaded a file named Setup.exe from an untrusted freeware website. The endpoint antivirus blocked execution multiple times.

#### Risk Assessment

Indicators of Risk:

* Downloaded from an unknown source
* Executable file type (.exe)
* Multiple antivirus detections
* User attempted execution several times

#### Recommended Response

1. Quarantine the file.
2. Prevent execution.
3. Verify the legitimacy of the software.
4. Direct the employee to download software from the official vendor website.
5. Maintain antivirus protection.
6. Educate the employee about software installation policies.

#### Security Reasoning

Disabling antivirus protection or adding the file to exclusion lists would increase organizational risk and could allow malware execution.

## SOC Analyst Perspective

As a SOC analyst, I would:

* Investigate the file reputation.
* Review endpoint security logs.
* Check antivirus alerts.
* Verify download sources.
* Document the incident.
* Educate the employee.
* Escalate if malicious activity is confirmed.

## Skills Demonstrated

* Threat Identification
* Risk Assessment
* Security Awareness
* Incident Response
* Security Policy Evaluation
* Endpoint Security Analysis

## Conclusion

This room provided practical insight into how human behavior can become an attack vector and how organizations can reduce risk through awareness training, security policies, and technical controls. The exercises reinforced the role of SOC analysts in identifying threats, protecting users, and responding to security incidents.




### References

* TryHackMe Room: Humans as Attack Vectors
* Security Awareness Best Practices
* SOC Analyst Fundamentals
