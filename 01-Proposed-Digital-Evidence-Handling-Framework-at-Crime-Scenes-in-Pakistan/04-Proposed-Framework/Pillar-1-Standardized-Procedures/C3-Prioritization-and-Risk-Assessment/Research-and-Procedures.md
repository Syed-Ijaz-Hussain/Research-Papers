# COMPONENT 03: DIGITAL EVIDENCE PRIORITIZATION, VOLATILITY AND RISK ASSESSMENT

## Purpose

To establish the priority of identified digital evidence sources by assessing their volatility, investigative relevance and potential preservation risks, ensuring that evidence requiring urgent attention is identified for subsequent preservation and handling activities.

## Main Activity 1: Prioritize Digital Evidence Sources

### Step 1: Prioritize Digital Evidence Sources

**Procedure ID:** PI-C3-S01

**Purpose:** To apply a standardized assessment matrix to identified digital evidence sources by considering data volatility, overwrite threats and investigative relevance.

**How to Perform It:**

1. Assess each identified evidence item against the following three criteria:
   - Volatility: High / Medium / Low.
   - Overwrite Threat: High / Medium / Low.
   - Investigative Relevance: High / Medium / Low.
2. Assign a priority level according to the assessment:
   - Priority Level 1 – Immediate: Evidence requiring immediate attention due to its volatility or preservation risk.
   - Priority Level 2 – High: Evidence requiring timely preservation after higher-priority evidence.
   - Priority Level 3 – Routine: Evidence that does not require immediate attention based on the assessment.
4. Establish the collection sequence according to the assigned priority levels.

**Responsible Personnel:** Digital Evidence Specialist (DES) / Crime Scene Supervisor.

**Required Documentation:** Evidence Preservation Priority Matrix Form (Form P3-01).

**Expected Output:** A documented evidence preservation priority assessment and collection sequence.

**Supporting References:** ISO/IEC 27037:2012, Clauses 5.1 and 6.8; ACPO Good Practice Guide for Digital Evidence, Version 5, Section 5.6. Exact references require verification against the original documents.

### Step 2: Volatile Data Assessment

**Procedure ID:** PI-C3-S02

**Purpose:** To identify transient system memory structures (RAM, network sockets, active processes) that will be permanently lost if power is removed.

**How to Perform It:**

1. Identify Critical Volatile Evidence.

   Check if powered-on devices contain critical volatile evidence:
   - System RAM.
   - Active chat sessions.
   - Open unrecorded documents.
   - Running network connections.
   - Mounted BitLocker/VeraCrypt volumes.

2. Determine Volatile Data Extraction Requirements.

   Determine whether volatile data extraction is required before powering down the machine.

3. Identify Devices for Live RAM Capture.

   If volatile data is required, tag the device for Live RAM Capture by a DES.

**Responsible Personnel:** DEFR / DES.

**Required Documentation:** Volatile Data Assessment Sheet (Form P3-02).

**Expected Output:** Identification of volatile data preservation requirements prior to power disconnection.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 6.8 (p. 23), Clause 7.1.3.1.2 (pp. 32–33).
2. ACPO v5 (2012), Appendix A (pp. 15–16).
3. Council of Europe C-PROC (2019), Section 3.3.4 (p. 14).

## Main Activity 3: Assess Evidence Preservation Risks

### Step 4: Network Connectivity and Remote-Wipe Risk Assessment

**Procedure ID:** PI-C3-S04

**Purpose:** To evaluate active network interfaces and assess risks of remote data wiping, remote access, or cloud data alteration.

**How to Perform It:**

1. Inspect devices for active network links: Ethernet cables, Wi-Fi connections, Bluetooth pairings, or cellular data connections.
2. Assess remote-wipe threat level: smartphones, tablets, and laptops running Find My Device / MDM agent software face extreme remote-wipe risks.
3. Determine isolation method: unplug Ethernet cables, disable Wi-Fi/Bluetooth, or deploy Faraday RF shielding packaging immediately.

**Responsible Personnel:** DEFR.

**Required Documentation:** Network Connectivity and Remote Threat Log (Form P3-04).

**Expected Output:** Threat evaluation establishing immediate network isolation requirements.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 7.2.2.2 (pp. 38–39).
2. NIJ (2008), Chapter 5 (p. 21).
3. ACPO v5 (2012), Appendix C, Section 3 (p. 19).
4. Council of Europe C-PROC (2019), Section 3.3.3 (p. 13).

**Exception Handling:** Do not unplug Ethernet from running enterprise servers providing critical services until the lead investigator and system administrator evaluate business and legal impacts.

### Step 5: Encryption, Passcode and Access Restriction Assessment

**Procedure ID:** PI-C3-S05

**Purpose:** To identify full-disk encryption, encrypted logical volumes, BIOS/UEFI passwords, or screen lock security preventing post-power-down access.

**How to Perform It:**

1. Inspect running system displays for encryption indicators (BitLocker active icon, VeraCrypt mounted volumes, FileVault status).
2. Check physical system for hardware tokens, smart cards, or USB encryption keys attached to ports.
3. If encryption is active on a running machine, capture volatile RAM immediately to harvest plain-text encryption keys before powering down.

