# Ticket 005: Printer Not Working

## 1. Incident Details

- **Ticket ID:** HD-005
- **Category:** Hardware / Printer Support
- **Priority:** P3 – Medium
- **Status:** Resolved (Simulated)
- **Operating System:** Windows 11
- **Device:** Shared HP LaserJet Office Printer

## 2. User Report

An employee reported that they were unable to print an important PDF document using the shared office printer. They had attempted printing several times, but nothing came out.

The issue started that morning.

## 3. Initial Investigation

The following questions were asked:

- Had the employee printed using this printer before?
- What type of document were they trying to print?
- Had another employee experienced the same problem?
- Had they tried another printer?
- Had they printed the same PDF before?
- Had another employee successfully used the printer after the failed attempt?

### Findings

- The employee had successfully used the printer before.
- The document was a PDF.
- Another employee successfully printed a document five minutes after the failed attempt.
- The employee had never printed that particular PDF before.
- The employee had not tried another printer.

## 4. Troubleshooting Steps

### Step 1: Verify Printer Selection

Checked the selected printer in Windows.

**Finding:** HP LaserJet Office Printer was selected correctly.

### Step 2: Check Printer Status

Navigated to:

Settings → Bluetooth & devices → Printers & scanners.

**Finding:** The printer showed Ready, not Offline or Paused.

### Step 3: Check Print Queue

Opened the printer queue to inspect pending print jobs.

**Finding:**
- The PDF document showed an Error – Printing status.
- Two older documents were also stuck in the queue.

### Step 4: Clear the Print Queue

- Confirmed that the pending jobs could be cancelled.
- Cancelled the two older jobs and the failed PDF.
- Waited for the queue to clear.

### Step 5: Verify Printing

Asked the employee to submit the PDF again.

**Finding:** The document printed successfully.

## 5. Root Cause Assessment

The immediate problem was associated with stuck print jobs in the Windows print queue.

The exact underlying cause of the stuck jobs was not established.

## 6. Resolution

The pending print jobs were cancelled, clearing the queue. The employee successfully printed the PDF afterward.

**Final Status:** Resolved (Simulated).

## 7. Preventive Recommendations

- Check the print queue when documents fail to print.
- Avoid repeatedly submitting the same print job.
- Report recurring printer errors to IT support.
- Monitor printer connectivity and status.
- Document recurring incidents for further investigation.

## 8. Skills Demonstrated

- User communication and information gathering.
- Printer selection and status verification.
- Windows printer management.
- Print queue troubleshooting.
- Incident resolution and verification.
- Help desk ticket documentation.

## 9. Practical Exercise Disclaimer

This was a simulated help desk exercise. The troubleshooting findings and resolution were provided as part of the training scenario and do not represent an actual repair performed on an office printer.
