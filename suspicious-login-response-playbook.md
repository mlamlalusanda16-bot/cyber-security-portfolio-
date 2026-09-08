# Suspicious Login Response Playbook

## Project Type

Beginner SOC Analyst Practice Project

## Disclaimer

This is a simulated cybersecurity project created for educational and portfolio purposes.

---

# Purpose

This playbook provides a simple step-by-step process for responding to suspicious login activity.

The goal is to help security analysts investigate unusual login attempts and reduce the risk of unauthorized access.

---

# When to Use This Playbook

This playbook can be used when:

- Multiple failed login attempts are detected.
- A successful login occurs after several failed attempts.
- A login occurs from an unusual location.
- A login occurs from an unfamiliar IP address.
- An account shows unusual activity.

---

# Step 1: Identify the Alert

Collect important information about the login activity:

- Username or account involved
- Date and time
- Source IP address
- Number of failed login attempts
- Whether a successful login occurred
- Location, if available

---

# Step 2: Investigate the Activity

Review the login information and look for suspicious patterns.

Check:

- Previous login history
- Source IP address
- Login location
- Time of login
- Other accounts targeted by the same IP address

---

# Step 3: Assess the Risk

Determine whether the activity may indicate:

- Password guessing
- Brute-force activity
- Unauthorized access
- A compromised account

More investigation may be required before confirming malicious activity.

---

# Step 4: Containment

If unauthorized access is suspected:

- Secure the affected account.
- Reset the password.
- End suspicious sessions if possible.
- Limit access if necessary.
- Monitor for further suspicious activity.

---

# Step 5: Review Account Activity

Check what happened after the suspicious login.

Review for:

- Unusual account activity
- Changes to account settings
- Unexpected file access
- New login locations
- Other suspicious events

---

# Step 6: Recovery

After securing the account:

- Confirm that the account is secure.
- Enable or verify Multi-Factor Authentication (MFA).
- Ensure a strong password is used.
- Continue monitoring for suspicious activity.

---

# Step 7: Document the Incident

Record:

- Details of the alert
- Investigation findings
- Source IP information
- Actions taken
- Final outcome
- Recommendations

---

# Conclusion

Following a structured process can help security teams investigate suspicious login activity consistently.

This playbook helps ensure that important investigation and response steps are not missed.

---

# Skills Demonstrated

- Alert triage
- Log analysis
- Security investigation
- Account security
- Incident response
- Documentation
- Basic SOC procedures
