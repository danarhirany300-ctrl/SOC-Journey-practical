---

# 📅 Day 101 – First SOC Shift

## Objective
Learn the standard workflow used by a Tier 1 SOC Analyst when investigating alerts.

## What I Learned
- A SOC analyst investigates alerts using evidence, not assumptions.
- Building a timeline helps explain what happened.
- Documentation is an essential part of every investigation.
- Not every alert is a security incident.

## Practical Exercise
Reviewed a high-severity PowerShell alert and identified the questions that should be answered before making a conclusion.

## Skills Practiced
- Alert triage
- Investigation planning
- Timeline creation
- Documentation

## Key Takeaway
Evidence → Timeline → Conclusion

---

# 📅 Day 102 – Authentication Alert Investigation

## 🎯 Objective
Learn how to investigate authentication alerts using evidence instead of assumptions.

## 📚 What I Learned
- Failed logins do not always indicate an attack.
- Context such as IP address, device, MFA, and location is essential.
- A timeline helps reveal the sequence of events.
- Evidence should be collected before making a decision.

## 🛠 Practical Exercise
Reviewed an authentication alert with multiple failed logins followed by a successful login. Identified additional evidence needed before determining whether the activity was malicious or legitimate.

## 💡 Skills Practiced
- Authentication analysis
- Evidence collection
- Timeline creation
- Critical thinking

## ✅ Key Takeaway
Never classify an authentication alert using only the number of failed logins. Always investigate the surrounding context first.

---

# 📅 Day 103 – Password Spraying vs. Brute Force

## 🎯 Objective
Understand how to distinguish password spraying attacks from brute-force attacks.

## 📚 What I Learned
- Password spraying targets many accounts using a small number of passwords.
- Brute-force attacks target one account with many password attempts.
- Authentication patterns are more important than individual failed logins.
- Successful logins after failed attempts require additional investigation.

## 🛠 Practical Exercise
Analyzed authentication logs to identify whether the activity matched password spraying or brute force. Practiced identifying additional evidence needed before escalating the incident.

## 💡 Skills Practiced
- Authentication log analysis
- Attack pattern recognition
- Incident triage
- Evidence collection

## ✅ Key Takeaway
The pattern of authentication attempts is often more important than the number of failed logins. Understanding that pattern helps accurately identify the attack type.

---

# 📅 Day 104 – Authentication Investigation: Benign or Malicious?

## 🎯 Objective
Learn how to determine whether an authentication alert represents normal user behavior or a security incident.

## 📚 What I Learned
- Authentication alerts require context before making a decision.
- Trusted devices, expected locations, and successful MFA often indicate legitimate activity.
- Analysts should gather evidence before escalating.
- Closing a benign alert is just as important as escalating a malicious one.

## 🛠 Practical Exercise
Investigated an authentication alert by reviewing sign-in logs, device information, MFA status, IP reputation, and location. Determined that the activity was consistent with normal user behavior.

## 💡 Skills Practiced
- Authentication investigation
- Identity analysis
- Evidence-based decision making
- Incident classification

## ✅ Key Takeaway
A good SOC analyst knows when **not** to escalate. Decisions should always be based on evidence, not assumptions.
