# HP Laptop Performance Optimization

## Overview

This project documents the troubleshooting and optimization of a Windows 11 HP laptop experiencing severe performance issues.

The engagement included:

- Diagnostics
- Startup optimization
- Storage cleanup
- Resource analysis
- Root cause identification
- Hardware upgrade recommendation

---

## Customer Complaint

The customer reported:

- Slow performance
- Delayed application launches
- General system sluggishness

---

## Environment

| Component | Details |
|------------|------------|
| Model | HP Laptop 14-dq3xxx |
| OS | Windows 11 Home |
| CPU | Intel Celeron N4500 |
| RAM | 4GB DDR4 |
| Storage | 64GB SSD/eMMC |

---

## Diagnostics

### Startup Applications

![Startup Apps](./02-Startup-Applications.png)
👉 [Startup Apps](./02-Startup-Applications.png)

Reviewed startup applications and disabled non-essential entries.

---

### Memory Analysis

![Memory Before](screenshots/task-manager-memory-before.jpg)

Findings:

- 4GB RAM
- 92% utilization
- Less than 400MB available

Root cause identified as insufficient memory.

---

### Storage Analysis

Before Cleanup:

![Storage Before](screenshots/storage-before.jpg)

After Cleanup:

![Storage After](screenshots/storage-after.jpg)

Storage improved from:

- 7.84GB free
- 13GB free

---

### Hardware Verification

![PowerShell Model](screenshots/powershell-model.jpg)

![PowerShell Memory](screenshots/powershell-memory.jpg)

Verified:

- HP Laptop 14-dq3xxx
- Samsung DDR4-3200 Memory

---

## Root Cause

Primary bottleneck:

- 4GB RAM running Windows 11

Secondary bottleneck:

- Low available storage

---

## Recommendation

Upgrade memory from:

- 4GB DDR4
- to 8GB DDR4

Expected improvements:

- Faster responsiveness
- Better multitasking
- Reduced memory saturation

---

## Skills Demonstrated

- Windows Administration
- Endpoint Troubleshooting
- Root Cause Analysis
- PowerShell
- Hardware Diagnostics
- Performance Optimization
