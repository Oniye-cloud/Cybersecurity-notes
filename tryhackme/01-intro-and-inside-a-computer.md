# TryHackMe Pre-Security: Day 1

**Date:** 3 October 2026
**Path:** Pre-Security
**Rooms completed:** Introduction to Cybersecurity, Inside a Computer

---

## 1. Introduction to Cybersecurity

**Offensive security** means thinking like a real attacker to find weaknesses (vulnerabilities) in a system, so they can be fixed before a real attacker uses them.

## 2. Inside a Computer

The room used the human body to explain the main parts of a computer:

| Component | What it does |
|---|---|
| Motherboard (The Skeleton and Nerves) | Connects all the parts together |
| CPU (The Brains) | Processes instructions (the brain) |
| RAM (Short-term Memory) | Temporary memory for running programs |
| HDD / SSD (Long-term Memory) | Permanent storage |
| Network adapter | Connects the computer to a network |
| Power Supply Unit (PSU) | Supplies power to the parts |

## 3. What Happens When You Press the Start Button

1. **Press the power button:** a signal tells the PSU to let power flow.
2. **Firmware starts:** BIOS or UEFI wakes up the hardware.
3. **POST (Power-On Self-Test):** checks that the hardware is working.
4. **Select boot device:** chooses where to find the operating system.
5. **Bootloader starts:** loads the operating system.

## Key Terms

- **BIOS:** Basic Input/Output System
- **UEFI:** Unified Extensible Firmware Interface (the modern replacement for BIOS)
- **POST:** Power-On Self-Test
- **PSU:** Power Supply Unit

## Why This Matters for Security

*Attackers can target the boot stage because it runs before antivirus*

## What I Found Easy / Confusing

*None*
