COMPONENT 05: EVIDENCE COLLECTION, PRESERVATION AND
CONTAMINATION PREVENTION

Main Activity 1: Decision-Making Process for Collection or Acquisition

Step 1: Assessment of Factors for Collection or Acquisition

Procedure ID: PI-C5-S01

Purpose:

To determine whether a digital device should be collected or potential digital
evidence should be acquired by considering the relevant factors before
making the decision.

How to Perform It:

Consider the following factors when deciding whether to collect a digital
device or acquire potential digital evidence:

1. Volatility of Potential Digital Evidence: Consider the volatility of potential
digital evidence.

2. Existence of Full Disk Encryption or Encrypted Volumes: Consider
whether full disk encryption or encrypted volumes exist, where passphrases
or keys may reside as volatile data in RAM, external tokens, smart cards, other
devices or media.

3. Criticality of the System: Consider the criticality of the system.

4. Legal Requirements: Consider the legal requirements of the relevant
jurisdiction.

5. Available Resources: Consider the size of storage required, availability of
personnel and time constraints.

Responsible Personnel: Not specified in the provided ISO excerpt.

Required Documentation: Not specified in the provided ISO excerpt.

Expected Output: Decision regarding collection of a digital device or
acquisition of potential digital evidence.

Supporting References:

      ISO/IEC 27037:2012, Clause 7.1.1.3.

   ISO/IEC 27037:2012, Figure 1 — Guidelines for decision-making of
       collection or acquisition of potential digital evidence.




Main Activity 2: Collection of Powered-On Digital Devices

Part 1: Collection of Powered-On Digital Devices

Step 1: Overview of Powered-On Digital Device Collection

Procedure ID: PI-C5-S02

Purpose:
To establish the collection approach for a powered-on digital device by
distinguishing between baseline and additional activities according to the
device and circumstances.

How to Perform It:

   1. The DEFR follows the applicable guidelines for collecting a powered-on
       digital device.

   2. Not all activities are appropriate or relevant in every case.

   3. Collection activities are categorized as:

           o   Baseline activities: Activities that should be applied in all
               circumstances.

o   Additional activities: Activities applied when relevant and
              applicable, depending on the device and circumstances.

   4. Follow the applicable activities illustrated in Figure 2.

Responsible Personnel:
Digital Evidence First Responder (DEFR).

Required Documentation:
Document the applicable collection activities and any relevant additional
activities.

Expected Output:
The collection approach for the powered-on digital device is established
according to the applicable baseline and additional activities.

Supporting References:

      ISO/IEC 27037:2012, Clause 7.1.2.1.1 — Overview.

      ISO/IEC 27037:2012, Figure 2 — Guidelines for collection of powered-on
       digital device.




Step 2: Baseline Activities — Powered-On Digital Device Collection

Procedure ID: PI-C5-S03

Purpose:
To follow the baseline activities when collecting a powered-on digital device,
considering volatile data, device configuration, power removal and
preservation of the device’s current state.

How to Perform It:

1. Consider Volatile Data and Current State

      Consider acquisition of the digital device’s volatile data and current
       state before powering the system off.

      Encryption keys and other crucial data may reside in active memory or
       inactive memory that has not yet been cleared.

      Consider logical acquisition when encryption is suspected.

      The live host operating system may be untrustworthy; consider using
       appropriate trusted and validated tools.

2. Determine the Appropriate Power-Off Method

      Consider the device configuration to determine whether to shut down
       through normal administrative procedures or remove the power supply.

      Consult a Digital Evidence Specialist (DES), if necessary, to determine the
       appropriate approach.

      If the decision is to remove the power cable, disconnect the end attached
       to the digital device, not the end attached to the power socket.

      Be aware that removing the wall-side cable from a device connected to a
       UPS may alter data.

3. Consider the Risks of Power Removal

      Removing power may make encrypted volumes inaccessible unless the
       decryption key has been obtained.

      Valuable live data may be lost, potentially resulting in damage claims or
       loss of human life, such as in digital devices controlling medical
       equipment.

      Ensure that volatile data is collected before removing the power supply.

4. Consider Maintaining Power Where Appropriate

   Hardware may allow a powered-on device to be transferred from utility
       power to a portable UPS without interrupting power.

      Mouse-jigglers may be used to prevent the screen-saver from activating.

      If the device is collected while remaining powered on, packaging and
       transportation should address cooling and protection from mechanical
       shock.

5. Label, Disconnect and Secure Cables

      Label, disconnect and secure all cables from the digital device.

      Label the ports so that the system can be reconstructed later.

6. Protect the Power Switch

      Place tape over the power switch, if necessary, to prevent it from
       changing state.

      Consider whether the switch state has been properly documented
       before taping or moving the device.

Responsible Personnel:
Digital Evidence First Responder (DEFR). A Digital Evidence Specialist (DES)
may be consulted when necessary.

Required Documentation:

      Cable and port labels.

      Power-switch state, where applicable.

      Relevant device and cable details needed for system reconstruction.

Expected Output:
The powered-on digital device is collected according to the applicable baseline
activities, with volatile data and the device’s current state considered, and
cables labeled, disconnected and secured.

Supporting References:

      ISO/IEC 27037:2012, Clause 7.1.2.1.2 — Baseline activities: powered-on
       digital device collection.

   ISO/IEC 27037:2012, Figure 2 — Guidelines for collection of powered-on
       digital device.




Step 3: Additional activities: powered on digital device collection

Procedure ID: PI-C5-S04

Purpose:

Following are additional activities that are relevant depending on the
configuration of the specific digital device.

