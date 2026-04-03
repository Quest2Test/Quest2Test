# Game QA & Design Glossary

"QA is not a finishing step, but a foundation to grow from."

This glossary defines the terminology and methodologies I apply to my testing process.

1. Technical Testing & Defects
    - Bug: An imperfection or deficiency in a work product where it does not meet its requirements or specifications or impairs its intended use.
    - Bug Reporting: The structured process of logging issues with clear reproduction steps, environment details, and severity.
    - Bug Lifecycle: The process of recognising, recording, classifying, investigating, fixing and disposing of bugs.
    - Root Cause Analysis (RCA): The process of identifying the underlying technical reason for a bug—such as a specific SQL query failure—rather than just reporting the symptom.
    - Regression Testing: Re-testing functional areas after code changes to ensure that new updates haven't introduced new defects or broken existing features.
    - OS Fragmentation: The challenge of testing a game across a vast array of hardware and operating systems, specifically across iOS, Android, macOS, and UWP.
    - Z-Fighting / Clipping: Visual or physical artifacts where textures flicker or objects pass through boundaries, requiring methodical documentation of environmental conditions.

3. Tools & Infrastructure
    - Test Case: A set of preconditions, inputs, actions (where applicable), expected results and postconditions, developed based on test conditions.
    - Test Plan: Documentation describing the test objectives to be achieved and the means and the schedule for achieving them, organized to coordinate testing activities.
    - Test Management: Using platforms like TestRail or Qase to build, organize, and execute structured test suites.
    - Defect Tracking: The lifecycle management of a bug using industry-standard tools like Jira or Asana.
    - API Testing: Validating the communication between the game client and the server using tools like Postman to ensure data integrity.
    - Automation & AI: Leveraging scripting and AI tools (e.g., ChatGPT) to eliminate repetitive manual tasks and accelerate the development of test scripts.
    - Knowledge Base (KB) Management: The creation of centralized documentation to standardize workflows and provide solutions for recurring technical issues.

4. Game Design & Product Philosophy
    - Holistic Product View: The ability to see beyond individual bugs to understand how mechanics influence player behavior and the overall user experience.
    - User Interface: All components of a system that provide information and controls for the user to accomplish specific tasks with the system.
    - Core Loop: The primary cycle of actions a player repeats. Understanding this is vital for identifying logic flaws or "feel" issues in mechanics.
    - UX Friction: Elements of the interface or gameplay that cause confusion or frustration, identified through manual testing and user experience analysis.
    - Feature Influence: The transition from identifying a bug to proposing a solution that improves the game's overall design and engagement.
