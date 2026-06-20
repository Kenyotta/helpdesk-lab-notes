# Ticket 002 - Mobile Email Sync Failure

## Ticket Information

**Ticket Number:** INC741961
**Priority:** Medium
**Status:** Resolved
**Department:** Marketing
**Location:** Floor 3

---

## User Issue

User reported that work email stopped syncing on their mobile device. The email application displays a "Cannot connect to server" error. The issue began suddenly after previously working without problems.

User confirmed:

* Internet connection is working on the device
* Other mobile applications function normally
* Email is accessible from a laptop

---

## Business Impact

User is unable to receive or respond to email while away from their workstation, resulting in delayed communication and potential missed urgent messages.

---

## Initial Assessment

Possible causes considered:

* Mobile email app corruption or cached data issue
* Authentication token expiration
* Device-specific configuration issue
* Server-side email outage (ruled out since desktop access works)

---

## Investigation

1. Verified email functionality on alternate device (laptop).
2. Confirmed email account is active and working normally.
3. Determined issue is isolated to mobile device only.
4. Identified that desktop/webmail access indicates no account-level issue.

---

## Resolution

1. Advised user to uninstall email application from mobile device.
2. User reinstalled the email app from official app store.
3. User signed back into email account.
4. Email synchronization restored successfully on mobile device.

---

## Root Cause

Mobile email application was in a corrupted or unstable state, likely due to cached authentication tokens or app-level data corruption.

---

## Security Considerations

* No password reset required since account credentials were valid.
* Verified account functionality before performing local device reset.
* Ensured reauthentication occurred after reinstall.

---

## Lessons Learned

* If email works on one device but not another, the issue is typically device-specific.
* Reinstalling mobile email applications resolves most sync/authentication issues.
* Always verify cross-device functionality before escalating to server-side troubleshooting.
