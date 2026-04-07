# Vibe Coding Quick Reference

A cheat sheet for when you need to remember the workflow fast.

---

## The Core Philosophy

**If you can explain what you want, you can build it.**

Describe behavior, not code. Let the tools handle the syntax.

---

## The Stack

1. **Google AI Studio** - Start the UI, prompts, and first feature ideas
2. **Firebase Console** - Create the backend project, Auth, Firestore, and App Hosting
3. **GitHub** - Where AI Studio pushes the starter code so you can clone it
4. **Cursor + Firebase CLI** - Build locally, connect Firebase, and deploy

**All free to start.**

---

## The Workflow

1. **Create the Firebase project first** - Do this in Firebase Console
2. **Start in Google AI Studio** - Prompt it to link to that Firebase project
3. **Turn on database and auth in AI Studio** - This helps it connect the project correctly
4. **Publish and push to GitHub** - Use AI Studio only for the starting point
5. **Open the repo in Cursor** - This is where you keep building
6. **Connect App Hosting locally** - Use the Firebase CLI in Cursor
7. **Build and deploy** - Run the build, then deploy with Firebase CLI

**Create Firebase project -> start in Google AI Studio -> push to GitHub -> build in Cursor -> deploy with Firebase CLI. Repeat.**

---

## Firebase CLI Setup

Run these inside Cursor the first time you connect the app:

```bash
npm install -g firebase-tools
firebase login
firebase init
```

During `firebase init`:
- choose `App Hosting`
- use the existing Firebase project
- link to the existing backend
- leave the app route directory alone unless you know it needs changing

When you are ready to ship:

```bash
npm run build
firebase deploy
```

**Important:** Create your Firebase project first at [console.firebase.google.com](https://console.firebase.google.com/) before you start in AI Studio or run `firebase init`.

---

## How to Talk to Cursor

### Good Prompts

- "Connect this app to my Firebase project and use Email/Password auth"
- "Add a notes list that saves to Firestore"
- "Make this homepage cleaner and mobile-friendly"

### Bad Prompts

- "Write code for Firebase"
- "Fix everything"
- "Make it better"

**Describe behavior, not code.**

---

## Picking Your First Idea

**The rule:** If it takes more than 1 sentence to explain, it is too big.

**Examples:**
- Note saver
- Daily checklist
- Idea tracker
- Resource bookmarker

**Start stupid simple. Make it work. Then make it better.**

---

## Shipping Checklist

- [ ] Core features work
- [ ] Users can accomplish the main goal
- [ ] Firebase project exists in Firebase Console
- [ ] App Hosting is connected
- [ ] `npm run build` succeeds
- [ ] `firebase deploy` succeeds
- [ ] Live URL works
- [ ] Share it

**Shipping != Perfect. Shipping = Usable.**

---

## Quick Fixes

| Problem | Solution |
|---------|----------|
| Firebase not defined | Check your Firebase config and imports |
| Permission denied | Update Firestore rules |
| Auth not working | Enable Email/Password in Firebase Console |
| Build errors | Run `npm run build` locally first |
| Deploy errors | Check `firebase init` App Hosting settings and selected project |
| Cursor code does not work | Be more specific in your prompt |

---

## Monetization Ideas

- SaaS
- Micro tools
- Paid communities
- APIs
- Internal business tools

**Solve a real problem. Charge for it.**

---

## The 30-Day Goal

**Idea -> Deployed App -> First Customers in ~30 days**

- Week 1: Build core feature
- Week 2: Test and improve
- Week 3: Add monetization
- Week 4: Launch and get customers

**Speed beats perfection.**

---

## When You're Stuck

1. Read the error message
2. Check the browser console
3. Ask Cursor to debug it
4. Simplify until it works
5. Ask the [community](https://www.skool.com/vibe-coding-with-chris-7196)

**Most bugs are simple. You just need to find them.**

---

## Essential Links

- [Google AI Studio](https://aistudio.google.com/)
- [Firebase Console](https://console.firebase.google.com/)
- [GitHub](https://github.com)
- [Cursor](https://cursor.sh)
- [Vibe Coding with Chris Skool](https://www.skool.com/vibe-coding-with-chris-7196)

---

## Remember

- Your first version is supposed to be bad
- Shipping beats perfect
- Speed matters more than perfection
- Real feedback beats assumptions
- Build daily, not perfectly

**Vibe coding is about momentum, not perfection.**

---

*For daily lessons and real builds, join the [Vibe Coding with Chris Skool community](https://www.skool.com/vibe-coding-with-chris-7196).*
