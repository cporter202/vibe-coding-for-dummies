# 🤖 SECTION 3 — Cursor: Your AI Co-Builder

Cursor is where the magic happens. It's not just a code editor. It's an AI co-builder that understands your entire project and helps you build faster.

This section shows you how to use Cursor like a pro (even if you're a beginner).

---

## Lesson 3.1 — What Cursor Does Differently

### Why Cursor Beats Copy/Paste ChatGPT

**The old way (ChatGPT):**
1. Copy your code
2. Paste it into ChatGPT
3. Ask a question
4. Copy the answer
5. Paste it back
6. Hope it works
7. Repeat

**The Cursor way:**
1. Ask a question in your editor
2. Cursor understands your entire codebase
3. It edits files directly
4. You see the changes immediately
5. You keep building

**Cursor is AI inside your codebase, not AI in a separate window.**

### AI Inside Your Codebase

Here's what makes Cursor different:

**Context awareness:**
- Cursor sees all your files
- It understands your project structure
- It knows what you're working on
- It suggests changes that fit your codebase

**Direct editing:**
- Cursor edits files directly
- No copy/paste
- No context switching
- You stay in the flow

**Project understanding:**
- Cursor knows your dependencies
- It understands your file structure
- It suggests improvements based on your code
- It's like having a senior developer who knows your entire project

### Editing Files with Context

**Example:**

You're building a note-taking app. You ask Cursor:

"I want users to be able to edit their notes."

**Cursor:**
- Looks at your existing code
- Sees how you're saving notes
- Understands your data structure
- Adds an edit function that matches your style
- Updates the UI to include edit buttons
- Does it all in context

**You don't explain your entire project. Cursor already knows it.**

### The Mental Model

Think of Cursor like this:

```
You (the thinker)     Cursor (the builder)
─────────────────    ────────────────────
"I want X"      →    "Here's the code for X"
"Change Y"      →    "Updated Y in 3 files"
"Fix Z"         →    "Fixed Z, here's what changed"
```

**You describe behavior. Cursor writes code.**

---

## Lesson 3.2 — How to Talk to AI Like a Builder

### Bad Prompts vs. Good Prompts

**Bad prompt:**
"Write code for authentication"

**Why it's bad:**
- Too vague
- No context
- Cursor doesn't know what you want
- You'll get generic code that doesn't fit

**Good prompt:**
"I want users to be able to sign up and log in. They should be able to reset their password if they forget it. Use Firebase authentication."

**Why it's good:**
- Specific behavior
- Clear requirements
- Mentions your stack
- Cursor knows exactly what to build

### Describing Behavior, Not Code

**Don't say:**
- "Write a function that..."
- "Create a component that..."
- "Add a database query..."

**Say:**
- "I want users to be able to..."
- "When a user clicks X, Y should happen..."
- "Users should see Z when..."

**Describe what should happen, not how to code it.**

### Example Prompts That Work

**Building a note app:**

✅ "I want users to be able to create notes. Each note should have a title and content. Notes should be saved to Firebase Firestore."

✅ "When a user clicks 'New Note', show them a form where they can enter a title and content. When they submit, save it to Firebase Firestore and show it in their list of notes."

✅ "I want users to be able to delete notes. Add a delete button to each note. When clicked, remove it from Firebase Firestore and update the list."

✅ "I want users to be able to edit their existing notes. Add an edit button that lets them change the title and content, then save the changes to Firebase."

**Notice:** All of these describe behavior, not code.

### More Real-World Examples

**For a habit tracker:**

✅ "I want users to be able to create a daily habit list. Each habit should have a name and a checkbox. When they check it off, save that they completed it today in Firebase."

✅ "Show users a list of their habits. Display how many days in a row they've completed each habit. Get this data from Firebase Firestore."

**For a resource bookmarker:**

✅ "I want users to be able to save links. They enter a URL and a title. Save it to Firebase. Show all their saved links in a list."

✅ "When a user clicks a saved link, open it in a new tab. Also track how many times each link has been clicked and show that number."

**The pattern:** Describe what should happen, mention Firebase/Firestore, and be specific about the user experience.

### Iterative Building

**You don't build everything at once. You build iteratively.**

**Step 1:** "I want a simple app where users can log in."

**Step 2:** "Now I want users to be able to save notes after they log in."

**Step 3:** "Now I want users to be able to edit their notes."

**Step 4:** "Now I want users to be able to delete notes."

**Each step builds on the last. You're not trying to build everything at once.**

### The Prompt Formula

**Good prompts follow this formula:**

1. **Who:** "Users" or "I want"
2. **What:** The action or behavior
3. **How:** The stack or method (optional, but helpful)
4. **Context:** What it should work with (optional)

**Example:**
"I want users to be able to save notes to Firebase after they log in."

- Who: Users
- What: Save notes
- How: Firebase
- Context: After they log in

**That's a perfect prompt.**

### Common Mistakes to Avoid

**Mistake 1: Being too vague**
❌ "Make it better"
✅ "I want the login form to show an error message if the password is wrong"

**Mistake 2: Asking for everything at once**
❌ "Build a complete note-taking app with authentication, CRUD operations, and a beautiful UI"
✅ "I want users to be able to log in" (then build from there)

**Mistake 3: Not providing context**
❌ "Add a button"
✅ "Add a delete button to each note that removes it from Firebase when clicked"

**Mistake 4: Asking for code, not behavior**
❌ "Write a function that queries the database"
✅ "I want to show all of the user's notes when they log in"

---

## 🎯 Action Step

**Practice writing prompts:**

Think about your project idea from Section 0. Write 3 prompts that describe what you want to build:

1. One prompt for the core feature
2. One prompt for a secondary feature
3. One prompt for improving the user experience

**Example (for a note app):**
1. "I want users to be able to create and save notes to Firebase"
2. "I want users to be able to see all their notes in a list"
3. "I want the note list to update automatically when a new note is created"

**These are the prompts you'll use when you start building in Section 4.**

---

## 🎯 Setting Up Cursor

### Install the Desktop App (Not the Browser Version!)

**Important:** Install Cursor on your computer. **Do NOT use the browser version.** The browser version is horrible and doesn't work well for vibe coding.

**Here's how to install Cursor properly:**

#### Step 1: Download Cursor

1. **Go to [Cursor.sh](https://cursor.sh/)**
2. **Click "Download"** (usually a big button on the homepage)
3. **Choose your operating system:**
   - **Windows:** Download the `.exe` file
   - **Mac:** Download the `.dmg` file
   - **Linux:** Download the appropriate package for your distribution

**It's free to start.** You can use the free tier, and paid plans start at $20/month if you want more features later.

#### Step 2: Install Cursor

**For Windows:**
1. Find the downloaded `.exe` file (usually in your Downloads folder)
2. Double-click it to run the installer
3. Follow the installation wizard (click "Next" through the prompts)
4. Choose where to install it (default location is fine)
5. Click "Install"
6. Wait for installation to complete
7. Click "Finish"

**For Mac:**
1. Find the downloaded `.dmg` file (usually in your Downloads folder)
2. Double-click it to open
3. Drag the Cursor icon to your Applications folder
4. Open Applications and double-click Cursor to launch it
5. If you get a security warning, go to System Preferences → Security & Privacy → Click "Open Anyway"

**For Linux:**
1. Extract or install the downloaded package based on your distribution
2. Follow your distribution's standard installation process

#### Step 3: Open Cursor

1. **Launch Cursor** from your applications or start menu
2. **Sign in or create an account** (if prompted)
3. **You're ready to go!**

### Why Not the Browser Version?

**The browser version of Cursor:**
- ❌ Doesn't have full access to your file system
- ❌ Can't understand your entire codebase properly
- ❌ Limited AI capabilities
- ❌ Slower and less reliable
- ❌ Missing key features you need for vibe coding

**The desktop app:**
- ✅ Full access to your files
- ✅ Understands your entire project
- ✅ Better AI assistance
- ✅ Faster and more reliable
- ✅ All the features you need

**Bottom line:** Install the desktop app. Don't use the browser version. It's worth the 2 minutes to install.

### How Cursor Works with Your Project

**Cursor works best when you open a folder (your project):**

1. **Open Cursor**
2. **Click "File" → "Open Folder"** (or use the keyboard shortcut)
3. **Select your project folder** (the one with your code)
4. **Cursor now understands your entire project**

**We'll do this in Section 4 when we start building.** For now, just make sure Cursor is installed on your computer.

### First Time Setup

**When you first open Cursor:**

1. It might ask you to sign in or create an account
2. It might show you a welcome screen or tutorial
3. You can skip the tutorial if you want (we'll learn by building)
4. You're ready to start building!

**That's it. Cursor is installed and ready.**

---

## 🎯 Action Step

**Install Cursor on your computer right now:**

1. Go to [Cursor.sh](https://cursor.sh/)
2. Download the desktop app (not browser version!)
3. Install it
4. Open it
5. Make sure it's working

**Don't wait. Don't use the browser version. Install the desktop app.**

**Next:** [SECTION 4 — Your First Real Build (Tiny but Real)](./05-first-build.md)

---

**Next:** [SECTION 4 — Your First Real Build (Tiny but Real)](./05-first-build.md)