How to Perform It:

   1. Ensure that volatile data has been acquired before removing the
       notebook computer's battery.

   2. Remove the main power-source battery first instead of pressing the
       notebook computer's power button to shut it down.

   3. Check whether a power adapter is connected.

   4. If a power adapter is present, remove it after removing the battery.

Important Considerations:

      Pressing the power button may initiate a script that changes or deletes
       information before shutdown.

      It may alert connected systems about an unexpected event, potentially
       causing them to erase evidential data.

      It may also be configured to trigger a device intended to cause physical
       harm to the DEFR or other individuals present.

Responsible Personnel: DEFR.

Required Documentation:

      Notebook power condition.

      Battery condition.

      Power adapter presence.

   Actions performed during battery and power-adapter removal.

Expected Output: Notebook computer collected with applicable additional
battery and power-adapter handling activities completed.

Supporting References:

      ISO/IEC 27037:2012, Clause 7.1.2.1.3.

      ISO/IEC 27037:2012, Figure 2.



Step 4: Additional Activities for Removable and Optical Drive Slots

Procedure ID: PI-C5-S05

Purpose:

To secure floppy disk slots and CD/DVD drive trays of powered-on digital
devices during collection.

How to Perform It:

   1. Place tape over the floppy disk slot, if present.

   2. Ensure that CD or DVD drive trays are retracted into place.

   3. Note whether the drive trays are:

           o   Empty.

           o   Contain disks.

           o   Unchecked.

   4. Tape the drive slot closed to prevent it from opening.

Important Consideration:

If bootable media is left inside the drive, the machine may boot from that
media when powered on again instead of booting from its hard drive or
forensic tools flash drive, depending on the computer's BIOS settings.

Responsible Personnel: DEFR.

Required Documentation:

      Floppy disk slot condition, where present.

   CD/DVD drive tray condition.

      Presence or absence of disks.

      Actions performed to secure the drive slots.

Expected Output: Floppy disk slots and CD/DVD drive trays secured and their
conditions documented.

Supporting References:

      ISO/IEC 27037:2012, Clause 7.1.2.1.3.

      ISO/IEC 27037:2012, Figure 2.



Step 5: Computer Display and Operational Condition Documentation

Procedure ID: PI-C5-S06

Purpose:

To document the visible screen contents and operational condition of
powered-on computers before further handling.

How to Perform It:

A. NIJ Monitor Display Situations

Follow the relevant monitor display situation:

   1. Situation 1 — Monitor ON, Display Visible: Photograph the screen
       display immediately.

   2. Situation 2 — Monitor ON, Screen Saver Active: Gently move the
       mouse 1–2 mm without clicking to restore the display and photograph
       the screen.

   3. Situation 3 — Monitor ON, Display Blank: Gently move the mouse 1–2
       mm. If the screen restores, photograph it. If it remains blank, check the
       PC tower power LEDs.

   4. Situation 4a/b — Monitor OFF: Turn the monitor ON. If a display
       appears, photograph it. If it remains blank, check the tower's power
       state.

5. Situation 5 — Monitor ON, Blank Screen, No Response: Listen for fans
       and check LEDs. If the system is completely quiet, treat it as powered
       OFF.

B. ACPO Powered-On Computer Handling

If the computer is switched ON:

   1. Photograph the screen and make written notes of its contents, including
       approximate window positions, titles and contents.

   2. Do not touch the keyboard or click the mouse.

   3. If the screen is blank or a screen saver is present, decide whether
       restoring the screen is necessary.

   4. If restoration is considered appropriate, use a short mouse movement to
       restore the screen or determine whether password protection is active.

   5. If the screen restores, photograph or video it and document its contents.

   6. If password protection appears, do not continue interacting with the
       mouse.

   7. Record the time and activity of mouse use.

   8. For game consoles or tablet computers, equivalent interaction may
       involve moving the controller joystick or touching the touchscreen.

   9. If valuable evidence may exist in the current state, such as relevant
       documents or instant-message conversations, seek advice from the local
       Digital Forensic Unit (DFU).

   10. Consider advice from the computer owner or user, but treat the
       information with caution.

   11. Allow equipment to cool down before removal.

   12. Track visible cables, as they may lead to other devices in other rooms.

Responsible Personnel: DEFR / DFU.

Required Documentation:

      Photographs or videos of the screen.

      Written notes of visible screen contents.

   Monitor and computer operational status.

      Mouse or other interaction details, where applicable.

      Cable connections and relevant observations.

Expected Output: Documented screen contents and operational condition of
the computer.

Supporting References:

      NIJ (2008), Electronic Crime Scene Investigation: A Guide for First
       Responders, Second Edition.

      ACPO v5 (October 2011), Good Practice Guide for Digital Evidence,
       Computer Handling Guidance.




Step 6: Collection of Powered-On Mobile Communication Devices

Procedure ID: PI-C5-S07

Purpose:

To handle and collect powered-on mobile communication devices while
considering network connectivity, potential remote changes and preservation
of device data.

How to Perform It:

A. ACPO Mobile Device Guidance

   1. Secure and take control of the area containing the equipment.

   2. Do not allow other persons to interact with the equipment.

   3. Photograph the device in situ or note where it was found.

4. Record the device's status and any on-screen information.

   5. If the device is switched ON, consider whether it should be powered OFF
       to isolate it from network signals and prevent potential remote wiping.

   6. In exceptional circumstances, consider keeping the device ON where
       timely access to handset data is critical.

   7. Consider placing the handset in a Faraday environment to prevent
       signal reception, where appropriate.

   8. Seek advice from the DFU in such circumstances.

   9. Seize associated cables, chargers, packaging, manuals and phone bills.

   10. Consider packaging materials and associated paperwork as potential
       sources of PIN/PUK details.

   11. Consider automatic housekeeping functions that may clear data after a
       specified period.

   12. Submit items for examination as soon as possible.

