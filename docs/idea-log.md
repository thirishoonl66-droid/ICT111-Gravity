
# Initial IT Venture Idea Log

## Idea 1: Web3 Airdrop and Quest Tracker

### Problem Area
Crypto users who farm airdrops follow dozens of protocols at the same time. Each protocol has its own tasks, eligibility rules, snapshot dates, and quest checklists, and this information is scattered across Twitter/X threads, Discord announcements, and project documentation. It is easy to miss a deadline, forget a required task, or lose track of which wallet did what. There is no single place to see the status of every airdrop campaign a person is working on.

### Target Users
Retail crypto users, airdrop hunters, and active DeFi participants, including students who are exploring Web3 as a side activity.

### Current Alternative
Users currently rely on manual spreadsheets, saved Twitter/X bookmarks, scattered Discord notifications, and memory. These methods are messy, easy to forget, and do not show overall progress or upcoming deadlines clearly.

### Proposed IT Solution
A web-based dashboard where a user adds the protocols they are farming, tracks the required tasks for each one as a checklist, records snapshot/deadline dates, and keeps short eligibility notes per wallet. The dashboard shows overall status at a glance and highlights tasks that are due soon.

### Possible Technology
HTML/CSS/JavaScript front end, a simple database or Google Sheet backend for storing campaigns and tasks, a checklist and status component, and optional read-only wallet lookups using public block-explorer APIs later in the semester.

### Why This Is Suitable
The core of this idea is a clickable, data-driven web dashboard that can be prototyped within 14 labs using web development, simple data storage, and UI/UX design. The team has direct domain experience in on-chain crypto mechanics, which makes validation with real crypto-active users realistic and fast.

---

## Idea 2: Degree Progress and Prerequisite Tracker

### Problem Area
Students in credit-based degree programs often lose track of how many credits they have completed, how many remain, and which prerequisite chains they still need to satisfy. Academic advising happens infrequently, and a single missed prerequisite can delay graduation by a whole semester.

### Target Users
University students, especially those in 120-credit programs who plan their own course schedules, plus academic advisors who support them.

### Current Alternative
Students currently check their progress manually against PDF curriculum sheets, ask advisors, or keep informal personal spreadsheets. This is error-prone and does not clearly flag unmet prerequisites.

### Proposed IT Solution
A web tool where a student inputs the courses they have completed and enrolled in. The tool calculates remaining credits toward the 120-credit goal, flags any prerequisites that are not yet satisfied, and shows a visual progress bar toward graduation.

### Possible Technology
HTML/CSS/JavaScript, a JSON file holding the curriculum and prerequisite rules, simple logic to compute remaining credits and check prerequisites, and a dashboard chart for progress visualization.

### Why This Is Suitable
The scope is clear and self-contained, the data is not sensitive, and validation is easy because every classmate is a potential user. It can be built as a clickable web prototype with database/JSON design and basic UI within one semester.

---

## Idea 3: Creator Content Planner and Repurposing Tracker

### Problem Area
Small content creators post the same or similar content across TikTok, Instagram, and YouTube, but they lose track of what has been posted where, which pieces could be repurposed, and how each post performed. Ideas, drafts, and finished posts live in different apps with no shared view.

### Target Users
Student creators, micro-influencers, and small businesses that run their own social media accounts.

### Current Alternative
Creators currently use notes apps, memory, group chats, or scattered spreadsheets to plan and remember posts. There is no single board showing each idea's status across platforms.

### Proposed IT Solution
A web planner with a simple board where each content idea moves through stages (idea, editing, posted) and is tagged by platform. Users can log basic manual metrics per post and quickly see which finished pieces are ready to repurpose on another platform.

### Possible Technology
HTML/CSS/JavaScript with a kanban-style board UI, local or Google Sheet storage for content items, and tag/filter functions by platform and status.

### Why This Is Suitable
A kanban-style content board is a realistic clickable web prototype for one semester. The team has direct content-creation and video-editing experience, so validating the workflow with real creators is straightforward.
