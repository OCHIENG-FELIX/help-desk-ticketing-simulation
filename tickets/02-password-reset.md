# Ticket 002 – Windows Domain Login Failure

## 1. Ticket Information

| Field | Details |
|---|---|
| Ticket ID | HD-002 |
| Issue Category | Account Access / Domain Authentication |
| Priority | P4 – Low (initial classification) |
| Operating System | Windows 11 |
| Reported Issue | Unable to log in to work computer |
| Status | Resolved – Simulated |
| Resolution | Workstation secure channel repaired |

## 2. User Report

A staff member reported that she could not log in to her work computer using her company credentials.

The user requested assistance to investigate the login problem and determine whether a password reset was necessary.

## 3. Initial Investigation

The technician gathered information from the user and established that:

- The user could log in successfully the previous day.
- The password had not recently been changed.
- Restarting the computer did not resolve the issue.
- Other employees could log in normally.
- The keyboard was functioning correctly.
- The keyboard layout was correct and Caps Lock was disabled.
- The user could access company email using the same credentials.

The administrator also confirmed that the account was enabled, not locked, and that the password had not expired.

## 4. Findings and Root Cause

The Windows login screen displayed:

"The trust relationship between this workstation and the primary domain failed."

Further investigation identified a broken secure channel between the workstation and the Active Directory domain.

This prevented the workstation from establishing the required domain trust relationship during authentication.

The problem was therefore related to workstation-domain authentication rather than an incorrect user password.

## 5. Resolution

The issue was escalated to the domain administrator.

The administrator successfully repaired the workstation's secure channel using appropriate administrative permissions.

The user was then able to log in normally.

## 6. Verification

Following the repair:

- The workstation successfully authenticated with the domain.
- The employee logged in using her existing credentials.
- The user confirmed that access had been restored.

## 7. Skills Demonstrated

- User communication and information gathering.
- Password and account troubleshooting.
- Keyboard and login troubleshooting.
- Basic Active Directory domain authentication concepts.
- Identifying workstation trust relationship failures.
- Appropriate escalation to a domain administrator.
- Resolution verification and ticket documentation.

## 8. Lessons Learned

Not every Windows login failure requires a password reset.

A technician should investigate account status, keyboard input, domain connectivity, and workstation authentication before changing user credentials.

Understanding the difference between user-account authentication and workstation-domain trust helps prevent unnecessary password resets.

**Note:** This is a simulated help desk ticket for learning and portfolio purposes. The repair was performed as part of the simulation, not on an actual company workstation.
