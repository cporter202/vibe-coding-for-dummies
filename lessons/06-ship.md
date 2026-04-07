# SECTION 5 - Shipping (Most People Never Get Here)

Most people build. Few people ship.

This section is about turning your project into a live app that people can use.

---

## Lesson 5.1 - What "Shipping" Actually Means

### Shipping != Perfect

Shipping does not mean:
- everything is polished
- every bug is gone
- every feature is done

Shipping means:
- it works
- people can use it
- it is live

That is enough.

### Why Shipping Matters

Shipping is how you learn:
- you get real feedback
- you see what matters
- you stop guessing
- you build momentum

Perfect is not the goal. Live is the goal.

---

## Lesson 5.2 - Deploying from Cursor with Firebase CLI

### Hosting Your App

Firebase App Hosting is still a great beginner option because it gives you:
- a live URL
- SSL
- global delivery
- a simple workflow

The difference now is **where you deploy from**.

We are not teaching one-click deployment from Firebase Studio.

We are teaching:
- build in Cursor
- deploy with Firebase CLI

### Before You Deploy

Make sure you already:
- started the app in Google AI Studio
- created the backend project in Firebase Console
- enabled Auth, Firestore, and App Hosting
- pushed the starter code to GitHub
- connected the local project with `firebase init`

### The Deployment Process

#### Step 1: Build the app locally

Run:

```bash
npm run build
```

Fix any errors before you deploy.

#### Step 2: Make sure Firebase CLI is ready

If this is your first time on the machine, run:

```bash
npm install -g firebase-tools
firebase login
firebase init
```

When `firebase init` asks questions:
- choose the Firebase project you already created in Firebase Console
- choose App Hosting
- link the existing backend
- keep the app route directory as-is unless you know it needs changing

#### Step 3: Deploy

Run:

```bash
firebase deploy
```

Firebase will give you a live URL, usually something like:

```text
your-app-name.web.app
```

That is your live app.

### Why This Workflow Is Better

Deploying from Cursor is better for this course because:
- it matches how real developers work
- you control the build process
- you see errors clearly
- you can fix problems immediately

### Common Deployment Issues

**Issue 1: `npm run build` fails**
- Fix the code before deploying
- Read the first real error, not the last one
- Ask Cursor to help debug the build

**Issue 2: Wrong Firebase project**
- Check which project you selected during `firebase init`
- Re-run init if needed

**Issue 3: App Hosting was not linked cleanly**
- Go back through the App Hosting setup
- Make sure the repo and backend are connected correctly

**Issue 4: AI Studio publish was flaky**
- That happens sometimes
- Finish the setup in Firebase Console and continue in Cursor

**Issue 5: App works locally but not after deploy**
- Check environment variables
- Check Firebase config
- Check browser console on the live site

Most deployment issues are fixable. Do not let them stop you.

---

## Action Step: Ship Your App

Do this:

1. Test the app locally
2. Run `npm run build`
3. Run `firebase deploy`
4. Open the live URL
5. Share it

That is shipping.

**Remember:** shipping beats perfect.

---

## You Shipped

Once the app is live, you are not just learning anymore.

You built something real and put it on the internet.

**Next:** [SECTION 6 - How This Turns Into Money](./07-monetize.md)
