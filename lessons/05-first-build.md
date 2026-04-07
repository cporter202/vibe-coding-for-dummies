# SECTION 4 - Your First Real Build (Tiny but Real)

This is where it gets real. You are going to build something small, useful, and live.

This section walks you through the new flow:
- create the backend in Firebase Console first
- start the first version in Google AI Studio
- push the starter code to GitHub
- keep building in Cursor

---

## Lesson 4.1 - Picking a "Stupid Simple" Idea

### Why Simple Wins

Most beginners make the same mistake:
- they try to build a huge app
- they get overwhelmed
- they never ship

**Vibe coding rule:** start stupid simple.

### What "Stupid Simple" Means

A stupid simple idea:
- takes 1 sentence to explain
- has 1-2 core features
- can be built in a few hours
- solves 1 clear problem

**Examples:**
- Note saver
- Daily checklist
- Idea tracker
- Resource bookmarker

**If it takes more than 1 sentence to explain, it is too big.**

---

## Lesson 4.2 - Scaffolding the App with Google AI Studio

### Start with the Project Bones

For this workflow, we start in **Google AI Studio**.

This is where you shape:
- the look
- the screens
- the first feature flow
- the project bones

You are not trying to finish the whole app there. You are trying to get momentum.

### Step 1: Create the Firebase Project First

Go to [Firebase Console](https://console.firebase.google.com/) and:

1. Create a Firebase project
2. Turn on analytics if you want it
3. Open the project settings page
4. Keep the project details handy so you can reference them in AI Studio

You want the backend ready before you start prompting AI Studio.

### Step 2: Start the First Version in Google AI Studio

Go to [Google AI Studio](https://aistudio.google.com/) and start building the first version of the app.

Focus on:
- a simple homepage
- the main screen
- the main form
- the core interaction

**Example prompts:**

1. "Create a simple web app for saving notes."
2. "Make the UI clean, modern, and mobile-friendly."
3. "Add a login screen and a notes list view."
4. "Keep the code simple and beginner-friendly."

Tell it clearly that:
- you already created the Firebase project
- you want this app linked to that project
- you want auth and database included if needed

### Step 3: Confirm the Firebase Link

In AI Studio:

1. paste in the Firebase project details
2. click database and auth if the app may need them
3. build the project
4. confirm the project is linked correctly

If auth and Firestore already look set up, that is a good sign the connection worked.

### Step 4: Publish the Starting Version

Use AI Studio to publish the starting app.

This gives you the first version and helps prime the App Hosting side.

If App Hosting is flaky or incomplete here, that is okay. The important part is getting the project started.

### Step 5: Push the Starter Code to GitHub

Once you have the first version:

1. Click GitHub in AI Studio
2. Create the repo
3. Push the starter code
2. Clone it to your computer
3. Open it in Cursor

This is the point where the project stops being a rough prototype and becomes a real app you can keep improving.

### Step 6: Finish App Hosting Setup If Needed

If AI Studio did not fully wire App Hosting for you:

1. go to App Hosting in Firebase Console
2. connect the GitHub repo
3. select the existing Firebase web app or backend when prompted
4. finish the initial setup there

### Step 7: Connect Firebase in Cursor

Inside Cursor, use the terminal and run:

```bash
npm install -g firebase-tools
firebase login
firebase init
```

During `firebase init`:
- choose `App Hosting`
- use the existing project
- link the existing backend
- leave the app route directory alone unless you know it should change

If Cursor generated the frontend but not the Firebase wiring, ask it to:
- add Firebase config
- wire up Authentication
- wire up Firestore reads and writes
- prepare App Hosting deployment

### Step 8: Keep Iterating in Cursor

Now build for real:

- clean up the UI
- fix rough code
- connect forms to Firestore
- add auth flows
- test everything locally

**This is the core loop:** prompt, run, test, fix, repeat.

### Why This Order Works

This order is cleaner:

1. Firebase Console gives you the real backend first
2. Google AI Studio gives you a polished first pass
3. Cursor gives you the best environment for actual development

That means you are not depending on one tool to do every job.

### Accepting "Ugly First"

Your first version will not be perfect:
- styling may be rough
- structure may be messy
- code may need cleanup

That is normal.

**First make it real. Then make it better.**

---

## Lesson 4.3 - Connecting Firebase (High Level)

### Auth Basics

Firebase Authentication handles:
- sign-up
- login
- password reset
- sessions

You do not need deep theory first. You just need it working.

### Database Basics

Firestore stores your app data.

Think in simple terms:
- a collection is a group of items
- a document is one item
- fields are the values inside it

Example:

```text
Collection: notes
  Document:
    title: "My first note"
    content: "Hello world"
    userId: "user123"
```

That is enough to get started.

### What You Actually Need to Know

You do not need to master:
- advanced security rules
- optimization
- scaling theory

You do need to know:
- users can sign in
- data can be saved
- data can be read back

That is enough for version 1.

---

## Action Step: Build Your First App

Do this in order:

1. Pick a stupid simple idea
2. Create the Firebase project in Firebase Console
3. Start the first version in Google AI Studio
4. Push the starter code to a private GitHub repo
5. Open the project in Cursor
6. Run:

```bash
npm install -g firebase-tools
firebase login
firebase init
```

7. Choose `App Hosting` and link the existing backend
8. Keep building and testing locally

Do not try to make it perfect. Just make it real.

**Next:** [SECTION 5 - Shipping (Most People Never Get Here)](./06-ship.md)

**Having issues?** Check out the [Troubleshooting Guide](./09-troubleshooting.md) for common fixes.
