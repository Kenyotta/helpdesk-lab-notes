# Ticket 003 - Legal Name Change (Active Directory Update)

## Ticket Information

**Ticket Number:** INC0012861
**Priority:** Low
**Status:** Resolved
**Request Type:** Account Update - Legal Name Change
**Department:** Finance

---

## User Request

User requested an account update due to a legal name change after marriage.

### Changes requested:

* Display name: Amanda Foster → Amanda Reyes
* Email address: [afoster@servicedesk-simulator.com](mailto:afoster@servicedesk-simulator.com) → [areyes@servicedesk-simulator.com](mailto:areyes@servicedesk-simulator.com)
* Keep previous email as alias for continued message delivery

HR has confirmed approval of the legal name change.

---

## Business Impact

Ensuring identity consistency across systems is important for:

* Email communication continuity
* HR record alignment
* Professional identity accuracy
* Preventing missed communications from legacy email addresses

---

## Initial Assessment

This is a standard Active Directory identity update request requiring:

* Display name modification
* Primary email update
* Alias preservation for legacy email routing

No account creation or deletion required.

---

## Investigation

1. Verified user identity and existing account (afoster).
2. Confirmed HR approval for legal name change.
3. Reviewed account attributes in Active Directory.
4. Verified current email routing configuration.

---

## Resolution

1. Accessed Active Directory user management tools.
2. Searched for user account: **afoster (Amanda Foster)**.
3. Updated display name to: **Amanda Reyes**.
4. Updated primary email address to: **[areyes@servicedesk-simulator.com](mailto:areyes@servicedesk-simulator.com)**.
5. Ensured legacy email **[afoster@servicedesk-simulator.com](mailto:afoster@servicedesk-simulator.com)** was retained as an alias.
6. Saved and applied changes.

---

## Root Cause

Not an issue or failure — this was a **legitimate HR-approved identity change** requiring directory updates.

---

## Security Considerations

* Verified HR approval before making changes.
* Ensured username remained unchanged to avoid login disruption.
* Preserved alias to prevent loss of incoming communication.
* Followed least-disruption principle for account continuity.

---

## Lessons Learned

* Legal name changes require coordinated updates across identity systems.
* Display name and email address should both be updated for consistency.
* Legacy email aliases are critical for communication continuity.
* Usernames should typically remain unchanged to avoid authentication issues.
* HR validation is required before executing identity modifications.

---

## Skills Practiced

* Active Directory user account management
* Email attribute modification
* Identity lifecycle management
* HR-IT coordination workflow
* Account continuity best practices