B. Council of Europe C-PROC Mobile Device Guidance

1. Determine the operational status of the mobile communication device.

If the device is turned OFF:

      Do not turn it ON.

      Check for a SIM card, including its type and serial number.

      Check for memory cards, including miniSD and microSD.

      Check the IMEI number.

If the device is turned ON:

      Identify the IMEI number by entering *#06#.

      Do not turn the device OFF while checking the IMEI.

      Switch the device to flight mode to minimize unintended alteration of
       data/logs and avoid remote locking or deletion.

      If the device is locked with an unknown code, isolate it, preferably in a
       Faraday bag.

2. Determine the users of each mobile device, allocated telephone number
       and connected network, if possible.

   3. Identify the device lock code, where applicable.

   4. Identify potential SIM PIN/PUK codes, including those printed on
       original SIM card packaging.

   5. Identify and seize the charger and data cables associated with each
       mobile device.

   6. Package mobile devices in cardboard boxes or paper bags rather than
       plastic materials, separately from other assets, valuable items or
       documentary evidence.

   7. Complete and attach an exhibit label.

Responsible Personnel: DEFR / DFU.

Required Documentation:

      Mobile device photographs and in-situ location.

      Operational and power status.

      IMEI number.

      SIM and memory card details.

      User, telephone number and network details, where available.

      Lock code and PIN/PUK information, where available.

      Associated accessories.

      Completed exhibit label.

Expected Output: Mobile communication device and associated materials
collected with operational condition, connectivity and available access
information documented.

Supporting References:

      ACPO v5 (October 2011), Good Practice Guide for Digital Evidence, Mobile
       Device Guidance.

   Council of Europe C-PROC (2019), Standard Operating Procedures for the
       Collection, Analysis and Presentation of Electronic Evidence, Mobile
       Devices section.

Step 7: Final Collection Documentation and Verification

Procedure ID: PI-C5-S08

Purpose:

To ensure that powered-on digital devices and associated materials have been
appropriately documented before completing collection activities.

How to Perform It:

   1. Confirm that the device's power and operational condition have been
       documented.

   2. Confirm that screen contents and visible device conditions have been
       photographed or recorded, where applicable.

   3. Confirm that cables and ports have been labeled and secured.

   4. Confirm that associated power adapters, batteries, chargers and data
       cables have been identified.

   5. Ensure that exhibit labels are signed and completed.

   6. Record any relevant user or access information obtained.

   7. Record any exceptional handling decisions and specialist advice.

Responsible Personnel: DEFR / DFU.

Required Documentation:

      Device power-state and operational-status records.

      Photographs and written notes.

      Cable and port records.

      Associated accessory records.

      Signed and completed exhibit labels.

      Relevant user and access information.

Expected Output: Properly documented powered-on digital devices and
associated materials ready for the next evidence-handling stage.

Supporting References:

      ISO/IEC 27037:2012, Clause 7.1.2.1.2–7.1.2.1.3.

      ACPO v5 (October 2011), Computer and Mobile Device Guidance.

      Council of Europe C-PROC (2019), Mobile Devices section.




Part 2: Collection of Powered-Off Digital Devices

Step 1: Overview of Powered-Off Digital Device Collection

Procedure ID: PI-C5-S09

Purpose:

To establish the collection approach for powered-off digital devices by
distinguishing between baseline and additional activities.

How to Perform It:

   1. The DEFR follows the applicable guidelines for collecting powered-off
       digital devices.

   2. Not all activities are relevant in every circumstance.

   3. Collection activities are divided into:

           o   Baseline activities: Activities that apply in all cases.

           o   Additional activities: Activities that may apply only in some
               cases.

   4. Follow the applicable baseline and additional activities illustrated in
       Figure 3.

Responsible Personnel: Digital Evidence First Responder (DEFR).

Required Documentation: Not specified in the provided ISO excerpt.

Expected Output: Collection approach established according to the applicable
baseline and additional activities.

Supporting References:

      ISO/IEC 27037:2012, Clause 7.1.2.2.1 — Overview.

      ISO/IEC 27037:2012, Figure 3 — Guidelines for collection of powered-off
       digital device.




Step 2: Baseline Activities — Powered-Off Digital Device Collection

Procedure ID: PI-C5-S10

Purpose:

To follow the recommended baseline activities when collecting a powered-off
digital device while preserving its connections, condition and associated
storage media.

How to Perform It:

1. Remove the Power Supply Cable

   Remove the power supply cable from the end attached to the digital
       device, not the end attached to the power socket.

2. Disconnect and Secure All Cables

      Disconnect and secure all cables from the digital device.

      Label the ports so that the system can be reconstructed at a later stage.

3. Protect the Power Switch

      Place tape over the power switch, if necessary, to prevent its state from
       changing.

      Consider whether the state of the switch has been properly documented
       before taping or moving the device.

4. Handle Storage Media

      In most cases, do not remove storage media from the digital device until
       it is going to be acquired.

      Removing storage media increases the risk of damaging it or confusing
       it with other storage media.

      Develop and follow local procedures regarding the need to remove
       storage media from digital devices.

Responsible Personnel: Digital Evidence First Responder (DEFR).

Required Documentation:

      Cable and port labels.

      Power-switch state, where applicable.

      Storage-media handling actions, where applicable.

Expected Output: Powered-off digital device collected with cables
disconnected and secured, ports labeled, and storage media handled according
to applicable procedures.

Supporting References:

      ISO/IEC 27037:2012, Clause 7.1.2.2.2 — Baseline activities: powered-off
       digital device collection.

   ISO/IEC 27037:2012, Figure 3 — Guidelines for collection of powered-off
       digital device.




