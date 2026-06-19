# 🗺️ Student Onboarding Guide & Repository Workflows
## PHL 3100 / MAC 5100 – Impacts of Computing (Summer 2026)

Welcome to the local decentralized environment for **Impacts of Computing**. In this course, we reject heavy commercial learning dashboards and corporate telemetry tracking. Instead, you will manage your entire coursework timeline directly from your machine using Git version control and plain-text Markdown. 

You may complete your weekly pipelines using either the command line **Terminal** or the **GitHub Desktop GUI application**. Choose the protocol below that best matches your technical comfort layer.

---

## 🎭 Step 1: Initialize Your Protocol Profile

To prevent corporate automated scraping and protect your data privacy, all public repository submissions are published under a secure pseudonymous alternative handle.

1. **Terminal Profile Configuration:**
   Open your operating system's native terminal emulator and configure your alternative handle variables:
   ```bash
   git config user.name "YourSovereignHandle"
   git config user.email "yourhandle@sovereign-classroom.university.edu"

1. **GitHub Desktop Configuration:**
   - Open the GitHub Desktop application.
   - Navigate to **File** > **Options** (Windows) or **GitHub Desktop** > **Settings** (Mac).
   - Click on the **Git** tab.
   - In the Name field, enter your assigned `YourSovereignHandle`.
   - In the Email field, enter `yourhandle@sovereign-classroom.university.edu`.
   - Click **Save**.

## 🔄 Step 2: The Weekly Delivery Pipeline

Every week, you choose either **Track A (Developer Track)** or **Track B (Analyst Track)** as defined in the master curriculum modules. Once you have saved your file changes (`.md` reports or `.py` scripts) inside your local directory structure, execute one of the two submission tracks below:

### 💻 Option A: The Terminal Protocol (Command Line Interface)

Execute this exact three-step transaction sequence inside your shell terminal environment:

Code snippet

```
graph TD
    A[Local Workstation File Changes] -->|Step 1: Snapshot Changes| B(git add . )
    B -->|Step 2: Sign Cryptographic Commit| C(git commit -m 'message')
    C -->|Step 3: Synchronize Main Branch| D(git push origin main)
```

1. **Snapshot Your Changes:** Stage your modified tracking logs or lab Markdown notes:

   Bash

   ```
   git add .
   ```

2. **Commit Your Progress:** Bundle your staged files into a permanent history snapshot:

   Bash

   ```
   git commit -m "commit-handle: completed module lab submission"
   ```

3. **Synchronize Your Remote Node:** Transmit your snapshots up to your hosted repository tree:

   Bash

   ```
   git push origin main
   ```

### 🖥️ Option B: The GitHub Desktop Protocol (Graphical User Interface)

If you prefer a visual, mouse-driven system, follow these steps inside the graphical app workspace:

1. **Review Changed Files:** Look at the left-hand sidebar under the **Changes** tab. You will see a list of files you modified or newly created. Ensure the checkboxes next to your lab files are checked.
2. **Author Your Commit:** At the bottom of that left sidebar, locate the **Summary** text field. Type a clear, anonymized descriptor (e.g., `completed module lab submission`).
3. **Commit to Main:** Click the blue button directly underneath labeled **Commit to main**. This records a permanent version snapshot on your hard drive storage metal.
4. **Push Upstream to Sovereign Server:** Locate the top navigation bar menu or the large center button workspace area labeled **Push origin** (or **Fetch/Publish branch**). Click it to securely transfer your local snapshots onto our class server network.

## 🔍 Step 3: Issue Boards and Peer Code Review

- **Tracking Progress:** All course announcements, scheduling notices, and project specifications are managed asynchronously through the repository **Issue Board**.
- **Peer Feedback:** When your weekly lab code or analytical report is pushed, you are expected to review at least one classmate's patch file. Submit your critiques using charitable, constructive dialogue directly inside the open issue thread matching their sovereign handle.