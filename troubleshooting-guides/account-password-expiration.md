# Account Password Expiration / Login Failure Troubleshooting Guide

## Overview

This guide covers issues where a user cannot log in due to an expired password or login failure after a period of inactivity.

---

## Common Symptoms

* User cannot log in to workstation
* Message indicates password is expired
* Password change option fails at login screen
* User recently returned from vacation or leave

---

## Possible Causes

* Password has expired due to policy enforcement
* User has been inactive for extended period
* Account requires reset in Active Directory
* Password change attempt requires authentication first

---

## Troubleshooting Steps

### 1. Verify User Identity

Confirm user identity using approved verification method before making any account changes.

---

### 2. Check Account Status (Active Directory)

* Locate user account
* Check if account is:

  * Active
  * Locked
  * Password expired

---

### 3. Determine Issue Type

* If account is locked → unlock account
* If password expired → reset password
* If account is active but login fails → investigate further authentication issues

---

### 4. Reset Password (If Required)

* Generate temporary password
* Ensure password meets policy requirements
* Force password change at next login

---

### 5. Communicate Securely

* Provide temporary password through secure channel (Teams or phone)
* Do NOT send passwords via email

---

## Resolution Path Summary

Most cases involve:

1. Password expiration during inactivity
2. User inability to authenticate to initiate password change
3. Admin reset required via Active Directory

---

## Prevention Tips

* Encourage users to log in periodically during extended leave
* Provide password manager tools if available
* Educate users on password expiration policies

---

## Related Skills

* Active Directory Management
* Identity Verification
* Password Policy Enforcement
* Incident Resolution
* Secure Communication Practices