Step 3: Additional Activities — Powered-Off Digital Device Collection

Procedure ID: PI-C5-S11

Purpose:

To apply additional collection activities according to the configuration of the
specific powered-off digital device.

How to Perform It:

1. Notebook Computer

      Ensure that the notebook computer is actually powered off, as some
       computers may be in standby mode.

      Be aware that some notebook computers can power on when their lids
       are opened.

      Remove the main power-source battery from the notebook computer.

2. Hard Drive Removal

      If field conditions require the hard drive to be removed, ground the
       digital device to prevent static electricity from damaging the hard drive.

      Otherwise, do not remove the hard drive in the field.

      Label the hard drive as a suspect disk.

      Document the hard drive's make, model name, serial number and size.

3. Floppy Disk Slot

      Place tape over the floppy disk slot, if present.

4. CD/DVD Drive

      Ensure that the CD/DVD drive trays are retracted into place.

      Note whether the trays are:

o   Empty.

          o   Contain disks.

          o   Unchecked.

      Tape the drive slot closed to prevent it from opening.

Important Consideration:

If bootable media is left inside the device, the machine may boot from that
media instead of its hard drive or forensic tools flash drive when powered on
again, depending on the computer's BIOS settings.

Responsible Personnel: Digital Evidence First Responder (DEFR).

Required Documentation:

      Notebook power condition and battery-removal details.

      Hard drive make, model name, serial number and size, where removed.

      Floppy disk slot condition, where present.

      CD/DVD drive tray condition.

      Presence or unchecked status of disks.

      Actions performed to secure the drive slots.

Expected Output: Powered-off digital device and applicable associated
components handled according to their configuration, with relevant details
documented.

Supporting References:

      ISO/IEC 27037:2012, Clause 7.1.2.2.3 — Additional activities: powered-off
       digital device collection.

      ISO/IEC 27037:2012, Figure 3 — Guidelines for collection of powered-off
       digital device.

MAIN ACTIVITY 3: DIGITAL EVIDENCE ACQUISITION

Part 1: Live Data Acquisition

Step 1: Overview of Live Data Acquisition

Procedure ID: PI-C5-S12

Purpose:

To acquire volatile digital evidence from a powered-on digital device before it
is lost due to power removal or system shutdown.

How to Perform It:

   1. Identify whether the digital device is powered on.

   2. Understand that live data acquisition involves collecting volatile data
       from a live or powered-on system.

Types of data captured during live acquisition

A. System Data

      Current system configuration.

      Running state.

      Current system date and time.

      System uptime.

      Running processes.

      Logged-on users.

      DLLs or shared libraries.

      Swap files and temporary files.

B. Network Data

      Routing tables.

      ARP cache.

      Network configuration.

      Network connections.

3. Acquire volatile information in real time because it is dynamic and may
       be lost when the device is switched off.

   4. Consider that live data acquisition may be followed by static/dead
       acquisition.

Responsible Personnel: Digital Evidence First Responder (DEFR).

Supporting References:

      Digital Forensics Essentials, Module 04 — Data Acquisition and
       Duplication, Live Acquisition, Pages 188–189.

Pasted text (2).txt

      ISO/IEC 27037:2012, Clause 7.1.3.1 — Powered-on Digital Devices.



Step 2: Order of Volatility

Procedure ID: PI-C5-S13

Purpose

To establish the sequence for collecting digital evidence during live data
acquisition, starting with the most volatile data and proceeding towards the
least volatile data.

How to Perform It

During live data acquisition, the investigator should collect the most volatile
data first because it may change or disappear quickly. According to RFC 3227,
the order of volatility for a typical computing system is:

   1. Registers and Processor Cache: The information in the registers or the
       processor cache on the computer exists for nanoseconds. It is constantly
       changing and can be classified as the most volatile data.

   2. Routing Table, Process Table, Kernel Statistics, and Memory: The
       routing table, ARP cache, and kernel statistics reside in the ordinary

memory of the computer. These are slightly less volatile than the
     information in the registers, with a life span of about ten nanoseconds

  3. Temporary System Files: Temporary system files tend to persist for a
     longer time on the computer compared to routing tables and ARP
     caches. These systems are eventually overwritten or changed,
     sometimes in seconds or minutes later.

  4. Disk or Other Storage Media: Anything stored on a disk stays for a
     while. However, sometimes due to unforeseen events, these data can be
     erased or overwritten. Therefore, disk data may also be considered
     somewhat volatile, with a lifespan of some minutes

  5. Remote Logging and Monitoring Data: Data that pass through a
     firewall cause a router or switch to generate logs. The system might
     store these logs elsewhere. These logs may overwrite themselves within
     an hour, a day, or a week. However, these are generally less volatile data.

  6. Physical Configuration and Network Topology: Physical configuration
     and network topology are less volatile and have a longer life span than
     some other logs

7. Archival Media: A DVD-ROM, a CD-ROM, or a tape contains the least
  volatile data because the digital information does not change in such data
  sources automatically unless damaged under a physical force.

Responsible Personnel

Investigator conducting live data acquisition.

Required Documentation

The provided DFE reference explains the order of volatility but does not
specify a separate documentation requirement for this step.



Supporting References

- Digital Forensics Essentials, Module 04 — Data Acquisition and Duplication,
“Order of Volatility,” Page 191.




3. Baseline Activities: Powered-On Digital Device Acquisition

Procedure ID: PI-C5-S14

Purpose

To acquire potential digital evidence from a powered-on digital device,
including volatile data that may be lost if the device is switched off.

How to Perform It

