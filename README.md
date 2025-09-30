# Interactive-Learning-Collaboration-Platform
It is a web application where user learner can enroll into the course. After completion of the course learner will get a score. There are 2 roles like mentor and learner. A mentor could able to check learner performance and guide accordingly to the learner. 

Technology-Html+css+javascript

These are the module of this project-

1. Authentication (Login + Register)

File: index.html

Features:

Combined login & register form (toggle with buttons).

User chooses role (Learner / Mentor) during registration.

Stores user details in localStorage (name, email, password, role, points, badges).

On successful login → navigates to dashboard.html.

Flow:
Register → Save user → Login → Redirect to Dashboard.

2. Dashboard

File: dashboard.html

Features:

Shows greeting (time-based: Good Morning/Afternoon/Evening).

Displays User Role (Learner/Mentor).

Shows Points & Badges.

Activity feed (study updates).

Leaderboard (top learners/mentors).

Dark/Light mode toggle.

Logout → redirects back to index.html.

Flow:
Load current user → personalize UI → display leaderboard & activities.

3. Profile Management

File: profile.html

Features:

View and update profile details (name, email, role).

Option to change password.

Profile picture upload (optional).

Flow:
Current user data loaded → editable → saved to localStorage.

4. Content Sharing

File: content.html

Features:

Upload content: articles, PDFs, tutorials, YouTube links.

Display uploaded content in a clean list/card format.

Content stored in localStorage.

Flow:
User uploads → content appears → all users can view.

5. Discussion Forum (Q&A Board)

File: discussion.html

Features:

Users can post questions.

Other users can reply (thread style).

Stores questions and replies in localStorage.

Flow:
Post → Save → Render → Replies linked to questions.

6. Groups (Study Groups)

File: groups.html

Features:

Create new study groups.

List existing groups.

Groups stored in localStorage.

Mini chat inside each group (can be added).

Flow:
Create group → Add to list → Join/View → Interact.

7. Logout

Every page

Features:

Clears currentUser from localStorage.

Redirects to index.html.

⚡ How They Work Together

User enters → index.html (login/register).

Registers as Learner/Mentor → stored in localStorage.

Logs in → redirected to dashboard.html.

From dashboard, user can go to:

Profile → update info.

Content → share & view learning material.

Discussion → Q&A forum.

Groups → create/join study groups.

Logout → back to index.html.
