# Ticket 004 - Floor 3 Network Outage (Critical)

## Ticket Information

**Ticket Number:** INC0012858
**Priority:** Critical
**Status:** Resolved
**Department:** Facilities
**Location:** Floor 3

---

## User Issue

Multiple users on Floor 3 reported complete loss of internet connectivity. Users were unable to access websites or cloud-based applications. Conference rooms were also affected.

Users confirmed:

* Floor 2 network was functioning normally
* Issue was isolated to Floor 3 only
* Outage began approximately 30 minutes prior to report

---

## Business Impact

This was a **high-impact outage affecting multiple departments**, including:

* Customer service team unable to access CRM systems
* General productivity loss across Floor 3
* Conference rooms unavailable for business operations

---

## Initial Assessment

Given the scope of the outage, possible causes included:

* Network switch failure (most likely)
* Localized access point failure
* VLAN or routing issue
* Firewall or upstream connectivity issue

Because only Floor 3 was affected, the issue was likely **localized to network hardware on that floor**.

---

## Investigation

1. Reviewed network topology for Floor 3.
2. Identified Floor 3 switch as primary network distribution point.
3. Confirmed other floors were unaffected (eliminates core network failure).
4. Isolated issue to Floor 3 network switch device.

---

## Resolution

1. Accessed server room / network device dashboard.
2. Located **Floor 3 network switch** in device list.
3. Initiated switch reboot via management interface.
4. Waited for device to fully restart (approximately 30–60 seconds).
5. Verified network restoration with end users via Teams chat.
6. Confirmed internet connectivity restored on Floor 3.

---

## Root Cause

The Floor 3 network switch became unresponsive, resulting in complete loss of network connectivity for all devices connected to that segment.

A reboot restored normal operation.

---

## Security Considerations

* Verified scope before performing infrastructure changes.
* Ensured only affected segment was modified.
* Avoided unnecessary changes to core network systems.
* Confirmed restoration with end users before closing ticket.

---

## Lessons Learned

* Entire floor outages typically indicate **switch-level failure**, not individual device issues.
* Verifying scope of impact is critical for fast diagnosis.
* Rebooting network switches is a valid first-response action for localized outages.
* Always confirm restoration with multiple users when possible.
* Infrastructure-level issues require faster escalation due to high business impact.

---

## Skills Practiced

* Network troubleshooting fundamentals
* Infrastructure isolation techniques
* Switch-level diagnostics
* Incident prioritization (Critical outage handling)
* Business impact assessment