1. Consider Volatile Data Acquisition

      Identify volatile data that may be lost if the device is powered off.

      Consider acquiring:

          o   Random Access Memory (RAM).

          o   Running processes.

          o   Network connections.

          o   Date and time settings.

2. Perform Live Data Acquisition

      Perform live acquisition when volatile information needs to be
       collected.

      RAM may contain useful information, such as network status, decrypted
       applications and passwords.

      Live acquisition may be performed through the system console or
       remotely over a network.

3. Store and Hash Volatile Data

      Store acquired volatile data in a logical file container where possible.

      Calculate the hash value of the container.

      If a logical file container cannot be used, store the data in a ZIP file and
       calculate its hash value.

      Document the calculated hash value.

      Store the acquired data on prepared and formatted storage media.

4. Image Live Non-Volatile Storage

      Create an image of the device's non-volatile storage using an
       appropriate imaging process.

      Store the image on prepared storage media.

   Web activity

      Spreadsheets

      Slack space

      Swap files

      Unallocated drive space

      Deleted files

Other static data that may be recovered from hard drives includes:

      Temporary files

      System registries

      Event/system logs

      Boot sectors

      Web browser cache

      Cookies

      Hidden files

D. Best Practices for Dead Data Acquisition

Follow these basic rules to preserve the original digital evidence and maintain
the integrity of acquired copies:

   1. Do Not Work on Original Evidence: Do not perform forensic
       investigation or other processes directly on the original digital evidence,
       as this may alter the data.

   2. Create a Bit-Stream Image: Create a duplicate bit-stream image of the
       suspect drive or file for forensic examination and analysis.

   3. Produce Two or More Copies: Create at least two copies of the original
       media:

          o   Working Copy: Used for forensic examination and analysis.

          o   Library/Control Copy: Stored for disclosure purposes or in case
              the working copy becomes corrupted.

4. Use Blank Media: If drive-to-drive imaging is required, use blank
       media, such as new drives.

   5. Verify Integrity: Verify the integrity of acquired copies by comparing
       their hash values with the original media. MD5 is provided as an
       example in the reference.

Responsible Personnel

Not specified in the provided DFE reference.

Required Documentation

Not specified in the provided DFE reference.

Expected Output

      Understanding of dead acquisition and static data.

      Identification of non-volatile data sources and types of static digital
       evidence.

      Preservation of original evidence.

      Creation of forensic copies for examination and control purposes.

      Verification of the integrity of acquired copies.

Supporting References

      DFE Module 04, page 193 — Dead Acquisition and Static Data.

      DFE Module 04, page 194 — Rules of Thumb for Data Acquisition.



2. Different Types of Data Acquisition

Procedure ID: PI-C5-S20

Purpose

To understand different types of data acquisition and identify the appropriate
acquisition method according to the investigation requirements.

How to Perform It

A. Logical Acquisition

1. Understand that logical acquisition allows an investigator to capture
       only selected files or file types relevant to the investigation.

   2. Use logical acquisition when only specific data is required instead of
       acquiring the entire storage media.

   3. Consider the following examples:

          o     Collecting Outlook .pst or .ost files during email investigations.

          o     Collecting specific records from a large RAID server.

B. Sparse Acquisition

   1. Understand that sparse acquisition is similar to logical acquisition.

   2. Recognize that this method also collects fragments of unallocated data,
       allowing investigators to acquire deleted files.

   3. Use this method when examination of the entire drive is not required.

C. Bit-Stream Imaging

   1. Understand that bit-stream imaging creates a bit-by-bit copy of the
       suspect drive.

   2. Ensure that the image contains a cloned copy of the entire storage
       media, including all its sectors and clusters.

   3. Recognize that this method allows investigators to retrieve deleted files
       and folders.

   4. Understand that bit-stream images help prevent contamination of the
       original media during forensic examination.

   5. Recognize that forensic tools such as FTK Imager and EnCase can read
       bit-stream images.

D. Types of Bit-Stream Imaging

Bit-stream imaging has two main types:

1. Bit-Stream Disk-to-Image File

      Understand that this method creates an image file from the suspect
       drive.

   Recognize that it is commonly used by forensic investigators.

      Understand that it is a flexible method that enables the creation of one
       or more copies of the suspect drive.

      Examples of tools:

          o   ProDiscover

          o   EnCase

          o   FTK

          o   The Sleuth Kit

          o   X-Ways Forensics

2. Bit-Stream Disk-to-Disk

   1. Consider disk-to-disk imaging when disk-to-image-file acquisition
       cannot be performed, including:

          o   When the suspect drive is very old and incompatible with the
              imaging software.

          o   When there is a need to recover credentials used for websites and
              user accounts.

   2. Create a bit-stream disk-to-disk copy of the original disk or drive.

   3. Adjust the target disk geometry, including its head, cylinder, and track
       configuration, to align with the suspect drive where required.

   4. Recognize that this adjustment helps achieve a smooth data acquisition
       process.

   5. Examples of tools:

          o   EnCase

          o   SafeBack

          o   Tableau Forensic Imager

E. Selection of an Appropriate Acquisition Method

   1. Recognize that acquiring a complete bit-by-bit copy of a drive may
       require significant time, especially for large storage disks.

2. Consider logical acquisition when the investigator knows which files are
       required and there are time constraints.

   3. Consider sparse acquisition when the entire drive does not need to be
       examined but fragments of deleted data are also required.

   4. Consider bit-stream imaging when a complete copy of the storage media
       is required.

Responsible Personnel

Not specified in the provided DFE reference.

Required Documentation

Not specified in the provided DFE reference.

Expected Output

      Identification of logical, sparse, and bit-stream acquisition methods.

      Understanding of disk-to-image-file and disk-to-disk imaging.

      Selection of an appropriate acquisition method according to
       investigation requirements.

