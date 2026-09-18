## Workshop Attendees
Thank you for registering for this Workshop.  
If you need to cancel, please do so earlier rather than later to give others a chance to register.

## Ticket Cancellation and No-Show Policy:
If you need to cancel your reservation, please contact us by email at qcl@cmc.edu at least 24 hours prior to the event. A prompt cancellation will help us contact the next person on the waitlist. In case of 2 or more no-shows (without cancellation), you will lose your privilege to take our free workshops during the semester.
#  Description:
This hands-on workshop introduces participants to GIT, a powerful version control system widely used in software development. Designed for beginners, the session covers essential GIT concepts, including repository setup, branching, merging, and collaborative workflows. Participants will gain practical experience in tracking file changes, managing repositories, and implementing best practices for seamless team collaboration. The workshop will utilize GitHub Web and GitHub Desktop to provide a user-friendly introduction, equipping attendees with the foundational skills needed to confidently work with version control systems.

## Agenda:
- Version Control systems
- Git and Github
- Create an organization
- Create a repository
- Create issues
- Forking a repository
- Cloning a repository
- Branching a project
- Contributing to a repository
- Code review and merging

## Pre-requisites:
Internet use: Introductory level<br>
GitHub account access (Use this same email to register for the workshop or let the moderator know your GitHub email for the workshop)<br>
GitHub desktop: Installed<br>
Optional: GitKraken, IDE (eg. PyCharm, VisualStudio)

## Participants:
7C Students, Faculty and Staff

# Materials

<a href="GitHubBasics3.pdf" target="_blank">Download Presentation PDF</a>

# Hands-On Project:

📘 Collaborative Story Exercise for Git Practice
Welcome to the **Git Collaboration Practice Exercise**!

## 🧠 Purpose
This exercise will help you practice core Git concepts:
- Cloning repositories
- Branching
- Making commits
- Opening pull requests
- Resolving merge conflicts

All while building a fun, creative story together. ✍️

---

## 🚀 Instructions for Students

### 📦 Step 1: Accept the Invitation
Your instructor will add you as a collaborator on the GitHub repository. Check your email or GitHub notifications to accept the invite.

---

### 🧑‍💻 Step 2: Generate a GitHub Personal Access Token (PAT)
GitHub no longer allows password authentication for Git operations. You’ll need a Personal Access Token to push your changes.

1. Go to: [https://github.com/settings/tokens](https://github.com/settings/tokens)
2. Click **"Generate new token → Fine-grained token"**
3. Under **Repository access**, choose:
   - `Only select repositories`
   - Select the repo your instructor invited you to (e.g., `Intro_GIT_bootcamp_year`)
4. Under **Permissions**:
   - `Contents` → **Read and Write**
   - ` ` → **Read and Write**
5. Set an expiration date (30–90 days is fine)
6. Click **Generate token**
7. **Copy the token** right away — you won’t be able to see it again!

---

### 💻 Step 3: Clone the Repository
```bash
git clone https://github.com/CMC-QCL/my_repo.git
cd my_repo
```

---

### 🌱 Step 4: Create a New Branch
```bash
git checkout -b your-name-branch
```

---

### ✍️ Step 5: Edit the Story
Open `story.txt` and add **one sentence** to the story. Be creative, but don’t delete anyone else’s work.

---

### 💾 Step 6: Commit and Push Your Changes
```bash
git add story.txt
git commit -m "Added a line by [Your Name]"
git push origin your-name-branch
```

> 💡 When prompted for username/password:
> - Username: your GitHub username
> - Password: paste the **Personal Access Token** you just created

To avoid typing your token every time:
```bash
git config --global credential.helper osxkeychain  # For macOS
# or
git config --global credential.helper cache         # For temporary session caching
```

---

### 🔁 Step 7: Open a Pull Request
1. Go to the GitHub repo in your browser
2. Click "Compare & pull request"
3. Write a short title and description
4. Submit your pull request

---

### ⚠️ Optional: Handling Merge Conflicts
If multiple people edit the same line, Git will show a conflict like:
```txt
<<<<<<< HEAD
This line was edited by Student A.
=======
This line was edited by Student B.
>>>>>>> your-branch
```
Manually choose which version to keep, then:
```bash
git add story.txt
git commit -m "Resolved merge conflict"
```

---

## 📜 story.txt
Start of the story:
```txt
Once upon a time, there was a magical Git repository...
```
Everyone should add **one sentence** beneath this line.

---

## ✅ Checklist (for instructors)

- [ ] Add students as collaborators to the repo
- [ ] Confirm they’ve accepted the invite
- [ ] Share these instructions
- [ ] Create Issues for each student
  - [ ] Setting – Establish the place and time where the story begins <br>
	Main Character Introduction – Introduce a central figure or protagonist <br>
	Supernatural or Sci-Fi Twist – Add an unusual or futuristic element <br>
	Conflict or Challenge – Present a problem or obstacle the characters must face <br>
	Dialogue (Conversation) – Include spoken interaction between characters <br>
	Internal Thoughts or Emotions – Show what a character is thinking or feeling <br>
	Plot Twist – Introduce a surprising or unexpected development <br>
	Technology or Invention – Describe a fictional device or discovery <br>
	World-building Details – Add unique elements that define the story’s universe <br>
	Resolution or Cliffhanger – Wrap up the moment or leave the reader in suspense <br>  
- [ ] Help troubleshoot token setup
- [ ] Review and merge pull requests
- [ ] Celebrate the final story!

---

Happy collaborating! 🎉


# Past dates
