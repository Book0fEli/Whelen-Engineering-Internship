Professional ITOps Journey & Technical Portfolio
Author: Elijah Cordova  
Role: PC Support Specialist / IT Operations  
Organization: Whelen Engineering — IT Operations (ITOps)  
Reporting Period: Summer / Fall 2026  
Security Classification: Public / Sanitized Portfolio (Security & Privacy Compliant)
---
1. Executive Summary & Operational Scope
During this operational tenure within the ITOps team at Whelen Engineering, Elijah Cordova delivered comprehensive IT support, hardware lifecycle management, manufacturing line uptime engineering, and enterprise systems administration across campus facilities.
Operating in a high-throughput hybrid manufacturing and enterprise environment, the core mission centered on minimizing production downtime, standardizing endpoint deployment workflows, securing device configurations, and streamlining user lifecycle management.
Key Performance & Impact Indicators
Total Work Items Managed: 94 assigned tickets across enterprise service desk queues.
Resolution Rate: ~93% first-and-second tier resolution efficiency.
Downtime Mitigation: Rapid triage and recovery for mission-critical manufacturing workstations (SMT, Aviation, Assembly lines).
Security & Hygiene Improvements: Remediation of physical credential risks and network transition of shop-floor hardware to segmented enterprise IoT infrastructure.
Process Standardization: Authored and refined procedural documentation for handheld barcode terminal provisioning, specialized engineering driver installations, and asset retirement.
---
2. Core Operational Pillars & Technical Domains
```
+-----------------------------------------------------------------------------------+
|                            ELIJAH CORDOVA - ITOPS DOMAINS                         |
+---------------------+---------------------+-------------------+-------------------+
| 🏭 Industrial IT &  | 🌐 Network & Fleet  | 🛡️ Identity &      | 💻 Endpoint Eng.  |
|    Shop Floor       |    Modernization    |    Access Control |    & Lifecycle    |
+---------------------+---------------------+-------------------+-------------------+
| • CK71/CK75 Fleets  | • IoT Segmentation  | • AD Provisioning | • Modern Imaging  |
| • Terminal Emulation| • Print Servers     | • Role-Based RBAC | • CAD/Lab Drivers |
| • Scan Stations     | • Levata/RMA Flow   | • Credential Audit| • Asset Disposal  |
| • Line-Down Triage  | • Wi-Fi Roaming     | • M365 / Visio    | • Dock/Multi-Disp |
+---------------------+---------------------+-------------------+-------------------+
```
2.1. Manufacturing & Industrial IoT Systems
Maintaining continuous operation on the factory floor is paramount. Elijah directly supported manufacturing assembly lines, quality test benches, and warehouse inventory workflows:
Barcode Terminal Lifecycle (Honeywell / Intermec CK71 & CK75):
Managed fleet configuration, custom OS/firmware deployment, and terminal emulation profiles.
Performed physical maintenance, trigger replacements, and vendor RMA tracking through Levata / Barcodes Inc.
Resolved connectivity drops and roaming failures across plant access points by tuning client radio configurations.
Shop Floor Scan Stations & Production Kiosks:
Audited, mapped, and deployed scan stations across Aviation, SMT, and Hotmelt departments.
Diagnosed terminal emulator disconnects, label printer misalignments, and COM-port serial scanner lockouts under active production constraints.
Critical Production Line Recovery:
Rapidly restored access to specialized manufacturing systems (e.g., SMT Line 1 Altium engineering stations, WIM terminals), preventing costly line stoppages.
2.2. Enterprise Network & Infrastructure Modernization
IoT Campus Migration (`Whelen Connect`):
Participated in transitioning legacy connected shop-floor devices and IoT endpoints onto dedicated, secure SSID segments (`Whelen Connect`), improving broadcast domain isolation and wireless security.
Print Infrastructure & Centralization:
Standardized enterprise network printer deployments utilizing centralized print server queues and universal print drivers.
Reduced user friction by documenting self-service printer mapping procedures and maintaining printer portal records.
2.3. Identity Governance, Access Management & Security Hygiene
User Lifecycle Administration (JML - Joiner/Mover/Leaver):
Executed end-to-end user provisioning in Active Directory / Azure AD, configuring organizational units, group memberships, and security policies.
Coordinated seamless offboarding procedures: immediate account deprovisioning, access revocation, license reclaim, and hardware chain-of-custody tracking.
Physical Credential Sanitization Initiative:
Led on-site inspections across workstation pods and common areas to identify and remediate exposed credentials, fostering stronger organizational security awareness.
Software Licensing & Governance:
Managed license allocation and entitlement validation for specialized productivity tools, including Microsoft Visio Plan 2, engineering CAD suites, and ERP enterprise modules.
2.4. Endpoint Engineering, Specialized Peripherals & Hardware Lifecycle
Workstation & Laptop Provisioning:
Configured and deployed standard enterprise workstations, Microsoft Surface laptops, and dual/curved monitor desktop configurations for remote, hybrid, and onsite staff.
Built repeatable setup checklists for docking stations, enterprise telephony (8x8), and unified communications hardware.
Engineering & Specialized Diagnostic Tooling:
Installed and configured specialized driver packages and hardware test equipment:
LabJack data acquisition interfaces
BK Precision programmable power supplies and test gear
Dialux Evo photometric simulation software
eDrawings CAD visualization viewers
IT Asset Management (ITAM) & Sustainable E-Waste Disposal:
Maintained inventory accuracy in Lansweeper and internal asset tracking databases.
Coordinated secure decommission, disk sanitization (NIST 800-88 compliant guidelines), and bulk disposal for retired training and enterprise laptop fleets.
---
3. Categorical Breakdown of Managed Ticket Work
The 94 assigned service requests and operational tickets span six primary operational categories:
Category	Workload Share	Focus Areas	Key Deliverables
Endpoint Hardware & Peripherals	32%	Laptops, docks, multi-monitor setups, audio/video peripherals	Zero-day deployment readiness, ergonomic desk installations, rapid hardware swap-outs
Manufacturing & Shop Floor Support	24%	CK71/CK75 handhelds, scan kiosks, serial scanners, production PC recovery	Factory floor uptime preservation, RMA processing, terminal config standard
Identity, Access & Account Admin	18%	Active Directory accounts, password resets, departmental permission updates	Fast JML turnaround, RBAC compliance, audit trail maintenance
Software, Drivers & Specialized Apps	14%	M365, Visio Plan 2, LabJack, BK Precision, Altium, Dialux Evo	Secure application delivery, license compliance, driver troubleshooting
Network, Wi-Fi & Printing	8%	Print queues, `Whelen Connect` migration, Wi-Fi connectivity	Network segmentation support, printer mapping simplification
Asset Lifecycle & Decommissioning	4%	ITAM auditing, inventory reconciliation, secure hardware disposal	Lansweeper hygiene, data destruction compliance, space reclamation
---
4. In-Depth Operational Case Studies (Sanitized)
Case Study A: Shop Floor Barcode Terminal Fleet Reliability
Challenge: High failure rates and network disconnection issues on legacy CK71/CK75 handheld units caused delays in manufacturing tracking and inventory scanning.
Investigation: Isolated root causes into two buckets: (1) physical hardware wear (scan engines, battery latch mechanisms), and (2) outdated wireless profiles failing to roam cleanly between campus APs.
Remediation:
Re-imaged units with standardized operating profiles and updated network security certificates.
Established a formal RMA workflow with hardware vendors (Levata / Barcodes Inc) for rapid turnaround of damaged units.
Documented a step-by-step flashing and provisioning guide for the ITOps knowledge base.
Outcome: Substantially reduced handheld trouble tickets and stabilized shop floor scanning operations.
Case Study B: Production-Critical SMT Engineering Station Recovery
Challenge: A high-priority workstation on SMT Line 1 experienced software corruption and licensing disconnects with Altium and manufacturing execution systems, halting line adjustments.
Action:
Responded immediately on-site; diagnosed corrupted application dependencies and network drive mapping disconnects.
Restored environment variables, verified secure service connectivity, and re-authenticated licensing services.
Validated full operational readiness alongside the manufacturing line lead prior to handoff.
Outcome: Restored production capabilities within minimal downtime, averting scheduled manufacturing delays.
Case Study C: Specialized Lab Hardware & Measurement Driver Deployments
Challenge: Engineering teams required complex multi-vendor diagnostic setups (LabJack measurement hardware, BK Precision supplies, photometric simulation tools) on fresh Windows 10/11 builds without compromising security policies.
Action:
Researched verified signed driver packages, isolated prerequisite runtime dependencies (.NET frameworks, C++ redistributables), and validated USB interface stability.
Packaged reusable configuration notes so fellow team specialists could replicate the setup seamlessly.
Outcome: Accelerated engineering onboarding and eliminated recurring driver installation tickets.
---
5. Technical Competencies & Tooling Matrix
Operating Systems & Infrastructure
Client Platforms: Windows 10 Enterprise, Windows 11, Apple iOS / iPadOS
Server & Directory Systems: Windows Server, Active Directory DS, Azure Active Directory / Entra ID
Remote Administration: Remote Desktop Protocol (RDP), Remote PowerShell, Quick Assist / TeamViewer
Enterprise Operations & ITAM
IT Service Management: Jira Service Management (JSM), Atlassian Confluence KB
Asset Discovery & Inventory: Lansweeper, SharePoint Lists, Vendor Portal Asset Trackers
Enterprise Collaboration: Microsoft 365, SharePoint Online, Visio, OneNote, 8x8 Cloud Telephony
Specialized Industrial & Hardware Tech
Mobile Enterprise Terminals: Intermec/Honeywell CK71, CK75, ScanPal, Zebra Enterprise Scanners
Industrial Interfaces: RS-232 / Serial-over-USB, Ethernet barcode scan stations, Zebra / Intermec industrial label printers
Engineering Utilities: Altium Viewer, Dialux Evo, eDrawings, LabJack DAQ tools, BK Precision Instrument Drivers
---
6. Comprehensive Assigned Ticket Log (Chronological & Sanitized)
The table below outlines the full registry of assigned tickets, detailing the functional scope, resolution state, and operational contribution:
#	Key / Identifier	Functional Focus Area	Category	Status	Operational Impact & Summary
1	`ITSUPPORT-74895`	Desktop Peripherals Setup	Hardware	Done	Configured dual-monitor workstation and docking hub.
2	`ITSUPPORT-74932`	Barcode Handheld Repair	Industrial IT	Done	Diagnosed CK71 trigger fault; initiated RMA tracking.
3	`ITSUPPORT-75010`	User Onboarding Provisioning	IAM	Done	Created AD account, mailbox, and provisioned base hardware.
4	`ITSUPPORT-75044`	Enterprise Print Queue Access	Network/Print	Done	Mapped network print queue and validated test output.
5	`ITSUPPORT-75102`	Specialized Driver Deployment	Software	Done	Installed LabJack DAQ drivers and validated communication.
6	`ITSUPPORT-75128`	Credential Security Walkthrough	Security	Done	Remediated exposed physical credentials in workstation pod.
7	`ITSUPPORT-75155`	Production Line Scan Station	Industrial IT	Done	Resolved COM port lock on SMT scan kiosk scanner.
8	`ITSUPPORT-75189`	Visio Plan 2 License Assignment	Software	Done	Validated business justification and provisioned license.
9	`ITSUPPORT-75210`	Laptop Replacement & Migration	Hardware	Done	Migrated user data and profile to replacement laptop.
10	`ITSUPPORT-75245`	Handheld Wi-Fi Profile Update	Network/Mobile	Done	Updated wireless roaming profile across 5 plant CK75 units.
11	`ITSUPPORT-75280`	Offboarding Hardware Recovery	IAM/ITAM	Done	Decommissioned user accounts and logged returned assets.
12	`ITSUPPORT-75304`	Dialux Evo Simulation Install	Software	Done	Deployed lighting simulation suite on engineering PC.
13	`ITSUPPORT-75339`	SMT Altium Access Restoration	Manufacturing	Done	Restored network path and licensing for line workstation.
14	`ITSUPPORT-75368`	Audio/Video Conferencing Triage	Hardware	Done	Replaced faulty USB conference room microphone/speaker.
15	`ITSUPPORT-75402`	Lansweeper Asset Audit	ITAM	Done	Reconciled serial records for Aviation department devices.
16	`ITSUPPORT-75431`	`Whelen Connect` IoT Transition	Network	Done	Migrated plant floor monitoring tablets to IoT network.
17	`ITSUPPORT-75467`	BK Precision Test Suite Setup	Software	Done	Configured programmable DC power supply communication.
18	`ITSUPPORT-75501`	Docking Station Firmware Update	Hardware	Done	Resolved display flickering via dock firmware patch.
19	`ITSUPPORT-75533`	Active Directory Group Access	IAM	Done	Updated departmental security group distribution lists.
20	`ITSUPPORT-75560`	Industrial Label Printer Calibration	Manufacturing	Done	Calibrated gap sensor and replaced thermal printhead.
21	`ITSUPPORT-75592`	Surface Pro Hardware Inspection	Hardware	Done	Diagnosed battery health degradation; initiated swap.
22	`ITSUPPORT-75624`	8x8 Telephony Headset Config	Telecom	Done	Configured softphone client and Bluetooth audio mapping.
23	`ITSUPPORT-75655`	Handheld Terminal Firmware Flash	Industrial IT	Done	Reflashed corrupted OS image on CK71 terminal.
24	`ITSUPPORT-75688`	E-Waste Secure Decommission	ITAM	Done	Sanitized legacy mechanical drives and logged disposition.
25	`ITSUPPORT-75712`	Production Scan Station Relocation	Manufacturing	Done	Extended cabling and remounted scan station for Hotmelt line.
26	`ITSUPPORT-75745`	ERP Client Configuration	Software	Done	Reconfigured local client configuration file for WIM access.
27	`ITSUPPORT-75778`	Curved Display Ergonomic Mount	Hardware	Done	Installed monitor arm and configured ultrawide resolution.
28	`ITSUPPORT-75810`	Password Reset & MFA Enrollment	IAM	Done	Assisted user with authenticator app re-registration.
29	`ITSUPPORT-75841`	Network Drop Connectivity Test	Network	Done	Tested and patched patch-panel port for newly added desk.
30	`ITSUPPORT-75870`	eDrawings CAD Viewer Install	Software	Done	Deployed lightweight viewer for assembly floor technician.
31	`ITSUPPORT-75902`	Barcode Scanner Gun Replacement	Industrial IT	Done	Replaced damaged tethered 2D scanner on packing line.
32	`ITSUPPORT-75933`	Remote Worker VPN Support	Network	Done	Resolved client gateway connectivity and profile binding.
33	`ITSUPPORT-75965`	Shared Mailbox Delegation	IAM	Done	Granted read/send-as permissions per manager approval.
34	`ITSUPPORT-75998`	Quality Lab PC Image Deployment	Endpoint	Done	Imaged standard Windows 10 workstation for QA station.
35	`ITSUPPORT-76025`	Printer Jam & Maintenance Routine	Hardware	Done	Cleared internal transport roller jam and replaced pickup pads.
36	`ITSUPPORT-76057`	New Hire Welcome Orientation	IAM/Support	Done	Conducted IT walkthrough and equipment signoff with employee.
37	`ITSUPPORT-76089`	Handheld Fleet Battery Refresh	Industrial IT	Done	Distributed conditioned battery packs to warehouse shift lead.
38	`ITSUPPORT-76120`	Security Patch Compatibility Check	Security	Done	Validated lab instrumentation software after OS cumulative update.
39	`ITSUPPORT-76151`	SharePoint List Mapping Support	Software	Done	Assisted department coordinator with list integration.
40	`ITSUPPORT-76182`	Dual Display Adapter Replacement	Hardware	Done	Swapped defective DisplayPort-to-HDMI active adapter.
41	`ITSUPPORT-76214`	Hotmelt Department Scan Audit	Manufacturing	Done	Verified handheld scanner connectivity across all Hotmelt bays.
42	`ITSUPPORT-76246`	Mobile Device Email Sync Setup	Telecom/Mobile	Done	Enrolled company-managed device into enterprise MDM.
43	`ITSUPPORT-76277`	Training Room Laptop Lab Setup	Hardware	Done	Configured 12 staging laptops for annual training module.
44	`ITSUPPORT-76308`	Local Admin Privilege Review	Security	Done	Audited and removed unauthorized local elevation rights.
45	`ITSUPPORT-76340`	SMT Scan Station Terminal Lock	Manufacturing	Done	Cleared locked background terminal session on Line 2.
46	`ITSUPPORT-76371`	Wireless Mouse/Keyboard Interference	Hardware	Done	Resolved 2.4GHz RF interference with USB extender placement.
47	`ITSUPPORT-76403`	Offboarding Hardware Check-in	IAM/ITAM	Done	Inspected, cleaned, and inventoried returned IT equipment.
48	`ITSUPPORT-76435`	Engineering Large-Format Plotter	Hardware/Print	Done	Replaced yellow ink cartridge and performed head alignment.
49	`ITSUPPORT-76466`	User Folder Redirection Triage	IAM/Storage	Done	Rebuilt local offline files cache to resolve sync conflict.
50	`ITSUPPORT-76498`	CK75 Scanner Beam Realignment	Industrial IT	Done	Cleaned optical window and adjusted decode aimer settings.
51	`ITSUPPORT-76530`	M365 Desktop Apps Re-activation	Software	Done	Cleared credential manager tokens to restore Office license.
52	`ITSUPPORT-76561`	Shipping Department Scale Interface	Industrial IT	Done	Re-established RS-232 serial connection to scale PC.
53	`ITSUPPORT-76593`	Temporary Contractor Access Setup	IAM	Done	Created time-bound domain account and assigned basic access.
54	`ITSUPPORT-76624`	Monitor Power Supply Replacement	Hardware	Done	Replaced faulty external AC power brick for display.
55	`ITSUPPORT-76656`	Warehouse Handheld Check-out System	Industrial IT	Done	Updated tracking sheet for handheld borrowing custody.
56	`ITSUPPORT-76687`	USB Web Camera Audio Troubleshooting	Hardware	Done	Reassigned default audio endpoint in unified comms client.
57	`ITSUPPORT-76719`	Network Share Permission Request	IAM	Done	Added explicit group read permissions on department archive.
58	`ITSUPPORT-76750`	Plant Wi-Fi Dead-zone Verification	Network	Done	Conducted signal sweep; coordinated with net team for AP survey.
59	`ITSUPPORT-76782`	SolidWorks Viewer Performance Tune	Software	Done	Enabled dedicated GPU rendering for CAD viewer client.
60	`ITSUPPORT-76814`	iPad OneNote Production Log Setup	Mobile/Software	Done	Deployed kiosk profile on iPad for digital shop floor signoffs.
61	`ITSUPPORT-76845`	Handheld RMA Return Tracking	Industrial IT	Done	Received repaired CK71 units from vendor; validated staging.
62	`ITSUPPORT-76877`	Standing Desk Cable Management	Hardware	Done	Rerouted power and display cables to prevent tension snagging.
63	`ITSUPPORT-76908`	Account Lockout Root Cause Analysis	IAM/Security	Done	Identified stale cached credentials on mobile device as culprit.
64	`ITSUPPORT-76940`	Desktop Memory (RAM) Upgrade	Hardware	Done	Upgraded workstation to 32GB RAM for multitasking stability.
65	`ITSUPPORT-76971`	Aviation Line Scan Kiosk Inspection	Manufacturing	Done	Verified barcode reader decode latency on assembly station.
66	`ITSUPPORT-77003`	Default Application Protocol Fix	Software	Done	Reset default PDF application handlers across deployment group.
67	`ITSUPPORT-77034`	Headset Mic Noise Suppression Triage	Hardware	Done	Configured audio driver noise cancellation for open office area.
68	`ITSUPPORT-77066`	Old Workstation Drive Erasure	Security/ITAM	Done	Executed multi-pass data wipe on batch of retired HDDs.
69	`ITSUPPORT-77097`	Visio Viewer Web Integration	Software	Done	Assisted user with browser-based diagram viewing workflow.
70	`ITSUPPORT-77129`	Network Switch Port Patching	Network	Done	Patched network drop for new testing bench in engineering.
71	`ITSUPPORT-77152`	Service Queue Review & Refinement	Operations	In Progress	Active ticket queue audit and procedural documentation update.
72	`ITSUPPORT-77180`	Handheld Scan Station Inventory	Industrial IT	Done	Completed physical audit of CTRF handheld units in plant.
73	`ITSUPPORT-77211`	Laptop Thermal Throttling Triage	Hardware	Done	Cleaned cooling vents and verified fan operation under load.
74	`ITSUPPORT-77243`	Onboarding Equipment Prep Batch	Endpoint	Done	Staged and configured 3 full workstation bundles for incoming hires.
75	`ITSUPPORT-77274`	Barcode Wedge Configuration Profile	Industrial IT	Done	Created custom prefix/suffix barcode scanning profile.
76	`ITSUPPORT-77306`	External Monitor Resolution Fix	Hardware	Done	Configured native 2560x1440 timing profile on high-res panel.
77	`ITSUPPORT-77337`	User Profile Corrupt Registry Repair	OS/Support	Done	Rebuilt user registry hive without requiring full system reimage.
78	`ITSUPPORT-77369`	Network Printer Driver Rollback	Network/Print	Done	Rolled back printer driver update that caused spooler crashes.
79	`ITSUPPORT-77400`	Security Awareness Guidance	Security	Done	Assisted user with identifying and reporting suspicious phishing email.
80	`ITSUPPORT-77432`	SMT Solder Station Kiosk Peripheral	Manufacturing	Done	Replaced liquid-damaged mechanical keyboard with sealed unit.
81	`ITSUPPORT-77463`	Bluetooth Mouse Pairing Drop Fix	Hardware	Done	Updated Bluetooth controller firmware to stabilize connection.
82	`ITSUPPORT-77495`	Asset Tagging & Database Update	ITAM	Done	Tagged 15 incoming curved displays and logged serial numbers.
83	`ITSUPPORT-77526`	Handheld Bootloop Diagnostics	Industrial IT	Done	Performed cold hardware boot and clean registry reload on CK75.
84	`ITSUPPORT-77558`	Virtual Meeting Room Camera Reset	Hardware	Done	Power-cycled and updated PTZ tracking camera in main conference room.
85	`ITSUPPORT-77589`	Windows Update Staged Deployment	OS/Security	Done	Monitored and verified monthly quality updates across pilot group.
86	`ITSUPPORT-77621`	Remote Desktop Gateway Connection	Network	Done	Reconfigured RDP gateway server endpoint address in client profile.
87	`ITSUPPORT-77652`	Warehouse Label Roll Alignment	Manufacturing	Done	Adjusted feed guide plates on high-speed industrial label printer.
88	`ITSUPPORT-77684`	Department Offboarding Reconciliation	IAM	Done	Finalized checklist confirmation for departing staff member.
89	`ITSUPPORT-77715`	Multi-Monitor Stand Installation	Hardware	Done	Assembled heavy-duty dual-arm desk clamp for engineering workstation.
90	`ITSUPPORT-77747`	Handheld Scan Engine Test Matrix	Industrial IT	Done	Validated 1D/2D symbology decoding across varying light conditions.
91	`ITSUPPORT-77778`	BitLocker Recovery Key Retrieval	Security	Done	Retrieved recovery key from AD and verified secure boot compliance.
92	`ITSUPPORT-77810`	Engineering Test Bench Power Hookup	Facilities/IT	Done	Assisted facilities with clean UPS power distribution for test rack.
93	`ITSUPPORT-77841`	Document Scanner Optical Glass Clean	Hardware	Done	Cleaned internal sensor glass to eliminate scan line artifacts.
94	`ITSUPPORT-77873`	ITOps Knowledge Base Documentation	Documentation	Done	Published standardized procedure for handheld repair RMA tracking.
---
7. Collaborative Ecosystem & Cross-Functional Alignment
Elijah actively collaborated with fellow IT Operations specialists and cross-departmental stakeholders to ensure smooth daily operations:
IT Operations Peers: Will Collins, David Anderson, Joshua Shook, Billy Whipple, Trey Neubert, John Keefe
Leadership & Supervision: Scott Fitzgerald
Manufacturing & Engineering Stakeholders: Production Line Supervisors (SMT, Aviation, Assembly, Hotmelt), Quality Engineers, Facilities Personnel, Warehouse & Inventory Logistics Leads
---
8. Conclusion & Continuous Improvement
Through consistent execution across both enterprise IT and industrial plant environments, Elijah Cordova has demonstrated technical agility, rigorous adherence to operational security, and a relentless focus on customer satisfaction and production uptime.
Document generated and certified for technical portfolio review.
