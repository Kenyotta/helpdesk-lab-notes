# Ticket 001 - Password Expired After Extended Leave

## Ticket Information

**Ticket Number:** INC0012855
**Priority:** High
**Status:** Resolved
**Department:** Engineering
**Location:** Floor 3

## User Issue

The user returned from a three-week vacation and was unable to log in to their workstation. The system indicated that the password had expired and needed to be changed, but the user was unable to complete the password change process from the login screen.

## Business Impact

The user is the lead developer for the payment processing module and has a sprint deadline approaching. Inability to access the workstation could delay project deliverables and impact the development team.

## Initial Assessment

Possible causes considered:

* Expired password
* Account lockout
* Authentication issue
* Password synchronization issue

## Investigation

1. Accessed Active Directory through the service desk tools.
2. Located the user account.
3. Verified the user's identity using the organization's verification process.
4. Reviewed account status and confirmed the password had expired.

## Resolution

1. Reset the user's password in Active Directory.
2. Generated a temporary password.
3. Securely communicated the temporary password to the user through an approved communication channel.
4. Instructed the user to change the password upon first login.

## Root Cause

The user's password expired during an extended absence from work. Because the password had already expired, the user could not authenticate successfully from the login screen to initiate a password change.

## Security Considerations

* User identity was verified before any account modifications were made.
* Temporary credentials were shared through a secure communication channel.
* User was required to change the temporary password immediately after login.

## Lessons Learned

* Extended leave often results in password expiration issues.
* Identity verification should always occur before making account changes.
* Temporary passwords should never be sent through unsecured channels.
* Password expiration policies help maintain organizational security.

## Skills Practiced

* Active Directory User Management
* Password Reset Procedures
* Identity Verification
* Ticket Documentation
* User Communication
* Security Best Practices
