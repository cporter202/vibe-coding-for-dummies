# SECTION 1 - The Vibe Coding Stack (Simple + Free)

You do not need $300/month in tools to ship your first app. You need a simple workflow that gets you moving.

This section covers the stack, why it works, and how to set it up without getting buried in setup hell.

---

## Lesson 1.1 - The Only Tools You Need to Start (Free)

### Why Beginners Overspend on Tools

Most beginners think they need:
- Premium hosting
- A paid database
- A separate auth product
- A paid editor
- Extra workflow tools

**Result:** they spend money before they have built anything real.

**Reality:** you can start with a very small stack.

### The Free Stack That Actually Works

Here is what you actually need:

#### 1. **Google AI Studio** (Free)
- Great place to start the UI and project bones
- Fast for prompts, structure, and first features
- Lets you get momentum before you worry about setup

#### 2. **Firebase Console** (Free tier)
- Create your real backend project
- Enable Authentication
- Enable Firestore
- Enable App Hosting

#### 3. **GitHub** (Free)
- AI Studio can push the starter code here
- You can clone the repo locally
- It becomes your safe backup and history

#### 4. **Cursor + Firebase CLI**
- Build locally with AI help
- Connect the app to your Firebase project
- Deploy from your machine with the Firebase CLI

**Total to start: basically $0**

### Why This Stack Works

**Google AI Studio** helps you start fast:
- You can prompt your way into a first version
- You can shape the UI before everything is perfect
- You stop staring at a blank screen

**Firebase Console** gives you the real backend:
- Auth
- Database
- App Hosting
- Project settings that match production

**GitHub** keeps you organized:
- Your code is backed up
- You can track changes
- You can always go back

**Cursor** helps you move faster:
- AI understands your codebase
- You can keep building after the first prototype
- It is the best place to wire the app to Firebase and fix issues

### The Key Point

You need:
1. A place to start the app
2. A real backend project
3. A place to save your work
4. A local build environment that can deploy

That is the stack.

---

## Lesson 1.2 - Why Google AI Studio + Firebase Is Beginner-Friendly

### What Each Tool Does Best

**Google AI Studio** is where you start:
- Rough UI
- Prompt-driven scaffolding
- First-pass feature ideas
- Early momentum

**Firebase Console** is where you create the real backend:
- Authentication
- Firestore
- App Hosting
- Project settings

**Cursor** is where you turn the prototype into a real app:
- Clean up code
- Add features
- Debug issues
- Deploy with the Firebase CLI

### Why This Removes Friction

**Old beginner mistake:**
1. Install everything
2. Configure everything
3. Get confused
4. Never build

**Better workflow:**
1. Start the app visually in Google AI Studio
2. Create the Firebase project in Firebase Console
3. Open the code in Cursor
4. Connect Firebase locally
5. Keep building
6. Deploy from Cursor

You separate the jobs:
- AI Studio for momentum
- Firebase Console for backend setup
- Cursor for real development

### The Actual Workflow

Here is the exact workflow we want in this course:

**Step 1: Create your backend project in Firebase Console**
- Go to [Firebase Console](https://console.firebase.google.com/)
- Create a new Firebase project
- This is the real backend your app will connect to

**Step 2: Start in Google AI Studio**
- Create the first version of the app
- Focus on the UI, screens, and basic feature flow
- Tell it you already created a Firebase project and want this app linked to it
- Build the project bones first

**Step 3: Enable Firebase services**
- Turn on Authentication
- Turn on Firestore
- Turn on App Hosting if needed
- In AI Studio, click database and auth when you want the link-up to happen cleanly

**Step 4: Push the starter code to GitHub**
- AI Studio can create the starting GitHub repo for you
- Push the starter code there
- Keep it private

**Step 5: Open the project in Cursor**
- Clone the repo locally
- Open it in Cursor
- This is where you keep building

**Step 6: Connect Firebase locally**

Run:

```bash
npm install -g firebase-tools
firebase login
firebase init
```

During `firebase init`:
- choose `App Hosting`
- use the existing project
- link the existing backend
- keep the default route directory unless you know it needs changing

**Step 7: Build and deploy from Cursor**

Run:

```bash
npm run build
firebase deploy
```

**That is the loop: create Firebase project -> start in Google AI Studio -> push to GitHub -> build in Cursor -> deploy with Firebase CLI.**

### Setting Up the Stack

**Exercise: set up the tools**

1. Go to [Google AI Studio](https://aistudio.google.com/)
2. Go to [Firebase Console](https://console.firebase.google.com/)
3. Create a Firebase project
4. Create a GitHub account if needed
5. Install Cursor on your computer

**That is enough to start.**

We will connect everything in the build section.

---

## Action Step

Do these right now:

1. Open Firebase Console
2. Create one Firebase project with a simple name
3. Open Google AI Studio

That way, when you start building in AI Studio, the backend already exists.

**Next:** [SECTION 2 - GitHub Without the Fear](./03-github.md)
