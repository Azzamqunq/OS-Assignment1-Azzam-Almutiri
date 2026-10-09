# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [azzam mishal hamid almutiri] |
| **Student ID** | [446050922] |
| **University Email** | [446050922@std.psau.edu.sa |
| **GitHub Username** | [Azzamqunq] |
| **Repository Link** | [https://github.com/Azzamqunq/OS-Assignment1-Azzam-Almutiri.git] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 7, 2026, 5 AM]
**What I did**:Set up my GitHub repository and prepared the starter code.

**Details**:
- Read the README.md file to understand the assignment requirements.
- Create Github Account using university email
- Forked the the starter repository on GitHub.
- Updated my student ID in SchedulerSimulation.java.
- Cleaned up the starter code.
- Removed merge conflict markers
- run the program successfully

**Challenges**:I needed to understand the repository setup and check the starter code before implementing the new features.


**Solution**:I followed the assignment instructions and reviewed the project files before continuing.

**Time spent**:3 hours

---

### Entry 2 - [October 7, 2026, 4 PM]
**What I did**:I implemented Feature 1 by adding a priority field to the Process class.

**Details**:
- Added a new int priority attribute inside the Process class to support priority-based scheduling.
- Updated the constructor so each process receives a priority value when created.
- Modified the output formatting to display the priority next to each process, making the simulation clearer.
- Re-ran the program to verify that the priority values were stored correctly and printed in the output.
- Committed the changes to GitHub with the message: “Feature 1: Added priority field to Process class”.

**Challenges**:
- At first, I wasn’t sure where the priority should be initialized because the constructor already had several parameters.
- I had to make sure adding the new field didn’t break the existing simulation flow.
- Understanding how priority might affect future scheduling logic required careful reading of the code.

**Solution**:
- Reviewed the constructor and traced how each parameter was used to ensure adding priority wouldn’t cause errors.
- Added print statements to confirm the priority was being passed correctly.
- Re-ran the simulation multiple times to ensure the output was consistent.

**Time spent**:3 hours

---

### Entry 3 - [October 8, 2026, 6 AM]
**What I did**:I implemented Feature 2 by adding a context switch counter to the scheduler.

**Details**:
- Added a static int contextSwitches variable inside SchedulerSimulation to track how many times the CPU switches between processes.
- Incremented the counter right before starting a new thread, which reflects a real context switch.
- Printed the total number of context switches at the end of the simulation for better visibility.
- Tested the program with different burst times to see how the counter changed depending on process behavior.
- Committed the update with the message: “Feature 2: Implemented context switch counter”.

**Challenges**:
- I had to determine the correct place to increment the counter so it accurately reflects a context switch.
- Some parts of the code start threads indirectly, so I needed to trace the flow carefully.
- Ensuring the counter didn’t increment during non-scheduling operations required attention.

**Solution**:
- Followed the scheduler loop step-by-step to identify the exact moment a new process begins running.
- Used temporary print statements to confirm the counter increased only when expected.
- Re-ran the simulation several times to validate the final count.

**Time spent**:3 and half hours 

---

### Entry 4 - [October 9, 2026, 7 AM]
**What I did**:I implemented Feature 3 by adding waiting time tracking and generating a summary table.

**Details**:
• Added a waitingTime variable to each process to track how long it stays in the ready queue.
• Updated the scheduler logic so the waiting time increases whenever a process is not running during a cycle.
• Created a summary table printed at the end of the simulation showing each process’s burst time, arrival time, and total waiting time.
• Tested the feature using processes with different burst times to ensure the waiting time calculation was accurate.
• Committed the feature with the message: “Feature 3: Added waiting time tracking and summary”.

**Challenges**:
- Understanding exactly when waiting time should increase required careful reading of the scheduling loop.
- I had to avoid double-counting waiting time when processes were re-queued.
- Formatting the summary table so it looked clean and readable took some trial and error.

**Solution**:
- Added print statements inside the ready queue loop to verify when each process was waiting.
- Compared the waiting time values with the expected behavior based on the time quantum.
- Adjusted the summary formatting until the output was clear and aligned.

**Time spent**: 4 hours

---

### Entry 5 - [October 10, 2026, 12 AM]
**What I did**: reviewed all the implemented features and started writing the documentation in MY_WORK.md.

**Details**:
- Re-ran the full simulation to verify that all three features (priority, context switches, and waiting time tracking) were working correctly and producing consistent output.
- Checked the commit history to make sure each feature had its own commit and that the dates matched the development log.
- Cleaned up a few comments in the code to make the logic clearer for the video explanation.
- Started filling out the reflection and technical answers sections, using real examples from my output to make the answers accurate.
- Tested the program again after writing the documentation to ensure nothing broke during the final edits.

**Challenges**:
- Making sure the development log entries matched the actual commit dates required going back and checking the GitHub history.
- Writing the reflection in my own words took time because I wanted it to be clear and connected to what I actually did.
- Ensuring the waiting time summary table looked clean in the output required a small formatting adjustment.

**Solution**:
- Compared the timestamps in GitHub with the dates in my log to keep everything consistent.
- Re-read the README instructions to make sure my documentation followed the required structure.
- Ran the simulation multiple times to confirm the final output before recording the video.

**Time spent**: 3 hours

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [4 days]

**Most challenging part**:
The hardest part was adding the waiting-time tracking feature because it needed careful following of the scheduler loop. I had to make sure the waiting time only went up when a process was waiting in line, not when it was running. It also took time to prevent counting the time twice and to check the values by testing many times.

**Most interesting learning**:
the most interesting part was seeing how multithreading works in practice, especially how threads switch between states during Round-Robin scheduling. Watching the output change depending on burst time and time quantum helped me understand how real operating systems manage CPU time. I also enjoyed building the summary table because it made the results easier to interpret.

**What I would do differently next time**:


---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[During this assignment, I learned how threads allow different parts of a program to run independently without blocking each other. I understood how Thread.start() begins the execution of a process and how Thread.join() forces the main thread to wait until the process finishes. Using Thread.sleep() helped me see how the program simulates real CPU work by pausing the thread for a short time. I also noticed how fast threads switch between states, especially when the scheduler moves from one process to another. Watching the output made it easier to understand how Round-Robin scheduling works with threads. Overall, I learned how threads make programs more responsive and how they help simulate real operating-system behavior.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part for me was implementing the waiting time feature because it required tracking exactly when each process was waiting in the ready queue. I had to follow the scheduler loop carefully to understand when a process was running and when it was not. It was also difficult to avoid counting waiting time twice when a process was re-queued multiple times. Another challenge was making sure the summary table showed correct values that matched the actual behavior of the simulation. This part took a lot of testing and re-running the program to confirm the logic was correct.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[To overcome these challenges, I added several print statements inside the scheduler loop to see when each process entered or left the ready queue. I re-read the README and the code multiple times to make sure I understood the expected behavior. I also tested the program with different burst times to see how the waiting time changed in each case. Whenever something looked wrong, I adjusted the logic and ran the simulation again until the output made sense. This step-by-step debugging helped me understand the scheduler more clearly and fix the mistakes.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is used in many real-world applications, like web browsers where each tab runs independently without freezing the whole program. It also appears in mobile apps, where background tasks such as downloading files run while the user continues using the app. Operating systems rely heavily on threads to manage multiple running programs and share CPU time fairly. The concepts I learned in this assignment, like context switching and time slicing, are similar to how modern systems keep applications responsive. Understanding these ideas helps me see how performance and user experience depend on efficient thread management.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process** Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*
A process is a program that has its own memory space, while a thread is a smaller unit of execution that shares memory with other threads inside the same process Threads are faster to create and communicate with each other because they use the same memory In this assignment the Process class is only a simulation, and each one is actually executed by a real Java thread This is shown in addProcessToQueue() where the code creates a thread using new Thread(process)  Using threads instead of real processes makes the simulation simpler and avoids the heavy cost of creating multiple operating-system processes. 



## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

in Round-Robin scheduling, when a process does not finish within its time quantum, it gets placed back into the ready queue so other processes can run. In my output, process P10 had a long burst time, so it was re‑queued two times before it finally finished. Each time the quantum ended, the scheduler printed that P3 did not finish and added it back to the ready queue. This re‑queueing makes the scheduling fair because it prevents P10 from taking the CPU for too long and allows other processes to get their turn. It also keeps the system responsive since no single process can block the rest

Example from my output:

P10 executing quantum [5000ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P10 completed quantum 5000ms │ Overall progress: [██████████████████░░] 91%
     Remaining time: 889ms
  ↻ P10 yields CPU for context switch

  ➕ P10 (Priority: 2) added to ready queue │ Burst time: 10889ms
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P3 → P9 → P10] 

[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [When is P1 in the New state?]

P1 is in the New state right after it is created inside addProcessToQueue() using new Thread(process). At this moment, the thread object exists but has not started running yet.

2. **Runnable**: [When does P1 become Runnable?]

P1 becomes Runnable when the scheduler selects it and calls thread.start(). This makes the thread ready to run whenever the CPU gives it time.

3. **Running**: [When is P1 Running?]

P1 enters the Running state when its run() method begins executing. This is where the process starts consuming its burst time and prints its quantum progress.

4. **Waiting**: [When and why would a thread be Waiting?]

P1 enters the Waiting state when Thread.sleep() is called inside the run() method. The sleep simulates CPU work by pausing the thread for the duration of the quantum.

5. **Terminated**: [When is P1 Terminated?]

P1 reaches the Terminated state after finishing its burst time and completing the run() method. The main thread confirms this by calling thread.join() to wait until P1 fully finishes.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*


### Example 1 ((Operating System Scheduler): [Name of scenario]

**Description**:
[Operating systems use Round-Robin scheduling to share CPU time among multiple running programs. Each program acts like a process, and the OS gives each one a small time slice before switching to the next.]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]

It ensures fairness because every program gets equal CPU time. It also keeps the system responsive since no single program can freeze the entire machine. The time quantum and context switching work exactly like the simulation in my assignment.

### Example 2: [Game Engine Tasks/scenario]

**Description**:
[Game engines run several tasks at the same time, such as physics updates, AI logic, and rendering frames. Each task needs regular CPU time to keep the game smooth.]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]

It prevents any single task from dominating the CPU and slowing the game. The time quantum acts like a frame update, and switching between tasks keeps gameplay responsive. This is similar to how my scheduler moved between processes in the simulation.
## Summary

**Key concepts I understood through these questions:**
1.How Round-Robin scheduling re-queues processes for fairness
2.How threads move through their lifecycle states
3.How context switching affects responsiveness

**Concepts I need to study more:**
1.Synchronization between threads
2.More advanced scheduling algorithms

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
