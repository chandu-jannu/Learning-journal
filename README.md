# 📚 My Learning Journal

## project 1 - February 9, 2026
**Project:** Mini Chrome Dashboard

**What I Built:**
- Created a custom browser start page
- Implemented live clock with JavaScript
- Added multi-search functionality (Google, YouTube, Spotify)
- Quick access apps with hover animation
- Learned: DOM manipulation, setInterval, event handling

**Repository:** [mini-chrome-dashboard](https://github.com/chandu-jannu/mini-chrome-dashboard)

---

## project 2 - March 4, 2026
**Project:** Campus Navigator

**What I Built:**
- Interactive pathfinding system
- Implemented Dijkstra's shortest path algorithm
- SVG-based interactive map
- 12 campus locations with weighted graph connections
- Real-time distance calculation and route visualization
- Smooth animations and modern gradient UI

**What I Learned:**
- Graph algorithms (Dijkstra's algorithm)
- SVG manipulation with JavaScript
- GitHub Pages deployment

 **Challenges Faced:**
- **Implementing Dijkstra's Algorithm**- First working with graph algorithm had to understand shortest path logic and translate into working     code
- **SVG manipulation** - Learning how to dynamically create and animate SVG elements with JavaScript was complex
- **Graph Data Structure** - Designing the weighted graph with bidirectional connections required careful planning to avoid bugs
- **Path Visualization** - making the animated route line appear smoothly along the correct path took multiple iterations
- **Debugging Route Calculations** - Some paths weren't calculating correctly; had to trace through the algorithm step-by-step to find the       issue

**How I Solved It:**
- Studied Dijkstra's algorithm concept first, then broke it down into smaller functions
- Practiced with simple SVG examples before building the full map
- Drew the campus graph on paper first to visualize connections
- Used console.log extensively to debug and verify each step
- Tested with different start/end points to ensure all routes worked correctly

**Repository:** [campus-navigator](https://github.com/chandu-jannu/campus-navigator)  
**Live Demo:** [View Live](https://chandu-jannu.github.io/campus-navigator)

---

## Project 3 -  March 23, 2026
**Project:** Activity-log

**What I Built:**
A full stack personal productivity web app with:
- task planner with Daily/Weekly/Monthly Catagories
- Health tracker - water, supplements, routine, mood, journal
- Meditation timer
- Weather widget
- Dark/light theme
- Google login
- Push notification per device
- Deployed live at my-activity-log.vercel.app

## What I Learned:

### Javascript
- localStorage to store data in browser
- DOM manipulation — creating, appending, removing elements
- setInterval for live clock and notification checks

### Firebase
- Google OAuth login with `signInWithPopup`
- `onAuthStateChanged` to check login state
- Firestore NoSQL database — saving data per user and per device
- FCM push notifications — each device has its own token
- VAPID keys for web push

### Backend
- Vercel Serverless Functions — running server code without a server
- Environment variables — hiding secrets from frontend
- Fetching config from server instead of hardcoding in HTML
- Cron jobs with cron-job.org to trigger notifications every minute

### Security
- Never hardcode API keys in HTML
- Restrict API keys to specific domains in Google Cloud
- Firebase authorised domains
- Firestore security rules only logged in users can read
- env.local for local secretes. Never push to github

### Deployment
- vercel for hosting and serverless functions
- 'npx vercel ---prod' to deploy from terminal
- Github for code backup - keeping secrets out of repo
- **Live demo:** [view Live](https://my-activity-log.vercel.app)
---

## 🛠️ Skills Progress

**HTML:** ✅ Completed  
**CSS:** ✅ Completed  
**JavaScript:** 🔄 In Progress (basics done, expanding knowledge)

---

## 🎯 Next Steps

- Continue learning advanced JavaScript
- Build more interactive projects
- Work with APIs

---

**Last Updated:** March 4, 2026
