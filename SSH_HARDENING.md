# SSH Hardening Documentation

## Objective
Secure SSH access by enforcing key-based authentication and disabling
insecure defaults.

## Changes Applied
- Configured SSH key-based authentication for admin user
- Disabled root login over SSH
- Disabled password-based authentication

## Verification
- Successfully connected using SSH keys
- Verified that password-based login is disabled
- Confirmed root login over SSH is not permitted

## Security Impact
These changes reduce the risk of brute-force attacks and unauthorized
access to the system.
