# SOC Alert Triage Project

## Project Type

Beginner SOC Analyst Practice Project

## Disclaimer

This is a simulated cybersecurity practice project created for educational and portfolio purposes.

---

# Scenario

A Security Information and Event Management (SIEM) system generates an alert for multiple failed login attempts followed by a successful login.

## Alert Details

| Alert Information | Details |
|---|---|
| Alert Type | Multiple Failed Logins |
| Username | employee1 |
| Failed Attempts | 8 |
| Successful Login | Yes |
| Source IP | 192.0.2.25 |
| Time | 09:30 |
| Severity | Medium |

---

# Step 1: Review the Alert

The first step is to review the available information.

I would check:

- Username involved
- Number of failed login attempts
- Source IP address
- Date and time
- Whether a successful login occurred

---

# Step 2: Initial Analysis

The alert shows multiple failed login attempts followed by a successful login.

This pattern may be suspicious because it could indicate:

- Password guessing
- Brute-force activity
- Unauthorized access

However, more investigation is required before confirming that the activity is malicious.

---

# Step 3: Investigation

I would investigate:

1. Previous login activity for the employee.
2. Whether the source IP is known.
3. Whether the login location is normal.
4. Whether other accounts were targeted.
5. Activity after the successful login.
6. Any unusual changes to the account.

---

# Step 4: Determine the Severity

The alert is initially classified as **Medium severity**.

The severity could increase if:

- The account has administrator privileges.
- The source IP is malicious.
- Unusual activity occurred after login.
- Sensitive systems were accessed.

---

# Step 5: Possible Outcomes

## True Positive

The alert may be a true positive if the investigation confirms suspicious or unauthorized activity.

## False Positive

The alert may be a false positive if the employee simply entered the wrong password several times before successfully logging in.

---

# Step 6: Recommended Actions

If suspicious activity is confirmed:

- Investigate the account further.
- Reset the password.
- Review account activity.
- Enable or verify MFA.
- Monitor for further suspicious activity.
- Escalate the incident if necessary.

---

# Final Assessment

Based on the initial information, I would classify this alert as:

**Status: Suspicious  Further Investigation Required**

There is not enough information to confirm whether this is a true positive or false positive.

---

# Skills Practiced

- SOC alert triage
- SIEM alert analysis
- Log analysis
- Security investigation
- Severity assessment
- True positive vs false positive analysis
- Incident response

## Key Learning

This project helped me understand that SOC analysts should not immediately assume that every security alert is a real attack.

Alerts need to be investigated using available evidence before making a final decision.