**Responsible Personnel:** DES.

**Required Documentation:** Encryption and Access Barrier Assessment (Form P3-05).

**Expected Output:** Identification of active encryption barriers and deployment of key capture protocols.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 7.1.1.3 (p. 27), Clause 7.1.3.1.3 (p. 33).
2. NIJ (2008), Chapter 5 (p. 22).
3. ACPO v5 (2012), Appendix C, Section 10 (p. 19).
4. Council of Europe C-PROC (2019), Section 3.3.4 (p. 14).

**Exception Handling:** If an encrypted system is powered OFF, search the physical scene thoroughly for paper notes, USB recovery keys, or original hardware documentation containing recovery keys.

### Step 6: Physical Damage, Battery Condition and Environmental Exposure Assessment

**Procedure ID:** PI-C3-S06

**Purpose:** To evaluate physical media degradation, swollen lithium batteries, overheating, or fluid contamination threatening media survival.

**How to Perform It:**

1. Inspect device casings for cracks, crushed drive bays, burnt circuit boards, or water submersion marks.
2. Inspect mobile phones and laptops for swollen batteries (bulging casings) posing fire or explosion hazards.
3. Check device operating temperature; if excessively hot, ensure airflow cooling without powering OFF if live capture is active.

**Responsible Personnel:** DEFR.

**Required Documentation:** Physical Condition and Battery Risk Sheet (Form P3-06).

**Expected Output:** Safety and preservation protocols for damaged or environmentally degraded hardware.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 6.6 (p. 21), Clause 6.9.1 (p. 24).
2. NIJ (2008), Chapter 6 (p. 35).
3. Council of Europe C-PROC (2019), Section 3.3.3 (p. 13).

**Exception Handling:** For swollen lithium batteries, do not apply pressure or attempt battery removal; wrap the device in non-conductive, fire-retardant padding inside an anti-static container.

### Step 7: Storage Technology and Device-Specific Risk Assessment

**Procedure ID:** PI-C3-S07

**Purpose:** To identify specific storage media characteristics (NVMe SSDs, soldered eMMC/NAND flash, magnetic tape, RAID arrays) requiring specialized handling.

**How to Perform It:**

1. Identify internal storage technology: traditional HDD (spinning platters), SATA SSD, NVMe M.2 flash, or soldered mainboard NAND storage.
2. Recognize that modern SSDs execute internal garbage collection (TRIM commands) when powered ON, which actively erases deleted space.
3. Identify RAID array configurations (RAID 0, 1, 5, 10) on server storage.

**Responsible Personnel:** DES / DEFR.

**Required Documentation:** Storage Technology Risk Log (Form P3-07).

**Expected Output:** Matching evidence extraction protocols to specific storage media engineering realities.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 7.1.3.2 (pp. 33–34).
2. Council of Europe C-PROC (2019), Section 3.3.2 (pp. 10–11).

**Exception Handling:** For modern laptops with soldered NAND storage where drives cannot be physically removed, plan for off-line boot acquisition using validated forensic boot media (e.g., CAINE/Paladin).

### Step 8: Automatic Overwrite, Deletion and Recording-Cycle Assessment

**Procedure ID:** PI-C3-S08

**Purpose:** To evaluate time-sensitive overwrite cycles on security DVRs, server log rotators, or dashcams.

**How to Perform It:**

1. Check storage capacity and current space utilization on DVRs/servers.
2. Estimate time remaining before FIFO recording cycles overwrite relevant incident timeframes.
3. Formulate immediate export or power-down plan to halt overwriting.

**Responsible Personnel:** DEFR / DES.

**Required Documentation:** Overwrite Risk and Retention Log (Form P3-08).

**Expected Output:** Quantification of overwrite risks and execution of immediate retention steps.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 7.3 (p. 40).
2. NIJ (2008), Chapter 5 (p. 27).
3. ACPO v5 (2012), Section 4.3.1 (p. 8).

**Exception Handling:** Record exact time of manual power disconnection on CCTV units to correlate footage timestamps with atomic reference time.

### Step 9: Original State and Metadata Alteration Risk Evaluation

**Procedure ID:** PI-C3-S09

**Purpose:** To evaluate risks of modifying file system metadata (MACB timestamps: Modified, Accessed, Created, Born) through improper user interaction.

**How to Perform It:**

1. Enforce strict prohibition against opening files, launching applications, or shutting down operating systems via standard GUI menus on live machines.
2. Identify that booting a suspect computer normally will cause the OS to write hundreds of system files, corrupting evidence.
3. Mandate write-blocker usage for all non-volatile disk extractions.

**Responsible Personnel:** DEFR / DES.

**Required Documentation:** Metadata Integrity Risk Assessment (Form P3-09).

**Expected Output:** Total prevention of unrecorded metadata modifications during field handling.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 5.4.1 (p. 15), Clause 5.4.4 (p. 16).
2. ACPO v5 (2012), Section 2.1 (Principle 1, p. 6).
3. Council of Europe C-PROC (2019), Section 3.3.4 (p. 14).
