# SECTION 2 - GitHub Without the Fear

GitHub scares a lot of beginners. It should not. It is just where your project lives online.

This section removes the fear and shows you how GitHub fits into the new workflow.

---

## Lesson 2.1 - GitHub Explained Like You're 5

### What GitHub Actually Is

**GitHub is like Google Drive for code.**

- You save your project there
- You can access it from anywhere
- You can see what changed
- You can go back to older versions

That is it.

### Repos = Project Folders

A **repository** (repo) is just a folder for your project.

Think of it like:
- A folder on your computer = a repo on GitHub
- Your files = your project
- Your README = your notes

### Commits = Save Points

A **commit** is like saving your game.

- You make changes
- You save those changes with a message
- GitHub remembers that point in time

### Why GitHub Matters Even If You Are Not a Dev

1. Your code is safe
2. You can track progress
3. You can work from different computers
4. You can share the project when needed
5. It keeps your work organized

---

## Lesson 2.2 - Creating Your First Repo (No Stress)

### GitHub Is the Hand-Off Point

We are no longer teaching "Firebase Studio will make the repo for you."

In this workflow:
- you create the Firebase project first
- you start the app in Google AI Studio
- you create the backend in Firebase Console
- you push the starter code to GitHub
- you build locally in Cursor

That means GitHub is the hand-off point between AI Studio and Cursor.

### What You Need to Do

1. Create a GitHub account at [GitHub.com](https://github.com) if you do not have one
2. Let AI Studio create the starter repo when you click GitHub
3. Keep it private

**Good repo names:**
- `my-note-app`
- `habit-tracker`
- `idea-saver`
- `resource-bookmarker`

**Bad repo names:**
- `project`
- `test`
- `new-thing`

### The Important GitHub Limitation

AI Studio can push code to GitHub, but it is not the place you want to keep syncing back and forth forever.

The big limitation is:
- it can push code to GitHub
- it cannot pull your GitHub changes back in the way we want for this stack

That is why our workflow is:
- start in AI Studio
- push to GitHub
- clone to Cursor
- stay in Cursor

### Basic Local Git Flow

Once the AI Studio repo is cloned to your computer, Cursor becomes your normal Git workflow:

- make changes
- commit changes
- push changes

GitHub becomes your project history from that point on.

### Keep Your Repos Private

Use a private repo because:
- your code is yours
- beginners often accidentally expose keys or config
- private repos are free

**Do not commit secret keys or sensitive information.**

### What Happens After the Repo Exists

Once the repo is set up:

1. Your code is backed up
2. You can clone it anywhere
3. Cursor can work on it locally
4. You can commit and push changes as you build

GitHub is your source of truth. Firebase is your backend. Cursor is your workshop.

---

## Action Step

Before you build your first app:

1. Create a GitHub account if needed
2. Be ready to connect AI Studio to GitHub for the starter repo
3. Keep the repo private

That is enough. You do not need to overthink GitHub.

**Next:** [SECTION 3 - Cursor: Your AI Co-Builder](./04-cursor.md)
