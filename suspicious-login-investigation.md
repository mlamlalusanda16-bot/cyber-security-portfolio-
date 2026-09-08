# Suspicious Login Investigation

## Project Type

Beginner SOC Analyst Practice Scenario

## Scenario

A security monitoring system generated an alert for multiple failed login attempts followed by a successful login.

The following activity was recorded:

| Time | Event |
|---|---|
| 10:01 | Failed login |
| 10:02 | Failed login |
| 10:03 | Failed login |
| 10:04 | Failed login |
| 10:05 | Successful login |

**Username:** admin  
**Source IP:** 185.220.101.45  
**Destination:** Company Server  

---

## Initial Observation

I noticed multiple failed login attempts against the same account within a short period of time.

The failed attempts were followed by a successful login.

This pattern could indicate suspicious activity.

---

## Possible Threat

One possible explanation is a password guessing or brute-force attack.

An attacker may repeatedly attempt different passwords until a correct password is found.

However, additional investigation would be required before confirming the activity as malicious.

---

## Investigation Steps

As a beginner SOC analyst, I would investigate:

1. Whether the source IP is known or trusted.
2. Whether the successful login was expected.
3. The location associated with the login attempt.
4. Other login activity involving the admin account.
5. Whether the source IP attempted to access other accounts.
6. Any activity that occurred after the successful login.

---

## Potential Impact

If the login was unauthorized, an attacker could potentially gain access to the company server.

This could lead to:

- Unauthorized access
- Data exposure
- Changes to system settings
- Further attacks on the network

---

## Recommended Actions

- Investigate the source IP address.
- Review the login history of the admin account.
- Check activity after the successful login.
- Reset the password if unauthorized access is suspected.
- Enable Multi-Factor Authentication (MFA).
- Monitor the account for further suspicious activity.

---

## Conclusion

Based on the available information, I would classify this activity as **suspicious**.

More investigation would be needed to determine whether the successful login was legitimate or unauthorized.

---

## Skills Practiced

- Basic log analysis
- Security alert triage
- Identifying suspicious activity
- Incident investigation
- Basic SOC analysis
- Security recommendations

## Disclaimer

This is a simulated cybersecurity practice scenario created for educational and portfolio purposes.