Supporting References

      DFE Module 04, page 195 — Types of Data Acquisition.

      DFE Module 04, page 196 — Types of Data Acquisition and Their
       Applications.




3. Data Acquisition Formats

Procedure ID: PI-C5-S21

Purpose

To understand different forensic data acquisition formats and identify their
features, advantages, disadvantages, and capabilities for storing digital
evidence and related metadata.

How to Perform It

A. Raw Format

   1. Understand that Raw format creates a bit-by-bit copy of the suspect
       drive.

   2. Recognize that images in this format are usually obtained using the dd
       command.

Advantages

      Provides fast data transfers.

      Minor data read errors on the source drive are ignored.

      Can be read by most forensic tools.

Disadvantages

      Requires the same amount of storage space as the original media.

      Some tools, mostly open-source tools, might fail to recognize or collect
       marginal (bad) sectors from the suspect drive.

      Freeware tools generally have a low threshold for retrying reads on
       weak media areas, whereas commercial acquisition tools use more
       retries to ensure that data is collected.

B. Proprietary Format

   1. Understand that commercial forensic tools acquire data from the
       suspect drive and save image files in their own formats.

   2. Identify the following features of proprietary formats:

          o     Image Compression: Provides an option to compress evidence
                disk or drive image files to save space on target media.

          o     Image Segmentation: Allows an image to be divided into
                multiple segments so that it can be stored on smaller target
                media, such as CDs or DVDs, while maintaining integrity.

o   Metadata Integration: Allows metadata to be incorporated into
             the image file, including:

                   Date and time of acquisition.

                   Hash values of files.

                   Case details.

Disadvantage

- An image file format created by one forensic tool may not be supported by
other forensic tools.

C. Advanced Forensics Format (AFF)

   1. Understand that AFF is an open-source data acquisition format used to
      store disk images and related metadata.

   2. Recognize that AFF was developed to provide an open disk imaging
      format as an alternative to proprietary formats.

   3. Identify the following file extensions:

         o   .afm — Used for AFF metadata.

         o   .afd — Used for segmented image files.

   4. Recognize that AFF does not impose implementation restrictions on
      forensic investigators because it is an open-source format.

   5. Identify the following features:

         o   Simple design.

         o   Accessibility across multiple computing platforms and operating
             systems.

         o   Image compression capability.

         o   Ability to store metadata about image files or segmented files.

         o   Internal consistency checks for self-authentication.

   6. Understand the compression algorithms supported by AFF:

         o   Zlib: Faster but less efficient.

         o   LZMA: Slower but more efficient.

7. Recognize that an AFF disk image is a single file composed of segments
     containing drive data and metadata.

  8. Understand that AFF file contents can be compressed or uncompressed.

  9. Recognize that AFFv3 supports the following file extensions:

        o   AFF

        o   AFD

        o   AFM

D. Advanced Forensic Framework 4 (AFF4)

  1. Understand that Advanced Forensic Framework 4 (AFF4) was created by
     Michael Cohen, Simson Garfinkel, and Bradly Schatz as a redesigned and
     improved version of AFF.

  2. Recognize that AFF4 was designed to support storage media with large
     capacities.

  3. Understand that AFF4 uses an object-oriented design consisting of
     generic objects with externally accessible behaviour.

  4. Identify the three main object types:

        o   Volumes

        o   Streams

        o   Graphs

  5. Understand that AFF4 objects can be addressed by their names within
     the AFF4 system and are universally referenced through unique URLs.

  6. Recognize that AFF4 is an abstract information model that allows:

        o   Storage of disk-image data in one or more locations.

        o   Storage of information about the data separately.

        o   Storage of different types of organized information in an evidence
            file.

  7. Identify the following AFF4 features:

        o   Unified data model and naming scheme.

o   Support for a large number of images.

          o   Support for container formats such as Zip and Zip64.

          o   Support for simple directory-based storage.

          o   Support for network storage.

          o   Support for WebDAV, an extension of the HTTP protocol that
              enables imaging directly to a central HTTP server.

          o   Support for maps, which are zero-copy transformations of data.

          o   Support for image signing and cryptography.

          o   Image transparency for clients.

   8. Understand the purpose of zero-copy transformations:

          o   They avoid copying data from one memory area to another.

          o   They reduce CPU workload and improve efficiency.

          o   For example, instead of storing a new copy of a carved file, AFF4
              can store a map of the blocks allocated to that file.

   9. Understand the globally unique identifier scheme used by AFF4 to
       identify and reference evidence.

E. Basic AFF4 Object Types

1. Volumes

      Store segments, which are indivisible blocks of data.

2. Streams

      Data objects that support reading or writing.

      Examples include segments, images, and maps.

3. Graphs

      Collections of RDF statements.

Responsible Personnel

Not specified in the provided DFE reference.

Required Documentation

Not specified in the provided DFE reference.

Expected Output

      Understanding of Raw, Proprietary, AFF, and AFF4 acquisition formats.

      Identification of their features, advantages, and disadvantages.

      Understanding of image compression, segmentation, and metadata.

      Identification of AFF and AFF4 file structures and object types.

      Understanding of the capabilities of different forensic image formats.

Supporting References

      DFE Module 04, page 200 — Raw Format, Proprietary Format, and
       Advanced Forensics Format (AFF).

      DFE Module 04, page 201 — Advanced Forensic Framework 4 (AFF4).




4. Acquisition of Powered-Off Digital Devices

Procedure ID: PI-C5-S22

Purpose

To acquire digital evidence from a powered-off digital device while
maintaining the integrity of the original storage media.

How to Perform It

