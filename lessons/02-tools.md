# 🧱 SECTION 1 — The Vibe Coding Stack (Simple + Free)

You don't need $300/month in tools to ship your first app. You need three things, and they're all free to start.

This section covers the exact stack that works, why it works, and how to set it up.

---

## Lesson 1.1 — The Only Tools You Need to Start (Free)

### Why Beginners Overspend on Tools

Most beginners think they need:
- Premium hosting ($20/month)
- Database services ($15/month)
- Authentication services ($10/month)
- Code editors ($10/month)
- Project management tools ($15/month)

**Total: $70+/month before you've even built anything.**

**Reality:** You don't need any of that to start.

### The Free Stack That Actually Works

Here's what you actually need:

#### 1. **Firebase Studio** (Free)
- Backend infrastructure
- Authentication
- Database
- Hosting
- **Cost:** Free tier covers most starter projects

#### 2. **GitHub** (Free)
- Source of truth for your code
- Version control
- Project history
- **Cost:** Free for public and private repos

#### 3. **Cursor** (Free tier available)
- AI-powered code editor
- Understands your entire codebase
- Helps you build faster
- **Cost:** Free tier available, paid plans start at $20/month (but you can start free)

**Total to start: $0/month**

### Why This Stack Works

**Firebase Studio** removes the friction:
- No server setup
- No database configuration
- No deployment headaches
- Everything in one place

**GitHub** keeps you organized:
- Your code is safe
- You can see what changed
- You can work from anywhere
- It's your project's memory

**Cursor** makes building fast:
- AI understands your project
- You describe what you want
- It writes the code
- You focus on building, not syntax

### The Key Point

**You don't need $300/month in tools to ship your first app.**

You need:
1. A place to build (Firebase Studio)
2. A place to save your work (GitHub)
3. A way to build fast (Cursor)

That's it.

---

## Lesson 1.2 — Why Firebase Studio Is Perfect for Beginners

### What Firebase Studio Gives You Out of the Box

When you create a project in Firebase Studio, you get:

#### Authentication
- User sign-up and login
- Password reset
- Email verification
- Social logins (Google, etc.)
- **You don't code this. It just works.**

#### Database
- Real-time database (Firestore)
- No SQL knowledge needed
- Store and retrieve data easily
- **You don't set up servers. It's already there.**

#### Hosting
- Deploy your app with one click
- Get a live URL instantly
- Automatic SSL certificates
- **You don't configure anything. It deploys.**

### Why It Removes Friction

**Traditional way:**
1. Set up a server (hours of configuration)
2. Set up a database (more configuration)
3. Set up authentication (even more configuration)
4. Set up hosting (deployment headaches)
5. Finally start building

**Firebase Studio way:**
1. Create a project
2. Start building
3. Deploy when ready

**The boring but important stuff is handled for you.**

### Why It's Better Than "Local Setup Hell"

Most tutorials start with:
- "Install Node.js"
- "Install npm packages"
- "Set up your local environment"
- "Configure your database"
- "Set up authentication"

**Result:** You spend 3 hours setting up and 30 minutes building.

Firebase Studio flips this:
- Create account (2 minutes)
- Create project (1 minute)
- Start building (immediately)

**You spend 3 minutes setting up and hours building.**

### The Actual Workflow (This Is Key)

Here's the exact workflow I use (and you'll use too):

**Step 1: Build Project Bones in Firebase Studio**
- Create your project in Firebase Studio
- Use prompts to build the "project bones" — the basic structure and skeleton
- Get a few prompts in to get it moving
- This is where you establish the foundation before diving deep

**Step 2: Publish from Firebase Studio**
- Publish your project from Firebase Studio
- This creates the project folder in Firebase Console
- **This step is crucial** — it sets up your project in the Firebase ecosystem

**Step 3: Enable Services in Firebase Console**
- Go to Firebase Console (the project you just published)
- Enable Authentication (Email/Password)
- Enable Firestore Database
- Enable Hosting
- Configure any other services you need
- **This makes your life much easier later** — all services are ready to go

**Step 4: Sync to GitHub (Automatic!)**
- When you sync from Firebase Studio, it will ask you to create a GitHub repo
- You just enter a repo name (like `my-note-app`)
- Firebase Studio automatically creates the repo and syncs your code to it
- **You don't manually create the repo. Firebase Studio does it for you.**
- **Important:** Keep your repos private (don't commit secret keys or sensitive info)

**Step 5: Clone to Cursor**
- Clone the GitHub repo to your computer
- Open the project folder in Cursor
- Now you can build fast with AI
- All your Firebase services are already configured, so Cursor can work with them immediately

**Step 6: Build and Iterate**
- Use Cursor to build features, refactor, and improve
- Commit changes to GitHub
- Sync back to Firebase Studio when ready
- Deploy from Firebase Studio (one-click deployment)

**That loop is the whole game: Build bones → Publish → Enable services → Sync to GitHub → Build in Cursor → Deploy. Repeat.**

**Why this workflow works:**
- Firebase Studio removes setup friction (start building immediately)
- Publishing first ensures all services are properly configured
- Enabling services early makes everything easier later
- Firebase Studio removes GitHub setup friction (creates repo for you automatically)
- Cursor removes building friction (AI helps you build fast with everything already set up)

**You don't fight the tools. You use each tool for what it's best at.**

### Setting Up Firebase Studio

**Exercise: Create Your Firebase Studio Account**

1. Go to [Firebase Studio](https://studio.firebase.google.com/)
2. Sign up with your Google account (or create one)
3. Create your first project
4. Name it something simple: `my-first-vibe-app`

**That's it. You're ready to build.**

**Note:** Don't worry about configuring anything yet. We'll cover building project bones and enabling services in Section 4 when we build something real.

---

## 🎯 Action Step

**Create your Firebase Studio account right now.**

Don't wait. Don't overthink it. Just create the account.

Drop a ✅ when you're done (even if it's just in your head).

**Next:** [SECTION 2 — GitHub Without the Fear](./03-github.md)

