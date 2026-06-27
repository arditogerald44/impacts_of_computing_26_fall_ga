# 🗺️ Student Onboarding Guide & Repository Workflows
## PHL 3100 / MAC 5100 – Impacts of Computing (Fall 2026)

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

## 🧪 Step 2.5: How to Physically Run the Interactive Labs
Our custom lab simulations (`labs/02-nudge-simulation.html`, etc.) are ultra-lightweight and run entirely on your personal device's hardware metal. You do not run them inside GitHub's website.

1. Locate your cloned course folder on your computer using **Finder** (Mac) or **File Explorer** (Windows).
2. Open the `labs/` directory and **double-click** the respective HTML file for the week.
3. The simulation will instantly execute offline inside your local web browser.
4. Interact with the system toggles. When complete, scroll to the bottom UI terminal box, highlight and **copy the raw generated text logs**.
5. Open your local text editor, open your module `LAB-SUBMISSION.md` file, and paste those empirical logs directly into your report before running your commit pipeline.

## 🔍 Step 3: Issue Boards and Peer Code Review

- **Tracking Progress:** All course announcements, scheduling notices, and project specifications are managed asynchronously through the repository **Issue Board**.

- **Peer Feedback:** When your weekly lab code or analytical report is pushed, you are expected to review at least one classmate's patch file. Submit your critiques using charitable, constructive dialogue directly inside the open issue thread matching their sovereign handle.

  

## 🔄 Keeping Your Course Files Up to Date (Syncing the Upstream)

As the 14-week semester progresses, the instructor will push new modules, analytical reading materials, and interactive laboratory files to the main master repository. Because your workspace is a personal, isolated fork, these new files do not sync automatically. 

You must pull these updates from the **Upstream** (the instructor's master repository) into your **Local Copy** (your machine), and then sync them to your **Origin** (your personal online fork account).

<Image src="image_agent_tag_7160144637982568763" alt="Diagram showing Git workflow: Pulling changes from Upstream original repo to Local clone, and pushing from Local clone to Origin Remote Forked repo." caption="The Fork, Sync, and Pull Request Architecture" />

Choose the operational track that matches your workspace setup below when a content update is announced:

### Track A: GitHub Desktop / Forgejo Visual GUI
1. Open **GitHub Desktop** and ensure your course repository is active.
2. Click the **Fetch origin** button at the top header panel.
3. If new materials are live, the app will display a notice stating your fork is behind the upstream master.
4. Click the **Sync Fork** or **Update from upstream** button. The GUI will cleanly download the new files to your local hard drive and automatically push them to your online account.

### Track B: The Command-Line Terminal
If you are running a minimal computing terminal configuration, use the following protocol:

**Step 1: Link the Upstream Source (One-time setup during Week 1)**
Tell your local workstation where the instructor's master repository is located:
```bash
git remote add upstream [https://github.com/YourInstructorHandle/impacts-of-computing.git](https://github.com/YourInstructorHandle/impacts-of-computing.git)


```

---
## 📝 License
This course curriculum and its interactive laboratories are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
