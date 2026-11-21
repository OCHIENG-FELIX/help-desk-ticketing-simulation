# Ticket 001 – Slow Computer

## 1. Ticket Information

| Field | Details |
|---|---|
| Ticket ID | HD-001 |
| Issue Category | Computer Performance |
| Priority | P3 – Medium |
| Operating System | Windows 11 |
| Reported Issue | Computer running slowly |
| Status | Investigated – Simulated |
| Resolution Status | Pending Further Investigation |

## 2. User Report

The user reported that their computer had become unusually slow since the morning. Applications were taking longer to open, and switching between applications was difficult.

The user confirmed that:
- The computer was working normally the previous day.
- Google Chrome and Microsoft Excel were being used.
- No new applications had been installed.
- The slowdown affected switching between applications.
- No error messages were displayed.

## 3. Initial Troubleshooting

The technician gathered information from the user to understand when the issue started, which applications were affected, and whether any recent changes had been made.

Task Manager was then identified as the first diagnostic tool to inspect system resource utilization.

### Task Manager Findings

| Resource | Usage |
|---|---:|
| CPU | 18% |
| Memory | 92% |
| Disk | 5% |

### Top Memory-Consuming Processes

| Process | Memory Usage |
|---|---:|
| Google Chrome | 3,200 MB |
| Microsoft Excel | 850 MB |
| Microsoft Defender | 250 MB |
| Windows Explorer | 180 MB |

An additional unknown background application was subsequently identified using approximately 1,500 MB of memory.

## 4. Findings and Analysis

The computer was experiencing high memory utilization, with memory usage reaching 92%.

Google Chrome was the largest identified memory consumer, making it a likely contributor to the performance problem.

The investigation also considered:
- Unnecessary Chrome tabs and browser extensions.
- Background applications consuming system resources.
- Applications configured to start automatically with Windows.
- Available disk space.
- Unrecognized or potentially unwanted software.

The unknown application required further investigation because the user did not recognize it.

## 5. Recommended Troubleshooting Actions

The following actions were identified as appropriate next steps:

1. Open Chrome Task Manager using `Shift + Esc` to identify memory-intensive tabs and extensions.
2. Consult the user before closing unnecessary browser tabs or disabling extensions.
3. Identify the unknown application's name, publisher, digital signature, and installation location.
4. Confirm whether the application is approved or required for organizational work.
5. Investigate potentially unwanted or malicious software according to organizational security procedures.
6. Review unnecessary startup applications and background processes.
7. Obtain appropriate authorization before disabling or uninstalling software.
8. Recheck Task Manager after authorized changes to determine whether memory utilization has improved.

## 6. Security Considerations

Unknown applications should not be terminated or uninstalled without first establishing their purpose.

If an application is suspected to be malicious, the technician should follow the organization's security incident response procedures and notify the appropriate IT or security personnel.

## 7. Resolution and Verification

No actual system changes were performed during this simulated ticket.

The investigation identified high memory utilization and Google Chrome as a likely contributor. The unknown background application also requires further verification.

The issue therefore remains pending further investigation and corrective action.

After any authorized changes, the technician should:
- Recheck CPU, memory, and disk utilization.
- Confirm whether the computer responds more quickly.
- Ask the user whether normal work has resumed.
- Record the final findings and actions taken in the ticket.

## 8. Skills Demonstrated

- User communication and information gathering.
- Task Manager and resource utilization analysis.
- Identifying high memory-consuming processes.
- Investigating background and startup applications.
- Basic software security awareness.
- User authorization and responsible troubleshooting.
- Verification and ticket documentation.

## 9. Lessons Learned

A slow computer should be investigated systematically rather than immediately assuming hardware failure.

Task Manager provides useful evidence about resource consumption. Technicians should identify the processes responsible for high utilization, consult users before making changes, and verify system performance after corrective actions.

**Note:** This ticket documents a simulated help desk investigation for learning and portfolio purposes. It does not represent an actual customer support incident or confirmed system repair.
