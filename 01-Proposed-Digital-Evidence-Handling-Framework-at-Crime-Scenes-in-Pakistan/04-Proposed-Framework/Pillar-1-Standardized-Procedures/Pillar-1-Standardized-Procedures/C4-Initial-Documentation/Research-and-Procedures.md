# COMPONENT 04: INITIAL DOCUMENTATION AND SCENE RECORDING

## Objective

To establish an unbroken, contemporaneous, visual, and textual record of the crime scene, device physical states, cable port connections, display screen contents, system clock skews, and investigator decisions prior to evidence packaging and removal.

## Expected Result

An auditable, permanent scene record containing high-resolution photography, spatial sketches, cable-to-port mapping diagrams, clock synchronization logs, screen display records, and contemporaneous decision logs satisfying ISO 27037 auditability requirements.

## Step-by-Step Operational Procedures

### Step 1: Crime Scene Photography and Visual Recording

**Procedure ID:** PI-C4-S01

**Purpose:** To capture comprehensive visual proof of the crime scene, device locations, cable layouts, and monitor displays in their original, undisturbed state.

**How to Perform It:**

1. Take overall wide-angle photographs of the entire crime scene showing spatial context and room entry points.
2. Take medium-range photographs showing digital devices in relation to desks, wall sockets, and surrounding furniture.
3. Take close-up photographs of every device showing make, model, serial numbers, physical damage, and attached cables.
4. Photograph front and rear connection panels of computers showing exact cable plug positions.
5. Photograph active monitor screens straight-on (avoiding flash glare) showing open windows and screen contents.

**Responsible Personnel:** Scene Documentation Officer / DEFR.

**Required Documentation:** Photographic Evidence Log (Form P4-01).

**Expected Output:** Complete, high-resolution photographic record of the scene and all exhibits.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 6.2.1 (p. 18), Clause 6.6 (p. 21).
2. NIJ (2008), Chapter 4 (p. 19), Chapter 5 (pp. 22–26).
3. ACPO v5 (2012), Appendix C, Section 3 (p. 19).
4. Council of Europe C-PROC (2019), Section 3.3.1 (p. 7).

**Exception Handling:** If screen display flickers under camera shutter, record a 10-second high-definition video of the monitor screen instead.

### Step 2: Scene Sketching and Spatial Relationship Mapping

**Procedure ID:** PI-C4-S02

**Purpose:** To construct an accurate, scaled or dimensioned diagram illustrating physical relationships between devices, network drops, and power outlets.

**How to Perform It:**

1. Measure room dimensions and fix positions of digital hardware using two fixed reference points (triangulation).
2. Draw detailed floor plan sketch showing desk arrangements, computer towers, monitors, routers, and cable runs.
3. Indicate exhibit numbers (EX-01, EX-02) on the sketch matching physical exhibit tags.

**Responsible Personnel:** Scene Documentation Officer.

**Required Documentation:** Final Crime Scene Diagram and Spatial Map (Form P4-02).

**Expected Output:** Precise spatial blueprint documenting exhibit positions within the crime scene.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 6.2.1 (p. 18).
2. NIJ (2008), Chapter 4 (p. 19).
3. ACPO v5 (2012), Appendix C, Section 3 (p. 19).

**Exception Handling:** If measuring tools are unavailable, draw a clear proportional sketch and note "not to scale — relative positions verified."

### Step 3: Physical Cable, Port, and Connection Documentation

**Procedure ID:** PI-C4-S03

**Purpose:** To document exact cable-to-port mappings on computers, routers, and CCTV DVRs to enable flawless physical reassembly during lab examination.

**How to Perform It:**

1. Inspect rear and front panels of desktop PCs, servers, and DVRs before unplugging any cable.
2. Attach uniquely numbered adhesive labels to both the cable plug and its corresponding port (e.g., Cable A-1 to port A-1; Cable A-2 to Port A-2).
3. Photograph the labeled port panel clearly before disconnecting any lead.
4. Record mapping in a Cable-to-port Connection Chart.

**Responsible Personnel:** DEFR.

**Required Documentation:** Cable and Port Connection Chart (Form P4-03).

