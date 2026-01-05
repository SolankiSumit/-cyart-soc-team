Rule: "Detect 5+ failed logins in 5 minutes"
Index: security-login-*
Condition: count > 5
