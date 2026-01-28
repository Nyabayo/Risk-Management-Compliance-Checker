# Risk Management Compliance Checker

## Overview

This repository contains a Python script developed for **FinSecure** to ensure system security compliance with internal audit policies. The script performs three key compliance checks:

1. **File system permissions** on sensitive directories.
2. **Active user session monitoring**.
3. **Disk space utilization** to prevent data loss or service disruption.

The repository includes:
- The **Python script** (`finsecure.py`) used for compliance checks.
- Two reports:
  - **C5M7 Risk Management Part 1 Report** (PDF)
  - **C5M7 Risk Assessment Part 2 Report** (PDF)

## Lab: Risk Assessment

The task was to develop a Python script to check the compliance of the system in three areas:
1. **File system permissions** on sensitive directories.
2. **Active user session monitoring** to identify unauthorized sessions.
3. **Disk space utilization** to avoid system crashes and ensure continuous operations.

## Steps to Solve

### Step 1: **Establish the Context**
   - Define the purpose of the script and its relevance to compliance with internal audit policies focusing on security.

### Step 2: **Implement File Permission Checks**
   - Check if sensitive directories (e.g., `/secure_data`) have restricted permissions, ensuring access is only granted to the owner.

### Step 3: **Implement Active Session Monitoring**
   - Monitor active user sessions, checking for unauthorized or suspicious logins that could indicate security risks.

### Step 4: **Implement Disk Space Utilization Check**
   - Ensure that disk space usage does not exceed 80%, to prevent data loss or system disruption.

### Step 5: **Test the Complete Script**
   - Verify that the script produces appropriate output for each compliance check and correctly identifies areas of non-compliance.

### Step 6: **Finalize and Submit**
   - Submit the completed script and report after testing and verifying all checks.

## Questions Addressed in the Lab:
- What is the purpose of the script in ensuring **FinSecure**’s compliance with internal audit policies?
- How does the script check and enforce file system permissions, active user sessions, and disk space utilization?
- What are the key functions implemented to carry out the compliance checks?
- How were the results tested and verified to ensure compliance?

## Files in this Repository:
- **finsecure.py**: The Python script for compliance checks.
- **C5M7 Risk Management Part 1 Report (PDF)**: The report covering the first part of risk management.
- **C5M7 Risk Assessment Part 2 Report (PDF)**: The report for the second part of the risk assessment.

## License

This repository is licensed under the MIT License.
