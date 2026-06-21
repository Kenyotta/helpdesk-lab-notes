# Floor-Wide Network Outage (Switch-Level Failure) Troubleshooting Guide

## Overview

This guide covers situations where an entire floor or network segment loses internet connectivity while other areas remain unaffected. These incidents are often caused by network switch or access point failures.

---

## Common Symptoms

* Entire floor cannot access the internet
* Multiple users report simultaneous connectivity loss
* Conference rooms or shared spaces also affected
* Other floors or departments remain online
* Issue appears suddenly with no user-side changes

---

## Initial Assessment

Before taking action:

* Confirm scope of outage (one floor vs multiple floors)
* Check if other departments are affected
* Verify if issue is isolated or widespread
* Determine when issue began

---

## Likely Causes

* Floor-level network switch failure (most common)
* Access point malfunction
* VLAN misconfiguration (less common)
* Network hardware freeze or crash
* Power interruption to network equipment

---

## Troubleshooting Steps

### Step 1: Confirm Scope

* Ask users if other floors are affected
* Verify network status across multiple locations

---

### Step 2: Identify Network Equipment

* Locate affected floor’s network switch
* Check network dashboard or server room interface
* Confirm device status (online/offline/unresponsive)

---

### Step 3: Isolate the Issue

* If only one floor is impacted → likely switch-level issue
* If multiple floors are impacted → escalate to core network team

---

### Step 4: Restart Network Switch (If Applicable)

* Access network management interface
* Reboot affected floor switch
* Wait 30–60 seconds for full restart

---

### Step 5: Verify Restoration

* Confirm connectivity returns
* Check with multiple users if possible
* Test access to websites or internal systems

---

## Resolution Summary

Most floor-wide outages are resolved by rebooting the affected network switch, which restores connectivity to all connected devices on that segment.

---

## When NOT to Escalate

* Single-floor outage with known switch identified
* Successful restoration after reboot
* No signs of upstream network failure

---

## When to Escalate

Escalate immediately if:

* Multiple floors are affected
* Core network devices are down
* Switch reboot does not restore service
* Firewall or routing issues suspected

---

## Key Takeaway

Floor-wide outages are typically **localized infrastructure failures**, not user device issues. Fast isolation of the affected network segment is critical for minimizing downtime.

---

## Skills Practiced

* Network segmentation analysis
* Infrastructure troubleshooting
* Switch-level diagnostics
* Incident prioritization (Critical outages)
* Service restoration verification