**Expected Output:** Unambiguous cable-to-port labeling enabling exact system reconstruction.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 6.2.1 (p. 18), Clause 7.1.2.1.2 (p. 29).
2. NIJ (2008), Chapter 5 (p. 24), Chapter 6 (pp. 35–36).
3. Council of Europe C-PROC (2019), Section 3.3.2 (p. 10).

**Exception Handling:** If port labels will not adhere to oily or dusty metal surfaces, attach tie-on tags to the cable neck and draw a detailed port location grid in the notes.

### Step 4: Device Identifiers and Serial Number Logging

**Procedure ID:** PI-C4-S04

**Purpose:** To record all permanent hardware identifiers (make, model, serial number, IMEI, MAC address, ESN) establishing positive physical identity.

**How to Perform It:**

1. Inspect manufacturer asset tags, laser-etched rear labels, and battery cavity labels.
2. Record exact make, model name, model number, and unique serial number.
3. For mobile phones, record 15-digit IMEI number from battery compartment label or by dialing on live unlocked devices.
4. Record MAC addresses printed on network card labels or router bases.

**Responsible Personnel:** DEFR.

**Required Documentation:** Hardware Identification Master Sheet (Form P4-04).

**Expected Output:** Absolute hardware identification preventing exhibit substitution claims.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 6.6 (p. 21), Clause 7.1.1.1 (p. 26).
2. NIJ (2008), Chapter 5 (p. 24).
3. Council of Europe C-PROC (2019), Section 3.3.2 (pp. 8–10).

**Exception Handling:** If serial number label is scratched or missing, photograph the defaced area, log "serial defaced," and apply a permanent police barcode exhibit sticker.

### Step 5: Power State, Condition, and Discovery Record

**Procedure ID:** PI-C4-S05

**Purpose:** To record the precise operational state, environmental context, and physical condition of every item at the exact moment of discovery.

**How to Perform It:**

1. Record discovery timestamp (date and exact time).
2. Record power state (Powered ON, powered OFF, Standby, Battery Dead).
3. Record physical condition (intact, hot, wet, damaged).
4. Record discovering officer name and agency.

**Responsible Personnel:** Scene Documentation Officer / DEFR.

**Required Documentation:** Device Discovery Master Log (Form P4-05).

**Expected Output:** Contemporaneous baseline record of exhibit discovery state.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 6.6 (p. 21).
2. NIJ (2008), Chapter 4 (p. 19).
3. Council of Europe C-PROC (2019), Section 3.3.1 (p. 7).

**Exception Handling:** Ensure time is recorded using a single synchronized team reference clock (e.g., official GPS/atomic time).

### Step 6: Device System Clock Synchronization and Time Skew Logging

**Procedure ID:** PI-C4-S06

**Purpose:** To compare device internal clock settings against a verified atomic reference time, recording time offsets (delta) required for multi-device timeline analysis.

**How to Perform It:**

1. On powered-on systems, observe display dock or access BIOS/UEFI clock settings (or command prompt time/date without altering system state).
2. Compare device system time against a traceable atomic time source (e.g., GPS time or official NTP server time).
3. Calculate and record the exact time skew (e.g., "Device Clock is +04 minutes 12 seconds fast relative to UTC").
4. DO NOT adjust or correct the device clock setting at the scene.

**Responsible Personnel:** DEFR / DES.

**Required Documentation:** Clock Synchronization and Time Skew Log (Form P4-06).

**Expected Output:** Accurate time delta determination enabling precise cross-device event timeline normalization.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 6.6 (p. 21).
2. ACPO v5 (2012), Section 6.5 (p. 11).
3. Council of Europe C-PROC (2019), Section 3.3.4 (p. 15), Section 4.2.1 (p. 20).

**Exception Handling:** For powered-off computers, defer clock checking until laboratory examination when BIOS time can be safely checked inside a write-blocked environment.

### Step 7: Screen Display and Visible Software State Recording

**Procedure ID:** PI-C4-S07

**Purpose:** To record active application windows, open text files, chat logs, user accounts, and error messages visible on running displays.

**How to Perform It:**

