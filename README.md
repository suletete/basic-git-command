Sure! Here's the entire Git project execution written in proper **Markdown (.md)** format:

---

```markdown
# 🚀 Hands-On Git Project – Collaboration with Tom and Jerry

## ✅ Part 1: Setup and Initial Configuration

### 1. Install Git
- Download Git from: [https://git-scm.com/downloads](https://git-scm.com/downloads)
- Install it for your OS (Windows/Mac/Linux)

---

### 2. Create a GitHub Repository
1. Go to [https://github.com](https://github.com)
2. Click the "+" icon in the top right corner → **New repository**
3. Repository name: `ai-startup-website`
4. Check the box: ✅ *Initialize this repository with a README*
5. Click **Create repository**

---

### 3. Clone the Repository

Open your terminal and run the following:

```bash
# Create a working directory
mkdir -p ~/Desktop/darey-training/git-project
cd ~/Desktop/darey-training/git-project

# Clone your GitHub repo (replace with your own repo URL)
git clone https://github.com/YOUR_USERNAME/ai-startup-website.git

# Move into the repo
cd ai-startup-website

# Create index.html
echo "This is the Admin creating an index.html file for Tom and Jerry." > index.html

# Check current status
git status

# Stage the file
git add index.html

# Confirm file is staged
git status

# Commit the change
git commit -m "This is my first commit"

# Push to GitHub
git push origin main
```

---

## ✅ Part 2: Simulating Team Collaboration (Tom and Jerry)

### 👨‍💻 Tom's Workflow

```bash
# Ensure you're in the repo directory
cd ~/Desktop/darey-training/git-project/ai-startup-website

# Check current branch
git branch

# Create and switch to Tom's branch
git checkout -b update-navigation

# Simulate changes by Tom
echo "This is Tom adding Navigation to the AI-website" > index.html

# Check status
git status

# Stage changes
git add index.html

# Confirm staged
git status

# Commit changes
git commit -m "Update navigation bar"

# Push to GitHub
git push origin update-navigation
```

---

### 👨‍💻 Jerry's Workflow

```bash
# Switch back to main branch
git checkout main

# Pull Tom's latest changes
git pull origin update-navigation

# Create and switch to Jerry's branch
git checkout -b add-contact-info

# Simulate changes by Jerry
echo "This is Jerry adding contact info to the AI-website" > index.html

# Stage changes
git add index.html

# Commit changes
git commit -m "Add contact information"

# Push to GitHub
git push origin add-contact-info
```

---


```

---

