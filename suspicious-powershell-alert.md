# Suspicious PowerShell Alert Investigation

## Project Type

Beginner SOC Analyst Practice Project

## Disclaimer

This is a simulated cybersecurity practice project created for educational and portfolio purposes.

---

# Scenario

A SIEM system generates an alert after detecting unusual PowerShell activity on an employee's computer.

The security alert shows that PowerShell was executed unexpectedly.

## Alert Details

| Alert Information | Details |
|---|---|
| Alert Type | Suspicious PowerShell Activity |
| Device | WORKSTATION-01 |
| User | employee1 |
| Process | PowerShell |
| Time | 14:25 |
| Severity | Medium |

---

# Step 1: Review the Alert

I would first collect the available information:

- Name of the affected device
- Username involved
- Date and time
- Process involved
- Alert severity
- Other related security events

---

# Step 2: Initial Analysis

PowerShell is a legitimate Windows tool used for system administration and automation.

However, attackers can also abuse PowerShell during malicious activity.

Therefore, the use of PowerShell alone does not automatically mean that an attack occurred.

Further investigation is required.

---

# Step 3: Investigation

I would investigate:

1. Why PowerShell was executed.
2. Whether the user normally uses PowerShell.
3. What process started PowerShell.
4. Whether there were unusual activities before or after the alert.
5. Whether other devices show similar activity.
6. Whether security tools detected additional suspicious behavior.

---

# Step 4: Assess the Risk

The alert may be suspicious if:

- PowerShell was executed unexpectedly.
- An unusual process started PowerShell.
- Other suspicious activity occurred.
- The device shows signs of compromise.

However, the activity may also be legitimate if PowerShell was used for normal administrative tasks.

---

# Step 5: Possible Outcomes

## True Positive

The alert may be a true positive if the investigation confirms that PowerShell was involved in unauthorized or suspicious activity.

## False Positive

The alert may be a false positive if PowerShell was being used for legitimate work or system administration.

---

# Step 6: Recommended Actions

If suspicious activity is confirmed:

- Investigate the affected device.
- Review related security logs.
- Check for other suspicious activity.
- Monitor the device.
- Escalate the incident if necessary.
- Follow the organization's incident response procedures.

---

# Final Assessment

Based on the initial alert:

**Status: Suspicious — Further Investigation Required**

The available information is not enough to confirm malicious activity.

---

# Key Learning

This project helped me understand that security alerts require investigation.

A legitimate tool can sometimes be used for malicious purposes, so analysts need to examine the surrounding evidence before making a decision.

---

# Skills Practiced

- SOC alert triage
- SIEM alert analysis
- Windows security awareness
- Process investigation
- True positive vs false positive analysis
- Security investigation
