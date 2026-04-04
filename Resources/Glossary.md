# Game QA & Design Glossary

> *"QA is not a finishing step, but a foundation to grow from."*

This glossary defines the terminology and methodologies applicable to general Quality Assurance and Game Testing.

### 1. Technical Testing & Defects
* **Black Box Testing:** A method of software testing that examines the functionality of an application without peering into its internal structures or workings.
* **Bug:** An imperfection or deficiency in a work product where it does not meet its requirements or specifications or impairs its intended use.
* **Bug Lifecycle:** The process of recognizing, recording, classifying, investigating, fixing, and disposing of bugs.
* **Bug Reporting:** The structured process of logging issues with clear reproduction steps, environment details, and severity.
* **Edge Case:** A problem or situation that occurs only at an extreme operating parameter, requiring specific and often unusual conditions to reproduce.
* **Exploit:** A flaw in the game's system, mechanics, or code that players can use to gain an unfair advantage (e.g., duplicating items or bypassing geometry).
* **Memory Leak:** A technical defect where the game fails to release discarded memory, leading to progressive performance degradation and eventual crashes.
* **OS Fragmentation:** The challenge of testing a game across a vast array of hardware and operating systems, specifically across iOS, Android, macOS, and PC/UWP.
* **Regression Testing:** Re-testing functional areas after code changes to ensure that new updates haven't introduced new defects or broken existing features.
* **Root Cause Analysis (RCA):** The process of identifying the underlying technical reason for a bug—such as a specific SQL query failure—rather than just reporting the symptom.
* **Smoke Testing:** A preliminary, high-level test pass to ensure the core functionalities of a new build work before committing to deeper, more time-consuming testing.
* **White Box Testing:** A method of testing the application at the level of the source code.
* **Z-Fighting / Clipping:** Visual or physical artifacts where textures flicker (Z-fighting) or objects pass through boundaries (clipping), requiring methodical documentation of environmental conditions.

---

### 2. Tools, Documentation & Infrastructure
* **API Testing:** Validating the communication between the game client and the server using tools like Postman to ensure data integrity.
* **Automation & AI:** Leveraging scripting and AI tools (e.g., LLMs) to eliminate repetitive manual tasks and accelerate the development of test scripts.
* **Crash Dump / Log:** A file containing a snapshot of the game's execution state or system memory at the time of a crash, vital for programmers to debug hard-to-reproduce issues.
* **Defect Tracking:** The lifecycle management of a bug using industry-standard tools like Jira or Asana.
* **Emulator:** Software used during testing that mimics the actual hardware and architecture of a target device.
* **Knowledge Base (KB) Management:** The creation of centralized documentation to standardize workflows and provide solutions for recurring technical issues (e.g., via Confluence).
* **Simulator:** A component or system used during testing which behaves or operates like a given component or system, without necessarily mimicking the underlying hardware.
* **Telemetry / Analytics:** Data automatically collected from the game client during playtesting or live ops, used by QA to track performance metrics and player behavior.
* **Test Case:** A set of preconditions, inputs, actions (where applicable), expected results, and postconditions, developed based on test conditions.
* **Test Management:** Using platforms like TestRail or Qase to build, organize, and execute structured test suites.
* **Test Plan:** Documentation describing the test objectives to be achieved and the means and the schedule for achieving them, organized to coordinate testing activities.
* **Version Control:** Systems (like Git, Perforce, or SVN) used to track changes to the game's code and assets. Crucial for QA to identify exactly which build introduced a bug.

---

### 3. Game Design & Product Philosophy
* **Balancing:** The iterative process of tweaking game mechanics, character stats, and economy to ensure fair, challenging, and rewarding gameplay without trivializing content.
* **Core Loop:** The primary cycle of actions a player repeats. Understanding this is vital for identifying logic flaws or "feel" issues in mechanics.
* **Feature Influence:** The transition from identifying a bug to proposing a solution that improves the game's overall design and engagement.
* **Holistic Product View:** The ability to see beyond individual bugs to understand how mechanics influence player behavior and the overall user experience.
* **Quality of Life (QoL):** Features or improvements designed to make the game smoother and less frustrating for the player without fundamentally changing the core gameplay (e.g., an "auto-sort" inventory button).
* **User Interface (UI):** All components of a system that provide information and controls for the user to accomplish specific tasks with the system.
* **UX Friction:** Elements of the interface or gameplay that cause confusion or frustration, identified through manual testing and user experience analysis.