A. Overview of Powered-Off Digital Device Acquisition

   1. Understand that acquiring evidence from a powered-off digital device is
       easier to handle compared to a powered-on digital device.

   2. Recognize that there is no need to acquire volatile data from a powered-
       off device.

   3. Follow the applicable activities illustrated in ISO/IEC 27037:2012, Figure
       5, for powered-off digital device acquisition.

B. Acquisition Activities for Powered-Off Digital Devices

1. Confirm Device Power Status: Ensure that the digital device is indeed
powered off.

2. Remove and Identify Storage (If Appropriate):

      If appropriate, remove the storage from the powered-off digital device,
       if it has not already been removed.

      Label the storage as suspect storage.

      Document the following details:

          o    Make

          o    Model name

          o    Serial number

          o    Storage size

3. Perform the Imaging Process:

      Use a validated imaging tool to create a digital evidence copy of the
       suspect disk.

C. Important Considerations

   1. In most cases, do not remove storage media from the digital device until
       it is ready to be acquired.

   2. Recognize that removing storage media increases the risk of:

o     Damage to the storage media.

          o     Confusing it with another storage medium.

   3. Develop and follow local procedures regarding the need to remove hard
       disks.

Responsible Personnel

Not specified in the provided ISO reference.

Required Documentation

Document the storage details, including:

      Make

      Model name

      Serial number

      Storage size

Expected Output

      Confirmation that the digital device is powered off.

      Identified and labelled suspect storage, where appropriate.

      Documented storage details.

      A digital evidence copy of the suspect disk created through the imaging
       process.

Supporting References

      ISO/IEC 27037:2012, Clause 7.1.3.2.1 — Overview.

      ISO/IEC 27037:2012, Clause 7.1.3.2.2 — Acquisition of Powered-Off Digital
       Device.

      ISO/IEC 27037:2012, Figure 5 — Guidelines for Acquisition of Powered-
       Off Digital Device




5. Acquisition of Digital Storage Media

Procedure ID: PI-C5-S23

Purpose

To identify, document, collect or acquire digital storage media found at an
incident scene while maintaining the integrity and preservation of the
collected media.

How to Perform It

A. Identification and Documentation of Digital Storage Media

   1. Identify the different types of digital storage media found at the incident
      scene.

   2. Recognize that digital storage media are usually among the least volatile
      types of data and may have the lowest priority during collection and
      acquisition.

   3. Understand that external digital storage media may contain important
      evidence required by forensic analysts.

   4. Check and document the following details for each digital storage
      medium:

          o    Location, such as drive bay, cable and connector, or USB slot.

          o    Make.

          o    Model.

          o    Serial number, if available.

B. Decision to Collect or Conduct On-Site Acquisition

   1. Decide whether to collect the identified digital storage media or conduct
      on-site acquisition.

   2. Base this decision on:

          o    The nature of the incident.

          o    Available resources.

   3. If on-site acquisition of digital storage media, primarily a hard disk, is
      selected, refer to ISO/IEC 27037:2012, Figure 4.

C. Packaging and Labelling of Collected Media

   1. If the DEFR decides to collect the digital storage media and is permitted
       to do so, wrap or place the collected media in appropriate packaging.

   2. Label all collected digital storage media and their associated parts.

   3. Follow these precautions when placing evidence labels:

          o    Do not place evidence labels directly on the mechanical parts of
               digital media.

          o    Do not cover or conceal important information, including serial
               number, model number, and part number.

   4. Acquire and store all collected media in a manner that ensures their
       integrity.

   5. When possible:

          o    Seal the evidence using tamper-evident seals.

          o    The DEFR or personnel in charge should sign the evidence label.

D. Storage and Data Retention

   1. Store collected digital storage media in an environment suitable for data
       preservation.

   2. Recognize that different types of digital storage media have different
       data retention capabilities.

   3. Be aware of the acceptable maximum time period specified by the
       relevant jurisdiction, considering the data retention capabilities of the
       digital storage media.

Responsible Personnel

Digital Evidence First Responder (DEFR).

Required Documentation

Document the following information:

      Location of each digital storage medium.

      Make.

   Model.

      Serial number, if available.

      Associated parts and their details.

      Evidence labelling and sealing details, where applicable.

Expected Output

      Identified and documented digital storage media.

      Decision regarding collection or on-site acquisition.

      Properly packaged and labelled collected media.

      Tamper-evident sealing and signature, where possible.

      Collected media stored in an appropriate preservation environment.

Supporting References

      ISO/IEC 27037:2012, Clause 7.1.3.3 — Digital Storage Media.

      ISO/IEC 27037:2012, Figure 4 — Guidelines for Acquisition of Powered-
       On Digital Device.




MAIN ACTIVITY 4: SPECIALIZED ACQUISITION GUIDELINES

1. Networked Device Acquisition

1.1 Overview of Networked Device Acquisition

Procedure ID: PI-C5-S24

Purpose

To understand the acquisition requirements of network-connected devices,
including their physical and virtual network connections, and identify the
necessary steps before network disconnection.

How to Perform It

1. Identify Multiple Network Connections

   Recognize that a device may be connected to more than one physical
      and/or virtual network.

     A device with one visible physical network connection may also be
      running a VPN and virtual machines with multiple IP addresses.

2. Conduct Logical Acquisition Before Disconnection

     Before disconnecting the device from the network, the DEFR should
      conduct logical acquisition of data related to its logical network
      connections, such as Internet connectivity.

     Acquire related information, including:

         o   IP configuration.

         o   Routing tables.

