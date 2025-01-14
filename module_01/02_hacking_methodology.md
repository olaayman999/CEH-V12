# Section 02: Hacking Methodology

## CEH Hacking Methodology
The CEH hacking methodology consists of the following phases:
- Gaining access
  - Cracking passwords
  - Vulnerability exploitation
- Escalating privileges
- Maintaining access
  - Executing applications
  - Hiding files
- Covering tracks
  - Clearing logs

Exploit

[Definition](../definitions/definitions_E.md#exploit)

Footprinting

[Definition](../definitions/definitions_F.md#footprinting)

Password cracking

[Definition](../definitions/definitions_P.md#password-cracking)

Privilege escalation

[Definition](../definitions/definitions_P.md#privilege-escalation)

Vulnerability assessment

[Definition](../definitions/definitions_V.md#vulnerability-assesment)

## Cyber Kill Chain
Cyber kill chain

[Definition](../definitions/definitions_C.md#cyber-kill-chain)

## Tactics, Techniques and Procedures (TTPs)
Tactics, techniques and procedures (TTPs)

[Definition](../definitions/definitions_T.md#tactics-techniques-and-procedures)

## why attackers use dns tunneling 

Attackers use DNS tunneling as a way to exfiltrate sensitive data from a network while bypassing security controls. DNS tunneling works by encoding data within DNS queries and responses, which are typically allowed to pass through firewalls and other security devices. By using DNS tunneling, attackers can exfiltrate sensitive data such as login credentials, confidential files, or sensitive information, while avoiding detection.

Some of the reasons why attackers might use DNS tunneling include:

1. Evasion: By encoding data within DNS queries and responses, attackers can bypass firewalls, intrusion detection systems, and other security controls that are designed to block unauthorized data transfers.

2. Anonymity: DNS tunneling allows attackers to hide their tracks by using legitimate DNS queries and responses, making it more difficult for security personnel to detect the attack.

3. Convenience: DNS is a widely-used protocol that is typically allowed to pass through security devices, making it an attractive option for attackers who want to exfiltrate data without having to bypass complex security measures.

4. Persistence: Attackers can use DNS tunneling to maintain a persistent connection to a compromised network, even if their initial access has been detected and blocked.

DNS tunneling can be a serious threat to organizations, and it is important to implement security measures to detect and prevent this type of attack. Some common measures include monitoring DNS traffic for unusual patterns or anomalies, implementing firewalls that block unauthorized DNS traffic, and deploying intrusion detection systems that can detect DNS tunneling attempts.

Here's an example of how DNS tunneling might be used:

An attacker gains access to a network, either through a vulnerability in a system or by tricking an employee into downloading malware.

The attacker sets up a DNS tunneling client on the compromised system and configures it to use a specific domain name to encode the data that they want to exfiltrate.

1. The attacker begins to encode sensitive data within DNS queries and responses, sending the encoded data to a DNS server that is under the attacker's control.

2. The DNS server decodes the data from the DNS queries and responses and stores it for the attacker to retrieve later.

3. The attacker continues to encode and exfiltrate sensitive data using DNS queries and responses, avoiding detection by security personnel who are monitoring the network for unusual activity.

4. Eventually, the attacker retrieves the encoded data from the DNS server and uses it for malicious purposes, such as selling it on the black market or using it to compromise other systems.

## Indicators of Compromise (IoC)
Indicator of compromise (IoC)

[Definition](../definitions/definitions_I.md#indicator-of-compromise)

## MITRE ATT&CK Framework
MITRE ATT&CK

[Definition](../definitions/definitions_M.md#mitre-attck-framework)
 
## Diamond Model of Intrusion Analysis

[Definition](../definitions/definitions_D.md#diamond-model-of-intrusion-analysis)
