# Parking Lot USB Exercise

## 📌 Contents
| Question | Answer |
|----------|--------|
| **Are there files that can contain PII?** | Yes, the device contains personally identifiable information (PII), such as personal photos of the owner and their family members. |
| **Are there sensitive work files?** | Yes, there are sensitive work-related documents, including a new hire letter and an employee shift schedule, which could expose organizational information. |
| **Is it safe to store personal files with work files?** | No, storing personal and work files on the same device, especially a USB drive used in the workplace, increases the risks of data leaks and malware infections. |

## 🕵️ Attacker Mindset
| Question | Answer |
|----------|--------|
| **Could the information be used against other employees?** | Yes, data such as schedules and hiring documents could be exploited to map employees and identify potential attack vectors against them. |
| **Could the information be used against relatives?** | Yes, personal photos, depending on their nature, could be leveraged for social engineering attacks or even blackmail against Jorge or his relatives. |
| **Could the information provide access to the business?** | While the documents may not grant direct access to the company's systems, they provide useful insights for a threat actor to conduct more targeted attacks. |

## 🔬 Risk Analysis
| Question | Answer |
|----------|--------|
| **What types of malicious software could be hidden on these devices? What could have happened if the device were infected and discovered by another employee?** | USB devices can contain malware such as AutoRun, Keyloggers, USB Rubber Ducky, and BadUSB attacks, which can compromise systems upon connection. If an unsuspecting employee were to use the USB drive, it could lead to network infection and exposure of sensitive data. |
| **What sensitive information could a threat actor find on a device like this?** | A threat actor could uncover details about employees, the organizational structure, and personal data, which could facilitate phishing, spear phishing, or social engineering attacks to gain unauthorized access. |
| **How might that information be used against an individual or an organization?** | In a corporate setting, an attacker could use the data to craft highly targeted spear phishing emails, gain access to internal systems, or sell confidential business information to competitors or cybercriminal groups. |


| **📌 Contents** | The device contains personal documents that Jorge would prefer to keep private, along with work-related files that include sensitive personal information about others. Additionally, the work files reveal confidential details about the hospital's operations and activities. |
|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **🕵️ Attacker Mindset** | This information could be used by attackers to gather insights about Jorge's colleagues, which could make it easier to target them in an attack. Whether the data is personal or professional, it can be exploited for social engineering. For example, an attacker might craft a fake email that appears to come from one of Jorge’s coworkers or family members, tricking him into clicking on a malicious link. |
| **🔬 Risk Analysis** | To minimize these risks, it’s important to focus on employee training regarding the dangers of suspicious USB drives and the actions to take if one is found. Routine antivirus scans should be scheduled to help detect and prevent malware. Additionally, a technical control like disabling AutoPlay on workplace computers can stop malicious software from running automatically when a USB device is plugged in. These combined controls offer multiple layers of protection against potential threats. |



---

## 🛡️ Mitigation Strategies
To prevent such risks, organizations should:
- **Block unauthorized USB devices** using endpoint security controls.
- **Enforce security policies** prohibiting personal USB drives.
- **Train employees** on the risks of unknown removable media.
- **Implement multi-factor authentication (MFA)** to limit access even if credentials are compromised.
- **Use endpoint protection solutions** to detect malicious USB activity.

**Stay secure and always think before plugging in unknown devices!**