3. Prevent Wireless Network Interaction

     If a networked device must remain continuously powered on, prevent it
      from interacting with wireless radio networks, including GPS-enabled
      devices.

     Use methods permitted by local law to isolate radio signals.

     Ensure that the device has an adequate power source because isolation
      methods may cause additional power consumption as the device
      attempts to contact a network.

4. Consider Wireless Isolation Methods

a. Jamming Device

     Use a jamming device to block transmission by creating strong
      interference in the same frequency range used by mobile devices.

     Consider that jamming devices may violate legal requirements in some
      jurisdictions.

     Consider their possible negative effects on electronic devices, such as
      medical equipment.

b. Shielded Work Area or Faraday Tent

   Use a shielded work area to conduct examinations safely at a fixed
       location.

      Shielding may cover the entire work area or use a portable Faraday tent.

      Ensure that cables entering the tent are properly isolated because they
       may behave as antennas and defeat the purpose of the shielding.

      Consider that the workspace may be restrictive.

c. RF-Shielded Workspace or Container

- Use a radio frequency (RF)-shielded workspace or container, such as a
Faraday cage, to prevent network connections.

5. Validate Wireless Isolation Methods

      Validate all methods used to block wireless network access for the
       appropriate frequencies.

      Include cables passing through shielding in the validation process.

6. Use a Substitute (U)SIM

      Use a substitute (U)SIM that mimics the identity of the original device's
       (U)SIM and prevents the device from accessing the network.

      Ensure that the substitute (U)SIM is validated for the specific device and
       network before use.

Responsible Personnel

Digital Evidence First Responder (DEFR).

Required Documentation

Not specifically detailed in the provided ISO reference.

Expected Output

      Logical network connection information acquired before disconnection.

      IP configuration and routing tables acquired.

      Appropriate wireless isolation method selected.

      Wireless isolation methods validated for relevant frequencies.

      Substitute (U)SIM validated before use, where applicable.

Supporting References

ISO/IEC 27037:2012, Clause 7.2.2.3 — Guidelines for Networked Device
Acquisition.




2. CCTV Acquisition

2.1 Pre-Acquisition Assessment

Procedure ID: PI-C5-S28

Purpose

To assess the CCTV system and identify the required video recordings, relevant
cameras, time frame, system details, and storage conditions before starting the
acquisition process.

How to Perform It

1. Understand the CCTV Acquisition Process

      Recognize that extracting video sequences from computer-based or
       embedded DVR CCTV systems is different from conventional digital
       evidence extraction from a computer.

2. Determine Whether the Required Video Exists

      Before starting acquisition, determine whether the CCTV system has
       documented the video sequence of interest.

3. Determine the Required Time Frame

      Identify the time frame of the video footage required for the
       investigation.

      Compare the CCTV system's time with the correct time.

      Note any difference or time offset between the system time and the
       correct time.

4. Identify the Required Cameras

      Determine which cameras are relevant to the investigation.

   Determine whether recordings from those cameras can be acquired
       separately.

5. Record CCTV System Details

      Note the make and model of the CCTV system.

      This information may be required to obtain the correct replay software.

6. Identify All Connected Cameras

      Note all cameras connected to the CCTV system.

      Determine which cameras are actively recording and which are not
       recording.

7. Assess CCTV Storage and Overwrite Schedule

      Determine the storage size of the CCTV system.

      Determine when the system is scheduled to overwrite existing video
       information.

      Establish how long the required video footage will remain available
       before it is lost.

8. Ensure Write Protection

      Take appropriate action to ensure that the evidence is not changed.

      Ensure that write protection is in place for digital video evidence.

Responsible Personnel

Digital Evidence First Responder (DEFR).

Required Documentation

      CCTV system make and model.

      Required video time frame.

      Difference or offset between system time and correct time.

      Required cameras and whether they can be acquired separately.

      All connected cameras and their recording status.

      CCTV storage size.

   Scheduled video overwrite information.

Expected Output

      Required video sequence and time frame identified.

      Relevant cameras identified.

      CCTV system make and model recorded.

      Recording status of connected cameras determined.

      Storage capacity and overwrite schedule assessed.

      Write protection requirements identified.

Supporting References

ISO/IEC 27037:2012, Clause 7.3 — CCTV Collection, Acquisition and
Preservation.




2.2 CCTV Video Acquisition Methods

Procedure ID: PI-C5-S29

Purpose

To acquire relevant video recordings from a CCTV system using an appropriate
acquisition method while maintaining the original video evidence.

How to Perform It

The DEFR may use the following methods to acquire potential digital evidence
from CCTV systems:

1. Acquire Video Files onto Optical Discs

      Acquire the required video files by writing them onto:

          o   CD

          o   DVD

          o   Blu-ray disc

   Consider that this method may not be practical when the video files are
       too large.

2. Acquire Video Files onto External Storage Media

- Acquire the required video files by writing them onto an external storage
medium.

3. Acquire Video Files Through a Network Connection

      Acquire the required video files through a network connection.

      This method may be available when the CCTV system is equipped with a
       network port.

4. Use the CCTV System's Export Feature

      Use the CCTV system's export feature to convert video recordings into
       other file formats, usually MPEG or AVI.

      Understand that exported video is a compressed version of the original
       footage.

      Use this method only as a last resort because recompression alters the
       original data and removes image detail.

      Do not rely on recompressed video for examination when the original
       data exists and is available for analysis.

      Consider that the quality of exported video may not be as good as the
       original footage.

5. Acquire an Analog Copy

      If it is not possible to directly acquire a digital evidence copy of the files
       from the recording device, the DEFR or Digital Evidence Specialist (DES)
       should attempt to acquire an analog copy.

      Use the analog output available on the original recording device.

      Use a suitable analog recording device to create the copy.

Responsible Personnel

      Digital Evidence First Responder (DEFR).