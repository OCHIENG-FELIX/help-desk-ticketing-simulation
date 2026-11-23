# Ticket 004 – Software Installation Failure

## 1. Ticket Information

| Field | Details |
|---|---|
| Ticket ID | HD-004 |
| Issue Category | Software Installation / Microsoft 365 |
| Priority | P3 – Medium |
| Operating System | Windows 11 |
| Software | Microsoft Teams |
| Status | Resolved – Simulated |
| Resolution | Approved software deployment and license assignment |

## 2. User Report

An employee contacted the Help Desk requesting assistance with installing Microsoft Teams on their work computer.

The employee needed the application to attend an upcoming online meeting with clients.

The user reported that the installation repeatedly failed before completion.

## 3. Initial Investigation

The technician gathered the following information:

- Microsoft Teams was downloaded from the official Microsoft website.
- The installation displayed the error: "This app has been blocked by your system administrator."
- Other software installations had also failed.
- The computer had approximately 45 GB of available storage.
- The employee was using a standard Windows account without administrator privileges.

## 4. Findings and Analysis

The error indicated that organizational security restrictions were preventing software installation.

Possible controls included Group Policy, AppLocker, Microsoft Defender Application Control, or other software deployment restrictions.

Further investigation with the system administrator confirmed:

- Microsoft Teams was approved for organizational use.
- Employees were not permitted to install software independently.
- Approved applications had to be deployed by the IT department.

The technician therefore did not attempt to bypass the installation restrictions.

## 5. Installation Escalation

The technician documented the installation error and escalated the request to the authorized IT software deployment team.

The IT department was responsible for installing Microsoft Teams through the organization's approved deployment process.

## 6. Additional Issue – Microsoft Teams Sign-in Failure

After the simulated installation, the employee reported that Microsoft Teams opened successfully but displayed:

"You don't have access to this organization."

### Additional Investigation

The technician established that:

- The employee had an active company email account.
- Company email was working normally.
- The employee had never signed in to Microsoft Teams before.
- Other employees could access Microsoft Teams successfully.

The issue was escalated to the system administrator for account and licensing verification.

### Administrator Findings

| Account Property | Result |
|---|---|
| Microsoft 365 Account | Active |
| Company Email | Working |
| Microsoft Teams License | Not Assigned |
| Other Employees | Properly Licensed |

## 7. Recommended Resolution

The technician recommended that the system administrator:

1. Assign an appropriate Microsoft Teams license, subject to organizational policy and availability.
2. Confirm that the Teams service is enabled within the assigned license.
3. Allow time for licensing changes to take effect.
4. Ask the employee to sign out and sign back in.
5. Verify that the employee can access Microsoft Teams.

The employee was informed that the issue required administrator action and that IT would provide an update once access was configured.

## 8. Verification

The simulated troubleshooting identified two separate issues:

- Organizational restrictions prevented the employee from installing Microsoft Teams independently.
- The employee's Microsoft 365 account did not have a Teams license assigned.

The recommended corrective actions were identified and escalated.

**Note:** Actual software deployment and license assignment were not performed by the trainee. This ticket documents a simulated Help Desk investigation and proposed resolution.

## 9. Skills Demonstrated

- Software installation troubleshooting.
- Understanding Windows user permissions.
- Identifying organizational software restrictions.
- Microsoft 365 account and licensing awareness.
- User communication and information gathering.
- Escalation to system administrators.
- Service request documentation.
- Security policy awareness.

## 10. Lessons Learned

Software installation failures can result from organizational security restrictions rather than corrupted installers or insufficient storage.

Additionally, having a working company email account does not automatically guarantee access to Microsoft Teams. Appropriate licensing and service permissions must be configured.

IT Support technicians should follow organizational software deployment procedures, avoid bypassing security controls, and escalate administrative changes to authorized personnel.