1. Photograph screen directly perpendicular to display to avoid distortion.
2. Document in written notes all open application window titles, active user login names, open document filenames, and URL browser bars.
3. Note running chat sessions, instant messaging contacts, or active file download meters.
4. Document any visible error messages or security warnings.

**Responsible Personnel:** DEFR / Scene Documentation Officer.

**Required Documentation:** Screen Display Observation Sheet (Form P4-07).

**Expected Output:** Complete photographic and textual capture of active user desktop session context.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 6.6 (p. 21), Clause 7.1.1.1 (p. 26).
2. NIJ (2008), Chapter 5 (pp. 22–25).
3. ACPO v5 (2012), Appendix C, Section 8 (p. 19).
4. Council of Europe C-PROC (2019), Section 3.3.3 (p. 13).

**Exception Handling:** If screen goes blank due to sleep timer while photographing, gently move mouse 1 mm to restore backlight, and log the mouse movement in notes.

### Step 8: Evidence Discovery and Scene Change Logging

**Procedure ID:** PI-C4-S08

**Purpose:** To maintain a contemporaneous chronological log of every evidence discovery event, physical movement, or scene modification.

**How to Perform It:**

1. Log events in real-time as they occur:
   - 10:15: Item EX-01 discovered on Desk 1.
   - 10:22: Item EX-01 screen display photographed.
   - 10:35: Item EX-01 power cable disconnected directly from PC rear.
   - 10:40: Item EX-01 moved to clean packaging table in Zone 3.
2. Ensure every entry includes timestamp, action, item ID, and acting officer signature.

**Responsible Personnel:** Scene Documentation Officer.

**Required Documentation:** Evidence Discovery and Scene Change Log (Form P4-08).

**Expected Output:** A seamless contemporaneous timeline of scene processing activities.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 5.3.2 (p. 14), Clause 6.1 (p. 17).
2. ACPO v5 (2012), Section 2.1 (Principle 3, p. 6).
3. Council of Europe C-PROC (2019), Section 3.3.4 (p. 15).

**Exception Handling:** Never reconstruct scene logs from memory after leaving the scene; all entries must be recorded contemporaneously during scene processing.

### Step 9: Standardized Scene Decision Logging

**Procedure ID:** PI-C4-S09

**Purpose:** To document the scientific and technical rationale for all operational decisions made at the scene, satisfying ISO 27037 justifiability requirements.

**How to Perform It:**

1. Record key decision points:
   - Rationale for executing immediate power pull vs. live RAM capture.
   - Rationale for seizing physical device vs. performing on-site imaging.
   - Rationale for uncollected/excluded electronics at the scene.
2. Include decision-maker name, role, timestamp, and technical justification.

**Responsible Personnel:** Crime Scene Supervisor / DES.

**Required Documentation:** Standardized Scene Decision Log (Form P4-09).

**Expected Output:** An auditable technical defense for every evidence handling decision.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 5.3.5 (p. 14), Clause 5.4.3 (p. 16).
2. ACPO v5 (2012), Section 2.1 (Principle 2, p. 6).

**Exception Handling:** If a decision deviates from standard baseline guidelines due to emergency conditions, detail the specific emergency threat justifying the deviation.

### Step 10: Digital Evidence Source Attribution Protocol

**Procedure ID:** PI-C4-S10

**Purpose:** To record objective physical and logical associations linking specific devices to user accounts, physical seating positions, or personal belongings without making legally premature statements.

**How to Perform It:**

1. Record physical proximity facts (e.g., "Phone EX-03 recovered from coat pocket belonging to Subject Y").
2. Record logical user account facts (e.g., "Desktop EX-01 active user profile displayed as 'j_doe'").
3. Frame all entries objectively as factual observations rather than conclusive declarations of ownership.

**Responsible Personnel:** Scene Documentation Officer / Investigation Officer.

**Required Documentation:** Source Attribution and Association Record (Form P4-10).

**Expected Output:** Objective factual foundation connecting physical exhibits to scene subjects.

**Supporting References:**

1. ISO/IEC 27037:2012, Clause 6.6 (p. 21).
2. NIJ (2008), Chapter 4 (p. 19).
3. ACPO v5 (2012), Section 4.3.1 (p. 8).
